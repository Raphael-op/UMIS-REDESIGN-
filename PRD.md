Product Requirements Document for UMIS Student Portal UI Redesign
Course: BU-209 Backend Engineering
Project Team: TEAM-oak
Author: Team Lead (Amojo Raphael_25/0025)

1. Product Overview and Problem Statement
Current Problem: The current Babcock University student portal (OpenBaraza/UMIS) looks outdated, rigid, and blocky. It features a stark, uninspired grey-and-white background, heavy blocks of unformatted text stuffed inside notification panels, and a massive expanse of unused white space on the right side of the desktop screen. Crucial institutional actions—such as semester course registration milestones and online exam entry points—are buried inside text-heavy, unformatted tables. Furthermore, the portal forces rigid constraints on students, requiring desktop or laptop access because the layout breaks, causes horizontal scrolling, and features tiny tap targets on mobile phone browsers.

Proposed Solution: A modern, highly polished, and visually engaging UI/UX redesign. This upgrade introduces organized, card-based dashboard containers, an interactive step-by-step course registration guide, a streamlined and collapsible side navigation menu, dual light and dark viewing modes, and a flexible, fully responsive grid layout that adapts flawlessly across all screen sizes and devices.

2. Project Objectives
Modern Visual Appeal: Elevate the look and feel of the platform using clean typography, structured card containers, soft drop shadows, rounded structural elements, and a professional, cohesive institutional color scheme.

Eliminate Wasted Space: Convert the sparse, single-column legacy layout into a dynamic, multi-column grid that utilizes screen space efficiently on desktop monitors while scaling cleanly onto tablets and smartphones.

Reduce Cognitive Load & Friction: Transform static, text-heavy instructions (such as the five mandatory registration steps and security warnings) into intuitive, interactive visual progress indicators and color-coded alert badges.

Improve Navigation Speed: Surface high-frequency student actions—including checking GPAs, viewing fee balances, and launching online examinations—directly onto the home dashboard to minimize unnecessary menu clicks.

Deliver True Cross-Device Usability: Remove the heavy dependency on desktop computers for routine academic tasks by ensuring every card, menu, and table scales correctly for mobile browsers.

3. Target Users and Research Findings
Primary Users: Undergraduate and postgraduate students across all academic levels who log into UMIS daily or weekly to monitor semester grades, check hostel and meal allocations, track school fee balances, complete course registrations, and access online examinations.

Secondary Users: University administrators and bursary staff members responsible for publishing official registration guidelines, fee payment deadlines, and security or fraud prevention notices on the student dashboard.

Student Feedback Summary & Campus Research: Through direct observations of peers using the portal on campus and informal interviews across various departments, the team identified several critical pain points:

Navigation Confusion: Over 70% of interviewed students noted that the current welcome screen gives no immediate summary of their academic or financial standing, forcing them to expand multiple side menus just to check basic details.

Registration Step Drop-Offs: Students frequently forget the exact sequence of the five registration steps (Course Selection, Commencement, Finance Statement, Select Payments, Current Charges) once they click away from the home page.

Mobile Friction: Almost all surveyed students check their portal primarily via smartphones between classes, yet the current interface forces horizontal scrolling and tiny tap targets on mobile browsers.

Overlooked Security Warnings: Important institutional alerts, such as warnings against payment fraud, blend into regular welcome paragraphs and are frequently skipped by students rushing to register.

4. Minimum Viable Product Features (MVP)
Redesigned Dashboard Grid: Quick summary cards showing your current Cumulative Grade Point Average (CGPA), fee payment clearance status, active registered credits, hall of residence and worship center allocations, and direct shortcut buttons for online exams.

Interactive Registration Stepper: A visual progress bar pinned at the top of the registration workspace replacing the plain text five-step instructions (Course Selection, Commencement, Finance Statement, Select Payments, and Current Charges). It features distinct visual states for Completed (green checkmark), Current Active Step (highlighted blue), and Locked/Pending Steps (grey), while preventing out-of-sequence navigation.

Smart Notification Cards: Replacing plain HTML tables with individual, scannable, color-coded notification cards that separate urgent alerts (such as Critical Security Alerts for anti-fraud notices and Action Required tags for deadlines) from general announcements, complete with timestamps and sender attribution (e.g., BU UMIS Office).

