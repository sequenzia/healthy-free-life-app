# Product Requirements Document

## 7 Biblical Habits for a Healthy Free Life
### Web Application

| Field | Value |
|-------|-------|
| Version | 1.0 |
| Date | November 2025 |
| Product Name | HFL Academy Habit Tracker |
| Status | Draft |

---

## 1. Executive Summary

This document outlines the requirements for a web-based habit tracking application designed to support the "7 Biblical Habits for a Healthy Free Life" program. The application will digitize the existing paper-based system used by HFL Academy, enabling users to build healthy habits through a faith-centered approach that combines behavioral science principles with biblical teaching.

The system incorporates James Clear's "Four Laws of Behavior Change" framework (from Atomic Habits) integrated with spiritual practices including daily prayer, Scripture reading, and community accountability. The application will serve members of the HFL Academy community who are working through the seven foundational habits: Worship, Rest, Hydrate, Sleep, Move, Eat, and Exercise.

---

## 2. Product Vision

### 2.1 Problem Statement

The current paper-based habit tracking system, while effective, presents several limitations. Users must manually print worksheets each month, physical trackers can be lost or damaged, there is no mechanism for tracking long-term progress across multiple months, community sharing requires photographing and uploading paper trackers, and users cannot easily review their historical "why" statements and commitment prayers. A digital solution will address these pain points while preserving the reflective, intentional nature of the paper system.

### 2.2 Vision Statement

To create a digital sanctuary where users can intentionally cultivate healthy habits through the integration of biblical wisdom and proven behavioral science, fostering both personal transformation and community accountability.

### 2.3 Target Users

The primary users are members of the HFL Academy community, typically adults seeking to improve their physical and spiritual health through structured habit formation. Users value faith integration in their wellness journey, appreciate structured guidance and accountability, range from digitally comfortable to those who prefer simplicity, and are committed to long-term lifestyle change rather than quick fixes.

---

## 3. Scope and Objectives

### 3.1 In Scope

1. Digital habit setup workflow ("Create Your System" worksheet)
2. Interactive monthly habit tracker with daily check-ins
3. Bible reading plan integration with progress tracking
4. Prayer and reflection journaling
5. Community features for Friday accountability posts
6. Progress analytics and historical data visualization
7. Reminder and notification system
8. Export functionality for printable versions

### 3.2 Out of Scope (Initial Release)

- Native mobile applications (web-responsive design will be used initially)
- Integration with wearable devices or health tracking apps
- Video content hosting (tutorials will link to external platforms)
- Direct messaging between users
- E-commerce or payment processing

---

## 4. The Seven Biblical Habits

The application centers on seven foundational habits, each building upon the previous. Users focus on establishing one primary habit at a time while maintaining previously established habits.

| # | Habit | Description |
|---|-------|-------------|
| 1 | Worship | Daily spiritual practice and connection with God |
| 2 | Rest | Sabbath observance and intentional rest periods |
| 3 | Hydrate | Adequate daily water intake |
| 4 | Sleep | Consistent, restorative sleep routines |
| 5 | Move | Regular daily movement and activity |
| 6 | Eat | Nourishing, intentional eating habits |
| 7 | Exercise | Structured physical fitness routines |

---

## 5. Functional Requirements

### 5.1 User Authentication and Profile Management

1. Users shall be able to create an account using email/password or social authentication (Google).
2. Users shall be able to create and edit a profile including name, profile photo, and time zone.
3. Users shall be able to set notification preferences for reminders and community updates.
4. Users shall be able to export or delete their personal data in compliance with privacy regulations.
5. The system shall support password reset via email verification.

### 5.2 Habit Setup Workflow ("Create Your System")

The habit setup workflow digitizes the paper worksheet and guides users through establishing their habit system.

#### 5.2.1 Step Selection

1. Users shall be able to select which habit (1-7) they are currently establishing as their primary focus.
2. The system shall display the habit name and brief description upon selection.
3. The system shall indicate which habits the user has previously completed.

#### 5.2.2 "Why" Reflection

1. Users shall be able to enter and save a free-text response explaining why this habit is important to them.
2. The system shall display prompting questions to guide reflection.
3. Users shall be able to edit their "why" statement at any time.
4. The system shall store historical versions of "why" statements with timestamps.

