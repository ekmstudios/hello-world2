# Working with React

## Create a Simple React App

1. Open your terminal and navigate to where you would like to create a new project.
2. Enter the following in the terminal (Starting with a basic 'Create React App' is a good way to get started wihen learing React.
```
npx create-react-app my-app
```
3. Once the 'create-react-app' is installced, change directories into the my-app directory you created in the previous step.
``` 
cd my-app
```
4. Then run `npm start` to display a development version of the site in your browser.

Note: The following combines the 3 termainal commands from the previous three steps.
```
npx create-react-app my-app
cd my-app
npm start
```



## Modify a Simple React App

Note: I am using Visual Studio Code for edting my React project files but feel free to use any code editor you like.

1. Open the project files in your code editor. 
2. Navigate to the **src** folder and open the **index.js** file.
3. Create the following constants above the line of code that starts with `ReactDOM.render...`:
```
const firstName = 'Errol';
const lastName = 'Mayer';
```
4. Then add the following H1 tag inside the `ReactDOM.render...` tag
```
<h1>Hello, {firstName} {lastName}</h1>
```
5. Your code should now look like this:
```
ReactDOM.render(
  <React.StrictMode>
    <h1>Hello, {firstName} {lastName}</h1>
    <App />
  </React.StrictMode>,
  document.getElementById('root')
);
```
6. Save the file and the page in the browser should automatically be updated.




