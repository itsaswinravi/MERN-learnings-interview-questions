## 1 What is Jsx?
- it is a syntax extension to JavaScript.It is used with react to describe what the user interface should look like. 
- By using this you can write HTML structures in the same file that contains javascript code.
- It helps in making the code easier to understand and debug as it avoid usage of JS DOM structures which are rather complex
![alt text](image.png)

## 2 what is virtual DOM?
- React keeps a lightweight representation of the Real DOM in the memory and that is known as the Virtual DOM.
Manipulating Real DOM is much slower than manipulating virtual DOM,because nothing gets drawn onscreen.

- When ths state of an object changes , virtual DOM changes every time the object changes and then    changes the DOM structure accordingly when the object changes again and then changes the DOM structure accordingly  when the object changes again![alt text](image-1.png)

## 3 What is the difference between Real DOM and Virtual DOM?
- Real DOM updates slow
- Can directly update HTML
- Creates a new DOM if element updates
- Too much of memory wastage
- No memory wastage
       ![alt text](image-2.png)
       ![alt text](image-3.png)
       ![alt text](image-4.png)

## 4 What are react extensions?
- React Developer Tools is a Chrome DevTools extension for the open-source React JavaScript library. It allows you to inspect the React component hierarchies in the Chrome Developer Tools.
 -React goes beyond simple UI and has many extensions for complete application arhitecture support.
 - It provides server side rendering, routing, and many other features.
 - It supports mobile app development using React Native.
 - Extended with flux and redux, it provides a complete application architecture.

 ## 5 What is an event in React? How do you  create one?
  - An event is an action that can be triggered by a User or any System event like pressing a key,a mouse click etc.![alt text](image-5.png)

  ## 6 What are  components in ReactJS?
  - Components are the building blocks of any React application and a single app usually consists of multiple components.
  - It splits the user Iterface into independent .reusable pieces that can be processed seperately.
  - A component is essentially a piece of the user interface.
  ## 7 What is a State in React?How donyou implement it?
  - A state is an object that stores the values of properties belonging to a component that could change over a period of time.
  - A state can be modified based on the user ation or network  changes.
  -Every time the state of an object changes ,React re-renders the component to the  browser.
  - The state object is initialized in the constructor.
  - the state object can store multiple properties.
  - this.setState() is used to change  the value of the state object.
  - setState () function performs a shallow merge between the new and the previous state.
## 8 What is a state in React?How do you implement it?
- A state holds the data that a component renders on the weppage
![alt text](image-6.png)
- This is how a state is accessed
## 9 What is a Highe  Order Component and pure component?
- A higher order component is a function that takes a component and returns a new component.
- It facilitates code reuse and logic sharing among different components.![alt text](image-8.png)
- A pure component is a component that does not re-renders if the state or props of the component has not changed.
- It is a class component that extends React.PureComponent instead of React.Component.
- It is used to improve the performance of the application.

## How do you implement React Routing?
-![alt text](image-9.png)


