# 🎬 BookMyTicket – Online Movie Ticket Booking System

A full-stack web application that digitizes the movie ticket booking experience — from browsing shows to interactive seat selection and booking confirmation — with a complete theater admin dashboard.

Built during my Java Full Stack internship at QSpiders Rajajinagar, Bangalore. Demonstrates end-to-end development using Java Servlets, JSP, JDBC, and MySQL on Apache Tomcat.

## Features

**User Module**
- Registration, login, and secure session management
- Browse movies, view show timings and available seats
- Interactive seat selection with real-time availability
- Instant booking confirmation

**Admin Module**
- Add, edit, and delete movies and shows
- Manage seat availability and theater schedules
- View and track all booking records from a dashboard

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript, JSP |
| Backend | Core Java, Java Servlets |
| Database | MySQL via JDBC |
| Server | Apache Tomcat |
| IDE | Eclipse / VS Code |

## Architecture
Browser (HTML/CSS/JSP)
↓
Java Servlets ←→ Session Management
↓
JDBC Layer
↓
MySQL Database

Follows MVC-style architecture. Servlets handle business logic, JDBC connects to MySQL, JSP renders the frontend dynamically.

## Getting Started

**Prerequisites**
- Java JDK 8+
- Apache Tomcat 9+
- MySQL 8+
- Eclipse IDE

**Setup**
1. Clone this repo: `git clone https://github.com/SaiAgalavi/movie-ticket-booking.git`
2. Import into Eclipse as a Dynamic Web Project
3. Create MySQL database and run `/db/schema.sql`
4. Update DB credentials in `DBConnection.java`
5. Deploy to Tomcat → open `http://localhost:8080/BookMyTicket`

## Key Learnings

- Full-stack Java web development (Servlet + JSP + JDBC)
- Session management and request-response lifecycle
- Relational database design and SQL query optimization
- Debugging real-world connectivity and workflow issues

## Future Enhancements

- [ ] Payment gateway integration (Razorpay)
- [ ] Mobile responsive UI
- [ ] Real-time seat locking
- [ ] Email/SMS booking confirmation
- [ ] Cloud deployment (AWS / Railway)

## Developer

**Sai Agalavi**
BE – Electronics and Communication Engineering
Java Full Stack Internship — QSpiders Rajajinagar, Bangalore
🔗 [LinkedIn](https://www.linkedin.com/in/sainath-agalavi/)
