# React Router v6 Catch-All Route Issue

This repository demonstrates a problem with the catch-all route ('*') in React Router v6.  The expectation is that when navigating to a non-existent route, the catch-all route should render. However, in this case, it does not behave as expected, instead showing a blank screen or other unexpected behavior.

## Setup

1. Clone the repository
2. Run `npm install`
3. Run `npm start`

Navigate to a non-existent path, such as '/invalid-route'.  Observe that the catch-all route does not render properly.

## Solution

The solution involves verifying the proper structure and setup of the Routes component, handling potential nesting issues and checking for conflicts with other routes.