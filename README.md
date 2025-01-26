# Hospital Management System

This project is a Python-based application designed to manage the operations of a hospital. It includes functionalities for managing doctors, patients, and administrative tasks.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Classes and Methods](#classes-and-methods)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

Follow these steps to set up the project:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd hospital-management-system
    ```

## Usage

1. Run the main script:
    ```bash
    python Main.py
    ```

2. Log in using the admin credentials:
    - Username: `admin`
    - Password: `123`

## Files

- [Admin.py](http://_vscodecontentref_/0): Contains the `Admin` class for handling administrative operations.
- [Doctor.py](http://_vscodecontentref_/1): Contains the `Doctor` class for managing doctor details.
- [Patient.py](http://_vscodecontentref_/2): Contains the `Patient` class for managing patient details.
- [Main.py](http://_vscodecontentref_/3): The main entry point of the application, initializes the system and handles the login process.

## Classes and Methods

### Admin Class (`Admin.py`)

- **Attributes**:
  - `username`: Admin username.
  - `password`: Admin password.
  - `postcode`: Admin postcode.

- **Methods**:
  - `login()`: Handles admin login.
  - `find_index(index, list)`: Finds the index in a list.
  - `add_doctor(doctor)`: Adds a doctor to the system.
  - `assign_doctor_to_patient(doctor_index, patient_index, doctors, patients)`: Assigns a doctor to a patient.
  - `discharge_patient(patient_index, patients, discharged_patients)`: Discharges a patient.
  - `update_details(new_username, new_password, new_postcode)`: Updates admin details.

### Doctor Class (`Doctor.py`)

- **Attributes**:
  - `__first_name`: First name of the doctor.
  - `__surname`: Surname of the doctor.
  - `__speciality`: Speciality of the doctor.
  - `__patients`: List of patients assigned to the doctor.
  - `__appointments`: List of appointments for the doctor.

- **Methods**:
  - `full_name()`: Returns the full name of the doctor.
  - `get_first_name()`: Returns the first name of the doctor.
  - `set_first_name(new_first_name)`: Sets a new first name for the doctor.

### Patient Class (`Patient.py`)

- **Attributes**:
  - `__first_name`: First name of the patient.
  - `__surname`: Surname of the patient.
  - `__doctor`: Doctor assigned to the patient.
  - `__age`: Age of the patient.
  - `__mobile`: Mobile number of the patient.
  - `__postcode`: Postcode of the patient.

- **Methods**:
  - `full_name()`: Returns the full name of the patient.
  - `get_doctor()`: Returns the doctor assigned to the patient.
  - `link(doctor)`: Links the patient to a doctor.
  - `print_symptoms()`: Prints a random symptom.
  - `__str__()`: Returns a formatted string representation of the patient's details.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Ranjesh Thakur - [rs0036870@gmail.com](mailto:your-email@example.com)
