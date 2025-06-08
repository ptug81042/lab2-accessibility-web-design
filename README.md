# Lab 2: Accessibility Web Design

## What accessibility enhancements were the most challenging to implement, and why?
The most challenging accessibility enhancements to implement were ensuring proper keyboard navigation and focus management. Making sure that all interactive elements could be accessed and operated using only the keyboard required careful attention to tabindex values and event handling. Additionally, providing meaningful alt text for images and ensuring that dynamic content updates were announced to screen readers required a good understanding of ARIA roles and properties.

## How do ARIA attributes improve the experience for users relying on assistive technologies?
ARIA (Accessible Rich Internet Applications) attributes improve the experience for users relying on assistive technologies by providing additional semantic information about elements that are not natively accessible. For example, ARIA roles can define the purpose of custom widgets, ARIA states and properties can communicate changes in the interface, and ARIA labels can provide descriptive text for screen readers. This helps users with disabilities better understand and interact with web content.

## What tools did you use to check color contrast, and how did they help?
To check color contrast, I used Google Chrome browser extensions such as "Color Contrast Analyzer" and "axe DevTools." These tools helped identify areas where text and background color combinations did not meet accessibility standards (such as WCAG AA or AAA). They provided visual feedback and suggestions for improving contrast, ensuring that the site is readable for users with low vision or color blindness.
