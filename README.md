# ESIC Employee & Family Details Collection Form 📝

This project is a real-world example of a structured data collection form built using **Google Forms**. It is designed to gather personal and family member details of employees for the purpose of **updating or generating ESIC (Employees’ State Insurance Corporation) cards**.

## 📌 Project Objective

To simplify and streamline the process of collecting verified employee and family information (Aadhar details, DOB, gender, etc.) required for ESIC registration. This form helps HR/admin teams ensure completeness, accuracy, and compliance in ESIC documentation.

---

## 🔧 Tools Used

- **Google Forms** – for frontend data collection
- **Google Sheets** – for backend data storage and analysis
- **Form Validation** – built-in regex and field requirements for clean data entry

---

## 📋 Form Sections

1. ### Employee Details
   - Name, Date of Birth, Gender
   - Employee Code (Format: `MOB1234`)
   - Mobile Number, Email ID
   - Aadhar Number & Card Upload
   - Registered Address

2. ### Spouse Details
   - Name, DOB, Aadhar Number, Aadhar Card

3. ### Parents' Details
   - Father: Name, DOB, Aadhar, Aadhar Card
   - Mother: Name, DOB, Aadhar, Aadhar Card

4. ### Children Details (Up to 3)
   - For each child: Name, DOB, Gender, Aadhar Number, Aadhar Card Upload

---

## ✅ Validations Implemented

- 📌 Employee Code: Must match format `MOB1234`  
  - **Regex Used**: `MOB\d{4}`
- 📌 Aadhar: Must be exactly 12-digit numbers  
  - **Regex Used**: `\d{12}`
- 📌 Mobile Number: Exactly 10 digits
  - **Regex Used**: `\d{10}`
- 📌 Required fields for critical data to avoid incomplete submissions
- 📌 File Upload Limits: Aadhar Card uploads allowed (max 10MB)

---

## 🧠 Use Cases

- HR onboarding and ESIC enrollment
- Internal employee management
- Government compliance documentation
- Scalable form template for similar identity/document verification workflows

---

## 📌 How to Replicate

1. Open [Google Forms]
2. Recreate the form using the section breakdown above
3. Apply field validations and file upload settings
4. Link to a Google Sheet for data collection
5. Share the form via link or email to employees

---

## 📜 License

This project is shared for educational and organizational purposes. You may adapt it freely for internal use, with credit.
