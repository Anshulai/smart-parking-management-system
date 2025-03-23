# Smart Parking Management System

A Django-based parking management system with dark theme support that allows users to manage parking spaces, reservations, and view parking availability in real-time.

## Features

- User Authentication (Login/Signup)
- Parking Zone Management
- Real-time Parking Space Availability
- Reservation System
- Dark/Light Theme Toggle
- Ticket Generation
- Checkout System

## Screenshots


![\[Screenshot of homepage with dark theme\]](<Screenshot from 2025-03-20 13-17-20.png>)


![\[Screenshot of available parking zones\]](<Screenshot from 2025-03-20 13-18-40.png>)


![\[Screenshot of reservation form\]](<Screenshot from 2025-03-20 13-19-05.png>)


![\[Screenshot of generated ticket\]](<Screenshot from 2025-03-20 13-18-40.png>)

## Setup Instructions



1. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables:
- Copy `.env.example` to `.env`
- Update the configuration as needed

4. Run migrations:
```bash
cd parking_management
python manage.py migrate
```

5. Run the development server:
```bash
python manage.py runserver
```

## Features in Detail

### Parking Zones
- View all available parking zones
- Check real-time availability
- View pricing information
- Location details

### Reservation System
- Select parking zone
- Choose dates
- Enter vehicle details
- Get confirmation and ticket

### Theme System
- Dark/Light theme toggle
- Theme preference persistence
- Responsive design
- Consistent styling across pages

## Current Sample Data

Parking Zones available:
1. West End Parking (75 slots)
2. Shopping Mall Parking (200 slots)
3. City Center Parking (150 slots)
4. Airport Parking (300 slots)
5. Hospital Parking (120 slots)
6. Metro Station Parking (250 slots)

## License

© 2021-2025 All Rights Reserved

## Contributors

- Original Design: Jeremiah George
- Development Team: [List of contributors]