#### 5.2.3 Spiritual Commitment

1. Users shall be able to write and save a personal prayer or commitment statement for their habit.
2. The system shall provide a default prayer template specific to each habit (e.g., the sleep prayer from the paper version).
3. Users shall be able to customize or write their own prayer.

#### 5.2.4 The Four Laws Application

Users shall complete structured input fields for each of the four behavioral laws:

**Make it Obvious:** Users shall define implementation intentions using the format "I will [BEHAVIOR] at [TIME] in [LOCATION]." Users shall also define habit stacking triggers using the format "After [CURRENT HABIT] I will [NEW HABIT]." The system shall provide example implementations for each habit type.

**Make it Attractive:** Users shall describe strategies to make the habit appealing. The system shall provide suggested strategies such as temptation bundling and motivation from benefits.

**Make it Easy:** Users shall identify ways to reduce friction and simplify the habit. The system shall suggest environment design strategies and two-minute rule applications.

**Make it Satisfying:** Users shall define immediate rewards and tracking methods. The system shall explain the importance of habit tracking and suggest reward strategies.

### 5.3 Daily Habit Tracker

#### 5.3.1 Tracker Display

1. The system shall display a monthly calendar grid showing all days of the current month.
2. The primary habit being established shall be displayed prominently at the top.
3. Previously established habits ("Habits to Maintain") shall be displayed in a secondary section.
4. Each habit row shall show the habit name and 31 daily checkboxes.
5. The user's habit intention statement shall be displayed above the tracker.
6. The daily prayer shall be accessible via a dedicated button or expandable section.

#### 5.3.2 Daily Check-In

1. Users shall be able to mark each habit as complete or incomplete for any day.
2. The system shall support three states: complete (checked), incomplete (unchecked), and skipped/rest day (optional marking).
3. Users shall be able to add optional notes for any day.
4. The system shall allow retroactive entry for missed days within the current month.
5. The system shall calculate and display current streak count for each habit.
6. The system shall calculate and display monthly completion percentage.

#### 5.3.3 Monthly Transitions

1. The system shall automatically generate a new tracker at the start of each month.
2. Users shall be prompted to review and optionally update their habit setup when starting a new month.
3. Historical months shall be viewable but not editable after a grace period.

### 5.4 Bible Reading Plan

1. The system shall display a monthly Bible reading plan with daily Scripture assignments.
2. Each day shall show readings from multiple sections (New Testament, Old Testament, Psalms) as per the HFL Academy plan.
3. Users shall be able to select their reading track: New Testament only, Old Testament only, or both.
4. Users shall be able to mark each day's reading as complete.
5. The system shall include designated "Reflect and Catch Up" days as shown in the paper plan.
6. Users shall be able to add personal reflection notes for each reading.
7. The system shall track reading plan completion across the full year.

### 5.5 Community Features

#### 5.5.1 Friday Accountability Posts

1. Users shall be able to share their weekly tracker progress to the community feed.
2. The system shall generate a shareable image/summary of the user's weekly progress.
3. Users shall be able to add a caption or reflection to their weekly post.
4. The system shall send reminders on Fridays to encourage posting.
5. Posts shall be viewable in a community feed organized by date.

#### 5.5.2 Community Interaction

1. Users shall be able to view and encourage other members' posts.
2. Users shall be able to react to posts with predefined encouraging responses (e.g., prayer emoji, celebration, encouragement).
3. The system shall not include open comments (to maintain a positive, moderation-light environment).
4. Users shall be able to control their own post visibility (public to community or private).

### 5.6 Dashboard and Analytics

1. The system shall display an overview dashboard upon login showing today's habits, reading plan, and streak status.
2. Users shall be able to view progress charts showing habit completion over time.
3. The system shall display longest streak achievements for each habit.
4. The system shall show overall program progress (which habits have been established).
5. Users shall be able to access historical data from previous months.
6. The system shall provide year-in-review summaries.

### 5.7 Notifications and Reminders

- Users shall be able to set custom reminder times for daily habit check-ins.
- Users shall receive optional reminders for Bible reading.
- The system shall send Friday reminders for community posting.
- Users shall be able to enable or disable each notification type independently.
- Notifications shall be delivered via email and/or browser push notifications based on user preference.