Collapsible Sidebar and Responsive Layout: Upgrades the left navigation panel (Dashboard, School Info, Personal Details, Academic Details, Registration, Finance, Online Exam) with clean icons, active-page pill highlights, icon-only collapse capability for compact laptops, and a smooth slide-out drawer layout for mobile phones.

Light and Dark Viewing Modes: A seamless theme toggle button integrated into the top navigation header next to the student profile name, allowing users to switch smoothly between a soft off-white daylight canvas and a low-glare dark slate evening theme to reduce eye strain during late-night sessions.

5. User Stories
Quick Status Check: As an undergraduate student, I want to see my current grade point average, registered credit load, and fee clearance status right on my dashboard when I log in, so that I do not have to search through hidden menus every time I check my portal.

Guided Registration: As a student registering for a new semester, I want a visual progress bar showing all five registration steps in order, so that I always know which step I have finished and what I need to do next without making mistakes.

Urgent Alert Visibility: As a student paying school fees, I want critical security and fraud warnings to appear in highlighted alert cards, so that I do not accidentally overlook important safety instructions buried in plain text.

Fast Exam Access: As a student preparing for an online test, I want the Online Exam button to be clearly styled and easily accessible on the main dashboard, so that I can launch my exam quickly without panicking.

Mobile Convenience: As a student on campus without my laptop, I want the portal layout to adjust cleanly to my smartphone screen, so that I can view my timetable, check announcements, and verify my registration status anywhere.

