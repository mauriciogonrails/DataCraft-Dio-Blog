# Data Craft

Data Craft is an Angular-based web application focused on data science, machine learning metrics, and open-source project management in the data domain. This application serves as a knowledge base and resource center for data professionals.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Development](#development)
- [Building for Production](#building-for-production)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Overview

Data Craft is a comprehensive platform that provides articles, tutorials, and resources focusing on machine learning model evaluation, open-source data projects, and probability calibration techniques. The application is built using Angular and TypeScript, with responsive design principles to ensure a seamless experience across devices.

## Features

- **Article Repository**: Collection of in-depth articles on data science topics
- **Machine Learning Metrics Guide**: Detailed explanations of metrics for model evaluation
- **Open-Source Project Management**: Resources on maintaining open-source data projects
- **Probability Calibration Tools**: Guides for calibrating probabilities in ML models
- **Responsive Design**: Mobile-friendly interface that adapts to different screen sizes
- **Multi-language Support**: Content available in multiple languages including Portuguese

## Technologies Used

- **Frontend Framework**: Angular 14+
- **Language**: TypeScript 4.9+
- **Styling**: SCSS/CSS with responsive design
- **UI Components**: Angular Material
- **Testing**: Jasmine & Karma
- **Linting**: ESLint
- **Build Tools**: Angular CLI
- **Package Manager**: npm

## Project Structure

```
data-craft/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── article/
│   │   │   ├── metrics/
│   │   │   ├── open-source/
│   │   │   └── probability/
│   │   ├── services/
│   │   ├── models/
│   │   ├── shared/
│   │   └── app.module.ts
│   ├── assets/
│   │   ├── images/
│   │   └── i18n/
│   ├── environments/
│   ├── styles/
│   └── index.html
├── .angular.json
├── package.json
├── tsconfig.json
└── README.md
```

## Installation

To get started with Data Craft, follow these installation steps:

```bash
# Clone the repository
git clone https://github.com/mauriciogonrails/data-craft.git

# Navigate to the project directory
cd data-craft

# Install dependencies
npm install
```

## Development

To start the development server:

```bash
ng serve
```

Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Development Commands

- `ng generate component component-name` - Generate a new component
- `ng add @angular/material` - Add Angular Material
- `ng generate service service-name` - Generate a new service
- `ng generate module module-name` - Generate a new module

## Building for Production

Run the following command to build the project for production:

```bash
ng build --prod
```

The build artifacts will be stored in the `dist/` directory.

## Testing

### Running Unit Tests

```bash
ng test
```

### Running End-to-End Tests

```bash
ng e2e
```

## Contributing

Contributions to Data Craft are welcome. Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

