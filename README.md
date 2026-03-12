What is this?
This is a responsive "Hero Section" I built for a laundry service. The goal was to create a clean, modern landing page that looks professional but remains simple enough to load quickly and work on any device.

How I Built It
The Header: I used Flexbox for the navigation bar to keep the logo on the left and the menu/user profile on the right. I wanted it to feel spacious, so I used justify-content: space-between.

The Hero Section: This is split into two halves.

Left side: Focuses on the "Call to Action" (the headline and the booking button).

Right side: Features a large, clean illustration to give the page some personality.

Layout Logic: I used calc(100vh - 80px) for the hero height. This ensures the section perfectly fills the screen regardless of the monitor size, after accounting for the 80px height of my navbar.

Making it Responsive (The "Why" behind my Media Queries)
I used a Desktop-First approach and then "broke" the design at specific widths to keep it readable:

1024px (Laptops): I scaled down the font sizes slightly because the text was getting too close to the image.

768px (Tablets): I adjusted the navigation links. I originally had them very small, but realized they were hard to read, so I bumped them back up to 14px for better accessibility.

480px (Mobile): At this stage, the side-by-side layout just didn't work. I used flex-direction: column to stack the text on top of the image so the user doesn't have to zoom in to read the description.

What I Learned
The biggest takeaway for me was learning how to balance font sizes across different screen sizes. It’s one thing to make a site "fit" on a phone, but it's another thing to make it actually usable and readable. I also practiced using CSS variables (:root) to make it easier to change the color scheme (like the "main-blue" and "bg-color") in one place instead of hunting through 200 lines of code.

This is the Live Host Link: https://task5-three-beta.vercel.app/