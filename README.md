# OpenCTI Installation Guide

This guide will help you set up OpenCTI on your VM or host machine using Docker and Portainer.

## Prerequisites

Before starting, ensure you have the following installed:

1. **Docker** - [Installation Guide](https://docs.docker.com/get-docker/)
2. **Docker Compose** - [Installation Guide](https://docs.docker.com/compose/install/)
3. **Portainer** - [Installation Guide](https://www.portainer.io/installation/)

## Installation Steps

Once the prerequisites are in place, follow these steps to install OpenCTI:

1. Open Portainer and go to the **App Templates** section.
2. Select **Stacks** and create a new stack, naming it `opencti`.
3. In the stack creation page:
   - **Paste the YAML file** into the Web Editor.
   - **Upload the .env file** with environment variables for OpenCTI.

4. Click **Deploy the stack** to begin the installation. The deployment process may take around 5 minutes.

## Troubleshooting

If you encounter any issues during installation, consult the official OpenCTI [documentation](https://www.opencti.io/docs/getting-started).

## Additional Resources

- [Docker Documentation](https://docs.docker.com/)
- [Portainer Documentation](https://docs.portainer.io/)

Good luck with your OpenCTI setup!
