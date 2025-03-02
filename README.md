# **Email Website**  

## **Description**  
A simple email website that allows users to send and receive emails within the platform. The website ensures smooth communication between registered users with a minimalistic and easy-to-use interface.  

---

## **Technologies Used**  
- Node.js  
- HTML  
- CSS  
- SQLite3  
- Additional libraries and packages for enhanced functionality  

---

## **How the Website Works**  
The website is designed for simplicity and ease of use. Users can create an account with just three basic details:  

- **Username (Email)**  
- **Password**  
- **Confirmation Password**  

Once registered, users are redirected to the homepage, where emails sent to them will appear in their inbox.  

---

## **Features**  

### **📥 Inbox**  
- Displays all received emails after logging in.  

### **✉️ Compose**  
- Allows users to send an email to another registered user.  
- Once an email is sent, users are redirected to the **Sent** folder to view their sent emails.  

### **📄 View Emails**  
- All received emails appear on the homepage.  
- Users can click **"View Email"** to see the email details.  

### **↩️ Reply to Emails**  
- Users can instantly reply to an email.  
- The recipient, sender, and subject fields are auto-filled for convenience.  

---

## **User Sessions**  
- The website uses session management to ensure users are authenticated and registered before accessing their inbox.  

---

## **Database Structure**  
The database consists of two main tables:  

1. **Users Table** – Stores all registered users.  
2. **Emails Table** – Stores all emails sent and received through the platform.  

---

## **Possible Improvements**  

Like any application, this project has room for enhancements. Some potential improvements include:  

- ✅ Enforcing stronger password requirements for better security.  
- 🔄 Allowing users to update their account details.  
- 🗑️ Adding an option to delete emails.  
- ⭐ Implementing a feature to mark emails as important or spam.  
- 📧 Verifying whether the recipient's email exists before sending a message.  

---

## **File Structure & Functionality**  
The project consists of seven main files, each handling different functionalities:  

1. **`apology`** – Redirects users here when an error occurs, such as incorrect login credentials.  
2. **`compose`** – Handles the email composition process.  
3. **`email`** – Displays email details when a user views a message.  
4. **`login`** – The login page for authentication.  
5. **`register`** – Handles user registration.  
6. **`reply`** – Manages the email reply feature.  
7. **`index`** – The homepage that displays all received emails.  

---

## **Reference**  
This project is heavily inspired by **CS50 Finance (Pset 9)**. Several concepts and functions have been reused to ensure simplicity and efficiency. The **helpers.py** file played a crucial role in accelerating the development process.  

---

🚀 **This project showcases my ability to build a functional email website using web development technologies.**
