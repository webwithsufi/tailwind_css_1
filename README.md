# tailwind_css_1

This is my first project built using Tailwind CSS. It's a simple landing page showcasing a brief introduction.

**[View Live Site](https://webwithsufi.github.io/tailwind_css_1/)**

## Overview

The page features:

- A basic navigation bar with a logo and links (hidden on smaller screens and visible on larger screens).
- A centered hero section with:
    - A circular profile image.
    - A prominent name ("Hi, i'm Sufyan Ali").
    - A headline describing the purpose ("Building digital products, brands, and experiences.").
    - A short introductory paragraph.
    - A "Connect With Me" button.

The layout is responsive, with the navigation links appearing in a menu icon on smaller devices.

## Technologies Used

- **HTML:** For the basic structure of the webpage.
- **Tailwind CSS:** A utility-first CSS framework for rapid styling. The CSS is included directly from a CDN link.
- **Remix Icons:** A set of open-source icons used for the menu icon on smaller screens.

## Getting Started (If you want to run it locally)

Since this project primarily uses a CDN for Tailwind CSS, you don't need a complex setup to run it locally.

1.  **Save the HTML:** Copy the provided HTML code and save it as an `.html` file (e.g., `index.html`).
2.  **Open in Browser:** Simply open the `index.html` file in your web browser.

## Key Tailwind CSS Features Used

- **Utility Classes:** The styling is done entirely through Tailwind's utility classes applied directly in the HTML (e.g., `h-screen`, `w-full`, `bg-gray-300`, `flex`, `justify-between`, `px-4`, `py-4`, `font-bold`, `hidden`, `lg:flex`, `gap-10`, `opacity-60`, `ri-menu-line`, `flex-col`, `items-center`, `justify-center`, `w-36`, `h-36`, `rounded-full`, `bg-blue-600`, `text-2xl`, `text-3xl`, `lg:text-4xl`, `text-center`, `text-base`, `lg:opacity-60`, `tracking-tight`, `px-4`, `py-2`, `lg:py-3`, `bg-black`, `text-white`, `rounded-full`, `text-sm`, `lg:text-base`).
- **Responsiveness:** The `lg:` prefix is used to apply styles specifically on larger screens (e.g., `lg:flex`, `lg:hidden`, `lg:gap-10`, `lg:text-4xl`, `lg:opacity-60`, `lg:py-3`, `lg:text-base`).
- **Layout Utilities:** Classes like `flex`, `grid`, `container` (though custom in this case), and spacing utilities (`gap`, `px`, `py`) are used for structuring the page.
- **Typography Utilities:** Classes for controlling font size (`text-xl`, `text-3xl`), font weight (`font-bold`, `font-semibold`), and text alignment (`text-center`).
- **Background and Color Utilities:** Classes for setting background colors (`bg-gray-300`, `bg-blue-600`, `bg-black`) and text color (`text-white`).
- **Sizing and Spacing Utilities:** Classes for setting height (`h-screen`, `h-full`, `h-[...]`), width (`w-screen`, `w-full`, `w-36`, `w-3/4`), and padding/margin.
- **Border and Effects Utilities:** Class for creating rounded corners (`rounded-full`).

## Future Improvements

- Adding more sections like "About," "Services," and "Contact."
- Implementing more complex layouts and components.
- Optimizing for different screen sizes and improving responsiveness.
- Potentially using a build process for Tailwind CSS for better performance and customization.
- Adding more styling and visual elements.
- Making the navigation menu on smaller screens interactive.
