# On Hand and Forecasted Quantity on Purchase Orders

![Odoo](https://img.shields.io/badge/Odoo-17.0-714B67) ![Editions](https://img.shields.io/badge/Editions-Community%2C_Enterprise%2C_Odoo.sh-2563EB) ![License](https://img.shields.io/badge/License-OPL--1-0F766E) [![Odoo App Store](https://img.shields.io/badge/Odoo_App_Store-Buy-875A7B)](https://apps.odoo.com/apps/modules/17.0/cc_po_onhand_quantity)

Buyers often reorder without knowing what is already in the warehouse or already on its way. This app shows on hand and forecasted quantity on every RFQ and purchase order line, and prints both on the RFQ PDF.

## What it does

- On hand quantity for each product on the purchase order line
- Forecasted quantity next to it, so incoming receipts are counted
- Per-location quantity breakdown on the line
- Both quantities printed on the Request for Quotation report

## How to use it

1. Install the app. No configuration is needed.
2. Open Purchase, Orders, Requests for Quotation and add products as usual.

## Screenshots

![On Hand and Forecasted Quantity on Purchase Orders screenshot 1](screenshots/CCLogo.png)
![On Hand and Forecasted Quantity on Purchase Orders screenshot 2](screenshots/banner.png)
![On Hand and Forecasted Quantity on Purchase Orders screenshot 3](screenshots/divider.png)

## Technical notes

Technical name `cc_po_onhand_quantity`, Odoo 17.0.

Extends `purchase.order` and `purchase.order.line` with computed quantity fields read from stock, and inherits the RFQ QWeb report. Depends on `purchase`.

## Get the module

Buy it on the [Odoo App Store](https://apps.odoo.com/apps/modules/17.0/cc_po_onhand_quantity) for EUR 7. The purchase includes the full source code under the OPL-1 licence.

Need it on another Odoo version, with changes for your workflow, or installed and tested on Odoo.sh? Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=cc_po_onhand_quantity%20customisation) or see [CODCrafters](https://codcrafters.org).

---

This repository is the product page. The module source is private and comes with the licence.

Built by [Usman Ghias](https://usmanghias.co.uk), [CODCrafters](https://codcrafters.org).
