**Objective:**
Build a web-based *Meeting Time Tracker* component that helps users keep meetings short, focused, and action-oriented.

---

### ✅ Functional Requirements

1. **Meeting Duration Input**

   * A simple input field where the user sets the meeting duration (default: 15 minutes).
   * A button labeled **“Enter Meeting”** to start the timer.

2. **Full-Viewport Timer Display**

   * On clicking “Enter Meeting”, the screen transitions into a full-viewport timer mode.
   * The countdown timer should be displayed prominently and legibly in the center.
   * Timer starts counting down immediately.

3. **Color Transition (Time Awareness)**

   * The background color should transition smoothly:

     * Start: **Green** (0% elapsed)
     * Middle: **Yellow** (50% elapsed)
     * End: **Red** (100% elapsed)

4. **5-Minute Reminder**

   * When 5 minutes remain, the timer should:

     * **Blink continuously**
     * Optionally, display a text reminder like:

       > “⏳ Wrap-up time! Summarize action points and closing notes.”

5. **Extend Time Feature**

   * A button labeled **“Extend by 5 Minutes”** should be available in full-screen mode.
   * Clicking it adds 5 minutes to the remaining time and resumes the countdown.
   * The color gradient should adjust accordingly.

6. **Responsiveness & Accessibility**

   * The design should be responsive across devices.
   * Ensure high contrast and readable font for accessibility.

### Deliverables

1. A basic HTML file with all the necessary elements in one page.
