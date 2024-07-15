# BridgeHealthApp

Welcome to BridgeHealthApp, a Laravel + React Vite web application designed to manage health records for mothers during their pre and post-natal term. This application ensures that mothers have access to doctor consultations and necessary tools, and tips to help mothers especially in rural areas to manage their pregnancy with ease.

BridgeHealthApp is built to support mothers through their pregnancy journey by providing a comprehensive health management system. The application facilitates easy access to professional consultation, essential tips, and tools for managing pregnancy effectively.

## Features

- **User Authentication:** Secure registration and login for mothers and doctors.
- **Profile Management:** Update and manage user profiles.
- **Health Records:** Record and access health records and symptom logs.
- **Appointments:** Schedule and manage appointments with doctors.
- **Tips and Tools:** Access personalized tips and tools for pregnancy management.
- **Emergency Support:** Quick access to emergency toll-free numbers.
- **Notifications:** Receive email notifications for appointment confirmations and reminders.
- **Analytics:** Track and view health analytics for better insights.

## Technologies Used

- **Backend:** Laravel
- **Frontend:** React with Vite
- **Database:** MySQL
- **Authentication:** Laravel Sanctum
- **Styling:** Tailwind CSS
- **Email Notifications:** Laravel Mail

## Installation

### Prerequisites

- PHP >= 8.x
- Composer
- Node.js >= 14.x
- NPM or Yarn
- MySQL

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/kc-allan/BridgeHealthApp.git
   cd BridgeHealthApp
   ```

2. Install backend dependencies:

   ```bash
   composer install
   ```

3. Install frontend dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

4. Copy the `.env.example` file to `.env` and configure your environment variables:

   ```bash
   cp .env.example .env
   ```

5. Generate the application key:

   ```bash
   php artisan key:generate
   ```

6. Run database migrations and seeders:

   ```bash
   php artisan migrate --seed
   ```

7. Start the development server:

   ```bash
   php artisan serve
   ```

8. In another terminal, start the Vite development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

## Usage

- **Access the application:** Open your browser and navigate to `http://localhost:8000`.
- **Register and login:** Create an account or log in with your existing credentials.
- **Manage profiles:** Update your profile information.
- **Record health logs:** Enter and track health records and symptoms.
- **Schedule appointments:** Book and manage appointments with doctors.
- **Access tips and tools:** View personalized tips and tools for managing your pregnancy.

## Contributing

We welcome contributions from the community! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

Please ensure your code follows our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please contact me at:

- **Email:** [kiruiallan401@gmail.com] [mailto:kiruiallan401@gmail.com]

Thank you for using BridgeHealthApp!
