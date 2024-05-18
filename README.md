# Fake-PHI-PII
fake and randomly generated patient health records and invoices

This Jupyter Notebook generates PDF documents containing fake and randomly generated patient health records and invoices. The generated data is for demonstration purposes only and is not real. The notebook uses the Faker and ReportLab libraries to create realistic-looking PDFs with professional formatting, including a disclaimer and footer.

Requirements
Python 3.x
Jupyter Notebook
Install required libraries:
bash
Copy code
pip install faker reportlab
Key Components
Libraries and Setup

faker: Generates fake data.
reportlab: Creates PDFs.
Directories for storing generated PDFs.
Clinic/Hospital Information

Details about the clinic or hospital, including name, address, phone number, email, and logo.
Styles

Custom styles for various text elements, including titles, normal text, and disclaimers.
Footer Function

Adds a footer with a hyperlink and copyright notice to each page of the PDFs.
Disclaimer

Adds a disclaimer at the top of each document to indicate that the data is fake and randomly generated.
Data Generation Functions

Functions to generate fake health data and invoice data using the Faker library.
PDF Creation Functions

Functions to create PDFs for patient health records and invoices using the ReportLab library.
PDF Generation Loop

Generates multiple PDFs (default: 100) and saves them in specified directories.
Usage Guide
Setup

Ensure you have Python 3.x and Jupyter Notebook installed.
Install the required libraries using pip install faker reportlab.
Download and save the clinic/hospital logo image at the specified path (path_to_logo.png).
Running the Notebook

Open the Jupyter Notebook and run each cell sequentially.
The notebook will generate 100 patient health records and invoices, saving them in the patient_records and invoices directories.
Customization

Clinic/Hospital Information: Update the clinic_info dictionary with your own details.
Number of Records: Change the num_records variable to generate a different number of PDFs.
Styles and Colors: Modify the styles in the styles dictionary to customize the look and feel of the PDFs.
Example Usage Scenarios

Software Testing: Use the generated data to test software applications that handle patient records and invoices.
Training and Education: Provide realistic data for training sessions or educational purposes without exposing real patient information.
UI/UX Design: Use the fake data to design and prototype user interfaces for medical and billing software.
Data Privacy Demonstrations: Showcase the importance of data privacy and handling with realistic-looking, but fake, data.
