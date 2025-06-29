# 🚗 Car Rental App

**Car Rental App** is a Flutter-based mobile application that allows users to **browse, book, and manage car rentals easily**. It is designed to provide a smooth and intuitive user experience for customers seeking affordable and reliable car rental services.


## 📑 Table of Contents

* [Introduction](#introduction)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Screenshots](#screenshots)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

The **Car Rental App** simplifies the process of renting a car by providing a **complete platform** where users can:

✅ View available cars with images and specifications

✅ Book a car by selecting rental dates and duration

✅ View booking history

✅ Manage their profile and bookings

✅ Contact support for assistance

This app is ideal for car rental companies or startups looking to digitize their booking process with a **cross-platform mobile solution**.



## ✨ Features

✔️ **User Authentication** – Sign up, login, and manage user sessions

✔️ **Browse Cars** – View available cars with images, models, prices, and specifications

✔️ **Search & Filter Cars** – Filter cars by category, price, availability, or brand

✔️ **Book a Car** – Select car, choose rental dates, and confirm bookings

✔️ **View Bookings** – Check current, upcoming, and past rentals

✔️ **Profile Management** – Update user details and preferences

✔️ **Notifications** – Receive booking confirmations and reminders

✔️ **Responsive Design** – Works seamlessly on Android and iOS devices



## 🛠️ Technologies Used

* **Flutter** (Dart)
* **Firebase** (Authentication, Firestore, Cloud Messaging)
* **Provider** or **Bloc** (State Management)
* `cloud_firestore` (Database)
* `firebase_auth` (Authentication)
* `firebase_storage` (Store car images)
* `flutter_local_notifications` (Optional for reminders)
* **Android Studio / VS Code**



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/car_rental_app.git
cd car_rental_app
```

2. **Get Flutter packages**

```bash
flutter pub get
```

3. **Setup Firebase**

* Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) following the [FlutterFire setup guide](https://firebase.flutter.dev/docs/overview/).

4. **Run the app**

* For Android:

```bash
flutter run
```

* For iOS (ensure Xcode setup is complete):

```bash
flutter run
```



## ▶️ Usage

1. **Register / Login:** Users sign up or log in to their account.
2. **Browse Cars:** Explore available cars, view details, and select for booking.
3. **Book a Car:** Choose rental dates and duration to confirm booking.
4. **Manage Bookings:** View current, upcoming, and previous rentals in the dashboard.
5. **Profile:** Update user details and manage settings.
6. **Notifications:** Receive confirmation and reminders for pickups and returns.



## 📁 Project Structure

```
lib/
 ┣ main.dart
 ┣ screens/
 ┃ ┣ login_screen.dart
 ┃ ┣ signup_screen.dart
 ┃ ┣ dashboard_screen.dart
 ┃ ┣ car_list_screen.dart
 ┃ ┣ car_detail_screen.dart
 ┃ ┣ booking_screen.dart
 ┃ ┣ profile_screen.dart
 ┃ ┗ booking_history_screen.dart
 ┣ models/
 ┃ ┣ car.dart
 ┃ ┣ booking.dart
 ┗ services/
 ┃ ┣ auth_service.dart
 ┃ ┣ car_service.dart
 ┃ ┣ booking_service.dart
 ┃ ┗ notification_service.dart
 ┣ providers/
 ┃ ┗ (state management files)
 ┗ utils/
    ┗ constants.dart
```



## 📸 Screenshots

> *(Screenshots coming soon.)*



## 🤝 Contributing

Contributions are welcome to add:

* Payment gateway integration (Paystack, Flutterwave, Stripe)
* Admin dashboard for managing cars and bookings
* Maps integration for car pickup and drop-off locations
* In-app chat with customer support

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio](#)



### ⭐️ If you find this project useful, please give it a star!


