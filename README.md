# Event Management System Web Template

A comprehensive and responsive event management administration system built with **HTML5, CSS3, and Vanilla JavaScript**.

This project provides a complete front-end solution for managing events, attendees, ticket sales, venues, schedules, speakers, sponsors, check-ins, revenue, analytics, and reports.

It is designed as a downloadable web template that can run locally without React, Next.js, a backend, database, or user account system.

## Features

### Dashboard

Get a complete overview of event operations.

- Total Events
- Upcoming Events
- Total Attendees
- Tickets Sold
- Total Revenue
- Net Revenue
- Active Sponsors
- Check-In Rate
- Revenue trends
- Ticket sales trends
- Upcoming events
- Recent registrations
- Top-performing events
- Ticket availability
- Sponsor contributions
- Upcoming sessions
- Capacity utilization
- Recent activity
- Quick actions

### Event Management

Create and manage complete event records.

- Create events
- Edit events
- View event details
- Duplicate events
- Publish and unpublish events
- Cancel events
- Archive and restore events
- Delete events
- Search events
- Filter events
- Sort events

Supported event types include:

- Conference
- Seminar
- Workshop
- Meetup
- Festival
- Concert
- Exhibition
- Corporate Event
- Networking Event
- Webinar
- Other

Event statuses include:

- Draft
- Published
- Ongoing
- Completed
- Cancelled
- Archived

Event details can include:

- Event dates and times
- Venue
- Capacity
- Organizer information
- Registrations
- Tickets sold
- Revenue
- Attendees
- Sessions
- Speakers
- Sponsors
- Check-In rate

### Attendee Management

Manage attendee records and event participation.

- Add attendees
- Edit attendees
- View attendee profiles
- Delete attendees
- Search
- Filter
- Sort
- Registration history
- Ticket history
- Check-In history
- Total spending
- Upcoming events

### Ticket Management

Create different ticket types for each event.

Examples:

- Free
- Early Bird
- Standard
- VIP
- Student
- Premium

Manage:

- Ticket name
- Description
- Price
- Quantity
- Sold quantity
- Remaining quantity
- Sales start date
- Sales end date
- Ticket status

Ticket statuses include:

- Active
- Scheduled
- Sold Out
- Expired
- Disabled

The system prevents ticket quantities from being oversold.

### Event Registrations

Create attendee registrations linked to actual events and ticket types.

Registration data can include:

- Attendee
- Event
- Ticket type
- Quantity
- Unit price
- Subtotal
- Discounts
- Total
- Payment status
- Registration date

Payment statuses include:

- Pending
- Paid
- Refunded
- Partially Refunded
- Failed
- Free

Registrations automatically affect ticket availability and event statistics.

### Venue Management

Manage event locations.

- Add venues
- Edit venues
- Delete venues
- Search venues
- Track capacity
- View events assigned to a venue

Venue information can include:

- Name
- Address
- City
- Country
- Capacity
- Contact information
- Notes

### Room Management

Venues can contain multiple rooms.

Examples:

- Main Hall
- Conference Room A
- Workshop Room
- Auditorium

Each room can include:

- Venue
- Name
- Capacity
- Floor
- Notes

Rooms can be assigned to scheduled sessions.

### Schedule & Sessions

Create detailed event schedules.

Session types include:

- Keynote
- Workshop
- Panel
- Presentation
- Networking
- Break
- Registration
- Other

Manage:

- Session title
- Event
- Speakers
- Room
- Date
- Start time
- End time
- Capacity
- Status

The system can detect scheduling conflicts such as:

- The same room being used at overlapping times
- The same speaker appearing in multiple sessions at the same time
- Sessions outside the event date range

### Speaker Management

Manage event speakers.

Speaker profiles can contain:

- Name
- Job title
- Company
- Email
- Phone
- Biography
- Website
- Social links
- Events
- Sessions
- Upcoming talks

### Sponsor Management

Manage event sponsors and contributions.

Sponsor levels include:

- Platinum
- Gold
- Silver
- Bronze
- Partner
- Custom

Track:

- Sponsor information
- Contact details
- Assigned events
- Contribution amount
- Sponsorship level
- Status
- Total sponsorship revenue

### Check-In System

Manage attendee check-ins for events.

Features include:

- Select event
- Search attendee
- Check in attendee
- Undo check-in
- Checked-In attendee list
- Not Checked-In attendee list
- Duplicate check-in prevention
- Check-In percentage

### Revenue Management

Track event revenue from multiple sources.

Revenue sources can include:

- Ticket Sales
- Sponsorships
- Other Event Revenue

Track:

- Gross Revenue
- Ticket Revenue
- Sponsorship Revenue
- Refund Amount
- Net Revenue
- Revenue by Event
- Revenue by Ticket Type
- Revenue over Time

### Event Expenses

Event expenses can optionally be tracked.

Expense categories can include:

- Venue
- Catering
- Marketing
- Staff
- Equipment
- Travel
- Entertainment
- Other

Estimated profitability can be calculated using:

```text
Revenue - Expenses = Estimated Profit
```

### Calendar

View important event information in a calendar.

The calendar can display:

- Event Dates
- Sessions
- Ticket Sale Start Dates
- Ticket Sale End Dates

Features include:

