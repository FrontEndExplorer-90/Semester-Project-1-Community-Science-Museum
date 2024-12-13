# Community Science Museum - Project Plan (Updated)

---

## **Project Goals**
- Design and build a responsive website for the Community Science Museum.
- **Target Audience**: Kids aged 7–15 and their families.
- **Purpose**: Make learning fun and encourage people to visit the museum.
- **Focus on Accessibility**: Make the website easy to use for everyone by following WCAG standards.
- **Interactivity Without JavaScript**: Use only HTML and CSS to make the site interactive with hover effects and toggled views.
- **Responsive Design**: Make sure the website works well on all screens, like phones, tablets, and computers.

---

## **Scope**

### **Included in the Project**
#### Pages:
- Home, Exhibits, Events, Visit Us, Get Involved, About, Contact, Privacy Policy.

#### Interactive Features:
- Highlight key attractions on each museum floor with hover and click features using CSS and HTML.
- Add click-based options for touchscreens to make sure everyone can use the site.

#### Accessibility:
- Follow WCAG standards to ensure the website is usable for all visitors:
  - Add clear focus indicators for keyboard users.
  - Use proper `<fieldset>` and `<legend>` tags for interactive sections.
  - Improve text contrast to make it easier to read.
- Write an **Accessibility Report** to explain what we did to make the site accessible.

#### Design for Kids and Teens:
- Use simple and easy-to-read language for all descriptions.
- Add fun visuals like icons and hover effects to make navigation enjoyable.

#### Responsive Design:
- Use CSS media queries to make sure all pages look good and work well on any device.

#### Testing:
- Test the site for accessibility using tools like **WAVE** or **VoiceOver**.
- Check usability with kids and families to ensure the site is easy to use.

### **Not Included**
- Backend features like logins or database connections.
- Advanced animations or interactive elements that require JavaScript.

---

## **Deliverables**
### Interactive Features:
- **Interactive Maps**:
  - Create hover effects for key attractions on each floor.
  - Provide a click-based fallback for devices that don’t support hover.

### Accessibility Features:
- Add clear focus indicators for navigation with a keyboard.
- Ensure the site structure is semantic and logical using accessibility tools.

### Responsive Design:
- Make sure all pages adjust properly on mobile, tablet, and desktop screens.

### Accessibility Report:
- Write a detailed report explaining how the site was made accessible.

### Testing Plan and Results:
- Test the site with kids and parents to make sure it’s easy and fun to use.

---

## **Lessons Learned**
1. **Fonts Are Important**:
   - Double-check font links and imports to make sure they load correctly on all browsers.
   - Fix cascading issues where fonts might get overridden.

2. **CSS Can Be Tricky**:
   - Pay attention to specificity and order in your stylesheets to avoid conflicts.
   - Use browser developer tools to fix overlapping styles.

3. **Interactivity Without JavaScript**:
   - Use CSS features like `:hover`, `:checked`, and sibling selectors to add interactions.
   - Add click-based fallbacks for touchscreens to ensure usability.

4. **Mobile Responsiveness**:
   - Use media queries to adjust fonts, layouts, and grids for different devices.

5. **Z-Index Debugging**:
   - Be careful with `z-index` values and make sure elements have the correct position property.

6. **Browser Cache Issues**:
   - Clear the cache regularly during testing to see updates right away.

---

## **Challenges and Solutions**

| **Challenge**                         | **Solution**                                                                                   |
|---------------------------------------|-----------------------------------------------------------------------------------------------|
| Aligning interactive dots on maps     | Used percentage-based positioning to keep dots in the right place.                            |
| Overlapping logo and text on mobile   | Adjusted margins and added flexbox properties for better spacing.                             |
| Hover effects not working on touchscreens | Added click-based toggles using radio buttons and CSS.                                       |
| Fonts not displaying correctly        | Checked font imports and cascading rules to fix font issues.                                  |
| Text hard to read over backgrounds    | Added opaque overlays and text shadows to improve contrast.                                   |
| Mobile usability                      | Used media queries to resize content and adjust layouts for smaller screens.                  |
| Misaligned header line                | Used `calc()` in the CSS to properly position the header line dynamically.                    |

---

## **Recommendations for Future Improvements**

### Interactive Features:
- Keep testing the interactive maps with real users to make sure they’re easy and fun to use.
- Update fallback features for new devices if necessary.

### Accessibility:
- Update the **Accessibility Report** whenever new features are added.
- Test the site with users who use screen readers or other assistive technologies.

### Responsive Design:
- Test the website on older devices and very large screens to identify any remaining issues.

---

## **Timeline and Milestones**

| **Milestone**                          | **Start Date** | **End Date** |
|----------------------------------------|----------------|--------------|
| Research Accessibility Requirements    | Nov 19         | Nov 19       |
| Define Content Plan                    | Nov 19         | Nov 20       |
| Create Project Plan                    | Nov 20         | Nov 21       |
| Wireframe Main Pages in Figma          | Nov 22         | Nov 23       |
| Review Wireframes and Revise           | Nov 24         | Nov 24       |
| Create High-Fidelity Mockups           | Nov 27         | Nov 28       |
| Develop HTML Structure                 | Nov 29         | Nov 30       |
| Develop CSS for Styling                | Nov 30         | Dec 1        |
| Ensure Contrast Ratio Compliance       | Nov 30         | Nov 30       |
| Interactive Exhibit Maps               | Dec 2          | Dec 3        |
| Create Fallbacks for Interactive Elements | Dec 3       | Dec 4        |
| Accessibility-Focused Updates          | Dec 4          | Dec 5        |
| Device and Usability Testing           | Dec 5          | Dec 6        |
| Test and Deploy                        | Dec 6          | Dec 6        |

---