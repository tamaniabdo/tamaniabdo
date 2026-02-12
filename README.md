## Hi there 👋

I am a passionate programmer currently building my foundation I believe the best way to learn is by breaking things in the real world, so I focus on building complex, end-to-end applications to solve actual problems. I’m currently working on " FreightCheck "

# FreightCheck

FreightCheck automatically ingests shipping invoices, compares them to carrier quotes and shipment manifests, recalculates expected charges based on contract rules, and flags discrepancies for auditors to review and dispute.

---

## What This Means

- **Automatically ingests shipping invoices**  
  The system accepts invoices in PDF, CSV, or EDI format from carriers or marketplaces.

- **Compares them to carrier quotes and shipment manifests**  
  Performs a three-way match between the contract/rate sheet, quote/manifest, and the invoice.

- **Recalculates expected charges based on contract rules**  
  Includes logic for fuel surcharges, dimensional weight, zone pricing, accessorials, and marketplace adjustments.

- **Flags discrepancies for auditors to review and dispute**  
  Highlights mismatches with severity scores and generates pre-filled dispute packets for payment hold or recovery.

---

## Why FreightCheck

Shipping and fulfillment are financially “dirty.” A carrier may quote $5,000, then add fuel surcharges, waiting fees, and gate fees, sending an invoice for $6,500. Large companies process 10,000+ invoices a month and cannot manually verify accuracy. FreightCheck automates detection, recovery, and dispute of overcharges.

---

## MERN Stack Scope for Phase 1

- **MongoDB** → store invoices, manifests, disputes, user accounts  
- **Express/Node.js** → API for upload, parse, and flagging logic  
- **React** → simple reviewer UI to display flagged invoices and allow disputes  
- **Node Backend Logic** → compute expected charge using contract rules and compare to invoice  
- **Phase 1 MVP focus** → ingest, parse, three-way match, flag discrepancies, simple reviewer UI

