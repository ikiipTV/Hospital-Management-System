//@author: Samuel Jim
//@Company: ikiip
//@website: ikiip.net
//@email: aiAdvocate@ikiip.net

//include the preprocessors
#include <iostream>
#include <cstring>

using namespace std;
//Declare the function which would be used later for clarification
void patientFilesDetails(struct PatientDetails HospitalArchive);
void doctorsFileDetails(struct DoctorsDetails HospitalAdmins);

//main program driver
struct PatientDetails{
char patientName [45];
char patientLocation [70];
char patientNextOfKin [89];
int patientRoomNumber;
int patientAge;
int patientDrugCabinet;
int patientDrugFile;
};

struct DoctorsDetails{
char doctorsName [45];
char doctorsLocation [98];
char doctorsNextOfKin [55];
char doctorsQualification [103];
int doctorsOfficeNumber;
int doctorsTelephone;
} ;

int main(){
struct PatientDetails Patient1; // declaring for the first patient its A Demo
struct PatientDetails Patient2; // declaring for the second patient its a demo
struct DoctorsDetails Doctor1; // declaring for the first doctor its a demo
struct DoctorsDetails Doctor2; // declaring for the second doctor its a demo

//listing the properties for the first patient.. which is patient1
strcpy(Patient1.patientName, "demo-patient");
strcpy(Patient1.patientLocation, "Room-345");
strcpy(Patient1.patientNextOfKin, "Demo-kin");
Patient1.patientRoomNumber = 345;
Patient1.patientAge = 45;
Patient1.patientDrugCabinet = 8767;
Patient1.patientDrugFile = 1;

//listing the properties for the second patient.. which is patient2
strcpy(Patient1.patientName, "demo-patients");
strcpy(Patient1.patientLocation, "Room-3450");
strcpy(Patient1.patientNextOfKin, "Demo-kins");
Patient1.patientRoomNumber = 3475;
Patient1.patientAge = 43;
Patient1.patientDrugCabinet = 9967;
Patient1.patientDrugFile = 2;

//listing the properties for the first doctor.. which is doctor1
strcpy(Doctor1.doctorsName, "demo-doctor");
strcpy(Doctor1.doctorsLocation, "Room-3225");
strcpy(Doctor1.doctorsNextOfKin, "Demo-kiin");
Doctor1.doctorsTelephone = 66556;

//listing the properties for the second doctor.. which is doctor2
strcpy(Doctor2.doctorsName, "demo-doctors");
strcpy(Doctor2.doctorsLocation, "Room-3235");
strcpy(Doctor2.doctorsNextOfKin, "Demo-kyin");
Doctor2.doctorsTelephone = 33445;

patientFilesDetails(Patient1);
patientFilesDetails(Patient2);
doctorsFileDetails(Doctor1);
doctorsFileDetails(Doctor2);

return 0;
}
//function declaration for the patient properties

void patientFilesDetails(struct PatientDetails HospitalArchive){
cout << "Patient name is :" << HospitalArchive.patientName << endl;
cout << "patient Location is:"<< HospitalArchive.patientLocation << endl;
cout << "patient next of kin is :" << HospitalArchive.patientNextOfKin << endl;
cout << "patient room number is: " << HospitalArchive.patientRoomNumber <<endl;
cout << "patient age is :" << HospitalArchive.patientAge<< endl;
cout << "patient drug cabinet is:"<< HospitalArchive.patientDrugCabinet<<endl;
cout << "patient drug file is:"<< HospitalArchive.patientDrugFile << endl;
}
//function declaration for the doctors properties

void doctorsFileDetails(struct DoctorsDetails HospitalAdmins){
cout << "Doctors name is:"<< HospitalAdmins.doctorsName <<endl;
cout << "Doctors Location is:" <<HospitalAdmins.doctorsLocation << endl;
cout << "Doctors nextOfKin is:" << HospitalAdmins.doctorsNextOfKin <<endl;
cout << "Doctors telephone is:" << HospitalAdmins.doctorsTelephone << endl;
}