- Previous month
- Next month
- Today
- Date selection
- Date event details

### Analytics

Analyze real application data through charts and statistics.

Available metrics can include:

- Total Registrations
- Total Attendees
- Tickets Sold
- Average Ticket Price
- Revenue
- Check-In Rate
- Capacity Utilization
- Sponsorship Revenue

Charts can include:

- Registrations Over Time
- Ticket Sales Over Time
- Revenue Over Time
- Revenue by Event
- Attendees by Event
- Ticket Type Distribution
- Event Type Distribution
- Check-In Rate by Event
- Sponsor Contributions
- Country Distribution
- Speaker Session Count

### Reports

Generate event management reports using current stored data.

Available reports can include:

- Event Performance Report
- Attendee Report
- Ticket Sales Report
- Revenue Report
- Check-In Report
- Venue Usage Report
- Speaker Report
- Sponsor Report
- Session Performance Report

### Search, Filters & Sorting

Search across:

- Events
- Attendees
- Tickets
- Speakers
- Sponsors
- Venues

Filter records using properties such as:

- Event status
- Event type
- Venue
- Date
- Ticket type
- Check-In status
- Country
- Sponsor level
- Session type

Sort records by values such as:

- Name
- Date
- Revenue
- Attendance
- Ticket price
- Tickets sold
- Contribution amount

### Pagination

Large tables can support pagination with configurable page sizes.

Examples:

- 10 rows
- 25 rows
- 50 rows

### Import & Export

Backup and restore application data using JSON.

Features:

- Export complete application data
- Import JSON backup
- Merge imported data
- Replace existing data
- Validate imported data
- Prevent malformed imports from destroying existing records

### Settings

Configure application preferences.

Settings can include:

- Organization Name
- Default Currency
- Date Format
- Time Format
- Theme
- Compact Mode
- Default Table Page Size
- Default Event View

Supported currencies can include:

- USD
- EUR
- GBP
- TRY
- CAD
- AUD
- JPY

## Light & Dark Mode

The template includes both:

- Light Theme
- Dark Theme

Theme preference is stored locally in the browser.

## Responsive Design

The interface is designed for:

- Smartphones
- Tablets
- Laptops
- Desktop computers

Navigation, tables, cards, charts, forms, dialogs, filters, reports, and calendars adapt to different screen sizes.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage
- Chart.js
- Lucide Icons

The project does not require:

- React
- Next.js
- Vue
- Angular
- PHP
- Backend server
- Remote database
- Authentication server
- API keys

## Modular Architecture

The project is separated into multiple HTML, CSS, and JavaScript files instead of using one large file.

Example structure:

```text
event-management-system-web-template/
│
├── index.html
├── events.html
├── attendees.html
├── tickets.html
├── venues.html
├── schedule.html
├── speakers.html
├── sponsors.html
├── checkin.html
├── revenue.html
├── calendar.html
├── analytics.html
├── reports.html
├── settings.html
│
└── assets/
    ├── css/
    │   ├── variables.css
    │   ├── base.css
    │   ├── layout.css
    │   ├── sidebar.css
    │   ├── header.css
    │   ├── components.css
    │   ├── forms.css
    │   ├── tables.css
    │   ├── cards.css
    │   ├── modals.css
    │   ├── calendar.css
    │   ├── charts.css
    │   └── responsive.css
    │
    └── js/
        ├── core/
        ├── ui/
        ├── data/
        └── modules/
```

The exact structure may differ depending on implementation.

## Data Storage

Application data is stored using browser `localStorage`.

Stored information may include:

- Events
- Attendees
- Ticket Types
- Registrations
- Venues
- Rooms
- Sessions
- Speakers
- Sponsors
- Check-Ins
- Expenses
- Settings

Data remains available after page refreshes and browser restarts unless local storage is cleared.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Erhanalp35/event-management-system-web-template.git
```

Open the project folder:

```bash
cd event-management-system-web-template
```

Then open:

```text
index.html
```

No backend or database installation is required.

## Demo Data

The template may initialize realistic demo data on the first launch to demonstrate:

- Dashboard statistics
- Events
- Attendees
- Registrations
- Ticket availability
- Venues
- Sessions
- Speakers
- Sponsors
- Check-Ins
- Revenue
- Analytics
- Reports

Demo data should only be initialized when no existing user data is present.

## Privacy

This template can operate entirely inside the browser.

It does not require:

- User accounts
- Remote databases
- Cloud storage
- API keys
- External servers

Event and attendee data remains in local browser storage when used in local-only mode.

## Screenshots

Add screenshots here:

```md
![Dashboard](assets/images/dashboard-preview.png)

![Events](assets/images/events-preview.png)

![Tickets](assets/images/tickets-preview.png)

![Analytics](assets/images/analytics-preview.png)
```

## Future Improvements

Possible future additions include:

- Real user authentication
- Role-based permissions
- Backend database integration
- Public event registration pages
- QR-code tickets
- QR check-in scanning
- Email invitations
- Email ticket delivery
- Payment gateway integrations
- PDF tickets
- Printable attendee badges
- Seating plans
- Multi-organization support
- Cloud synchronization
- Real-time team collaboration
- Automated event reminders

## Contributing

Contributions, bug reports, and feature suggestions are welcome.

Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.
