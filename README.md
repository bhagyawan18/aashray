# Aashray: Disaster Management & Emergency Response Platform 🚨🌐

## Project Overview

Aashray is an innovative web-based platform designed to enhance disaster preparedness and emergency response. By providing real-time alerts, resource locators, and community support, Aashray empowers individuals and organizations to stay informed and connected during critical situations.

## Key Features

- **Emergency Alerts**: 📢 Receive instant notifications about natural disasters and emergencies in your vicinity, ensuring timely awareness and action.

- **Resource Locator**: 🏥 Locate nearby shelters, medical facilities, and emergency services with ease, facilitating quick access to essential resources.

- **Community Support**: 🤝 Connect with local communities and emergency response teams to share vital information and coordinate efforts effectively.

- **Weather Monitoring**: ☁️ Stay updated on weather conditions that could lead to potential emergencies, with detailed forecasts and alerts.

## Technology Stack

Aashray leverages a robust and modern technology stack to deliver a seamless and efficient user experience:

- **Frontend**: Developed using [Next.js](https://nextjs.org/) for server-side rendering and optimized performance.

- **Backend**: Managed with [Prisma](https://www.prisma.io/) as the ORM for efficient database interactions.

- **Authentication**: Secured by [Clerk](https://clerk.dev/) to provide seamless user authentication and management.

- **Forms Management**: Implemented with [React Hook Form](https://react-hook-form.com/) and [Zod](https://zod.dev/) for robust form handling and validation.

- **UI Components**: Built with [Radix UI](https://www.radix-ui.com/) to ensure accessible and customizable interface elements.

- **Mapping**: Integrated with [Leaflet](https://leafletjs.com/) and [React Leaflet](https://react-leaflet.js.org/) for interactive and responsive maps.

- **Styling**: Styled using [Tailwind CSS](https://tailwindcss.com/) complemented by [Framer Motion](https://www.framer.com/motion/) for smooth animations.

- **Carousel**: Enhanced with [Embla Carousel](https://www.embla-carousel.com/) for responsive and customizable carousel components.

## Business Objectives

Aashray aims to address critical challenges in disaster management and emergency response:

- **Enhance Public Safety**: By providing timely alerts and information, Aashray helps reduce response times and improve safety outcomes during emergencies.

- **Resource Optimization**: Facilitates efficient allocation and utilization of emergency resources, ensuring aid reaches those in need promptly.

- **Community Engagement**: Encourages active participation from local communities, fostering a collaborative approach to disaster preparedness and response.

- **Scalability**: Designed to adapt and scale, Aashray can be customized to meet the specific needs of different regions and organizations.

## Getting Started

To set up Aashray locally for development or testing purposes:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/bhagywan18/aashray.git
   cd aashray
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the root directory with the necessary configurations:
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

Aashray is optimized for deployment on platforms like [Vercel](https://vercel.com/):

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Authenticate with Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy the Application**:
   ```bash
   vercel
   ```
   Follow the interactive prompts to complete the deployment process.

## Contributing

We welcome contributions from the community to enhance Aashray:

1. **Fork the Repository**: Create a personal copy of the project.

2. **Create a New Branch**: Develop your feature or fix in a dedicated branch.

3. **Commit Your Changes**: Write clear and concise commit messages.

4. **Submit a Pull Request**: Provide a detailed description of your changes for review.

## License

Aashray is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.

## Acknowledgements

We extend our gratitude to the following technologies and platforms that made Aashray possible:

- [Clerk](https://clerk.dev/) for authentication solutions.

- [Prisma](https://www.prisma.io/) for streamlined database management.

- [Radix UI](https://www.radix-ui.com/) for accessible UI components.

- [Leaflet](https://leafletjs.com/) and [React Leaflet](https://react-leaflet.js.org/) for interactive mapping.

- [Embla Carousel](https://www.embla-carousel.com/) for advanced carousel functionalities.

---
