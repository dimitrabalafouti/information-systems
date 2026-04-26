# HIND Maritime Enterprises S.A. — Strategic Shield IS

**Μέρος 3ο — Σχεδιασμός Ιστοσελίδων**
Πληροφοριακά Συστήματα · Ομάδα 69 · Αθήνα, Απρίλιος 2026

> *"One automated source of truth, a world of trust:
> Your real-time digital shield in dry cargo brokerage."*

## Μέλη Ομάδας

| Αριθμός μητρώου | Ονοματεπώνυμο |
|-----------------|----------------------|
| 8240029 | ΓΚΑΝΑΡΑ-ΕΥΑΓΓΕΛΙΑ |
| 8240083 | ΜΠΑΛΑΦΟΥΤΗ-ΔΗΜΗΤΡΑ |
| 8240142 | ΤΖΙΝΑ-ΔΗΜΗΤΡΑ |
| 8240149 | ΤΣΑΚΩΝΑ-ΣΤΑΥΡΟΥΛΑ |

## Αρχείο Σελίδων

Όλα τα αρχεία βρίσκονται στο root του repository.

| # | Αρχείο | Περιγραφή | Actor |
|---|--------|-----------|-------|
| 1 | `index.html` | Αρχική Σελίδα + Σύνδεση Χρήστη + Navigation Cards | Όλοι |
| 2 | `fleet-status.html` | Compliance Dashboard — Πιστοποιητικά στόλου, Alerts λήξης, Vetting Folder Export | DPA / HSEQ, Operations |
| 3 | `voyage-dashboard.html` | Real-Time Voyage Monitoring — KPIs, ενεργά ταξίδια, αποκλίσεις | Operations |
| 4 | `noon-report.html` | Τυποποιημένη Φόρμα Υποβολής Noon Report | Πλοίαρχος (Master) |
| 5 | `approve-procurement.html` | Ψηφιακή Έγκριση Αιτημάτων Προμήθειας με Audit Trail | Διοίκηση / CEO |

Επιπλέον:

- `style.css` — Κοινό stylesheet για όλες τις σελίδες
- `use-cases.md` — Τεκμηρίωση Περιπτώσεων Χρήσης (όπως ζητάει το template)

## Πώς να το ανοίξετε

Ανοίξτε το `index.html` σε οποιονδήποτε σύγχρονο browser (Chrome, Firefox, Edge, Safari).
Δεν απαιτείται server. Δοκιμασμένο σε Chrome 120+ / Firefox 121+ / Edge 120+.

## Live Preview (GitHub Pages)

Ενεργοποιήστε το GitHub Pages από Settings → Pages → Source: `main` branch / root.
URL μετά την ενεργοποίηση: `https://dimitrabalafouti.github.io/information-systems/`

## Αρχιτεκτονική Συστήματος (Στρατηγική Ασπίδα)

Το σύστημα οργανώνεται σε 5 λειτουργικούς πυλώνες:

1. **Compliance & Certification Module** — Fleet Status Dashboard, αυτόματα Alerts (90/60/30 ημέρες), Vetting Folder Export
2. **Voyage & Operations Module** — Noon Report parsing, Real-time Voyage Dashboard, Voyage Instructions
3. **Procurement & Maintenance Workflow** — Ψηφιακή φόρμα αιτημάτων, auto-routing, multi-level approval
4. **Finance & Accounting Module** — Auto invoices, Host-to-Host banking, real-time cash flow
5. **Management BI / Reporting** — KPIs, P&L ανά ταξίδι, one-click Export PDF/Excel

## Σχέση με τα προηγούμενα Μέρη

- **Μέρος 1ο** — Διερευνητική Μελέτη με Μεθοδολογία Ευμετάβλητων Συστημάτων (SSM)
- **Μέρος 2ο** — Όραμα + 8 User Stories + 11 Use Cases τεκμηριωμένες
- **Μέρος 3ο** — Σχεδιασμός 5 ενδεικτικών οθονών (παρόν repository)
