# Vogues - FrontEnd

<p align="left">
  <img src="https://img.shields.io/badge/React-19.0-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Vite-6.3-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.1-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/React_Router-7.5-CA4245?style=for-the-badge&logo=react-router&logoColor=white" alt="React Router" />
  <img src="https://img.shields.io/badge/Framer_Motion-12.1-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" />
  <img src="https://img.shields.io/badge/Axios-1.9-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios" />
</p>

> A modern, responsive, and dynamic e-commerce frontend built to deliver a seamless shopping experience. Fast page loads, elegant animations, and a secure checkout flow.

Vogues FrontEnd is the user-facing storefront of the Vogues e-commerce platform. It provides customers with an intuitive interface to browse products, manage their shopping cart, and securely complete purchases. The application is highly optimized for performance and scalability, utilizing the latest React 19 features and Tailwind CSS for utility-first styling.

## Key Features

- **Modern Tech Stack**: Built with Vite and React 19 for blazing-fast development and optimized production builds.
- **Responsive Design**: Fully responsive layout tailored with Tailwind CSS v4 to look great on any device.
- **Fluid Animations**: Smooth page transitions and component animations powered by Framer Motion.
- **Seamless Checkout**: Integrated payment processing and cart management for a frictionless user experience.
- **State Management**: Context-based global state for efficient cart and user session handling.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm, yarn, or pnpm

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Vogues-FrontEnd
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   Copy the example environment file and fill in your details:
   ```bash
   cp .env.example .env.local
   ```
   *Note: Never commit your actual `.env.local` file to version control.*

4. **Start the development server:**
   ```bash
   npm run dev
   ```

## Folder Structure

```text
src/
├── assets/        # Static images and global assets
├── components/    # Reusable UI components (Buttons, Navbars, etc.)
├── context/       # React Context providers for global state
├── pages/         # Page-level components mapped to routes
├── App.jsx        # Root application layout and routing setup
└── main.jsx       # Application entry point
```

## Contributing

Contributions are welcome! Please ensure your code follows the existing style and passes all linting checks before submitting a pull request.
