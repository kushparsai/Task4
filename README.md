# Task 4: Make a Website Mobile-Friendly Using CSS Media Queries

This task focuses on converting an existing desktop-only webpage into a fully responsive, mobile-friendly layout using CSS media queries.
You will adjust layout, spacing, navigation, and typography so that the page works correctly on all devices.

## Objective

Transform the provided HTML landing page into a responsive layout that adapts smoothly to mobile screens.

## Tools Required

Any existing HTML file (given)

VS Code or any code editor

Chrome DevTools (Device Toolbar for testing)

## Deliverables

A style.css file containing responsive CSS

A webpage that works correctly on mobile, tablet, and desktop

## Steps to Complete the Task
1. Open the Project in VS Code

Open the index.html and style.css files.

2. Identify Desktop-Only Issues

Look for:

Fixed widths

Large images

Wide text blocks

Navigation that doesn’t collapse

3. Add the Mobile Meta Tag

(Already added in your HTML)

<meta name="viewport" content="width=device-width, initial-scale=1.0">

4. Write a Media Query for Mobile Devices

Use a media query targeting screens 768px and below:

@media (max-width: 768px) {
    /* mobile styles here */
}

5. Make the Navigation Mobile-Friendly

Hide the desktop navigation on mobile

Show a hamburger icon

Make the menu stack vertically

6. Adjust Typography & Layout

Reduce heading size

Reduce paragraph size

Add more padding

Stack sections vertically

7. Ensure Images Scale Properly
img {
    max-width: 100%;
    height: auto;
}

8. Test on Chrome DevTools

Open DevTools → Toggle Device Toolbar

Check layouts on devices like:

iPhone SE

iPhone 14

Pixel 7

iPad Mini

Fix any spacing or overflow issues.

## Included Files
✔ HTML (Landing Page)

A simple header, hero section, and footer.

✔ CSS (Fully Responsive)

A complete desktop + mobile CSS file including:

Flexbox layout

Media queries

Hero scaling

Responsive typography

Collapsible navigation

## Optional Add-ons

You can improve the project by adding:

Smooth menu animations

Dark/Light mode

Sticky header

Responsive grid-based layout

## How to Run the Project

Open the folder in VS Code

Run using Live Server or simply open index.html in a browser

Resize the browser window or use DevTools to test responsiveness
