<h1> Deployment Link : <href> afju-histogram.netlify.app </href> </h1>

Explanation of the code :
>>>we import necessary dependencies. We're using the react-chartjs-2 library to render a bar chart, along with the chart.js library for additional chart functionality. We also import React hooks such as useState, useRef, and useEffect to manage state and perform side effects. Finally, we import the Head component from Next.js for managing the page's head elements.
>>> the necessary modules from chart.js that we'll be using.
>>>  I have defined TypeScript types for the data points and labels used in the chart.
>>>I have defined the ChartData type, which represents the structure of the data needed for the chart. It consists of an array of labels and an array of datasets. Each dataset has a label, an array of data points, a background color array, and bar percentage values. We also initialize initialData as null or undefined for the chart's initial state.
>>>I have defined the App component, which represents our application. We use the useState hook to manage the state of data (the chart data) and loading (to track whether the data is being fetched). We also use the useRef hook to create a reference to the refresh button (buttonRef). Inside the useEffect hook, we focus on the button when the component mounts.
>>>The function handleSubmit is called when the button is clicked. It is an asynchronous function that fetches data from a specific URL (https://www.terriblytinytales.com/test.txt). The fetched text is split into words and stored in the words array. We initialize an empty frequency object to track the frequency of each word.
>>> 
