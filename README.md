# Next.js 15 Routing Issue

This repository demonstrates a routing issue encountered in a Next.js 15 application. Links to other pages within the application are not functioning correctly. The About page, for example, fails to render.

## Problem Description

The application has two pages, Home and About.  A link from the Home page is supposed to navigate to the About page. However, this link is not working causing a broken navigation.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the home page.  Clicking on the link to the About page will not correctly route to the About page.

## Solution

The issue has been resolved by confirming the correct file path in the `Link` component and ensuring no issues in the page rendering itself.