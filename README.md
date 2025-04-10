# D3.js Dashboard

## About this project

This is a dashboard I built using D3.js and React for my assignment. It shows different types of charts that display sales data. You can filter the data by year using the dropdown.

## What I used

- React & Next.js for the UI
- D3.js for the charts
- Framer-motion for animations
- Tailwind CSS for styling
- shadcn/ui for some components
- ESLint, Prettier and Husky for code quality

## What I built

- Bar chart showing sales by category
- Line chart showing monthly sales
- Scatter plot comparing price vs rating
- Year filter to change the data
- Tooltips when you hover over data points

## Challenges I faced

Getting D3 to work with React was harder then I expected. D3 wants to control the DOM directly but React has it's virtual DOM, so I had to use refs to make them work together.

Making the charts responsive was also tricky. I had to recalculate dimensions when the window resizes and adjust the margins and spacing.

The animations were fun to implement but took some time to get right. I wanted smooth transitions when changing between years.

## What I'd add with more time

- More chart types
- More filter options
- Dark mode
- Tests

I learned alot about data visualization during this project and got better at using D3.js with React.
