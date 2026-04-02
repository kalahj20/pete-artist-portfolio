# README.md

## Project: Pete Thinkful Artist Portfolio
**Version:** 1.0.0  
**Developer:** Pete Thinkful  
**Tech Stack:** HTML5, CSS3

---

## 1. Design Mock-up
**Theme:** *Modern Industrial Gallery* The design focuses on a clean, minimalist aesthetic to ensure the abstract artwork remains the focal point.

* **Colors:** White background (`#FFFFFF`), Charcoal text (`#333333`), and Muted Blue (`#007BFF`) for interactive elements.
* **Typography:** Sans-serif stack for a modern, approachable feel.
* **Alignment:**
    * **Header:** Centered navigation links for balanced visual weight.
    * **About:** Split-layout with a circular profile image left-aligned and descriptive text right-aligned.
    * **Portfolio:** A responsive grid that stacks vertically on mobile and expands to a multi-column view on desktop.

---

## 2. Implementation Plan
1.  **Semantic Skeleton:** Use HTML5 tags (`<header>`, `<main>`, `<section>`, `<footer>`) to provide structure and improve accessibility.
2.  **Navigation:** Implement anchor tags linked to section IDs for smooth internal page jumping (e.g., `#About`, `#Portfolio`).
3.  **Styling Strategy:**
    * Integrate `normalize.css` to reset browser defaults and ensure cross-browser consistency.
    * Use **CSS Flexbox** for navigation spacing and the "About" section alignment.
    * Apply `border-radius: 50%` to the profile image class for a professional "headshot" look.
4.  **Responsive Design:** Use media queries to ensure the portfolio images resize appropriately for tablet and mobile screens.

---

## 3. Design Trade-offs
* **Simplicity vs. Flashiness:** I chose a stark white background. While a more "artistic" textured background was considered, it was traded off to prevent visual clashing with the diverse colors and textures of the abstract art.
* **Single-Page Layout:** I opted for a single-page scrolling experience. This simplifies the user journey but requires clear visual separators (like the `hr` tags) to define content boundaries and maintain focus.

---

## 4. Justification & Challenges
* **Justification:** I utilized an ordered list (`<ol>`) for the Contact section to create a clear hierarchy of engagement, intentionally placing professional networking (LinkedIn) at the top of the list.
* **Challenges:** Achieving perfect vertical alignment of the "About Me" text relative to the circular profile image proved tricky across different screen sizes.
* **Debugging:** I encountered an issue where portfolio images were overflowing their containers. I resolved this by applying `max-width: 100%` and `height: auto` to all images within the portfolio section to ensure they remain contained and proportional.

---

## 5. AI Tool Usage
* **Gemini/ChatGPT:** Used for generating creative placeholder text (the "Vaporware" descriptions). This allowed for rapid prototyping of the layout and typography without waiting for final copy.
* **Replit AI:** Assisted in troubleshooting the `flex-direction` logic for mobile responsiveness when transitioning from a row to a column layout.
* **Justification:** These tools were used to supplement technical execution and creative brainstorming; all structural logic, final design decisions, and code integrations were performed independently.


## 6. Deployment Histories
<img width="1252" height="662" alt="Screenshot 2026-04-01 at 10 35 33 PM" src="https://github.com/user-attachments/assets/e69b601f-bcd0-473a-820a-6f0a621879b8" />
<img width="452" height="366" alt="Screenshot 2026-04-01 at 10 37 18 PM" src="https://github.com/user-attachments/assets/a387bfa3-54cc-4702-99fc-33252715c355" />
