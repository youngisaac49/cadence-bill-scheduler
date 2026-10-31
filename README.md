# Cadence - Budgeting and Financial Planning 2026

> **Cadence is a browser-based budgeting application built for daily earners. It projects cash flow, keeps track of scheduled bills, and models balances day by day so financial planning decisions rest on clearer information.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/youngisaac49/cadence-bill-scheduler?style=flat-square)](https://github.com/youngisaac49/cadence-bill-scheduler)

---

<p align="center">
  <a href="https://youngisaac49.github.io/cadence-bill-scheduler/">
    <img src="https://img.shields.io/badge/Download-Cadence%20Latest-brightgreen?style=for-the-badge" alt="Download Cadence">
  </a>
</p>

> **[Download Cadence](https://youngisaac49.github.io/cadence-bill-scheduler/)**

---

[Download Latest Build](https://youngisaac49.github.io/cadence-bill-scheduler/)

---

## About Cadence

Cadence targets a specific planning problem: income and expenses that land on particular dates, not neatly bundled into one monthly figure. The application pulls together expected incoming payments, repeating obligations, and account activity, then shows how the money you have available could shift across the coming 14 days.

For daily earners, that means a clearer read on where the tight spots are, what options might relieve them, and whether an advance could become necessary. A deterministic simulation lays out the balance for each individual day, while ledger and receipt inputs let you organize records from cash, e-transfer, debit, prepaid, payroll card, and direct-deposit transactions.

---

## Features

- Projects possible cash-flow collisions over a 14-day window.
- Estimates when payments arrive and how much income to expect.
- Stores recurring bills, obligations, and their due dates.
- Runs a deterministic per-day balance simulation across the forecast period.
- Weighs intervention costs against the alternatives on hand.
- Ingests ledger activity from cash, e-transfer, debit, prepaid, payroll card, and direct deposit.
- Parses receipts and pay stubs to speed up record entry.
- Generates risk scores tied to potential advance needs.
- Exports offline-trained model outputs as JSON.

---

## Installation

### Use the hosted build

Load the [latest Cadence build](https://youngisaac49.github.io/cadence-bill-scheduler/) in any current web browser.

### Run from a local checkout

```bash
git clone https://github.com/youngisaac49/cadence-bill-scheduler.git
cd REPO
```

Point any static web server at the repository, then visit the local address it serves. Cadence runs as a web application, so the frontend files need no separate runtime installation.

---

## Usage

1. Launch Cadence in your browser.
2. Enter expected income payments along with the dates you anticipate them.
3. Record recurring obligations, their amounts, and when they come due.
4. Add the relevant ledger activity, receipts, or pay-stub details.
5. Examine the 14-day balance simulation.
6. Look into any projected cash-flow collision and the risk score attached to it.
7. Compare the cost of available interventions with the alternatives before deciding.
8. Export model results as JSON whenever you need an offline record.

---

## Configuration

Cadence does not rely on a command-line configuration file. Setup happens through the application's budgeting and ledger inputs.

Typical setup data includes:

- Expected payment dates and amounts
- Recurring obligations and due dates
- Ledger entries grouped by payment method
- Receipt and pay-stub details
- Forecast and intervention information

Update entries whenever payment timing or bill schedules change, so the day-by-day projection stays aligned with the most recent information available.

---

## Requirements

- A modern web browser
- Access to the Cadence web build or a local copy of the repository
- Enough browser storage for the application's budgeting data and exported results
- Financial records such as payment details, recurring obligations, receipts, or pay stubs, where applicable

Cadence is built for the web. Its static frontend files do not need a server-side runtime.

---

## FAQ

### Who is Cadence for?

It is aimed at daily earners and anyone whose planning has to account for shifting income dates, recurring bills, and short-term cash-flow timing.

### How far ahead does the forecast look?

The collision forecast spans a 14-day period, with a deterministic balance simulation presented for every day in that window.

### Can I record different payment methods?

Yes. The ledger model covers cash, e-transfer, debit, prepaid, payroll card, and direct deposit activity.

### Can Cadence use receipts or pay stubs?

Receipt and pay-stub entries can be parsed, which helps bring relevant financial information into the planning workflow.

### What should I do if the forecast looks incorrect?

Check payment dates and amounts, verify the due dates on recurring obligations, and make sure ledger entries match the information behind your planning scenario.

### Can results be saved outside the application?

Offline-trained model outputs can be exported in JSON format for separate storage or later analysis.

### How are updates provided?

The [latest available build](https://youngisaac49.github.io/cadence-bill-scheduler/) gives you the current published version of Cadence.

### Where can I get support?

For questions about the project or to report an issue, visit the repository's [GitHub page](https://github.com/youngisaac49/cadence-bill-scheduler).

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
