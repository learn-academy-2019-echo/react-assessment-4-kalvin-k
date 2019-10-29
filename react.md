# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications (true/false)
- true
- React will only render on the server using Node.js (true/false)
- false
- React is a full stack framework for modern web applications (true/false)
- false
- React is a flexible library that plays the role of V in an MVC framework (true/false)
- false 
- You should always update a component's state directly using this.state (true/false)
- false 
- React is made up of encapsulated components that manage their own state (true/false)
- true 
- React components render HTML (true/false)
- true 

1b. Add an interesting TRUE fact about React to the list.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: smart components are ones that hold state in them, dumb components are ones that dont but can be passed down state from the smart components 

  Researched answer: Dumb components are also called ‘presentational’ components because their only responsibility is to present something to the DOM.
                     Dumb components are often filled with a bunch of javascript functions that can do things with the data they are given but can never display
                     anything unless they are passed props. 
                     
                     Smart componets are used more to manage the way that an app will work and hold much more of logic. The smart componets are often passing down
                     state to their child components as props so that they can alter the way information is displayed. The main difference between the two is 
                     on what kind of responsibility that each one has. Dumb components are mostly for either just displaying or just holding functions to use in other
                     places, while the smart componets have the responsibility of changing and displaying the information.. 



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: yarn add installs to update your packages so that others can run you code using yarn 

  Researched answer:  You use yarn add to install into your project.This will also update your package.
  json and your yarn.lock so that other developers working on the project will get the same dependencies as you when they run yarn or yarn install.



4. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: component state is set within the component itself, it allows you to display and change different types of data. Props can be either state passed
               down to dumb components or functions created in different files. the difference is that stat is created in the component and props are passed down 

  Researched answer: In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly 
                     initialized and managed by the component.



5. How would you explain state to a friend who doesn't know code?

  Your answer: state is a way to store the different types of data and behavior that a componenet will have. This is the main way that a react component have functionality
               as well as the main way that data and behavior are displayed to the user. 
