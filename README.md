# React Router Dom Unexpected Behavior with window.location.href

This repository demonstrates an unexpected behavior when using `window.location.href` for navigation within a React application using `react-router-dom`. While navigation appears to work, it leads to full page reloads and other inconsistencies compared to using the recommended `Link` component.

## Bug Description
The `window.location.href` method, though functional, bypasses React Router's internal navigation mechanism.  This results in the loss of React Router's benefits such as client-side routing, optimized rendering and state management.