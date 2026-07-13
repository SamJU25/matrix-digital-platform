# MATRIX - Digital Subscription and Gift Card Management System

**Course:** Software Engineering (CSC3115)  
**Institution:** American International University-Bangladesh (AIUB)  
**Semester:** Summer 2025-2026  
**Project Group:** Group 04  

---

## 1. Project Overview
MATRIX is an e-commerce platform designed for digital voucher distribution and subscription management. The platform allows individual customers to purchase gaming gift cards (PlayStation, Steam, Xbox) and software subscriptions (Spotify, Netflix) with instant digital delivery. Purchased license keys are stored and protected inside a secure customer digital locker.

The platform also supports automated inventory tracking with low-stock threshold alerts, a corporate B2B wholesale portal for bulk purchasing with tiered volume discounts, and an administrative console for employee access management and customer support ticketing.

---

## 2. Team Members & Responsibilities

| Student Name | Student ID | Domain / Module Responsibility | Feature Branch |
| :--- | :--- | :--- | :--- |
| **Sampad Chakma** (Leader) | 23-53146-3 | Git Architecture, Inventory Automation, Trello Board Setup | `feature/inventory` |
| **Muntasir Mujib** | 23-54747-3 | Storefront Catalog & Corporate B2B Portal | `feature/storefront` |
| **Nafisa Lubna** | 23-54759-3 | Customer Digital Locker, Cart & Checkout | `feature/customer` |
| **MD. Charim Hossain** | 22-46769-1 | Support Staff Desk & Order Verification | `feature/sales-support` |
| **MST. Tanzim Hossain Suborna** | 23-54781-3 | Admin Governance, System Settings & Sprint Backlog | `feature/admin` |

---

## 3. Repository Structure

```
matrix-digital-platform/
├── assets/
│   └── gantt_chart.png               # Project timeline and sprint schedule
├── figma-screens/
│   ├── storefront/                   # Product catalog, category filters, and B2B portal screens
│   ├── customer/                     # Customer auth, cart, checkout, and digital locker screens
│   ├── inventory/                    # Stock tracking, CSV key upload, and reorder PO screens
│   ├── sales-support/                # Order verification and support desk screens
│   └── admin/                        # Admin analytics, employee management, and gateway screens
├── trello/
│   ├── 01_final_trello_board_overview.jpeg          # Overview of completed board (18 Done)
│   ├── 02_customer_cards_checklists.jpeg            # Customer task cards with checklists
│   ├── 03_inventory_and_buyer_cards.jpeg            # Inventory and Buyer task cards
│   ├── 04_support_staff_cards_checklists.jpeg       # Support staff task cards
│   ├── 05_corporate_buyer_cards_checklists.jpeg     # Corporate Buyer task cards
│   └── 06_admin_governance_cards_checklists.jpeg    # Admin console task cards
├── trello-cards/
│   ├── INV-01-low-stock-alerts.txt                  # Card serial INV-01 description & checklist
│   ├── ...                                          # All 18 sprint task cards
├── .gitignore
├── LICENSE
└── README.md
```

---

## 4. Git Branching & Workflow

This repository follows the Git feature branching model in compliance with project instructions:
- `main`: Primary branch for project integration and final release (tagged at `v1.0`).
- Feature branches (`feature/*`): Created by each group member to design, prototype, and stage their respective UI modules and sprint backlog deliverables before peer review and merging into `main`.
