# 🩺 Book A Doctor - Doctor Appointment Booking System

Book A Doctor is a **full-stack MERN (MongoDB, Express.js, React.js, Node.js)** web application that simplifies the process of booking doctor appointments online. The platform provides dedicated portals for **Patients**, **Doctors**, and **Administrators**, allowing each user to perform tasks based on their role. Patients can search for doctors, book appointments, and manage their profiles, while doctors and administrators can efficiently manage appointments and healthcare services.

The application is built using modern web technologies with **JWT Authentication**, **Cloudinary** for image storage, and a responsive user interface to provide a smooth user experience across all devices.

---

## 🚀 Features

- 🔐 Secure JWT Authentication
- 👤 Role-Based Access (Patient, Doctor & Admin)
- 📅 Online Doctor Appointment Booking
- 🔍 Search Doctors by Specialty
- 👨‍⚕️ Doctor Profile Management
- 👨‍💼 Admin Dashboard
- 📊 Doctor Dashboard
- 👤 Patient Profile Management
- ☁️ Cloudinary Image Upload
- 📱 Fully Responsive Design

---

# 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- Context API
- CSS

### Backend
- Node.js
- Express.js
- JWT Authentication
- Bcrypt
- Multer

### Database
- MongoDB
- Mongoose

### Cloud Services
- Cloudinary

### Development Tools
- Git
- GitHub
- Postman
- Vite
- npm

---

# 🔐 Authentication

The application provides three different user roles with separate dashboards and permissions.

## 👤 Patient

Patients can:

- Register and Login
- Browse all doctors
- Search doctors by specialty
- View doctor profiles
- Book appointments
- View appointment history
- Cancel appointments
- Update profile information
- Upload profile picture

---

## 👨‍⚕️ Doctor

Doctors can:

- Login securely
- View dashboard statistics
- Manage appointments
- Mark appointments as completed
- Cancel appointments
- Update profile details
- Manage consultation fees
- Manage availability status
- View earnings
- View latest appointments

---

## 👨‍💼 Admin

Administrators can:

- Login securely
- Add new doctors
- View all doctors
- Delete doctor profiles
- Manage appointments
- View platform statistics
- View registered patients

---

# 🏠 Home Page

The Home page contains:

- Hero Banner
- Search by Specialty
- Top Doctors Section
- About Prescripto
- Contact Information
- Footer Navigation

---

# 🔍 All Doctors Page

Users can:

- View all available doctors
- Filter doctors by specialty
- Open doctor profiles
- Navigate to appointment booking

Available specialties include:

- General Physician
- Gynecologist
- Dermatologist
- Pediatrician
- Neurologist
- Gastroenterologist

---

# 👨‍⚕️ Doctor Details Page

Displays:

- Doctor Image
- Name
- Qualification
- Experience
- Specialization
- Consultation Fee
- About Doctor
- Available Appointment Slots
- Related Doctors

Patients can directly book appointments from this page.

---

# 📅 Appointment Booking

Patients can:

- Select an appointment date
- Choose an available time slot
- Confirm appointment
- View booked appointments
- Cancel appointments

---

# 👤 Patient Profile

Patients can update:

- Profile Picture
- Name
- Email Address
- Phone Number
- Gender
- Date of Birth
- Address

They can also:

- View booked appointments
- Cancel appointments
- Manage personal information

---

# 👨‍⚕️ Doctor Dashboard

The Doctor Dashboard includes:

### Dashboard Overview

- Total Earnings
- Total Patients
- Total Appointments
- Latest Bookings

### Appointment Management

Doctors can:

- View patient details
- View appointment schedules
- Mark appointments as completed
- Cancel appointments

### Profile Management

Doctors can update:

- About Information
- Consultation Fee
- Address
- Availability Status

---

# 👨‍💼 Admin Dashboard

The Admin Dashboard provides complete management of the platform.

### Dashboard Statistics

- Total Doctors
- Total Patients
- Total Appointments
- Latest Bookings

### Doctor Management

Admin can:

- Add new doctors
- View all doctors
- Delete doctor profiles

Doctor details include:

- Profile Image
- Name
- Email
- Password
- Degree
- Specialty
- Experience
- Consultation Fee
- Address
- Description

### Appointment Management

Admin can:

- View all appointments
- Cancel appointments
- Monitor appointment status

---

# ☁️ Cloudinary Integration

Cloudinary is used for:

- Doctor profile images
- Patient profile pictures
- Image optimization
- Secure cloud storage

---

# 📂 Project Structure

```plaintext
BookADoctor/
│
├── admin/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── Documentation/
│   └── Book_A_Doctor_Document.pdf
│
├── Demo-Video/
│   ├── Book-A-Doctor-Video.mp4
│   
├── README.md
└── .gitignore
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/KomatiAnkitha28/Book-A-Doctor-Project.git
cd Book-A-Doctor-Project
```

---

## Install Backend Dependencies

```bash
cd backend
npm install
```

---

## Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

## Install Admin Dependencies

```bash
cd ../admin
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the **backend** folder.

```env
MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_cloudinary_api_key

CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

ADMIN_EMAIL=your_admin_email

ADMIN_PASSWORD=your_admin_password
```

---

# ▶️ Running the Application

### Start Backend

```bash
cd backend
npm run server
```

### Start Frontend

```bash
cd frontend
npm run dev
```

### Start Admin Panel

```bash
cd admin
npm run dev
```

---

---

# 🎥 Demo Video

Demo Video is available inside the **Demo-Video** folder.

```
```
# 📄 Documentation

The complete project documentation is available in the **Documentation** folder.

```
Documentation/
└── Book_A_Doctor_Document.pdf
```

---

# 🚀 Future Enhancements

- Online Payment Integration
- Email Notifications
- SMS Appointment Reminders
- Video Consultation
- Medical Prescription Upload
- Appointment Rescheduling
- Patient Medical History
- AI-Based Doctor Recommendation
- Multi-language Support
- Dark Mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added a new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 🙏 Acknowledgements

Special thanks to the developers and communities behind:

- MongoDB
- Express.js
- React.js
- Node.js
- Cloudinary
- Vite
- Git
- GitHub

---

# 👩‍💻 Author

**Ankitha Komati**

- 🎓 B.Tech – Computer Science & Engineering
- 💻 MERN Stack Developer
- 🌱 Passionate about Full Stack Development and Problem Solving

---

⭐ **If you like this project, don't forget to give it a Star!**