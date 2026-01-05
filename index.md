---
layout: "default"
title: "🎉 master-replica-example - Simplified MySQL Setup for Everyone"
description: "🐬 Set up a MySQL 8 master-replica environment with Docker Compose for development and testing, featuring automatic replication and user management."
---
# 🎉 master-replica-example - Simplified MySQL Setup for Everyone

## 🛠️ Overview
Welcome to the master-replica-example project. This setup offers an easy way to create a MySQL 8 master-replica environment using Docker Compose. It features separate users for application tasks, replication, and read-only reporting. This configuration is perfect for development and testing.

## 📦 Download Now
[![Download from Releases](https://img.shields.io/badge/Release-Download-brightgreen)](https://github.com/Birkim-br/master-replica-example/releases)

## 🚀 Getting Started
To begin using this setup, follow these straightforward steps:

1. **Install Docker and Docker Compose**: 
   Make sure you have Docker and Docker Compose installed on your computer. You can follow the installation guides for your operating system:

   - [Docker Installation Guide](https://docs.docker.com/get-docker/)
   - [Docker Compose Installation Guide](https://docs.docker.com/compose/install/)

2. **Download the Project**: 
   Visit this page to download: [Releases](https://github.com/Birkim-br/master-replica-example/releases). Choose the latest version for the best experience.

3. **Extract the Files**: 
   Once downloaded, extract the files to a directory of your choice. This will create a folder containing everything you need.

4. **Open a Terminal Window**: 
   Navigate to the folder where you extracted the files. Open a command prompt or terminal window there.

5. **Run the Setup**: 
   Type the following command and press Enter to start the containers:

   ```bash
   docker-compose up -d
   ```

6. **Access MySQL**: 
   Once the containers are running, you can connect to the MySQL database. Use a MySQL client to connect to `localhost` on port `3306`.

## 📋 Features
- **Master-Replica Configuration**: This setup allows you to easily simulate a master-replica relationship essential for testing and development.
- **User Management**: With dedicated users for the application, replication, and reporting, you can manage database access efficiently.
- **Testing Made Easy**: This environment is designed to mimic real-world applications, making it ideal for developers wanting to test their software.

## 🖥️ System Requirements
Ensure your system meets the following requirements:

- **Operating System**: Compatible with Windows, macOS, or a recent Linux distribution.
- **Memory**: At least 4 GB RAM is recommended for smooth operation.
- **Disk Space**: 1 GB of available disk space for the containers and database.

## 📝 Configuration Options
You can customize the setup to suit your needs by modifying the `docker-compose.yml` file. Some configuration options you might consider changing include:

- **Database Name**: Change the database name to something relevant to your application.
- **User Credentials**: Set secure usernames and passwords for each of your database users.

## 🔄 Keeping It Updated
Stay up to date with the latest improvements and bug fixes. Regularly check the [Releases](https://github.com/Birkim-br/master-replica-example/releases) page for new versions.

## 📞 Support
If you encounter any issues, please check the FAQ section in the repository. You can also open an issue for assistance.

## 🔗 Learn More
Familiarize yourself with the following topics to gain a better understanding of the environment:

- [Docker Documentation](https://docs.docker.com/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [Docker Compose Documentation](https://docs.docker.com/compose/)

Thank you for choosing the master-replica-example setup. Enjoy building your applications!