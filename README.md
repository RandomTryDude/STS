# Simple Ticket System (STS) - Python - Django

A ticketing system built in Python with Django as the backend.

The project was put together in a few days in response to a friend's task involving Django. While it wasn't a technology I had mastered, I decided to build something to explore its capabilities.

## Functionality:

- **Login / Password Recovery (mail)**
  - As an on-premise solution, there is no provision for users to register themselves. Instead, accounts must be created by a SuperUser.

- **Ticket Creation / Display**
  - Users can create tickets with the following fields: Title, Description, Equipment Concerned, and State. The display includes the date of ticket creation, a search feature to filter by state (completed, not opened yet, in progress), and a Solver search based on the SuperUser list.

- **Equipment Creation / Removal / Display**
  - Users can create equipment with fields such as UID, Name, and Warranty Date. The display includes a search feature to filter equipment by name or UID.

- **Pie Chart on Home Page (based on ChartJS)**
  - A pie chart on the home page provides a quick overview of tickets categorized as "Completed," "Not opened yet," and "In progress." Clicking on a category redirects to the Ticket Display with filters based on the state.

## Functionality Capacity:

- **Login / Password Recovery**
  - User registration is not enabled. Accounts must be created by a SuperUser.

- **Ticket Creation / Display**
  - Tickets can be created with fields: Title, Description, Equipment Concerned, and State. The display includes the date of creation, a search for filtering by state, and a Solver search based on the SuperUser list.

- **Equipment Creation / Removal / Display**
  - Equipment creation includes fields: UID, Name, and Warranty Date. A search feature is available to filter equipment by name or UID.

- **Pie Chart**
  - The pie chart on the home page categorizes tickets into "Completed," "Not opened yet," and "In progress." Clicking on a category redirects to the Ticket Display with state-based filters.

This information is intended for a GitHub readme.
