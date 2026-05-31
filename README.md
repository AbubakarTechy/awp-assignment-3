# MyStudentApp

A React Native mobile application built with Expo as part of my Mobile Application Development (MAD) assignment.

## About

This is a Student Management App that I built and completed from my village. The app allows users to view a list of students, add new students, view student details, and explore a scroll demo screen.

## Screens

### Screen 1 - Home Screen
- Fetches a list of students from a live API using Axios
- Displays students in a FlatList with name, email and phone
- Pull to refresh support
- Navigate to Add Student or Scroll Demo from this screen

### Screen 2 - Add Student Screen
- Form with TextInput fields for Name, Email, Phone and City
- Switch toggle to mark student as Active or Inactive
- Validates all fields before submitting
- Adds new student to the top of the list on HomeScreen

### Screen 3 - Student Detail Screen
- Shows full details of a selected student
- Displays name, username, email, phone, website, city and company
- Header title updates dynamically to student name
- Navigate to Scroll Demo from this screen

### Screen 4 - Scroll Demo Screen
- Outer vertical ScrollView for the whole page
- Inner horizontal ScrollViews for Skills and Projects sections
- nestedScrollEnabled set to true for Android compatibility

## Tech Stack

- React Native
- Expo
- React Navigation (Native Stack)
- Axios
- JavaScript

## API Used

Students are fetched from:
https://jsonplaceholder.typicode.com/users

## Project Structure
MyStudentApp/
├── screens/
│   ├── HomeScreen.js
│   ├── AddStudentScreen.js
│   ├── StudentDetailScreen.js
│   └── ScrollInfoScreen.js
├── App.js
├── package.json
└── README.md

## How to Run

1. Install dependencies:
npm install

2. Start the app:
npx expo start

3. Scan the QR code with Expo Go app on your phone


## Notes

- All styles are written using StyleSheet.create() only
- No inline styles used anywhere in the project
- Built and completed as a university assignment

## Author

Student — Mobile Application Development Assignment
