# Dashboard Project

This project is a dashboard application designed to manage customers and their invoices. It provides essential metrics such as total revenue, collected money, and pending money, along with options to create and edit customer profiles. The application also includes authentication to ensure secure access.

## Features

### 1. **Customer Management**
- View a list of all customers.
- Edit existing customer information.
- Create new customer profiles.

### 2. **Invoice Management**
- View all invoices associated with customers.
- Monitor key metrics:
  - **Total Revenue**: Displays the total amount invoiced.
  - **Collected Money**: Displays the amount received.
  - **Pending Money**: Displays the amount yet to be collected.

### 3. **Authentication**
- Secure login system to ensure only authorized users can access the dashboard.

### 4. **Responsive Design**
- Fully responsive and optimized for various devices.

## Deployment
The application is deployed on Vercel and can be accessed using the link below:

**[Live Dashboard Link](https://next-dashboard-flax-sigma-54.vercel.app/dashboard/invoices)**

## Tech Stack
- **Framework**: [Next.js](https://nextjs.org/)
- **Styling**: Tailwind CSS / CSS Modules
- **Authentication**: Implemented with NextAuth.js
- **Deployment**: Vercel

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd dashboard-project
   ```

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

4. Create a `.env.local` file in the root directory and add necessary environment variables (e.g., database credentials, authentication secrets).

5. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open the application in your browser at `http://localhost:3000`.

## Usage

- **Login**: Enter your credentials to access the dashboard.
- **View Metrics**: Check total revenue, collected money, and pending money at a glance.
- **Manage Customers**: Create or edit customer profiles.
- **Track Invoices**: Monitor invoice details and associated customer information.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

If you encounter any issues or have suggestions for improvement, feel free to open an issue or contact the project maintainers.

