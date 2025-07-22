# Seekly - Smart Search Engine

<p align="center">
  <img src="https://i.ibb.co/Y4jzTXzq/Seeklyphoto.jpg" alt="Seekly Screenshot" width="600"/>
</p>

Seekly is a modern, privacy-focused search engine that delivers fast and relevant search results while respecting user privacy. The project consists of two main components: the public-facing search interface and an admin panel for managing content.

## Features

### Search Engine (project.html)
- Clean, responsive interface with dark/light mode
- Web and image search functionality
- Multi-language support (English & Arabic)
- Safe search filtering
- Website submission system
- User visit tracking and analytics
- Cookie consent management

### Admin Panel (admin.html)
- Dashboard with key metrics overview
- Website management (approve/reject submissions)
- Promotion management
- User analytics
- Maintenance mode control
- Admin user management

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS
- **Icons**: Font Awesome
- **Database**: Firebase Realtime Database
- **Authentication**: Firebase Authentication

## Project Structure

```
searchengine/
├── project/
│   └── project.html       # Main search engine interface
└── admin/
    └── admin.html         # Admin control panel
```

## Getting Started

### Prerequisites
- Firebase project with Realtime Database enabled
- Web server to host the HTML files (or run locally)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/georgmichelle/searchengine.git
   ```

2. Configure Firebase:
   - Replace the Firebase configuration in both HTML files with your project's credentials
   - Set up Firebase Authentication (Email/Password method)
   - Configure Realtime Database rules

3. Deploy the files to your web server

## Usage

### Search Engine
Access the search engine by opening `project.html` in a web browser. Users can:
- Perform web and image searches
- Submit their websites for inclusion
- Toggle between light/dark modes
- Switch between English and Arabic interfaces

### Admin Panel
Access the admin panel by opening `admin.html` and logging in with admin credentials. Admins can:
- Manage website submissions
- Create promotions for featured websites
- View user analytics
- Configure system settings

## Configuration

Both files contain configuration sections where you can:
- Set Firebase credentials
- Adjust default settings (dark mode, language, etc.)
- Modify the database reference path

## Contact

For support or questions, contact the developer:

- **GitHub**: [@georgmichelle](https://github.com/georgmichelle)
- **Website**: [georg-michelle.ct.ws](https://georg-michelle.ct.ws)
- **Instagram**: [@h1xzblu](https://instagram.com/h1xzblu)
- **Discord**: @shadowDevv
- **Telegram**: @Addmepleasenow
- **WeChat ID**: wxid_2aa15bz1369r22

## License

This project is under MIT license. All rights reserved.
