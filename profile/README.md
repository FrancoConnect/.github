# FrancoConnect

**Modern Business Management Platform for UK Construction & Service Companies**

---

## 🏗️ About FrancoConnect

FrancoConnect is a comprehensive business management platform built with Laravel 12, designed specifically for UK construction and service companies. With a modular plugin architecture, it provides everything from employee management to project tracking, legal compliance, and customer portals.

## 🎯 Core Features

- **🔐 Multi-Portal System** - Separate admin, client, and worker portals with role-based access
- **📋 Legal Document Management** - Dynamic terms, privacy policies, and compliance documents with variable replacement
- **🔌 RESTful API** - Key-based authentication with granular permissions for third-party integrations
- **📊 Business Dashboard** - Comprehensive overview with real-time metrics and insights
- **🎨 Form Builder** - Create custom forms with drag-and-drop ease
- **💬 Live Chat** - Built-in customer support system with real-time messaging
- **🔗 WordPress Integration** - Seamless theme-based integration for public-facing sites
- **📅 Google Calendar Sync** - Two-way synchronization for scheduling

## 🧩 Plugin Architecture

FrancoConnect uses a modular plugin system allowing functionality to be added or removed as needed:

### Available Plugins

- **📍 Attendance** - Clock in/out system, kiosk mode, timesheet management
- **✅ Task Manager** - Project tasks, job sheets, quotes, and workflow management
- *(More plugins in development)*

### Why Plugins?

- **Lightweight Core** - Only install features you need
- **Independent Development** - Plugins can be updated without affecting core
- **Easy Customization** - Build your own plugins to extend functionality
- **Clean Separation** - Each plugin has its own models, controllers, views, and migrations

## 📚 Documentation

Comprehensive documentation for developers and system administrators:

- **[Plugin Development Guide](https://github.com/FrancoConnect/francoconnect-docs)** - Complete tutorial for building plugins (designed for WordPress developers transitioning to Laravel)
- **API Documentation** - RESTful API reference with authentication and endpoints
- **Deployment Guide** - Step-by-step deployment instructions

## 🛠️ Technology Stack

- **Backend**: Laravel 12 (PHP 8.2+)
- **Database**: MySQL 8.0
- **Frontend**: Blade templates with Tailwind CSS + Alpine.js
- **Build Tool**: Vite
- **Authentication**: Laravel Sanctum + API Keys
- **Queue/Cache**: Redis
- **Testing**: PHPUnit

## 📦 Repositories

| Repository | Description | Status |
|------------|-------------|--------|
| **francoconnect-core** | Core system with API, portals, and base functionality | ✅ Active |
| **francoconnect-attendance** | Attendance tracking and kiosk system | ✅ Active |
| **francoconnect-task-manager** | Project management and job tracking | ✅ Active |
| **francoconnect-docs** | Comprehensive documentation and guides | ✅ Active |

## 🎨 Design Philosophy

- **🎯 Purpose-Built** - Designed for UK construction and service industries
- **🔓 Extensible Architecture** - Plugin system allows unlimited customization
- **⚡ Performance-First** - Optimized queries, caching, and lean codebase
- **🎨 Modern UI** - Clean, responsive interface with Tailwind CSS
- **🔐 Security-Focused** - Role-based access, API key management, CSRF protection
- **📱 Mobile-Ready** - Responsive design works on all devices

## 🧑‍💻 For Developers

### Contributing

We welcome contributions! Whether it's:

- 🐛 Bug fixes
- ✨ New features
- 📖 Documentation improvements
- 🔌 Plugin development

Check individual repositories for contribution guidelines.

## 🏢 Use Cases

Perfect for businesses that need:

- Employee attendance and time tracking
- Client and project management
- Quote and invoice generation
- Multi-location management
- Customer portals and communication
- Legal compliance documentation
- Third-party system integrations via API

## 📄 License

FrancoConnect is proprietary software. All rights reserved.

---

**Current Version**: 2.0 (Plugin Architecture)
**Target Market**: UK Construction & Service Companies
**Status**: Active Development
