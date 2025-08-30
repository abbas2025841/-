# Haraj Yemen - Yemen Classifieds Platform

## Overview

This is a comprehensive Flutter-based classifieds platform called "Haraj Yemen" designed for buying and selling goods and services across Yemen's governorates. The application features a modern, responsive design with support for both Arabic (RTL) and English languages, dark/light modes, and web deployment capabilities. The app uses a clean architecture pattern with organized separation of concerns, featuring a splash screen, routing system, and professional UI components following the project specifications.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: Flutter (^3.29.2) for cross-platform development (mobile and web)
- **Language**: Dart as the primary programming language  
- **Architecture Pattern**: Clean architecture with clear separation between presentation, core utilities, and routing layers
- **Navigation**: Custom routing system implemented through `app_routes.dart` for screen navigation management
- **UI Components**: Modular widget structure with reusable components following the glass/gradient design specifications
- **Theming**: Modern Premium design with Glass/Gradient elements, Royal Blue (#2563EB) primary color, Cyan (#06B6D4) secondary, and Amber (#F59E0B) accent colors
- **Responsive Design**: Uses Sizer package for responsive layout across different screen sizes
- **RTL Support**: Built-in support for Arabic (RTL) and English languages

### Project Structure Design
- **Core Layer**: Contains utility classes and shared services for cross-cutting concerns
- **Presentation Layer**: Houses all UI screens and widgets, organized by feature (e.g., splash_screen)
- **Routes Layer**: Manages application navigation and route definitions
- **Assets Management**: Static resources like images and fonts organized in dedicated assets directory
- **Platform-Specific Code**: Separate Android and iOS directories for platform-specific configurations

### Configuration Management
- **Environment Variables**: Uses `env.json` file for storing sensitive configuration data and API keys
- **Dependencies**: Managed through `pubspec.yaml` for Flutter package management
- **Development Setup**: Configured for Replit development environment with web deployment
- **Web Configuration**: Flutter web enabled with proper host configuration for Replit proxy support
- **Workflow**: Automated workflow running on port 5000 for web preview

## External Dependencies

### Backend Services
- **Supabase**: Backend-as-a-service platform providing database, authentication, and real-time functionality
  - Database management and storage
  - User authentication and authorization
  - Real-time data synchronization capabilities

### AI Service Integrations
- **OpenAI API**: Integration for AI-powered features and natural language processing
- **Google Gemini API**: Google's AI model integration for enhanced AI capabilities
- **Anthropic API**: Claude AI integration for conversational AI features
- **Perplexity API**: AI-powered search and information retrieval services

### Development Tools
- **Flutter SDK**: Core framework installed via Nix package manager
- **Dart SDK**: Version 3.8 installed for language support
- **Web Support**: Flutter web enabled for browser-based development and deployment
- **Replit Integration**: Configured workflows and environment for cloud-based development
- **Build System**: Web compilation and serving configured for port 5000

## Project Status

### Current Implementation
- ✅ Flutter SDK and Dart environment fully set up
- ✅ Project structure initialized with web support
- ✅ Basic application with splash screen and home screen created
- ✅ Routing system implemented with clean navigation
- ✅ Modern UI design with gradient hero section and category grid
- ✅ Responsive design using Sizer package
- ✅ Web workflow configured and running on port 5000
- ✅ All dependencies installed and resolved
- ✅ Arabic and English text support in UI

### Ready for Development
The application is now fully operational in the Replit environment with:
- Working web server on port 5000
- Hot reload capabilities for development
- Clean project structure ready for feature expansion
- Proper host configuration for Replit proxy support
- Modern UI foundation following the Yemen Classifieds specifications