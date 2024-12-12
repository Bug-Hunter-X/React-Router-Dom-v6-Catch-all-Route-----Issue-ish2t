# React Router Dom v6 Catch-all Route '*' Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router Dom v6.  The catch-all route is intended to handle any unmatched routes, but in certain scenarios, it may unexpectedly override other defined routes.

The issue is that the catch-all route is too broad and intercepts all routes. This example showcases how a malformed catch-all route overrides the other routes and always renders the NotFound component.