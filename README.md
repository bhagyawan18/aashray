# Aashray: Disaster Management & Emergency Response Platform

## Project Overview

Aashray is a comprehensive web-based platform designed to enhance disaster preparedness and emergency response. It provides real-time information, resource locators, and community support to help individuals and communities stay informed and connected during emergencies.

## Features

- **Emergency Alerts**: Receive real-time notifications about natural disasters and emergencies in your area.
- **Resource Locator**: Find nearby shelters, medical facilities, and emergency services based on your current location.
- **Community Support**: Connect with local communities and emergency response teams to share information and resources.
- **Weather Monitoring**: Stay informed about weather conditions that could lead to potential emergencies, with detailed forecasts and alerts.

## Technology Stack

- **Frontend**: Built with [Next.js](https://nextjs.org/) for server-side rendering and a seamless user experience.
- **Backend**: Developed using [Prisma](https://www.prisma.io/) as the ORM for efficient database management.
- **Authentication**: Implemented with [Clerk](https://clerk.dev/) for secure and user-friendly authentication.
- **Forms Management**: Utilized [React Hook Form](https://react-hook-form.com/) along with [Zod](https://zod.dev/) for form validation and management.
- **UI Components**: Leveraged [Radix UI](https://www.radix-ui.com/) for accessible and customizable components.
- **Maps Integration**: Incorporated [Leaflet](https://leafletjs.com/) and [React Leaflet](https://react-leaflet.js.org/) for interactive map functionalities.
- **Styling**: Styled with [Tailwind CSS](https://tailwindcss.com/) and enhanced with [Framer Motion](https://www.framer.com/motion/) for animations.
- **Carousel**: Implemented using [Embla Carousel](https://www.embla-carousel.com/) for responsive and customizable carousels.

## Getting Started

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/disaster-mvj.git
   cd disaster-mvj
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory with the necessary configuration. For example:
   ```
   NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api
   DATABASE_URL=your_database_url
   ```

4. **Run Database Migrations**:
   ```bash
   npx prisma migrate dev
   ```

5. **Start the Development Server**:
   ```bash
   npm run dev
   ```

## Deployment

Aashray can be deployed on platforms like [Vercel](https://vercel.com/) for seamless integration with Next.js applications. To deploy:

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Log In to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy the Project**:
   ```bash
   vercel
   ```

   Follow the prompts to complete the deployment.

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear and concise messages.
4. Submit a pull request detailing the changes made.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Clerk](https://clerk.dev/) for authentication solutions.
- [Prisma](https://www.prisma.io/) for database management.
- [Radix UI](https://www.radix-ui.com/) for UI components.
- [Leaflet](https://leafletjs.com/) and [React Leaflet](https://react-leaflet.js.org/) for map functionalities.
- [Embla Carousel](https://www.embla-carousel.com/) for carousel implementation.

---
