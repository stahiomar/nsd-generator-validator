# Network Service Descriptor (NSD) Management Application

## Project Overview

This web application facilitates the creation, generation, validation, and export of Network Service Descriptors (NSDs), providing an efficient tool for managing NSD workflows.

## Features

- **NSD Creation:** Users can create new Network Service Descriptors, specifying all necessary configurations and parameters.
- **NSD Generation:** The application supports automated generation of NSDs based on user input, ensuring consistency and accuracy.
- **NSD Validation:** The system provides validation functionality to check NSDs for errors and compliance with required standards.
- **NSD Exporting:** Users have the option to export NSDs in the desired format for integration with external systems.

### "Apply to MANO" Button and MANO Validation

The application includes an **"Apply to MANO"** button, which allows users to submit the generated NSD to a Management and Orchestration (MANO) system. MANO (Management and Orchestration) is a framework used in network function virtualization (NFV) environments to manage and orchestrate virtual network functions and services.

Upon clicking the **"Apply to MANO"** button, the application sends the NSD to the MANO system, which then validates the NSD. The MANO system responds to the application with a status indicating whether the NSD is valid. If the NSD does not meet the required standards, the application displays the validation errors, allowing users to make necessary adjustments before resubmitting.

## Tech Stack

### Backend
- **Django:** A robust web framework used to handle backend logic, data processing, and server interactions.

### Frontend
- **HTML, CSS, JavaScript:** Core web technologies used to build and style the user interface.
- **Bootstrap:** CSS framework to create responsive and mobile-first web designs with pre-built components and utilities.

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/stahiomar/nsd-generator-validator.git
   cd nsd-generator-validator
   ```
   
2. **Run Django migrations**
   ```bash
   python manage.py migrate
   ```
   
3. **Run the Application**
   ```bash
    python manage.py runserver
   ```
   
4. **Access the Application**
Open your browser and navigate to http://127.0.0.1:8000.

## Application interface
![image](https://github.com/user-attachments/assets/f7c3f719-e5ff-4ac2-86bc-71ece91107eb)


## Contributing
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.
