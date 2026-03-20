# Participant Experience Timeline

This document describes the end-to-end experience from a participant's perspective,
from first learning about the boot camp through post-workshop follow-up.

## Pre-Boot Camp

### Discovery and Application

1. Participant learns about the Senzing Boot Camp (referral, website, sales contact)
2. Participant (or their manager) completes the application questionnaire
3. Participant reviews and sends the generated qualification email to Senzing
4. Senzing reviews the application and responds with next steps

### Preparation — On-site (company-sponsored, at company's location)

5. Participant receives confirmation and boot camp dates
6. Company designates a venue and confirms facilities (tables, projector, power, Wi-Fi)
7. Company arranges visitor access for Senzing facilitators (registration, badges, escort requirements)
8. Participant receives a preparation checklist:
   - Install Docker and verify `docker run hello-world` works
   - Install preferred AI tool (Claude Code recommended)
   - Confirm internet access, external API reachability, and ability to download software from the workshop network
   - Prepare sample data (extract, clean, anonymize if needed)
   - Share data artifacts with Senzing in advance (if agreed during application)
9. Senzing provisions a trial license (if needed) and shares it with the participant
10. Participant completes all preparation items before Day 1

### Preparation — Senzing-hosted (at a Senzing-chosen location)

5. Participant receives confirmation, boot camp dates, and venue location
6. Participant arranges travel to the Senzing location
7. Participant determines how to access their data during the workshop:
   - Bring it on their laptop
   - Access it remotely over the internet
8. Participant receives a preparation checklist:
   - Install Docker and verify `docker run hello-world` works
   - Install preferred AI tool (Claude Code recommended)
   - Prepare sample data (extract, clean, anonymize if needed)
   - Share data artifacts with Senzing in advance (if agreed during application)
9. Senzing provisions a trial license (if needed) and shares it with the participant
10. Participant completes all preparation items before Day 1

## Day 1

### Morning — Setup and Foundations

9. Arrive at venue; introductions and boot camp overview
10. Verify environment: Docker, AI tools, internet access, license
11. Introduction to Senzing and entity resolution concepts
12. First exercise: load sample data into Senzing using AI-assisted coding

### Afternoon — Building

13. Map participant's own data to Senzing entity specification
14. Load participant's data and review entity resolution results
15. Explore resolved entities — who matched, why, and what relationships were discovered
16. End-of-day review: what worked, what needs adjustment

## Day 2

### Morning — Deeper Integration

17. Refine data mapping based on Day 1 results
18. Build working code in participant's preferred language (Python, Java, or C#)
19. Integrate Senzing into a target form factor (REST API, script, batch job, microservice)

### Afternoon — Production Readiness

20. Answer business questions using resolved entities (see `business-questions.md`)
21. Test and validate the working code
22. Package deliverables — participant leaves with code they can use in their own environment
23. Final review: confirm each participant has working, usable output

## Post-Boot Camp

24. Participant deploys working code in their own environment
25. Follow-up with Senzing for questions, licensing, or production support
26. Evaluate next steps: production license, expanded data sources, additional use cases
