*********************
# ReactDocumentation
*******************
# Props
## Props Definition:-
  * “Props” is a special keyword in React, which stands for properties and is being used for **passing data from one component to another**. But the important part here is that data with props are being passed in a **uni-directional flow**. (one way from parent to child) 

  * Further more, **props data is read-only**, which means that data coming from the parent should not be changed by child components. 
  * It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. 
  * It is similar to function arguments. 
  * Props are **immutable** so we **cannot modify the props from inside the component**. Inside the components, we can add attributes called props. These attributes are available in the component as this.props and can be used to render dynamic data in our render method. 
  * **this.props.property name** => Passing parameters from one component to another component
 ## Using Props in React
 * I will be explaining how to use Props step by step.
  # Firstly, define an attribute and its value(data)
  # Then pass it to child component(s) by using Props
  #Finally, render the Props Data

