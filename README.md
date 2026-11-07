# Nyumba Dashboard

A phone-first rental tracker for a small portfolio of apartments in Tanzania. All amounts are in TSh.

- **Properties and apartments:** each apartment shows whether it is paid up, owing, vacant or under maintenance.
- **Tenants:** contacts, ID, emergency contact, lease dates, rent and deposit, and how far they have paid.
- **Transaction log:** rent payments (M-Pesa, Tigo Pesa, Airtel Money, bank, cash) and costs in one list, grouped by month.
- **Reports:** income, costs and net by month, property and apartment.
- **Tour:** a guided walkthrough that loads sample data.

Rent paid in advance is spread across the months it covers.

## Where the data is saved

The app is a single `index.html` file with no build step.

- **On GitHub Pages**, data is saved in the browser's local storage. It stays on that device and in that browser only, and clearing the browser's site data erases it.
- **As a Claude artifact on claude.ai**, the same file uses the artifact's private database, which keeps data across devices.
