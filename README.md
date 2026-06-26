# CALIFOXGLOBALTRADELTD
Califox Global Trade LTD
│
├── Frontend (React + TypeScript + Tailwind CSS)
│   ├── Landing Page
│   ├── Login
│   ├── Register
│   ├── User Dashboard
│   ├── Deposit
│   ├── Withdrawal
│   ├── Investment Plans
│   ├── Portfolio
│   ├── Transaction History
│   ├── Profile
│   └── Settings
│
├── Backend (Node.js + Express)
│   ├── Authentication API
│   ├── User API
│   ├── Investment API
│   ├── Deposit API
│   ├── Withdrawal API
│   ├── Admin API
│   └── Notifications
│
├── Database (PostgreSQL)
│
└── Admin Dashboard
    ├── Users
    ├── Deposits
    ├── Withdrawals
    ├── Investment Plans
    ├── Reports
    └── Settings








Build Request: Califox Global Trade LTD Investment Platform

Create a modern, responsive, full-stack investment management platform called Califox Global Trade LTD. The application should have a premium black, gold, and white design with smooth animations, a professional financial appearance, and work on desktop, tablet, and mobile devices.

Technology Stack

Frontend:

- React
- TypeScript
- Tailwind CSS
- Framer Motion
- React Router
- React Query
- Chart.js or TradingView widgets

Backend:

- Node.js
- Express.js
- Prisma ORM
- PostgreSQL
- JWT Authentication
- bcrypt password hashing

Public Website

Build a modern landing page containing:

- Hero section
- Company overview
- Investment plans
- Why choose us
- Market overview
- Statistics
- FAQ
- Testimonials
- Contact form
- Footer
- Responsive navigation

Authentication

Create a secure authentication system with:

- User registration
- User login
- Password hashing
- JWT authentication
- Forgot password page
- Password reset support
- Email verification support (structure ready)

User Dashboard

After login, users should access a dashboard containing:

- Portfolio balance
- Total investment
- Available balance
- Profit/Loss
- ROI percentage
- Investment summary
- Portfolio performance chart
- Recent activity
- Notifications

Investment Plans

Create an admin-managed investment plan system.

Each plan should contain:

- Plan name
- Description
- Minimum investment
- Maximum investment
- Investment duration
- Risk level
- Status (Active/Inactive)

The application should calculate returns according to the investment configuration defined by the administrator. Any displayed performance should accurately reflect the configured investment rules and applicable regulations.

Deposits

Users should be able to:

- Submit deposit requests
- Choose payment method
- View deposit history
- Track deposit status
- Upload payment proof if required

Supported payment methods:

- Bitcoin (BTC)
- Ethereum (ETH)
- USDT (TRC20)
- USDT (ERC20)
- USDT (BEP20)
- Bank Transfer

Administrators should be able to approve or reject deposit requests.

Withdrawals

Users should be able to:

- Request withdrawals
- Choose payment method
- Save payout wallet or bank details
- View withdrawal history
- Track request status

Administrators should review and approve or reject withdrawal requests.

Transaction History

Create a complete transaction ledger displaying:

- Deposits
- Withdrawals
- Investment activity
- Profits credited
- Fees (if applicable)
- Date and time
- Status
- Transaction ID

User Profile

Allow users to:

- Edit profile
- Change password
- Manage notification preferences
- Enable optional two-factor authentication
- View login history

Admin Dashboard

Create a secure admin dashboard with:

User Management

- View users
- Search users
- Suspend or reactivate users
- Edit user details

Investment Management

- Create plans
- Edit plans
- Activate or deactivate plans

Deposit Management

- View deposit requests
- Approve or reject deposits

Withdrawal Management

- View withdrawal requests
- Approve or reject withdrawals

Reports

- Dashboard analytics
- Deposits
- Withdrawals
- User growth
- Investment performance
- Export reports

Notifications

- Send announcements
- Notify users of account activity

Database

Create tables for:

- Users
- Admins
- Investment Plans
- Investments
- Deposits
- Withdrawals
- Transactions
- Notifications
- Audit Logs

Security

Implement:

- Password hashing using bcrypt
- JWT authentication
- Role-based authorization
- CSRF protection
- Rate limiting
- Input validation
- Secure API endpoints
- Audit logging

Design

Theme:

- Primary: Gold
- Secondary: Black
- Accent: White

Style:

- Premium
- Professional
- Financial
- Smooth animations
- Responsive
- Modern dashboard UI

Deliverables

Generate:

- Complete frontend
- Complete backend
- Database schema
- API endpoints
- Authentication system
- Admin dashboard
- User dashboard
- Responsive layouts
- Deployment-ready project
- README with setup instructions
- Environment variable template (.env.example)

The code should be clean, modular, well-commented, and production-ready.