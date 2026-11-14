# Fit-GAP Analysis – Odoo 16 Community

| Req ID | Business Requirement | Odoo 16 Standard Capability | Status | Proposed Solution / Workaround |
| :--- | :--- | :--- | :--- | :--- |
| **REQ-01** | Differentiated B2B/B2C pricing. | Standard Odoo supports Pricelists based on Customer Groups. | **Fit** | Configure standard Pricelists and assign them to specific B2B contact tags. |
| **REQ-02** | Display specific partner brands (Celestron, Orion, ZWO, HAS). | Odoo eCommerce has an eCommerce Categories feature, but lacks a dedicated "Brand" ribbon out-of-the-box. | **GAP** | Use Product Attributes to define "Brand" and enable sidebar filtering on the shop page. |
| **REQ-03** | Remove "Contact Us" button from top navbar to streamline checkout. | Default Odoo Website theme hardcodes the Contact CTA in the header navigation. | **Partial Fit** | Use the Odoo Website Builder's HTML/CSS editor to manually hide/remove the redundant header menu item. |
| **REQ-04** | B2B Quotation request from website. | Odoo standard eCommerce pushes direct to cart/checkout. | **GAP** | Enable "B2B Options" or add a web form routed to the CRM/Sales module to handle quote requests before creating an SO. |
