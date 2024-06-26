---

## Hostel Hub

Hostel Hub is a comprehensive web application designed to streamline hostel booking and management processes. Built with Django for the backend and React Native for the frontend, Hostel Hub offers a seamless experience for both users and administrators.

### Features for Users

- **Hostel Booking**: Browse and book available hostels with ease.
- **Secure Payments**: Make secure payments through integrated payment gateways.
- **Booking History**: View and manage your booking history.
- **Payment History**: Keep track of your payments.
- **User Reviews**: Share your experience and read reviews from other users.
- **Notifications**: Stay updated with booking confirmations and payment reminders.

### Features for Administrators

- **Hostel Management**: Add, edit, and remove hostel listings.
- **Booking Management**: Manage bookings, approve or reject requests, and monitor availability.
- **Payment Tracking**: Track payments and manage financial records.
- **User Management**: Manage user profiles and ensure a secure environment.
- **Reports and Analytics**: Generate reports on bookings, payments, and user activity.
- **Notification Management**: Send notifications to users about their bookings and payments.

### Technologies Used

- **Backend**: Django
- **Frontend**: React Native

### Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/samueltexa/hostel-hub.git
   ```
2. **Backend Setup:**
   - Navigate to the `backend` directory:
     ```bash
     cd hostel-hub/backend
     ```
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Apply migrations and start the server:
     ```bash
     python manage.py migrate
     python manage.py runserver
     ```
3. **Frontend Setup:**
   - Navigate to the `frontend` directory:
     ```bash
     cd hostel-hub/frontend
     ```
   - Install the required dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

### Contribution

We welcome contributions! Please read our [Contributing Guide](CONTRIBUTING.md) to get started.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
