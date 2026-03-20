# Business Questions You Can Ask Using Senzing

Senzing entity resolution helps answer questions about **who is who** and **who is related to whom** across your data. Below are common business questions organized by use case.

## Identity Resolution & Data Quality

- Do we have duplicate records for the same person or organization?
- How many unique customers do we actually have across all our systems?
- Which records in different data sources refer to the same real-world entity?
- Where are the inconsistencies, conflicts, or gaps in our identity data?
- What is the true count of distinct entities in our dataset?

## Fraud Detection & Prevention

- Is this new applicant the same person as a previously known fraudster?
- Are there hidden connections between seemingly unrelated accounts?
- Is someone using multiple identities across different channels to evade detection?
- Are any of our customers connected to known bad actors through shared addresses, phones, or other features?
- Which entities appear across multiple data sources under slightly different names or identifiers?

## Know Your Customer (KYC) & Compliance

- Does this customer appear on any sanctions or watchlist?
- Are we meeting our regulatory obligations for customer identification (BSA/AML)?
- Can we demonstrate why an entity resolution decision was made (explainability for auditors)?
- Has a customer's risk profile changed based on newly discovered relationships?
- Are any of our customers linked to politically exposed persons (PEPs)?

## Watchlist & Screening

- Do any of our records match entries on government sanctions lists (e.g., OFAC)?
- Are there partial or fuzzy matches to watchlist entries that need human review?
- When a watchlist is updated, which of our existing entities are affected?

## Relationship Discovery

- Is person X an inventor of a patent that is owned by a company that is on a watchlist?
- What relationships exist between entities that were not explicitly disclosed?
- Are there shared households, addresses, or contact information linking separate entities?
- What is the network of relationships around a specific entity of interest?
- Are there corporate hierarchies or ownership structures connecting our entities?

## Risk Assessment

- Which entities in our data have the highest number of connections to risky or flagged entities?
- Are there clusters of entities that share suspicious patterns of overlapping features?
- Which new records, when added, change the risk profile of existing entities?

## Operational Intelligence

- When a new record arrives, does it match an existing entity or is it genuinely new?
- Which of our data sources contribute the most (or least) to entity resolution quality?
- How many entities span multiple data sources versus appearing in only one?
- What is the overlap between two specific data sources?

## Insider Threat & Personnel

- Do any of our employees appear in external watchlists or adverse media sources?
- Are there undisclosed relationships between employees and vendors or contractors?
- Is the same person employed under different identities in different departments?

## Supply Chain & Vendor Management

- Are any of our vendors connected to sanctioned entities?
- Do we have duplicate vendor records that could lead to duplicate payments?
- Are there undisclosed ownership relationships between vendors competing for the same contract?
