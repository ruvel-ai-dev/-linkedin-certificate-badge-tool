# LinkedIn Certificate Badge Integration Tool

This project provides a reusable HTML snippet that enables staff in the Employability and Apprenticeships Department at the University of Greenwich to create LinkedIn certificate badges for their employability pathways. The tool allows students to add a verified certificate, along with an official badge image, directly to their LinkedIn profiles.

## Purpose

This tool helps students receive recognition for completing employability pathways by publishing certificates directly to LinkedIn. The badge includes the course title, issuing organisation, and year.

## How to Use This Tool

1. Open the file named `badge_template.html`.

2. In the code, find this part:

&name=REPLACE_WITH_CERTIFICATE_NAME_USING_%20_FOR_SPACES


3. Replace it with your actual course name, using `%20` instead of spaces.

Examples:
- Digital Detectives → `&amp;name=Digital%20Detectives`
- Green Careers Bootcamp → `&amp;name=Green%20Careers%20Bootcamp`

4. Do not change the organisation name or year unless instructed. These are fixed as:
- Organisation: Employability & Apprenticeships – University of Greenwich
- Year: 2025

5. The badge image is already included. You may change the link to a new badge if needed.

6. Upload this HTML file into your internal student-facing site (e.g. Target Connect, Moodle, careers pages).

7. When students click the button, it will open the LinkedIn certificate form, pre-filled and ready to publish.

## Example Screenshots

### 1. How the certificate button and badge appear on a web page
![Certificate Button](screenshot1.png)

### 2. What the LinkedIn certificate form looks like when opened
![LinkedIn Form](linkedin-form.png)

### 3. How it looks on a completed LinkedIn profile
![Profile View](profile-preview.png)

(Upload screenshots with exactly these filenames so they display correctly.)

## Files Included

- `badge_template.html`: The editable HTML tool
- `README.md`: Instructions for staff use and GitHub viewers

## Author

Ruvel Miah  


