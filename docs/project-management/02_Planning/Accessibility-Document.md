# Accessibility Document v1.0

### Yek Accessibility & Inclusive Design Requirements

**Purpose:**

Define accessibility and inclusive-design requirements that will guide Yek's UX design, development, testing, and release activities.

**Project Phase:**

Sprint 3 — UX Research & Planning

**Applies To:**

UX/UI Design, Flutter Development, QA Testing, and Release

**Objective:**

Ensure Yek's interface can be effectively used by people with a range of visual, auditory, motor, cognitive, and language-related needs.

### 1. Color & Color Blindness

- [ ]  Color is never the only way information is communicated
- [ ]  Correct/incorrect states use icons and/or text in addition to color
- [ ]  Avoid relying on **red vs. green** to communicate meaning
- [ ]  Selected/unselected states have more than just a color difference
- [ ]  Error/success/warning states include text or recognizable icons
- [ ]  Charts and statistics don't depend solely on different colors
- [ ]  Color combinations have sufficient contrast
- [ ]  Colors remain distinguishable for common forms of color-vision deficiency
- [ ]  Don't use extremely similar shades to represent different states

### 2. Vision & Readability

- [ ]  Text has sufficient contrast against its background
- [ ]  Body text is comfortably readable on a phone
- [ ]  Important information isn't presented in extremely small text
- [ ]  Icons are large enough to recognize
- [ ]  Important controls have adequate visual prominence
- [ ]  Information isn't dependent on tiny visual details
- [ ]  Text remains usable when the user increases system font size
- [ ]  UI doesn't break when text becomes larger
- [ ]  Dark mode, if supported, maintains adequate contrast
- [ ]  Disabled elements are still distinguishable without becoming unreadable

### 3. Typography

Particularly important for Yek because of Persian.

- [ ]  Persian font is highly legible
- [ ]  English font is highly legible
- [ ]  Persian and English remain visually distinct when appropriate
- [ ]  Font sizes are appropriate for learning content
- [ ]  Line spacing is comfortable
- [ ]  Text isn't unnecessarily condensed
- [ ]  Long Persian words don't cause unexpected layout problems
- [ ]  Text wrapping works correctly
- [ ]  Larger system font sizes don't destroy layouts

### 4. Persian / RTL Accessibility

- [ ]  Persian screens use correct RTL layout
- [ ]  English screens use correct LTR layout
- [ ]  Mixed Persian/English content behaves correctly
- [ ]  Text alignment is appropriate
- [ ]  Navigation behaves correctly in RTL
- [ ]  Back/forward arrows are appropriate for the current direction
- [ ]  Icons don't accidentally communicate the wrong direction
- [ ]  Numbers display correctly
- [ ]  Dates display correctly
- [ ]  Punctuation behaves correctly
- [ ]  Text doesn't overlap or clip when switching languages
- [ ]  UI accommodates different text lengths
- [ ]  Switching language direction doesn't break the layout

### 5. Touch & Motor Accessibility

- [ ]  Buttons have sufficiently large touch targets
- [ ]  Small icons have larger invisible/tappable areas
- [ ]  Users don't need extremely precise taps
- [ ]  Important actions aren't hidden behind tiny icons
- [ ]  Users aren't required to perform complicated gestures
- [ ]  Gestures have an alternative when practical
- [ ]  Swipe isn't the only way to perform an important action
- [ ]  Controls aren't positioned so close together that accidental taps are likely
- [ ]  Interface works reasonably well with one hand

### 6. Audio Accessibility

- [ ]  Audio isn't the **only** way important information is communicated
- [ ]  Pronunciation buttons are clearly labeled
- [ ]  Audio controls have accessible labels
- [ ]  Users can tell whether audio is playing
- [ ]  Users can replay pronunciation easily
- [ ]  Volume doesn't unexpectedly jump to an uncomfortable level
- [ ]  Audio playback works with headphones
- [ ]  Background audio behavior is predictable
- [ ]  Lock-screen/headphone controls are understandable
- [ ]  Important visual information isn't removed just because audio is available

### 7. Screen Readers & Assistive Technology

- [ ]  Buttons have meaningful accessibility labels
- [ ]  Icon-only buttons have descriptive labels
- [ ]  Images have appropriate accessibility descriptions when needed
- [ ]  Decorative elements aren't unnecessarily announced
- [ ]  Screen readers encounter content in a logical order
- [ ]  Interactive elements can be reached using assistive technology
- [ ]  Correct/incorrect feedback is understandable without color
- [ ]  Audio controls are understandable to screen readers
- [ ]  Navigation elements are clearly identified

### 8. Cognitive Accessibility

- [ ]  Users can understand what to do without extensive instructions
- [ ]  Primary actions are obvious
- [ ]  Navigation is predictable
- [ ]  Similar actions behave consistently
- [ ]  Screens aren't unnecessarily cluttered
- [ ]  Important information isn't buried
- [ ]  Users aren't forced through unnecessary steps
- [ ]  Error messages explain what went wrong
- [ ]  Error messages explain how to recover
- [ ]  Users receive clear feedback after important actions
- [ ]  Terminology is consistent throughout the app
- [ ]  Users aren't overwhelmed with too many choices at once

### 9. Animation & Motion

- [ ]  Animation isn't required to understand the interface
- [ ]  Important feedback doesn't disappear too quickly
- [ ]  Animations aren't unnecessarily distracting
- [ ]  Rapid flashing is avoided
- [ ]  The app can accommodate reduced-motion preferences where appropriate
- [ ]  Animations don't interfere with reading or learning
- [ ]  Loading animations don't prevent users from interacting unnecessarily

### 10. Responsive & Device Accessibility

- [ ]  Small phone screen
- [ ]  Large phone screen
- [ ]  Different screen resolutions
- [ ]  Portrait orientation
- [ ]  Landscape behavior, if supported
- [ ]  iOS
- [ ]  Android
- [ ]  Larger system font
- [ ]  Dark mode/light mode, if supported
- [ ]  Different language settings
- [ ]  RTL/LTR switching

## 11. Accessibility Testing

- [ ]  Test every major screen with increased font size
- [ ]  Test color combinations for color blindness
- [ ]  Test contrast
- [ ]  Test screen-reader navigation
- [ ]  Test touch targets
- [ ]  Test Persian RTL screens
- [ ]  Test English LTR screens
- [ ]  Test mixed Persian/English content
- [ ]  Test audio controls
- [ ]  Test dark mode
- [ ]  Test error/success states
- [ ]  Test on iOS
- [ ]  Test on Android
- [ ]  Record accessibility bugs in Jira
- [ ]  Retest accessibility bugs after fixes

# ⭐ Yek's "Golden Rules"

1. **Never communicate meaning through color alone.**
2. **Never rely solely on red vs. green.**
3. **Use readable typography and sufficient contrast.**
4. **Make interactive controls easy to tap.**
5. **Don't require complicated gestures for important actions.**
6. **Support both LTR English and RTL Persian properly.**
7. **Don't make audio the only way to understand information.**
8. **Make screen-reader labels meaningful.**
9. **Keep interactions simple and predictable.**
10. **Test accessibility on real iOS and Android devices before launch.**