---
title: "Basic Understanding of React"
description: "The setup"
date: "2019-01-30T18:26:37.458Z"
categories: []
published: true
canonical_link: https://medium.com/@ak8393267/basic-understanding-of-react-446945305471
redirect_from:
  - /basic-understanding-of-react-446945305471
---

![source:-[https://cdn-images-1.medium.com/max/1000/1\*HSisLuifMO6KbLfPOKtLow.jpeg](https://cdn-images-1.medium.com/max/1000/1*HSisLuifMO6KbLfPOKtLow.jpeg)](./asset-1.jpeg)

### **The setup**

Now getting started with React we should make simple setup of HTML file in which we import react and react-Dom libraries. e.g

```
<html>
<head>
<script src="https://unpkg.com/react@15/dist/react.min.js"> </script><script src="https://unpkg.com/react-dom@15/dist/react-dom.min.js">
</script>
<script src="https://unpkg.com/babel-standalone@6.15.0/babel.min.js"></script>
</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
    
    /* 
    ADD REACT CODE HERE 
    */
    
    </script>
</body>
</html>
```

### Component

A component is the basic building block the React. There are two types of component in React one is the Presentational Component and another one is container Component. A presentational component is a functional component and represented by the function it takes the prop. functional component is a stateless component. The container component is a stateful component because it contains other components.

Example of functional Component:-

```
const greeting = () => {
 return {
  <h1>Hi, I’m a smart component!</h1>;
 }
}
export default greeting
```

Example of class component:-

```
import greeting from './greeting'

class Greeting extends React.Component {
   constructor(props) {
   super(props)
   }
    this.state= {
    info:[]
   }
 render(){
    return (
       <div>
         <greeting />
       </div>
    ) 
  }
}
```

#### Props

In the React props is used for sharing the information of one component to another component. The props are Read-only properties. A component is passed to props as input to one component which can access the property of props but cannot modify the content of the props.

#### State

The state is another way of storing the data React in the component state. To initialize the state we simply set state as an object in the constructor() or directly in the class.
