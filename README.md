# Hospital Management System

This is a C++ console-based Hospital Management System for managing patients, doctors, appointments, and patient bills. The program allows users to add, edit, delete, search, display, and sort hospital records through a menu-driven interface.

## Features

- Patient management
- Doctor management
- Appointment management
- Patient billing management
- Search and sorting functions
- File storage for patient and doctor records

## Required Files

Make sure these files are included in the project folder:

```text
main.cpp
patient.cpp
patient.h
doctor.cpp
doctor.h
Appointment.cpp
Appointment.h
bill.cpp
bill.h
patients.txt
doctors.txt
```

The files `patients.txt` and `doctors.txt` should be placed in the same folder where the program is run.

## How to Compile and Run

### Using g++

Open a terminal in the project folder and run:

```bash
g++ main.cpp patient.cpp doctor.cpp Appointment.cpp bill.cpp -o hospital_system
```

Then run the program:

```bash
./hospital_system
```

On Windows, run:

```bash
hospital_system.exe
```

### Using Code::Blocks

1. Open Code::Blocks.
2. Create or open the project.
3. Add all `.cpp` and `.h` files to the project.
4. Build and run the project.

## Important Note

If you are running this project on Linux or GitHub Codespaces, file names are case-sensitive. Make sure the include statement and file name match exactly, especially for `Appointment.h`.

## Program Usage

After running the program, choose an option from the main menu:

```text
1. Patient Management
2. Doctor Management
3. Patient Bills
4. Appointment Management
5. Exit
```

Follow the on-screen instructions to manage the hospital records.
