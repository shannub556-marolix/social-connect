# 🚀 Social-Connect - User Access Guide

## 📋 Project Overview
Social-Connect is a modern, real-time social media platform built with Django REST Framework backend and React TypeScript frontend. The platform features comprehensive user authentication, real-time notifications, post management, engagement system, and admin panel.

## 🌟 Key Features
- **Email-based registration** with verification
- **JWT token authentication** with refresh tokens
- **Password reset** via email
- **Role-based access control** (User/Admin)
- **Real-time notifications** via Supabase
- **Responsive design** (Mobile & Web)
- **Post creation and management**
- **Follow/Unfollow system**
- **Like and comment functionality**
- **Admin panel** for platform management

## 🚀 Quick Start Guide

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- Email account for verification

### Accessing the Platform

#### 1. **Social Connect Access**
- **URL**: https://social-connect-frontend-steel.vercel.app/login
- **Alternative**: `http://localhost:5173` (if running locally)

## 🔐 Authentication System

### Default Admin Credentials
```
Email: shanmukha@example.com
Password: Strongpass123!
```

### User Registration Process

#### Step 1: Register New Account
1. Navigate to the registration page (`/register`)
2. Fill in the required information:
   - **Username**: Choose a unique username
   - **Email**: Enter your valid email address
   - **Password**: Create a strong password (min 8 characters)
   - **Confirm Password**: Re-enter your password

#### Step 2: Email Verification
1. **Check your email** for verification link
2. **Click the verification link** in the email
3. **Account will be activated** automatically
4. **Return to the platform** and login

#### Step 3: Login
1. Navigate to login page (`/login`)
2. Enter your credentials:
   - **Email/Username**: Your registered email or username
   - **Password**: Your account password
3. Click "Login" to access the platform

### Password Reset Process
1. Click "Forgot Password?" on login page
2. Enter your registered email address
3. Check email for password reset link
4. Click the link and set a new password
5. Login with new credentials

## 📱 Platform Accessibility

### Web Access
- **Desktop**: Full-featured experience with all functionality
- **Tablet**: Responsive design optimized for touch interaction
- **Mobile**: Mobile-first design with touch-friendly interface

### Mobile Responsiveness
- **Responsive Design**: Automatically adapts to screen size
- **Touch-Friendly**: Large buttons and touch targets
- **Mobile Navigation**: Optimized navigation for mobile devices
- **Image Optimization**: Fast loading on mobile networks

### Browser Compatibility
- **Chrome**: 90+ (Recommended)
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

## 🎯 Platform Features

### User Dashboard
- **Profile Management**: Edit bio, avatar, website, location
- **Privacy Settings**: Public, Private, Followers-only
- **Activity Feed**: View posts from followed users
- **Notifications**: Real-time notification center

### Content Creation
- **Create Posts**: Text content with image support
- **Image Upload**: JPEG/PNG files (max 2MB)
- **Post Categories**: Organize content by category
- **Privacy Controls**: Control who can see your posts

### Social Features
- **Follow Users**: Connect with other users
- **Like Posts**: Show appreciation for content
- **Comment System**: Engage in discussions
- **Real-time Updates**: Live engagement counters

### Admin Panel (Admin Users Only)
- **User Management**: View and manage all users
- **Content Moderation**: Review and manage posts
- **Platform Statistics**: View usage analytics
- **System Administration**: Platform configuration

## 🔔 Real-time Features

### Live Notifications
- **Follow Notifications**: When someone follows you
- **Like Notifications**: When someone likes your post
- **Comment Notifications**: When someone comments on your post
- **Real-time Updates**: Instant notification delivery

### Live Engagement
- **Like Counters**: Real-time like count updates
- **Comment Counters**: Live comment count updates
- **Feed Updates**: New posts appear instantly
- **User Activity**: Live user status updates

## 📧 Email System

### SMTP Configuration
The platform uses configured SMTP email service for:
- **Account Verification**: Email verification links
- **Password Reset**: Secure password reset links
- **Notifications**: Important account notifications
- **Admin Communications**: System announcements

### Email Features
- **Verification Links**: One-click account activation
- **Password Reset**: Secure token-based reset
- **Welcome Emails**: New user onboarding
- **Security Alerts**: Account security notifications

## 🔒 Security Features

### Authentication Security
- **JWT Tokens**: Secure token-based authentication
- **Password Policies**: Strong password requirements
- **Email Verification**: Required account activation
- **Session Management**: Secure session handling

### Data Protection
- **HTTPS Encryption**: Secure data transmission
- **Input Validation**: Protection against malicious input
- **XSS Protection**: Cross-site scripting prevention
- **CSRF Protection**: Cross-site request forgery protection

## 🛠️ Technical Support

### Common Issues & Solutions

#### Login Problems
- **Email not verified**: Check email and click verification link
- **Wrong password**: Use password reset feature
- **Account locked**: Contact admin for assistance

#### Email Issues
- **Verification email not received**: Check spam folder
- **Reset email not sent**: Verify email address is correct
- **Email delivery delays**: Wait 5-10 minutes for delivery

#### Mobile Access Issues
- **Slow loading**: Check internet connection
- **Display problems**: Refresh page or clear cache
- **Touch issues**: Ensure browser is updated

### Getting Help
1. **Check FAQ**: Common questions and answers
2. **Contact Support**: Email support team
3. **Admin Panel**: For admin-related issues
4. **Documentation**: Technical documentation available

## 📊 Platform Statistics

### Current Features
- ✅ User authentication system
- ✅ Email verification system
- ✅ Post creation and management
- ✅ Follow/unfollow system
- ✅ Like and comment functionality
- ✅ Real-time notifications
- ✅ Admin panel
- ✅ Mobile responsiveness
- ✅ SMTP email integration

### Upcoming Features
- 🔄 Direct messaging system
- 🔄 Story/Status feature
- 🔄 Advanced search and filters
- 🔄 Mobile app (React Native)
- 🔄 Push notifications

## 🎉 Getting Started

### First Time Users
1. **Register**: Create your account with email verification
2. **Complete Profile**: Add bio, avatar, and personal information
3. **Follow Users**: Connect with other platform users
4. **Create Content**: Share your first post
5. **Engage**: Like and comment on other posts

### Admin Users
1. **Login**: Use admin credentials provided
2. **Access Admin Panel**: Navigate to admin dashboard
3. **Manage Users**: View and manage user accounts
4. **Moderate Content**: Review and manage posts
5. **View Statistics**: Monitor platform usage

---



### Admin Access
- **Email**: shanmukha@example.com
- **Password**: Strongpass123!
- **Admin Panel**: `/admin-dashboard`

---

**🌟 Welcome to Social-Connect! Start connecting with others today!**
