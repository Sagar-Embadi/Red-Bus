
---

# Red Bus Clone 🚍  

A web-based clone of the popular Red Bus platform, featuring real-time bus booking functionality. This project includes a custom API for managing bus data and Firebase for user authentication.

---

## 📌 Features  
- **Custom API for Bus Data**: Fetch and display real-time bus schedules, routes, and pricing.  
- **User Authentication with Firebase**: Secure sign-up, login, and logout functionalities.  
- **Responsive Design**: Seamless experience across desktops, tablets, and mobile devices.  
- **Search & Filter Buses**: Search for available buses based on source, destination, and date.  
- **Booking Management**: Allows users to view and manage their bookings.  

---

## 🛠️ Technologies Used  
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js (for serving custom API)  
- **Database**: Custom API for bus data  
- **Authentication**: Firebase Authentication  
- **Hosting**: Firebase Hosting (or your preferred hosting platform)  

---

## 🚀 Getting Started  

### Prerequisites  
Make sure you have the following installed on your system:  
- Node.js  
- Firebase CLI  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/red-bus-clone.git
   cd red-bus-clone
   ```  

2. Install dependencies:  
   ```bash
   npm install
   ```  

3. Configure Firebase:  
   - Set up a Firebase project and enable Authentication.  
   - Add your Firebase configuration in `firebaseConfig.js`.  

4. Run the project:  
   ```bash
   npm start
   ```  

---

## 🔑 Firebase Authentication  
- **Email & Password Authentication**: Used for secure user login and registration.  
- **Authentication Flow**:  
  1. Users can sign up with their email and password.  
  2. On successful authentication, users can access booking features.  
  3. Secure logout to end the session.  

---

## 📦 API Details  
The project uses a custom Node.js API for bus data. The following endpoints are available:  

- **GET /api/buses** – Fetch all available buses  
- **POST /api/bookings** – Create a new booking  
- **GET /api/bookings/:userId** – Fetch bookings for a specific user  

---

## 🎨 Screenshots  
- **Homepage**  
- **Login/Register Page**  
- **Bus Search Results**  
- **Booking Details**  

(Add screenshots here for a visual representation of your website.)

---

## 📄 License  
This project is licensed under the MIT License.  

---

## ✨ Acknowledgements  
- Red Bus for the original concept.  
- Firebase for authentication and hosting.  

---

## 📧 Contact  
For any questions or feedback, feel free to reach out:  
**Sagar Embadi** – [Your Email]  

---