6. User Interface Design Specifications
Color Palette: Deep navy blue (#1E293B) and slate tones for structural headers, primary headings, and navigation authority; vibrant sky blue or teal (#0EA5E9) accents for clickable call-to-action buttons, active progress steps, and links; soft off-white (#F8FAFC) canvas backgrounds to reduce eye strain during extended sessions; and semantic status colors (emerald green for completed/cleared items, amber yellow for pending tasks, and crimson red for urgent security alerts).

Typography: Clean, highly legible sans-serif font styles (such as Inter or Roboto) with clear sizing and weight hierarchy—bold titles for page headers, semi-bold labels for card headings, comfortable regular body copy, and compact uppercase text for status badges and timestamps.

Component Styling: Raised white cards with generous internal padding, rounded corners (border-radius: 12px), thin light-grey container border lines, and soft drop shadows to cleanly separate content categories across a multi-column desktop grid that stacks neatly into a single column on mobile screens.

7. Success Metrics
Task Completion Speed: A measurable reduction (targeting at least 30%) in the average time students spend locating fee statements and completing their five-step semester course registration compared to the legacy portal.

Student Satisfaction: Positive feedback ratings (targeting 85% or higher) regarding the visual appeal, legibility, and ease of navigation in post-launch student surveys.

Mobile Completion Rate: A significant increase in the proportion of routine portal tasks—such as checking grades, timetables, and registration status—completed successfully on mobile phone browsers without layout errors.

Support Inquiries: A measurable decrease in helpdesk complaints submitted to university administrative offices regarding hard-to-find features, mobile display issues, or confusing registration steps.

8. User Flow & End-to-End Walkthrough
Login and Authentication Phase: The student enters their valid matriculation number and secure password on the login screen, triggering authentication and redirecting them immediately to the redesigned Student Summary Dashboard.

At-a-Glance Assessment Phase: Upon landing, the student scans the top summary cards (CGPA, Fee Status, Registered Credits) and reviews the Smart Notification Cards on the right side of the screen for any urgent deadlines or security bulletins.

Initiating Semester Registration: The student clicks either the Registration tab in the collapsible left sidebar or the Continue Registration shortcut button on the main dashboard.

Sequential Progress Execution: The Interactive Registration Stepper opens, automatically pointing to the student's current active phase (for instance, Step 2: Commence Registration), guiding them sequentially through Meal, Residence, Worship Center, and Course selection before unlocking Step 3 (Finance Statement).

Final Confirmation Phase: Once all five registration steps are completed and marked with green checkmarks, the system automatically updates the home dashboard card to display an Active Registered Status badge.

9. Functional Requirements & Acceptance Criteria
FR-01 Dashboard Summary Cards: Upon successful login, the system must render summary metrics without requiring sub-menu expansion. Acceptance Criteria: CGPA, registered credits, fee balance, and the Online Exam button are visible above the fold on desktop (1440px) and stacked cleanly on mobile (375px).

FR-02 Sequential Registration Guardrails: The registration stepper must enforce strict step ordering. Acceptance Criteria: Clicking a locked future step displays a tooltip indicating the prerequisite step that must be completed first.

FR-03 Notification Priority Filtering: Administrators can tag announcements by urgency level. Acceptance Criteria: Critical Security Alerts automatically pin to the top of the notification feed with a high-contrast crimson badge.

FR-04 Theme Persistence: The user's selected Light or Dark mode preference must persist across page reloads during an active session. Acceptance Criteria: Toggling the theme updates background and text contrast ratios to meet accessibility standards without page flickering.

10. Non-Functional Requirements
Performance & Load Speed: Dashboard UI assets, icons, and stylesheets must load in under 1.5 seconds on standard campus Wi-Fi and 4G mobile networks.

Accessibility (WCAG 2.1 Level AA): All text elements, buttons, and status badges must maintain a minimum color contrast ratio of 4.5:1 in both Light and Dark modes, with full keyboard tab-navigation support.

Cross-Browser Compatibility: The redesigned interface must render consistently across modern versions of Google Chrome, Mozilla Firefox, Apple Safari, and Microsoft Edge on Windows, macOS, Android, and iOS.

Security & Session Integrity: Redesigning the frontend UI must not alter existing OpenBaraza authentication tokens, HTTPS encryption, or role-based access controls preventing unauthorized access to student records.

11. Scope Boundaries (In-Scope vs. Out-of-Scope)
In-Scope:

Complete frontend visual overhaul of the Student Dashboard, Left Sidebar Navigation, Notification Feed, and Course Registration Stepper.

Implementation of responsive CSS grid layouts for desktop, tablet, and mobile viewports.

Introduction of Light Mode and Dark Mode UI themes.

Out-of-Scope:

Modifications to the underlying OpenBaraza/UMIS backend database schema, SQL queries, or core university ERP business logic.

Changes to payment gateway providers, bursary fee calculation formulas, or academic grading algorithms.

Redesign of internal staff-only or lecturer grading portals (planned for future phases).

12. Technical Architecture & Backend Integration (BU-209 Context)
Frontend Presentation Layer: Built using semantic HTML5, modern CSS3 (Flexbox and CSS Grid), and modular JavaScript to ensure lightweight performance and zero dependency bloat.

RESTful API / Backend Data Binding: The frontend dashboard cards and registration stepper will consume existing OpenBaraza/UMIS backend endpoints (JSON/XML payloads) for student profile metadata, CGPA records, financial ledger balances, and registration state flags.

State Management: Client-side session storage will manage UI states such as sidebar collapse status, active theme mode (Light/Dark), and temporary form progress between registration steps.

13. Responsive Breakpoint Specifications
Desktop Viewport (1200px and above): Full 3-zone layout featuring the expanded left sidebar (240px), central main workspace grid, and right-hand Smart Notification column (320px).

Tablet Viewport (768px to 1199px): Left sidebar defaults to compact icon-only mode (72px) to maximize central card grid width; notifications stack smoothly beneath primary summary cards.

Mobile Viewport (Below 768px): Sidebar collapses completely into a top-left hamburger toggle opening a slide-out navigation drawer; all dashboard cards, registration steps, and fee tables stack into a single vertical column with touch-friendly (44px minimum) buttons.

14. Information Architecture & Sitemap
Top Global Header: University Brand Logo, Current Academic Session/Semester Indicator, Light/Dark Theme Toggle, Notification Bell Counter, and Student Profile Dropdown.

Primary Left Navigation Menu:

Dashboard (Home Overview, Quick Metrics, Online Exam Shortcut, Alerts)

School Info (Academic Calendar, Institutional Notices, Campus Directory)

Personal Details (Bio-data, Next of Kin, Passport Photo, Contact Info)

Academic Details (Semester Results, CGPA History, Class Timetable, Course Catalog)

Registration (5-Step Interactive Course & Residence Registration Wizard)

Finance (Fee Statement, Payment History, Remita/Online Payment Portal, Current Charges)

Online Exam (Active CBT Exam Schedule, Exam Instructions, Direct Exam Launch)

15. Edge Cases & Error Handling
Incomplete Fee Clearance Lock: If a student attempts to access Step 1 (Course Selection) or launch an Online Exam while carrying an uncleared financial hold, the UI will display a clear Amber/Red contextual banner explaining the exact balance due with a direct "Go to Finance" button.

Slow Network / API Timeout: If backend student data takes longer than 1 second to fetch, dashboard cards will display smooth skeleton loading placeholders rather than blank boxes or broken layouts.

Zero Active Notifications: When a student has no unread alerts, the Smart Notification panel will display a clean, reassuring empty-state card ("You're all caught up! No urgent notices.") instead of collapsing the layout.

16. Risks and Mitigation Strategies
Risk 1: Legacy Backend Data Formatting Issues: Old OpenBaraza endpoints may return unformatted HTML strings inside announcement bodies. Mitigation: Implement a frontend text-sanitization and parser utility to strip legacy table tags and format announcements cleanly into modern cards.

Risk 2: User Resistance to Interface Changes: Returning students accustomed to the old menu locations might initially feel disoriented. Mitigation: Retain familiar menu titles (School Info, Academic Details, Finance) while enhancing them with icons and a brief first-login walkthrough tooltip.

Risk 3: Peak-Period Server Traffic: High concurrent traffic during registration week could slow down asset loading. Mitigation: Minify CSS/JS bundles, use lightweight vector SVG icons instead of heavy images, and cache static layout components.

17. Testing & Quality Assurance Plan
Usability & Peer Testing: Conduct timed task-completion tests with 15–20 Babcock University students across different departments to verify that registration and GPA lookup times drop as expected.

Cross-Device & Browser Matrix Testing: Validate all breakpoints (375px mobile, 768px tablet, 1440px desktop) using browser developer tools and physical Android/iOS smartphones.

Accessibility & Contrast Audits: Run automated Lighthouse and WAVE accessibility checks to confirm zero contrast violations in both Light and Dark themes.

18. Implementation Roadmap & Milestones (TEAM-oak)
Phase 1: Research & Wireframing (Week 1): Audit existing UMIS screens, gather peer feedback, and finalize low-fidelity layout wireframes.

Phase 2: High-Fidelity UI Design System (Week 2): Define color tokens, typography scale, card components, and Light/Dark theme prototypes.

Phase 3: Frontend Component Development (Weeks 3–4): Code the responsive grid, collapsible sidebar, summary cards, and interactive 5-step registration stepper.

Phase 4: Backend Integration & QA Testing (Week 5): Connect UI components to UMIS data endpoints, resolve edge cases, and conduct student usability testing.

Phase 5: Final Documentation & Deployment (Week 6): Submit final PRD, push clean code to the TEAM-oak GitHub repository, and present the live demo for BU-209 evaluation.

19. Team Roles and Responsibilities (TEAM-oak)
Team Lead (Amojo Raphael_25/0025): Overall project coordination, PRD authorship, GitHub repository and pull-request management, and final architectural review.

UI/UX Design Lead: Wireframing, color palette and typography standardization, card styling, and Light/Dark mode visual mockups.

Frontend Engineering Sub-Team: HTML/CSS grid architecture, collapsible sidebar implementation, mobile responsiveness, and interactive registration stepper logic.

Backend & API Integration Sub-Team: Mapping OpenBaraza/UMIS data endpoints, sanitizing legacy notification text, and ensuring secure session handling.

Quality Assurance & User Research Lead: Conducting campus student interviews, running cross-device browser tests, and tracking post-launch success metrics.

20. Glossary of Terms and Appendix
UMIS (University Management Information System): The official student academic, financial, and administrative web portal used by Babcock University.

OpenBaraza: The underlying open-source enterprise web framework powering the legacy UMIS interface.

MVP (Minimum Viable Product): The core set of high-impact UI features required to deliver immediate usability improvements for the first release.

Stepper / Progress Wizard: A horizontal visual navigation component that breaks a multi-step workflow (such as the 5-step course registration process) into sequential, trackable stages.

Cognitive Load: The mental effort required by a student to read, interpret, and navigate an interface to complete a task.
