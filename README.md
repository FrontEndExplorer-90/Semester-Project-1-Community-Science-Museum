## This section documents the feedback received for the project and the changes made in response, along with reflections on decisions and prioritization.

## Mobile Prototype
I chose not to create a separate mobile prototype in Figma for this delivery. While I understand its value in the planning process, I focused my efforts on directly implementing and testing a fully responsive mobile layout through CSS media queries and live screen testing. With a two-week timeframe, extensive feedback revisions on three separate pages, building an entirely new portfolio, and balancing family and work commitments, I had to prioritize. The final mobile layout is tested, functional, and visually consistent, even without a dedicated mobile prototype.


## GitHub Project board status
Changes Made:
- Moved all completed tasks to the Done column

- Reviewed open tasks and left comments or archived unused ones


## Hamburger Menu for Mobile
After testing the mobile layout on multiple devices and breakpoints, I decided not to implement a hamburger menu. The navigation links fit well on smaller screens, remain clear and easy to interact with, and do not disrupt the visual hierarchy or usability. I intentionally prioritized simplicity and accessibility over adding unnecessary complexity to the user interface.

## CSS DRY Principle

Changes Made:

-Refactored all CSS files to use :root variables for fonts, colors, sizes, and spacing

-Removed repeated declarations and applied shared values consistently across pages

-Improved maintainability and readability of all stylesheets


# Community Science Museum Website

## Project Overview
An interactive, engaging, and responsive website for the Community Science Museum, designed to appeal to middle school children, families, and curious visitors.

### Target Audience
- **Age Group**: 7–15 years and families with young children.
- **Tone**: Informative, intelligent, engaging.

---

## Sitemap
The website will consist of the following pages:

1. **Home**
   - Brief introduction to the museum.
   - Call-to-action: Visit the museum or learn more about exhibits.
   - Highlight special features like interactive exhibits and events.

2. **Exhibits**
   - Sub-sections for key exhibits:
     - **Cosmology**: The wonders of the cosmos and constellations.
     - **Evolution**: Origins of life and extinct species (e.g., Woolly Mammoth).
     - **Robotics and AI**: Science of the future with interactive robot displays.
   - Informative descriptions and images for each exhibit.

3. **Events**
   - Highlight special events like "Night in the Museum" and visiting professors.
   - Include event descriptions, dates, and how to register.

4. **Visit Us**
   - Practical information:
     - Opening hours.
     - Location and accessibility.
     - Admission fees (including free entry details).

5. **Get Involved**
   - Opportunities to:
     - Volunteer.
     - Donate or become a member.
     - Participate in internship programs for students.

6. **About**
   - Mission and vision of the museum.
   - Brief history of its significance to the community.

7. **Contact**
   - Accessible contact form.
   - Call-to-action for inquiries or feedback.

---

## Content Plan

### Home
- **Header**: "Explore Together at the Community Science Museum."
- **Sections**:
  - Introductory paragraph about the museum.
  - Highlights: Interactive exhibits and key events.
  - Featured CTA: Links to “Exhibits” or “Plan Your Visit.”

### Exhibits
- **Header**: "Discover the Wonders of Science."
- **Sections**:
  - Sub-sections for Cosmology, Evolution, Robotics, Medicine, and more.
  - Each section includes:
    - Engaging text descriptions.
    - Images with descriptive alt text.
    - Interactive map features for floor navigation.

### Events
- **Header**: "Exciting Events for the Whole Family."
- **Sections**:
  - Featured events with descriptions and dates.
  - Registration instructions for workshops or lectures.

### Visit Us
- **Header**: "Plan Your Visit."
- **Sections**:
  - Practical details:
    - Address, opening hours, and ticket prices.
    - Accessibility services.

### Get Involved
- **Header**: "Support the Museum."
- **Sections**:
  - Volunteer opportunities.
  - Instructions on donating or becoming a member.
  - Internship programs for students.

### About
- **Header**: "About the Community Science Museum."
- **Sections**:
  - Mission and vision statement.
  - A brief history of the museum.

### Contact
- **Header**: "Get in Touch."
- **Sections**:
  - Accessible contact form with validation.
  - Information about response times and other contact options.

---

## Features
- Fully responsive design for mobile, tablet, and desktop.
- Interactive maps with accessible, clickable exhibit highlights.
- WCAG-compliant accessibility, including ARIA roles, semantic HTML, and proper color contrast.
- Optimized images (<200KB) for faster loading times.
- Accessible and validated forms for user interaction.

---

## Assets and Resources
- **Text Content**: Written in collaboration with project partners.
- **Images**: Compressed and optimized for performance.
- **Validation Tools**: WAVE, WebAIM, and Nu HTML Checker.
- **Deployment**: Hosted on Netlify, with GitHub for version control.

---

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/community-science-museum.git
