# react-Documentation


### prerequisites
.Node(nodejs.org)
.knowledge on
   .html
   .css
   .js(ES6)
   
 ###  installation
 node -v
 npm -v
 npm install create-react-app -g
 create-react-app<project-name>
  npx create-react-app<project-name>
   
 ### components in React
   . class components
       .For representing a class component we have to use class keyword
       .render() for returning a statement
       .we have to acquire the properties from base class for implementing
       
    . Functional component
       .we have to use  function  | ()=>{}  fro implementing a functional component
       .can return a statement directly
       .High performance than class component
       
###  styling  components
     javascript
     //inline styles
     <h2 style={{backgroundColor:"green"}}>sample content</h2>
     
     //style component using javascript object
     var style={
     backgroundColor:"red",
     color:"green"
     
     }
     
     
###  composition
  The process of combining multiple components together
  
### React fragments
we have to use react fragment for avoiding number of division
javascript
   <React fragment>
   <Header />
   <h2>sample heading </h2>
   
    </React fragment>
    
    we have to use Empty tags also(<> </>)....
     
