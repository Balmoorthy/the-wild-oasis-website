# The Wild Oasis Hotel (Client Version)

Welcome to the Wild Oasis Hotel Booking Platform! This is a modern web application designed to help potential and current guests explore, reserve, and manage their stay at Wild Oasis Hotel. Built with a full stack of cutting-edge technologies, this app provides a seamless user experience for all your booking needs.

[View Demo](https://the-wild-oasis-website-demo-72.vercel.app)


## 🚀 Features

- **Explore the Hotel:**
  - Detailed information about Wild Oasis Hotel.
  - Browse various cabins with descriptions, amenities, and images.

- **Cabin Information:**
  - View cabin details, including availability and booked dates.
  - Filter cabins based on maximum guest capacity.

- **Reservations:**
  - Reserve a cabin for a specific date range.
  - Reservations are initially marked as "unconfirmed" with payment to be made at the property.

- **Manage Reservations:**
  - View all past and future reservations.
  - Update or cancel existing reservations.

- **User Accounts & Profiles:**
  - Sign up and log in to make reservations and manage bookings.
  - Create and update user profiles for faster check-in.

## 🛠️ Technology Stack

- **Frontend:**
  - [Next.js](https://nextjs.org/)
  - [TailwindCSS](https://tailwindcss.com/)

- **Authentication:**
  - [NextAuth](https://next-auth.js.org/)

- **State Management:**
  - Context API

- **Database:**
  - [Supabase](https://supabase.com/)

## What I Learned

While building this project, I gained knowledge in the following areas:

- **Next.js Routing**: Implemented dynamic and static routing for seamless navigation.
- **User Interaction**: Managed user input and interactions using React hooks and state management.
- **Login with Google Provider**: Integrated Google login functionality using NextAuth for OAuth authentication.
- **NextAuth**: Utilized NextAuth for secure and flexible user authentication and session management.
- **API Creation**: Developed APIs for handling user data, authentication, and more, using Next.js API routes.
- **User Authentication and Authorization**: Implemented a sign-up and login system, ensuring guests must create an account and log in before making a reservation or performing any operations.
- **Profile Management**: Developed a guest profile system where users can set and update personal information to streamline the check-in process.
- **Cabin Filtering and Information**: Enabled guests to filter cabins by their maximum guest capacity and view important details, such as booked dates and cabin descriptions.
- **Reservation System**: Built a system where guests can reserve cabins for specific date ranges, with reservations marked as "unconfirmed" until payment is made at the property upon arrival.
- **Reservation Management**: Implemented features for guests to view all past and future reservations, as well as update or delete their reservations if needed.

## ⚙️ Future Updates

In the near future, we plan to integrate an Express backend with MongoDB to enhance functionality and scalability.

## 📦 Installation

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Balmoorthy/the-wild-oasis-website.git

1. **Navigate to the project directory:**
   ```bash
   cd the-wild-oasis-website

3. **Install dependencies:**
   ```bash
   npm install

4. **Create a** .env.local **file with the following environment variables:**
   ```bash
   SUPABASE_URL=your-supabase-url
   SUPABASE_KEY=your-supabase-key

5. **Run the development server:**
   ```bash
   npm run dev
   
6. **Open your browser and navigate to:**
   ```bash
   http://localhost:3000

## Author

Bal Moorthy:

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bal-moorthy/)

Feel free to contact me with any questions or feedback!
