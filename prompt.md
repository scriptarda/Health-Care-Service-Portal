You are a senior software architect and principal full-stack engineer.

Build a complete production-ready Hospital Service Desk, Incident Management, Asset Management, Maintenance Management, Inventory Management, and Internal Support Platform using the provided UI designs/screens.

The goal is to create a modern enterprise SaaS application for hospitals, clinics, and large organizations where staff can report incidents such as computer failures, printer issues, Wi-Fi outages, software problems, medical equipment faults, facility issues, and service requests.

TECHNOLOGY STACK

Frontend:

* Next.js 15 App Router
* TypeScript
* Tailwind CSS
* shadcn/ui
* React Hook Form
* Zod Validation
* TanStack Query
* Zustand

Backend:

* NestJS
* TypeScript
* Prisma ORM

Database:

* PostgreSQL

Authentication:

* JWT
* Refresh Tokens
* RBAC
* MFA-ready

Storage:

* S3 compatible storage
* Local storage fallback

Notifications:

* Email
* SMS-ready
* Push notification ready

Real-time:

* Socket.IO

Reporting:

* Dashboard analytics
* Export to PDF
* Export to Excel

Architecture:

* Modular architecture
* Scalable enterprise architecture
* Clean code principles
* SOLID principles
* Repository pattern
* Service layer architecture

SYSTEM MODULES

1. Authentication Module

Features:

* Login
* Logout
* Forgot Password
* Reset Password
* User Registration
* Role Management
* Permissions
* Session Management
* Multi-factor Authentication support

Roles:

* Staff
* Nurse
* Doctor
* Technician
* Biomedical Engineer
* Department Manager
* Administrator
* Super Administrator

2. Dashboard Module

Staff Dashboard:

* My Open Tickets
* Resolved Tickets
* Recent Activity
* Quick Actions

Technician Dashboard:

* Assigned Tickets
* SLA Breaches
* Due Today
* Work Queue

Management Dashboard:

* Incident Trends
* Resolution Metrics
* Department Performance
* Asset Health

3. Incident Management

Ticket Features:

* Create Ticket
* Edit Ticket
* Assign Ticket
* Escalate Ticket
* Resolve Ticket
* Close Ticket
* Reopen Ticket

Fields:

* Ticket Number
* Title
* Description
* Category
* Subcategory
* Priority
* Severity
* Department
* Building
* Floor
* Room
* Asset
* Attachments

Categories:

* Computer
* Printer
* Scanner
* Wi-Fi
* Network
* Email
* Software
* Medical Equipment
* Facilities
* Security

Workflow:
New
Acknowledged
Assigned
In Progress
Waiting User
Waiting Vendor
Resolved
Closed

4. Service Request Module

Examples:

* New Computer Request
* Software Installation
* User Account Creation
* Email Setup
* Access Requests
* Hardware Request

Features:

* Approval Workflow
* Tracking
* Notifications

5. Asset Management

Features:

* Asset Registry
* Asset Assignment
* Asset Tracking
* Asset History
* Asset Lifecycle

Asset Fields:

* Asset ID
* Asset Tag
* Serial Number
* Model
* Manufacturer
* Purchase Date
* Warranty Date
* Department
* Assigned User
* Status

6. QR Code Management

Features:

* Generate QR Codes
* Scan QR Codes
* Quick Incident Reporting
* Asset Identification

7. Maintenance Management

Features:

* Preventive Maintenance
* Corrective Maintenance
* Work Orders
* Maintenance Calendar
* Service History

8. Inventory Management

Features:

* Spare Parts
* Stock Tracking
* Reorder Alerts
* Purchase Requests

9. Knowledge Base

Features:

* Articles
* Categories
* Search
* FAQ
* Attachments

10. Notification Center

Features:

* In-app Notifications
* Email Notifications
* SMS Integration Ready
* Push Notification Ready

11. SLA Management

Features:

* SLA Rules
* Response Targets
* Resolution Targets
* Escalation Rules
* SLA Dashboard

12. Reporting Module

Reports:

* Ticket Reports
* Asset Reports
* Department Reports
* Technician Reports
* SLA Reports
* Maintenance Reports

Charts:

* Bar Charts
* Pie Charts
* Line Charts
* KPI Cards

13. Audit System

Track:

* User Actions
* Ticket Changes
* Asset Changes
* Login History

14. Organization Structure

Features:

* Multi-Hospital Support
* Branches
* Departments
* Buildings
* Floors
* Rooms

DATABASE DESIGN

Generate complete Prisma schema for:

users
roles
permissions
departments
buildings
floors
rooms
tickets
ticket_comments
ticket_attachments
ticket_assignments
assets
asset_categories
asset_assignments
maintenance_tasks
maintenance_history
inventory_items
inventory_transactions
notifications
knowledge_articles
sla_rules
audit_logs

Generate:

* Database relationships
* Indexes
* Constraints
* Seed data

API DEVELOPMENT

Generate complete REST APIs:

Authentication APIs
User APIs
Role APIs
Department APIs
Ticket APIs
Asset APIs
Maintenance APIs
Inventory APIs
Knowledge Base APIs
Notification APIs
Report APIs

Include:

* Validation
* Authorization
* Pagination
* Filtering
* Search
* Sorting

UI IMPLEMENTATION

Use all supplied screens as design references.

Build:

* Responsive desktop layouts
* Tablet layouts
* Mobile layouts

Implement:

* Tables
* Forms
* Filters
* Search
* Charts
* Modals
* Drawers
* Calendars
* Kanban Boards
* Timelines

SECURITY

Implement:

* RBAC
* Input validation
* CSRF protection
* XSS protection
* SQL injection prevention
* Secure file uploads
* Password hashing

DEVOPS

Generate:

* Docker setup
* Docker Compose
* Environment variables
* CI/CD workflow
* Production configuration

TESTING

Generate:

* Unit Tests
* Integration Tests
* API Tests
* End-to-End Tests

OUTPUT REQUIREMENTS

Generate the complete application codebase.

Create:

1. Folder structure
2. Database schema
3. Backend APIs
4. Frontend pages
5. Components
6. Authentication system
7. Dashboard implementation
8. Role permissions
9. Seed data
10. Docker deployment files

The application must be production-ready, scalable, maintainable, and suitable for hospitals with thousands of users across multiple branches.
