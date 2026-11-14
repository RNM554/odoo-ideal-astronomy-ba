# Business Requirements – Ideal Astronomy ERP (Odoo 18)

## 1. Storefront, Catalog & Customer Engagement (Website & Live Chat)
| Req ID | Module | Business Requirement | Acceptance Criteria | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **REQ-01** | Website / eCommerce | Display structured catalog of optical & astronomy equipment (telescopes, binoculars, astrophotography cameras, accessories). | - Products categorized clearly with variant attributes (e.g., magnification `10x` vs `22x`).<br>- Multi-tier sidebar filtering by category and brand. | High |
| **REQ-02** | Website | Showcase official brand partnerships to build customer trust. | - Homepage displays partner logos: **Celestron, Orion, ZWO Astronomy, and Hội Thiên văn Hà Nội (HAS)**. | High |
| **REQ-03** | Website | Streamline navigation and checkout flow to reduce cart abandonment. | - Redundant "Contact Us" CTA removed from the top header bar.<br>- Support guest checkout and demo payment gateway integration. | High |
| **REQ-04** | Live Chat | Provide real-time technical consultation for customers choosing complex optical gear. | - Embedded Live Chat widget active on storefront.<br>- Incoming visitor chats route directly to assigned support staff in the Discuss module. | Medium |

## 2. Lead Management & Sales Operations (CRM & Sales)
| Req ID | Module | Business Requirement | Acceptance Criteria | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **REQ-05** | CRM | Capture and track B2B/institutional leads (schools, astronomy clubs) before issuing formal quotes. | - Sales pipeline tracks stages (`New → Qualified → Proposition → Won`).<br>- Ability to convert qualified CRM opportunities directly into Sales Quotations. | Medium |
| **REQ-06** | Sales | Differentiate pricing policies between retail (B2C) and wholesale/club (B2B) customers. | - Automated Pricelists apply specific discount rules based on customer segment/tags. | High |
| **REQ-07** | Sales | Standardize shipping methods and Vietnamese VAT calculation on orders. | - Automated delivery fee calculation (e.g., `Giao hàng tiêu chuẩn`).<br>- Accurate line-item VAT tax computation (`5%` and `10%` VAT).<br>- Automated order confirmation email sent to customer upon SO confirmation. | High |

## 3. Fulfillment, Accounting & Analytics (Inventory, Invoicing, Dashboards)
| Req ID | Module | Business Requirement | Acceptance Criteria | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **REQ-08** | Inventory | Automate stock reservation and delivery order creation upon sales confirmation. | - Confirming a Sales Order automatically generates a Delivery Order (`WH/OUT`) and reserves stock.<br>- Real-time stock on-hand updates once delivery is validated. | High |
| **REQ-09** | Invoicing | Generate compliant customer invoices and reconcile payments seamlessly. | - One-click invoice creation from confirmed/delivered Sales Orders.<br>- Payment status updates (`In Payment` / `Paid`) linked to accounting journals. | High |
| **REQ-10** | Dashboards & HR | Monitor sales performance and manage internal staff access rights. | - Management dashboard displays revenue, top-selling products, and order volume.<br>- Employee profiles linked to system user accounts with role-based permissions. | Medium |
