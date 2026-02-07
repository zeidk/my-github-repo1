# MyApp

A sample application for learning Git version control.

## Overview

This project demonstrates Git workflows including branching, merging, and collaboration. It serves as a hands-on example for the ENPM702 Version Control tutorial.

## Getting Started

### Prerequisites

- Git 2.x or later
- Your favorite text editor

### Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:yourusername/my-project.git
   cd my-project
   ```

2. Review the configuration:
   ```bash
   cat config.yaml
   ```

3. Start developing!

## Configuration

The application is configured via `config.yaml`. Key settings include:

- **Server settings**: Host, port, and timeout values
- **Database settings**: Connection parameters
- **Logging settings**: Log level and output format
- **Feature flags**: Enable/disable application features

<!-- Uncomment when authentication feature is complete:
## Authentication

The application supports user authentication with the following features:

- Local authentication with configurable password policies
- Session management with customizable timeout
- Login attempt limiting for security -->


## Project Structure

```
my-project/
├── config.yaml      # Application configuration
├── README.md        # This file
└── .gitignore       # Git ignore rules
```

## Contributing

1. Create a feature branch: `git switch -c feature/your-feature`
2. Make your changes and commit them
3. Push to your branch: `git push origin feature/your-feature`
4. Open a Pull Request

## License

This project is for educational purposes.
