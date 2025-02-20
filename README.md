# Next.js Query Parameter Parsing Issue

This repository demonstrates a common issue in Next.js related to query parameters not parsing correctly after navigation.  Specifically, when navigating from one page to another with query parameters, the parameters might not be correctly accessible on the destination page.  The issue is resolved by demonstrating the correct method to access these parameters.

## Problem
The original code attempts to pass a query parameter from the `/about` page to the `/` page. However, upon navigating to the home page, the query parameter is not properly reflected in the URL and cannot be accessed in the home page's component.

## Solution
The solution showcases the proper way to access query parameters in the Next.js environment. It ensures that the query parameter is correctly parsed and displayed on the home page.

## How to Reproduce
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to `/about`. 
5. Click the button to navigate back to the home page.
6. Observe that the query parameter is not initially correctly displayed in the URL or accessed in the component. 
7. See the corrected solution to resolve the issue.