### 5.8 Export and Print

- Users shall be able to generate a printable PDF of their monthly habit tracker.
- Users shall be able to export their "Create Your System" worksheet as PDF.
- Users shall be able to export their Bible reading plan with progress.
- Users shall be able to download all personal data in a standard format (JSON/CSV).

---

## 6. Non-Functional Requirements

### 6.1 Performance

1. Page load time shall not exceed 3 seconds on standard broadband connections.
2. Habit check-in interactions shall respond within 500 milliseconds.
3. The system shall support at least 1,000 concurrent users.

### 6.2 Security

1. All data transmission shall use HTTPS encryption.
2. User passwords shall be hashed using industry-standard algorithms.
3. The system shall implement rate limiting to prevent abuse.
4. Personal reflection and prayer content shall be encrypted at rest.

### 6.3 Accessibility

1. The application shall conform to WCAG 2.1 Level AA standards.
2. All interactive elements shall be keyboard accessible.
3. The application shall support screen readers.
4. Color contrast shall meet accessibility guidelines.

### 6.4 Reliability

1. The system shall maintain 99.5% uptime.
2. Data shall be backed up daily with 30-day retention.
3. The system shall gracefully handle network interruptions during data entry.

### 6.5 Usability

1. The interface shall be fully responsive, supporting desktop, tablet, and mobile viewports.
2. Core daily tracking functionality shall be accessible within two clicks from the dashboard.
3. The design shall maintain visual consistency with HFL Academy branding (coral/salmon accent colors, clean aesthetic).

---

## 7. Technical Recommendations

The following technical stack is recommended based on the requirements:

### 7.1 Frontend

1. React or Next.js for component-based UI development
2. Tailwind CSS for responsive, consistent styling
3. Progressive Web App (PWA) capabilities for offline tracking and mobile installation

### 7.2 Backend

1. Node.js with Express or Python with FastAPI
2. PostgreSQL for relational data storage
3. Redis for session management and caching

### 7.3 Infrastructure

1. Cloud hosting (AWS, Google Cloud, or Vercel)
2. CDN for static asset delivery
3. Automated CI/CD pipeline for deployments

---

## 8. Implementation Phases

### Phase 1: Core Functionality (MVP)

1. User authentication and profile management
2. Habit setup workflow ("Create Your System")
3. Daily habit tracker with check-ins
4. Basic dashboard

### Phase 2: Extended Features

1. Bible reading plan integration
2. Community posting and feed
3. Notification system
4. Progress analytics

### Phase 3: Enhancement

1. Export and print functionality
2. Advanced analytics and year-in-review
3. PWA offline capabilities
4. Accessibility audit and improvements

---

## 9. Success Metrics

The following metrics will be used to evaluate the success of the application:

- Daily Active Users (DAU) and Weekly Active Users (WAU)
- Habit check-in completion rate (percentage of expected check-ins completed)
- Average streak length across users
- Bible reading plan completion rate
- Weekly community post participation rate
- User retention at 30, 60, and 90 days
- Net Promoter Score (NPS) from user surveys

---

## 10. Appendices

### Appendix A: Default Prayer Templates

Each habit will include a default prayer template. Example for Sleep habit:

> *"Dear God, I recognize my need for sleep as a healthy limitation. I surrender to your Lordship and trust you as a child. Help me create an atmosphere and routine conducive to deep, restorative sleep and still my mind from fretting. Beyond my efforts, I am trusting you for the gift of sleep. Thank you that you never slumber nor sleep and are always working for the good of your children. I am glad to be your child. Keep me in perfect peace. Amen."*

### Appendix B: Glossary

**Implementation Intention:** A specific plan stating when, where, and how you will perform a habit.

**Habit Stacking:** Linking a new habit to an existing habit by using the formula "After [CURRENT HABIT], I will [NEW HABIT]."

**The Four Laws:** James Clear's framework for habit formation consisting of Make it Obvious, Make it Attractive, Make it Easy, and Make it Satisfying.

**Streak:** Consecutive days of completing a habit without missing.

---

*End of Document*
