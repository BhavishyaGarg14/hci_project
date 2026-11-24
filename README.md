Opportunity Compass — High-Fidelity Prototype

Group 8 (Project Grp8 P2) | Human-Computer Interaction (HCI)

Domain: Educational Technology & Student Career Development

Overview

Opportunity Compass is a centralized, personalized discovery and deadline-tracking web application built for college students. Students frequently miss scholarships, hackathons, and internships—or abandon applications altogether—because opportunities are scattered across WhatsApp groups, college notice boards, and unverified portals with 30–40 page eligibility PDFs.

This repository contains the High-Fidelity (Hi-Fi) Interactive Prototype developed for Assignment 5, building directly on user research, personas, low-fidelity sketches, and mid-fidelity usability testing from Assignments 1–4.

Core Features

Personalized Profile & Feed Matching: Students select their Year of Study, Branch/Stream, and Primary Goals (Hackathons, Scholarships, Internships), with a "Skip for Now" option for sensitive financial details.

Binary Eligibility Match Checklists: Replaces dense eligibility PDFs with instant, verified green checkmarks (e.g., ✓ 1st/2nd Year B.Tech, ✓ CS / IT Branch, ✓ Free Registration) alongside explicit 100% Eligible text badges.

Verified Official Source Badging: Every listing displays a ✓ Verified Official Source indicator to eliminate fear of unverified links or phishing scams.

In-Feed Quick Category Filters: One-tap filter pills (All, Hackathons, Scholarships, Internships) directly on both the Home dashboard and Explore page.

Dedicated Opportunity Detail View: Full-page breakdown featuring About, Prizes/Stipend, 3-Bullet Rule Summary, Binary Eligibility Match, an interactive Checkable Document Checklist, and a Team Milestone Tracker.

Customizable 3-Stage Deadline Alerts & Calendar Sync: Centralized deadline tracker with toggleable 7-day, 3-day, and 24-hour reminders, Month/Timeline toggles, and one-click Google Calendar Sync.

Per-Event Team Milestone Tracker: Collaborative 3-step progress tracker (Team Formed → Draft Proposal → Final Submission) scoped to individual hackathons with team invite link sharing.

Design Evolution: Mid-Fi to Hi-Fi Improvements

Based on think-aloud usability testing with representative student participants (P01 and P02) in Assignment 4, seven key refinements were engineered into this Hi-Fi build:

Dedicated Opportunity Detail Page: Converted static opportunity cards into interactive entry points leading to a comprehensive detail view with an integrated share button.

System Status & Micro-Interaction Feedback: Added real-time toast notifications (✓ Profile saved!, ✓ Saved to Tracker, ✓ Synced to Google Calendar) and live badge counters so users always receive immediate confirmation.

Granular Notification Control: Replaced fixed reminders with an interactive alert modal allowing students to individually toggle 7d, 3d, and 24h alerts to prevent notification fatigue.

Clear Internal vs. External Button Hierarchy: Styled internal actions (Save, Doc Checklist & Details) as solid primary buttons and external links (Go to Official Portal ↗) as outlined ghost buttons with external-link affordances.

In-Feed Quick Filters on Home: Added category filter chips directly above Recommended for You on the Home screen to eliminate unnecessary navigation back to Explore or Profile.

Per-Event Milestone Placement: Moved full team milestone steppers inside each opportunity's Detail page while keeping compact collapsed progress bars (Milestone Step 1/3) on Calendar cards so multiple competitions stay organized.

Accessibility Enhancements: Paired all color-coded indicators with explicit text and icon labels (✓ 100% Eligible, ⚠ Urgent · 3 Days Left) so status is never conveyed by color alone.

Tech Stack & Architecture

Frontend: Semantic HTML5, Vanilla JavaScript (ES6+ event delegation), Custom Responsive CSS3

Deployment: Zero-dependency single-file architecture (index.html), deployable directly on Vercel, Netlify, or GitHub Pages without build steps.

Running Locally

Clone or download the repository containing index.html.

Open index.html directly in any modern browser (Google Chrome, Microsoft Edge, Safari, or Firefox), or serve it locally:

npx serve .


Recommended Walkthrough Flow:

Step 1 (Profile): Navigate to Profile, adjust Academic Year/Branch, and click Save & See Matches → to observe toast confirmation and live header/feed updates.

Step 2 (Home & Filtering): Use the quick filter pills (Hackathons, Scholarships, Internships) above Recommended for You and bookmark an opportunity.

Step 3 (Detail & Checklists): Click View Details → on HackPulse 2026 – AI & Web to inspect eligibility criteria, check off documents in the Required Document Checklist, and toggle team milestones.

Step 4 (Calendar & Alerts): Open Calendar, toggle between Month view and Timeline view, customize 7d / 3d / 24h reminders, and click Sync with Google Cal.

Group 8 Contributors

Bhavishya Garg — UI/UX Architecture, Hi-Fi Prototype Development & Deployment

Bhavishya Chahar — User Evaluation & Testing Coordination

Bhavishya Meena — Survey Design & Quantitative Analysis

Bhavya Goyal — Usability Testing & Thematic Analysis

Bhavya Kashyap — Content Curation & Requirement Mapping

Bhavya — Documentation & Concept Abstract
