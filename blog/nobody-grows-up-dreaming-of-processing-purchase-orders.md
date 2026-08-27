---
title: "Nobody grows up dreaming of processing purchase orders"
description: "Purchase order automation used to mean templates and routing rules. Now AI agents run the whole loop, and the cost gap between manual and automated teams is hard to ignore."
canonical: https://arboraistudio.com/blog/nobody-grows-up-dreaming-of-processing-purchase-orders/
last-updated: 2026-08-04
---

# Nobody grows up dreaming of processing purchase orders

> Purchase order automation used to mean templates and routing rules. Now AI agents run the whole loop, and the cost gap between manual and automated teams is hard to ignore.

- Canonical: https://arboraistudio.com/blog/nobody-grows-up-dreaming-of-processing-purchase-orders/
- Published: 2026-08-05
- Updated: 2026-08-04

Every growing company has a version of the same email thread. Someone needs to buy something, so they email a manager. The manager approves in a reply. Someone else retypes the details into a purchase order template, and three weeks later accounting is staring at an invoice that matches nothing on file, wondering which of the four versions of the PO was the real one.
It is boring work, and it stays invisible right up until it goes wrong. What surprised me, digging into the current numbers, is how wide the gap has grown between teams that automate this loop and teams that still run it on goodwill and reply-all.

## The price of doing it by hand
The benchmark AP people cite right now is Ardent Partners' State of ePayables 2024, a survey of 212 AP professionals published in May 2024. The average organization in that survey spends $9.40 and about nine days to process a single invoice. The best-run teams spend $2.78 and three days. Everyone else averages $12.88 and more than two weeks.

Both groups handle the same document. One spends roughly four times less and moves five times faster, and the difference is not that their people try harder. Only 32.6% of B2B invoices move straight through without a human touching them, and the best teams hold their exception rate to 9% while everyone else wrestles with 22%. Those exceptions are where the days go; a price that does not match the PO or a receipt that was never logged can stall an invoice for a week.

APQC measures the same function through a different lens, cost per $1,000 of revenue, and finds top performers at $0.38 against $0.92 for bottom performers.

One honest caveat: the internet is full of "$15 to $40 per invoice" figures. I could not trace any of them to a primary source, so I am not repeating them here. The numbers above come from pages I actually opened and read.

## What the automated version looks like
Strip away the vendor marketing and purchase order automation is a short, logical chain. A request comes in through a form instead of an email, and the system already knows the preferred vendor, the contract price, and the budget code. Once the request is approved, the system writes the PO itself. Routing rules decide who signs off: small recurring orders slide through, a $40,000 PO goes to a director. The PO reaches the vendor by email, portal, or EDI. When the goods arrive, the receipt gets logged, and when the invoice lands, the system compares all three documents. Match within tolerance, and payment just happens. Mismatch, and the invoice stops until a person looks at it.

Every step posts back to the accounting system, so nobody retypes anything. That matters more than it sounds: most matching errors are born at a keyboard, when someone copies a number from one place to another.

## Then the agents showed up
Basic automation handles the happy path. The last year made the messier parts interesting.
In June 2025, Genpact launched an agentic accounts payable suite whose self-learning agents ingest and validate invoices, resolve exceptions, and adapt to supplier terms and approval hierarchies. In October, Oracle announced a Payables Agent that ingests invoices from email, portals, EDI, and PDFs, extracts and normalizes the data, matches it to POs and receipts, applies tax, policy, and fraud checks, and routes for approval. Announced is doing some work in that sentence: Oracle described planned capabilities, so file it under roadmap, not shipping product. The same month, SAP introduced 14 new Joule agents across finance, HR, procurement, and supply chain, and published commissioned research with Oxford Economics, 1,600 executives, that found an average 16% return on AI investments. Vendor-commissioned research deserves a raised eyebrow, but at least it is a named survey with a stated sample, which is more than most ROI claims give you.

On the purchase-order side specifically, GEP describes an agent that takes a requisition, checks vendor details and pricing against current contracts, confirms budget availability, then generates and routes the PO for approval. That is the contract-checking, approval-chasing work that used to eat a person's afternoon. Ardent Partners estimates 75% of AP departments now use some form of AI. Analyst estimate, not a surveyed number, but the direction is hard to argue with.

For the thoughtful version of where this is heading, the Art of Procurement podcast's episode 814 has Zip's Head of Research Nick Heinzmann on where agentic AI genuinely fits procurement workflows. It is 25 minutes and refreshingly hype-free: https://artofprocurement.libsyn.com/814-how-agentic-ai-can-transform-procurement-outcomes-w-nick-heinzmann

## The part that is not about software
Here is what I keep coming back to. A month-end close should never depend on someone's ability to find an email. The purchase order was never the job; it was always the tax on the job.

Does a five-person company need this stack? Probably not yet. A template and a shared drive will carry you a long way. But when two or three people have to touch every approval, and nobody can answer "did we receive what we were billed for" without an email search, you are already paying for automation. You just pay for it in salaries and days instead of software.

If your team has made this jump, I am curious where it broke first: the matching, the approvals, or the politics. Tell me in the comments.
