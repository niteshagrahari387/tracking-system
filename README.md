# SCHOOL BUS TRACKER MANAGEMENT SYSTEM

**Smart & Connected School Transportation**

A responsive, role-based frontend prototype for a school transport management system. It follows the project documentation’s Administrator, Driver and Parent roles and uses fictional Mumbai-style demo records.

## Run locally

```bash
npm install
npm run dev
```

Open the local address printed by Vite (normally `http://localhost:5173`). No paid API key or backend is required for the prototype. The interactive OpenStreetMap tiles need an internet connection.

## Demo sign-in

Choose a role on the login screen. The demo credentials are prefilled; the password for each role is `demo1234`.

| Role          | Demo username              |
| ------------- | -------------------------- |
| Administrator | `admin@school.demo`        |
| Driver        | `rajesh.patil@school.demo` |
| Parent        | `parent@school.demo`       |

## Included

- Administrator dashboard with fleet overview, searchable student, parent, bus, driver and route records, trips, notifications, reports and settings.
- OpenStreetMap fleet tracking with simulated bus locations, route lines and selected vehicle details.
- Driver dashboard with trip controls, route stops, boarding toggles, location sharing and a demo SOS confirmation flow.
- Parent dashboard restricted to the assigned child’s BUS-01 route, trip information and notifications.
- In-session add and edit forms, record removal, route stop ordering, CSV report download and print view.
- Responsive navigation and layouts for desktop and mobile.

## Demo boundaries

All records and account details are fictional. GPS positions, ETA and trip events are simulated in the browser; there is no live GPS device, backend, database, deployment or real emergency-service integration. Data changes are held in the current browser session and are not shared with a school.

## Validation

```bash
npm run build
npm run lint
```
