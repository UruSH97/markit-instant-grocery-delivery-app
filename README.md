# MARKIT – Real-Time Instant Grocery Delivery System

MARKIT is a prototype for a real-time, scalable, and modular grocery delivery platform. The system supports three major actors — **Customers**, **Shopkeepers**, and **Delivery Agents**, each with tailored dashboards. The goal is to simulate real-time ordering, stock management, and delivery logistics with instant updates and interaction between stakeholders.

---

## Project Objective

To simulate and build a scalable event-driven delivery app for groceries that reflects actual supply chain interactions including:

- Real-time stock updates from vendors
- Dynamic cart and order management for users
- Live tracking of deliveries
- Feedback and issue escalation support

---

## Functional Modules

### 1. Customer Dashboard
- Register, login, and manage profile
- Browse nearby shops and available inventory
- Place instant orders
- View order history and status
- Provide feedback or raise complaints

### 2. Shopkeeper Dashboard
- Upload and update real-time stock inventory
- Accept or reject orders
- Update stock quantities post-order
- View complaints and feedback
- Dashboard for shop statistics (orders, income)

### 3. Delivery Agent Dashboard
- View available deliveries
- Accept, reject, or complete a delivery
- Live status updates to customer & vendor
- Agent performance stats (delivery time, ratings)

---

## Key Features

- **Modular Architecture**: Each actor has a distinct UI and data pipeline
- **Real-Time Updates**: Simulated delivery tracking and live stock availability
- **Order Lifecycle Management**: Cart → Confirmed → Accepted → In Transit → Delivered
- **Rating System**: For customers to rate shopkeepers and agents
- **Complaint Escalation**: A simple feedback form to simulate post-delivery issue handling

---

## Technologies Used

- **Frontend**: HTML, CSS, JS (prototyped screens, UI flows)
- **Backend (Proposed)**: Flask / Node.js with WebSockets (for real-time)
- **Database (Simulated)**: Static JSON/CSV mocks; future-ready for MongoDB/PostgreSQL
- **Architecture Design**: Event-driven modular blocks with simulation for APIs

---

## Design Architecture

- **3-Tier System**: UI layer, logic layer, and data layer
- **Event Queue Simulation**: To manage order and delivery pipeline
- **Mock Routing**: Pre-defined paths to simulate delivery logic and ETA

---

## Evaluation Metrics

- **Usability**: Separate dashboards with focused UI
- **Scalability**: Designed to extend for large user base with real-time interaction
- **Performance**: Simulated order-to-delivery cycle time tracking
- **Error Handling**: Flow for feedback and complaints

---

## Files Included

- `GP1_Report.pdf`: Initial system design, use cases, data flow
- `GP3_Report.pdf`: Final integrated project report with implementation and testing
- `GP3_Presentation.pdf`: Slide deck for live demo and walkthrough
- UI Screens (PNG): Wireframes and screen mockups

---

## Key Learnings & Takeaways

- Designing scalable modular systems
- Real-time order simulation and stakeholder coordination
- Building low-latency dashboards with role-based access
- Visualizing delivery logistics using route mapping logic

---

## Future Improvements

- Integrate real-time backend using WebSockets and MQTT
- Add payment gateway (Razorpay/Stripe) for online payments
- Optimize delivery routing using Dijkstra/A* algorithms
- Mobile-first frontend using React Native or Flutter



