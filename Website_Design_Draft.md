# Website Design Draft: Diabetes Management Portal

## 1. Vision & Tone
- **Goal:** Provide a mission-driven, accessible resource for diabetes management, inspired by a personal success story.
- **Tone:** Personal, empowering, clear, and calm. "No medical jargon, no spreading fear"
- **Aesthetic:** "Soft" and "Appealing."
- **Color Palette:** 
  - Primary: Light Sky Blue (Backgrounds)
  - Secondary: Navy Blue (Headings/Bold Text)
  - Accent: Soft Teal (Interactions/Buttons)
- **Motion:** Soft transitions (0.8s fades) and scroll-triggered animations.

## 2. Architecture: Approach 2 (The Portal)
The site consists of a high-impact Landing Page that "portals" users into specific educational sub-pages via immersive transitions.

### 2.1 Navigation
2 Options:
- **Option 1 - If the text is short:** Top Navigation Bar (Labels: "Home", "What is Diabetes?", "Eating Guide", "Tools").
- **Option 2 - If the text is long:** Collapsible Table of Contents on the left side for long-form content pages (e.g., "What is Diabetes").

## 3. Page Specifications

### 3.1 Home Page (Landing)
- **Hero Section (Unique Centered Style):**
  - Centered layout featuring Jackie's personal story transcript.
  - Image integration (Jackie/Father or symbolic health imagery).
- **Quote Section:**
  - Transition piece: "My dad was diagnosed... He chose a different path — and it worked."
  - **Format:** Bold text on a Light Blue background.
- **Mission Section:**
  - Text: "I built this website because nobody should have to piece together that information alone..."
  - Visuals: 1-2 images representing the mission (health, control, support).
- **The "Start" Transition:**
  - **Action:** Clicking the "Start" button triggers a full-page fade-out.
  - **Effect:** The home page fades to a solid color/white, and the "What is Diabetes" page fades in (emerges).

### 3.2 "What is Diabetes" Page (Sub-page)
- **Statistics Strip:**
  - **Animated Numbers:** Counters for ">500M people worldwide," "100M unaware," etc.
  - **Data Visuals:** Dynamic icons or small charts that animate on scroll.
- **Content Layout:**
  - Background changes color subtly as the user scrolls through sections.
  - Integration of "Windows Transition" style where content enters the viewport with soft motion.

### 3.3 Tools Section (Ongoing)
- **Features:**
  - Calendar
  - Clinics Contact
  - Meal Tracker
  - Community Searching
  - Prescription Tracking

## 4. Technical Requirements
- **Transitions:** Use CSS/JS for scroll-triggered background shifts and full-page fade transitions.
- **Responsiveness:** Ensure the centered hero and top-nav remain legible on mobile.
- **Accessibility:** High contrast for Navy Blue text on Light Blue backgrounds.

## 5. Success Criteria
- User feels a personal connection through the story.
- Information is delivered without overwhelming medical complexity.
- Navigation is intuitive, moving from "The Story" to "The Tools."
