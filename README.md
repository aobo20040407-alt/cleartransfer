# ClearTransfer

An interactive prototype exploring how the presentation of fees and transfer requirements affects users’ understanding of investment apps.

The first version focuses on one task: transferring selected holdings to another brokerage. It asks whether users can identify the transfer fee, understand the available-cash requirement, and determine what to do next.

[Open the live prototype](https://clear-transfer-lab-1025.chirpycrane12.chatgpt.site/) (access may require the owner’s account).

## Features

- Two interface versions with the same holdings, fees, and task: **A — Standard** and **B — Clear guidance**.
- Interactive holding selection, insufficient-cash feedback, simulated cash funding, and a demo submission status.
- A three-question comprehension check.
- Browser-local answer records and elapsed time, with CSV export.
- A responsive layout built with HTML, CSS, and JavaScript, without external dependencies.

## Getting started

Download or clone this repository, then open `dist/index.html` in a modern browser. No installation or build step is required.

All brokerages, accounts, prices, and transfer steps are fictional or simulated. The prototype does not connect to financial accounts or move money.

Test records are stored only in the current browser when browser storage is available. If storage is unavailable, records remain only for the current page session. Download the CSV before clearing records or changing browsers. Records are not automatically collected from other participants.

## Running an exploratory usability test

1. Assign each participant to either A or B for their first experience, alternating assignments where practical. Avoid showing both versions before the first test.
2. Give the participant this task: **Transfer the whole-share AAPL and VTI holdings to Harbor. Identify the fee, what initially prevents submission, and the next action needed.**
3. Let the participant explore without explaining the answers, then complete the **Quick check** for their assigned version.
4. Save and export the answers. Separately note points of confusion without collecting real account details.
5. Compare comprehension and observed difficulties. Elapsed time includes reading and runs from the first view of a version until answers are saved; it is not a precise measure of task execution time.

## Research scope and limitations

Forum discussions provide leads about user needs, not verified findings of brokerage misconduct. This prototype does not reproduce or evaluate a real brokerage.

The **$75 fee**, **$20 initial cash balance**, and **3–5 business day timeline** are fixed example parameters, not current quotes or service commitments from any brokerage. Fractional shares are outside the scope of this example.

Small samples, participant differences, device differences, and exposure to both versions limit any conclusions. This is an exploratory prototype, not a validated experiment. No participant results are included, and improved understanding or trust has not been established.

## Inspiration

[A Reddit discussion about a partial account transfer](https://www.reddit.com/r/Webull/comments/1xbupf0/partial_account_transfer_denied/) inspired questions about fee visibility, explanations for rejected requests, and access to support.

## Next steps

- Verify relevant fees and conditions against official documents before making any real-world comparisons.
- Interview users to understand their expectations and points of confusion.
- Refine the test protocol and compare first-time experiences across versions.
- Use the findings to improve the interface and document what changed.
