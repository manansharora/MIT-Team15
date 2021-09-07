# MIT-Team15
This application uses ReactJS (bootstrapped using create-react-app) as the frontend and ExpressJS as the backend. While we were not able to implement the required specifications, we have included the following to describe the steps taken and issues in each:

1. Used a library (react-financial-charts). This library, while being updated recently, is severely undocumented, causing us considerable issues in the deployment of charts.
2. Since the above did not work, we used the react-stockcharts which was deprecated, and hence unusable
3. Following that, we tried using ChartJS. Here, we faced an error in a wrapper file: "Function components cannot have refs. Did you mean to use React.forwardRef()". This was unresolvable, despite extensive research.
4. Finally, we used recharts, where we once again faced several issues regarding compiling.

Run the following commands in both the frontend and backend folders to start the servers and access on localhost.
```
npm i
npm start
```
