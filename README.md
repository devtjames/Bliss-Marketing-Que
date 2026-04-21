# Bliss Marketing Que Website & Lead Management CMS

A dynamic digital agency website with an integrated custom CMS for managing services, projects, reviews, team members, and customer leads. Built with procedural PHP and MySQL, featuring an admin dashboard, contact automation, review moderation, and dynamic frontend rendering.

---

## 🚀 Project Overview

This project is a full-stack website solution developed for a digital marketing agency. It combines a visually engaging frontend with a powerful backend CMS that allows non-technical users to manage website content efficiently.

The system supports dynamic updates across services, projects, testimonials, and team members, while also handling customer inquiries through a structured lead management system.

---

## 🔄 System Flow

1. Visitors browse the website (services, projects, testimonials, etc.)
2. Users submit inquiries through the contact form
3. Data is stored in the database as leads
4. Email notifications are triggered:
   - Admin receives the lead
   - User receives an autoresponse
5. Users can submit reviews via the public interface
6. Reviews are moderated in the admin dashboard
7. Approved reviews appear as testimonials on the frontend
8. Admin manages all content via the CMS

---

## ✨ Key Features

- Dynamic homepage content rendering
- Service management with slug-based routing
- Project portfolio management
- Team member management
- Public review submission system
- Testimonial display system (image/video-based)
- Lead capture with PHPMailer email automation
- Newsletter subscription UI
- Admin dashboard with content control
- Secure environment-based configuration using `.env`

---

## 📸 Screenshots

> Add screenshots to a `/screenshots` folder and reference them below

### Homepage
![Homepage](screenshots/homepage.png)

### Admin Dashboard
![Dashboard](screenshots/dashboard.png)

### Services Page
![Services](screenshots/services.png)

### Contact Page
![Contact](screenshots/contact.png)

---

## 🛠 Tech Stack

- PHP (Procedural)
- MySQL (PDO)
- PHPMailer
- HTML5
- CSS3
- Tailwind CSS
- Bootstrap
- JavaScript
- Dotenv (vlucas/phpdotenv)

---


---

## 👨‍💻 My Role

I designed and developed the entire system, including:

- Database architecture and relationships
- CMS backend logic
- Dynamic frontend rendering
- Review moderation system
- Testimonial display system
- Email automation using PHPMailer
- Secure configuration using environment variables

---

## 🧠 Development Notes

This project was built using procedural PHP to allow rapid development and easy deployment while maintaining modular structure through reusable partials.

Security considerations included:
- Use of prepared statements (PDO)
- Environment-based configuration for sensitive data
- Controlled file uploads for reviews

The architecture prioritizes simplicity, flexibility, and scalability for small-to-medium business use.

---

## 📚 Documentation

- [System Architecture](docs/architecture.md)
- [Technical Decisions](docs/decisions.md)

---

## 📬 Contact

For collaboration or inquiries:

- Email: mail.devtjames@gmail.com
- GitHub: https://github.com/devtjames
