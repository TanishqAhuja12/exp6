# Experiment 6.2 – Client-Side Form Validation (Login Form)

## Aim
To validate form inputs on the client side before submission.

## Requirements
The login form contains **only two fields**:
1. Email ID  
2. Password  

### Email Validation Rules
- Email must contain `@`
- Email must end with `.com`, `.in`, or any valid country code (e.g., `.uk`, `.us`)

### Password Validation Rules
The password must:
1. Start with a **capital letter (A–Z)**
2. Contain **at least one number (0–9)**
3. Contain **at least one special character** (`!@#$%^&*`)
4. Have **minimum 5 characters**

---

## Theory
Client-side validation ensures correctness of user data and provides immediate feedback without server interaction. It improves user experience and prevents invalid data submission.

---

## Procedure
1. Create a login form with Email ID and Password fields.
2. Apply validation rules using JavaScript.
3. Display error messages for invalid inputs.
4. Prevent form submission until all conditions are satisfied.
5. Display a success message on valid submission.

---

## Screenshots

### Login Form
<img width="1769" height="1113" alt="Screenshot 2026-03-06 102454" src="https://github.com/user-attachments/assets/4a2b3fcd-dd52-48b2-b3c0-af27fc21b3c8" />


### Invalid Password Validation
<img width="1770" height="1108" alt="Screenshot 2026-03-06 104137" src="https://github.com/user-attachments/assets/cfab58ca-01a2-4e6c-a0d8-70c3a8834287" />


### Form Submitted Successfully
<img width="1750" height="1117" alt="Screenshot 2026-03-06 104216" src="https://github.com/user-attachments/assets/966c693b-e2ec-4e99-9b9b-4e0bcad71850" />


### Login Successful
<img width="1768" height="1113" alt="Screenshot 2026-03-06 104303" src="https://github.com/user-attachments/assets/9963e083-fe25-4c53-8745-bdc40a3bb0df" />



---

## Result
The login form successfully validates email and password on the client side and allows submission only when all validation conditions are satisfied.

## Running the Project

```bash
npm install
npm run dev
```

Open your browser and navigate to `http://localhost:5173`

## Form Fields
1. **Email ID** - Required field with format validation
2. **Password** - Required field with multi-condition validation

## Technologies Used
- React
- Vite
- CSS3
