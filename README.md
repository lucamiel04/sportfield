# SportField - Sports Court Booking Platform

A web application that allows users to book sports courts (football, padel, tennis, basketball) online.

## Description

SportField is a Spring Boot web application where users can create an account, browse available courts, make reservations and view their booking history. Admins can manage courts, time slots and user accounts.

This project was built as part of a web development course at university.

## User Stories

### Story 1 - Booking a court

As a registered user,
I want to choose a sport, an available court and a time slot,
so that I can easily make a reservation without having to call anyone.

Example: Marc wants to play padel on Saturday morning. He logs in, filters by "Padel", sees the available slots on Saturday, picks 10am-11am and confirms his booking. He gets a confirmation in his personal space.

### Story 2 - Viewing booking history

As a logged-in user,
I want to see a list of my past and upcoming reservations,
so that I can keep track of my sports activities and manage my schedule.

Example: Sophie wants to check if she already booked a court this month. She goes to "My Reservations" and sees all her sessions with the court name, sport and time.

### Story 3 - Admin managing courts

As an admin,
I want to add new courts, edit their details and manage their availability,
so that I can keep the catalogue up to date and control access to facilities.

Example: The admin notices a tennis court is under renovation. He marks it as unavailable from the admin panel, which removes it from search results automatically.

## Features

- User registration and login with Spring Security (passwords encrypted with BCrypt)
- User profile page
- Search and filter courts by sport, date and time slot
- Booking system with confirmation
- Booking history
- Admin panel to manage courts, time slots and users
- Responsive design with Bootstrap

## Tech Stack

- Backend: Spring Boot (Java)
- Frontend: Thymeleaf, HTML, CSS, Bootstrap
- Database: PostgreSQL
- Security: Spring Security with BCrypt
- Deployment: Docker and Docker Compose

## Running the project

```bash
docker-compose up --build
```

The application will be available at http://localhost:8080

## Wireframes

Figma link: https://www.figma.com/design/8UvRFgZA9vDMjk2GNeli4s/Untitled?node-id=0-1&t=6NSbxyOt4KDhAumA-1

## Project Board

Trello link: https://trello.com/invite/b/69e9f1c2710aa79534083ed4/ATTI98b85bb618c3cca4f352668dd353db25F51F8B7C/sportfield
