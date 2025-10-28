To develop a Dashboard Web Application that displays employee performance metrics, supports theme switching (light/dark), and allows users to filter data interactively.

The dashboard should be visually appealing, interactive, and responsive on all screen sizes.

HTML5 - Structure & Layout

We use semantic HTML5 elements like <header>, <main>, <section>, and <footer> to keep the structure clean and organized.

Key Features:

The header displays the dashboard title.

The main section contains filters, theme toggle buttons, and performance panels.

The section inside main uses Bootstrap grid (row, col) to show employee cards.

Each card includes progress bars to represent performance metrics visually.

CSS3 - Styling & Layout

We combine CSS3 with Bootstrap for styling and responsive design.
CSS provides the custom visual appeal, while Bootstrap handles most of the layout.

CSS Features Used:

Box Model: Applied padding, margins, and shadows for neat spacing.

Rounded Corners: Used for cards and buttons to give a smooth, modern look.

Media Queries: Adjust text and layout for smaller screens (mobile view).

Theme Styling: Custom classes like .dark-theme switch between dark and light modes smoothly.

JavaScript + jQuery - Interactivity & Behavior

We make the dashboard interactive and dynamic using JavaScript and jQuery.

JavaScript Functions:

Theme Switching:
Toggles between light and dark mode by adding or removing the .dark-theme class dynamically.

Filtering:
The dropdown filter lets users view employees by department (e.g., Development, Design, Marketing).
JavaScript shows/hides employee cards accordingly.

jQuery Enhancements:

Smooth Panel Animation:
Expanding and collapsing employee performance panels using slideToggle() for better user experience.

DOM Manipulation:
Dynamically changes button icons ("+" or "-") when panels are expanded or collapsed.

Bootstrap - Responsive Design & Components

Bootstrap ensures the dashboard is fully responsive and mobile-friendly.

Bootstrap Features Used:

Grid System:
Used container, row, and col-md-6 / col-lg-4 to arrange employee cards neatly across devices.

Progress Bars:
Visual representation of performance metrics (e.g., Task Completion 85%).
Bootstrap's .progress and .progress-bar classes make it easy to display performance visually.

Utility Classes:
Used built-in classes like text-center, shadow, and btn for instant styling consistency.

