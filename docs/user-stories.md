# Lab 04: User Stories & Acceptance Criteria - FoodFast

### [cite_start]User Story 1: Pre-ordering to Save Time [cite: 85]
* [cite_start]**As a** Time-Constrained Student [cite: 85]
* [cite_start]**I want to** select my meal and place a digital pre-order before arriving at the cafeteria [cite: 85]
* [cite_start]**So that** I can avoid spending my entire 20-minute break waiting in a physical queue[cite: 85].

#### [cite_start]Acceptance Criteria (AC) [cite: 85]
1. Given that the student views a vendor menu, when they click "Pre-order", then the system must display an explicit meal selection confirmation page.
2. Given a confirmed selection, when the student taps checkout, then the system must log the entry into the order table and return a unique confirmation number.

---

### [cite_start]User Story 2: Live Queue Visibility [cite: 85]
* [cite_start]**As a** Busy Faculty or Student User [cite: 85]
* [cite_start]**I want to** check the preparation state of my order on a web dashboard [cite: 85]
* [cite_start]**So that** I only walk down to the pickup counter when my food is explicitly ready[cite: 85].

#### [cite_start]Acceptance Criteria (AC) [cite: 85]
1. Given that an order is actively being cooked by a vendor, when the user checks their live status page, then the token state must display "Preparing".
2. Given that the food is fully prepared, when the state updates to "Ready for Pickup", then the system must instantly display a highly visible alert container on the screen.
