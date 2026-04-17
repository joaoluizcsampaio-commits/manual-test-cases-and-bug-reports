# Bug Report

## Title
Map does not update route after entering destination in "To" field on home screen

## Description
After entering a valid address in the "To" field, the map does not update to display the corresponding route. The expected system behavior is not met, preventing the visualization of the route.

## Preconditions
- Urban Routes application is running
- User is on the home screen
- Browser: Google Chrome
- Resolution: 1200x720
- Active server connection with valid URL

## Steps to Reproduce
1. Open the Urban Routes application
2. In the "To" field, enter: 1300 1st St
3. Wait for the map to update

## Expected Result
- The map should update automatically after entering the destination
- The route should be displayed
- Markers should appear correctly positioned on the map

## Actual Result
- The map does not update after entering the destination
- The route is not displayed
- Markers are not rendered
- The issue occurs consistently (100% of attempts)

## Severity
High

## Priority
High

## Evidence
![Map Bug](./images/map-bug.png)

## Jira Reference:
https://joaoluizcsampaio.atlassian.net/browse/KAN-15?atlOrigin=eyJpIjoiMzNjYjhhMDYwYjdjNGUzYzkwNzY3MDhhNmJjNTA5YjgiLCJwIjoiaiJ9
