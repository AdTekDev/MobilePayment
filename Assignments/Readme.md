
# Assignments

Each group will build a mobile payment app and design interfaces & functions for this particular product/service or company app. 


### **Project Overview: Mobile Payment & Catalog Application**
**Goal:** Students will work in groups to develop a functional mobile payment application that integrates product management, multiple payment workflows, and marketing strategies using the **Google AppSheet** no-code platform.

---

### **Phase 1: Minimum Viable Product (MVP) & Core Payment Logic**
*Focus: Data Specification, UX Design, and Basic Transaction Flow (Weeks 2-5 of the syllabus).*

#### **Requirements:**
1.  **Product Catalog:**
    *   Design a database (Google Sheets) to store product information (Name, Category, Price, Image, Stock level).
    *   Implement a "Gallery" or "Deck" view in AppSheet for users to browse items.
2.  **Primary Payment Method (In-App Wallet):**
    *   Implement a **Top-up (Nạp tiền)** function to simulate adding funds to a virtual wallet.
    *   Create a "Pay" action that checks for **Authorization**: the app must verify if the user has a sufficient balance before approving the transaction.
3.  **Basic Transaction Records:**
    *   The app must automatically record every successful transaction in a "Sales History" table (simulating the **Clearing** process where data is recorded for reconciliation).

#### **Assessment Criteria (Phase 1):**
*   **Data Structure (20%):** Efficiency and relationship between tables (Users, Products, Transactions).
*   **UX/UI Design (15%):** Ease of navigation and item selection.
*   **Authorization Logic (15%):** Correct implementation of balance checks and "Approved/Declined" states.

---

### **Phase 2: Advanced Features, Marketing & Multiple Payment Methods**
*Focus: CRM, Advanced Functions, and Alternative Payment Methods (Weeks 6-13 of the syllabus).*

#### **Requirements:**
1.  **Multiple Payment Methods:**
    *   **QR Code Payment (Proximity):** Generate or scan a simulated QR code to initiate a payment.
    *   **Simulation of Bank Transfer/Card Payment:** Implement a workflow for "Card-on-File" or simulated "A2A (Account-to-Account)" transfers.
2.  **Marketing & Promotion Policies:**
    *   **Discount Logic:** Apply automated discounts (e.g., 10% off for orders over $100) using AppSheet expressions.
    *   **Loyalty Program (Gamification):** Implement a point-based system where users earn points for each purchase that can be redeemed later.
3.  **Advanced Functionality:**
    *   **Location Search:** Integrate a map view to show physical store locations or delivery tracking.
    *   **Lead Tracking/Forum:** Add a simple CRM feature like a feedback forum or customer lead tracking.

#### **Assessment Criteria (Phase 2):**
*   **Technical Sophistication (20%):** Successful simulation of diverse payment "rails" (QR, virtual cards, etc.).
*   **Marketing Logic (15%):** Correct application of promotional rules and loyalty point calculations.
*   **Final Report & Presentation (15%):** Explaining the technical details of the system in English (CLO3) and demonstrating the app's behavior.

---

### **Summary of Assessment Rubric (Total: 50% of Course Grade)**
| Category | Key Requirements | Weight |
| :--- | :--- | :--- |
| **System Specification** | Accurate data modeling and technical explanation (CLO1, CLO3). | 30% |
| **Implementation** | Effective use of AppSheet features (Behavior, UX, Branding) (CLO2.1). | 40% |
| **Functionality** | Working simulation of payment ecosystem (Auth, Clearing, Settlement). | 20% |
| **Team Collaboration** | Individual contribution clearly stated in the group report. | 10% |

**Note for Students:** All students must ensure **Academic Integrity**. Plagiarism or reuse of existing app templates without significant modification will result in a zero grade.
