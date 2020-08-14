# -Javascripts Tutorial Guide

> Click :star:if you like the project. Pull Request are highly appreciated. Follow me [@mcljs15](https://twitter.com/mcljs15).

---

<div align="center">
    <p>
        <a href="https://michael-chacon.netlify.app/">
            <b>Do you want to learn JavaScript?</b>
            <br> Guide for beginners.
            <br>
            <div>
                <img src="https://danielrodriguez.info/wp-content/uploads/2015/12/habilidades-desarrollador-web.jpg" width="260" alt="Guide">
            </div>
        </a>
        <sub><i>Proudly supporting the beginner's guide to Javascripts</i></sub>
    </p>
</div>

---

### Table of Contents

| No. | Questions |
| --- | --------- |
|   | **Core Javascript** |
|1  | [What is JavaScript?](#what-is-javascript) |
|2  | [ECMAScript](#ecmascript) |
|3  | [Characteristics and Grammar](#characteristics-and-grammar) |
|4  | [Variables: var y let](#variables-var-y-let) |
|5  | [Arrow Function](#arrow-function) |
|6  | [When to use a Class Component over a Function Component?](#when-to-use-a-class-component-over-a-function-component) |
|7  | [What are Pure Components?](#what-are-pure-components) |
|8  | [What is state in React?](#what-is-state-in-react) |
|9  | [What are props in React?](#what-are-props-in-react) |
|10 | [What is the difference between state and props?](#what-is-the-difference-between-state-and-props) |
|11 | [Why should we not update the state directly?](#why-should-we-not-update-the-state-directly) |
|12 | [What is the purpose of callback function as an argument of setState()?](#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)
|13 | [What is the difference between HTML and React event handling?](#what-is-the-difference-between-html-and-react-event-handling) |
|14 | [How to bind methods or event handlers in JSX callbacks?](#how-to-bind-methods-or-event-handlers-in-jsx-callbacks) |
|15 | [How to pass a parameter to an event handler or callback?](#how-to-pass-a-parameter-to-an-event-handler-or-callback) |
|16 | [What are synthetic events in React?](#what-are-synthetic-events-in-react) |
|17 | [What are inline conditional expressions?](#what-are-inline-conditional-expressions) |
|18 | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements) |
|19 | [What is the use of refs?](#what-is-the-use-of-refs) |
|20 | [How to create refs?](#how-to-create-refs)

## Core JavaScript


    
1. ### What is JavaScript?
    
    JavaScript is a programming language that makes websites come to life. This is in contrast to HTML (which specifies content) and CSS (which specifies layout) and, unlike PHP, runs on visitor devices and not on the server. It was created by Brendan Eich in 1995, the folks at Netscape Navigator ask Brendan Eich to make a technology that implements dynamic things like creating forms, reacting to buttons with HTML.



   **[⬆ Back to Top](#table-of-contents)**
    
2. ### EcmaScript

| Edition | Published | Changes |
| ------- | --------- | ------- |
|1  | June 1997 | First edition | 
|2  | June 1998 | Editorial changes to keep the specification fully aligned with ISO/IEC 16262 international standard | 
|3  | December 1999 | Added regular expressions, better string handling, new control statements, try/catch exception handling, tighter definition of errors, formatting for numeric output and other enhancements |
|4  | Abandoned (last draft 30 June 2003) | Fourth Edition was abandoned, due to political differences concerning language complexity. Many features proposed for the Fourth Edition have been completely dropped; some were incorporated into the sixth edition.	 |
|5  | December 2009 | Adds **"strict mode,"** a subset intended to provide more thorough error checking and avoid error-prone constructs. Clarifies many ambiguities in the 3rd edition specification, and accommodates behaviour of real-world implementations that differed consistently from that specification. Adds some new features, such as getters and setters, library support for JSON, and more complete reflection on object properties. |
|6  | June 2015 | See [6th Edition – ECMAScript 2015](https://en.wikipedia.org/wiki/ECMAScript#ES2015), |
|7  | June 2016 | See [7th Edition – ECMAScript 2016](https://en.wikipedia.org/wiki/ECMAScript#ES2016), |
|8  | June 2017 | See [8th Edition – ECMAScript 2017](https://en.wikipedia.org/wiki/ECMAScript#ES2017), |
|9  | June 2018 | See [9th Edition – ECMAScript 2018](https://en.wikipedia.org/wiki/ECMAScript#ES2018), |
|10  | June 2019 | See [10th Edition – ECMAScript 2019](https://en.wikipedia.org/wiki/ECMAScript#ES2019), |
|11  | June 2020 | See [11th Edition – ECMAScript 2020](https://en.wikipedia.org/wiki/ECMAScript#ES2018), |
|ESNext  |  | ~ and so on...|


   **[⬆ Back to Top](#table-of-contents)**
    
3. ###   Characteristics and Grammar

   Javascripts is a superior programming language, a feature is the only language capable of **ISOMORPHISM** to make an application with a single language from start to finish, capable of running in all 3 layers of an application.
   
   1. Fronted(JavaScript).
   2. Backend(Node.js).
   3. Data Persistence(MongoDB,Couch DB, Firebase,etc).

    **With Javascript you can:**
    
    - Web Design and Development.
    - Videogame.
    - 3D Experiences, Augmented Reality, Virtual Reality.
    - Control hardware (Drones, robots, appliances).
    - Hybrid and mobile applications.
    - Machine learning.
    - etc.
    
     **Characteristics**
     
     - High Level Language
     - Interpreted
     - Dynamic
     - Weakly Typed
     - Multi paradigm
     - Sensitive to UPPERCASE and lower case
     - You do not need the semicolons at the end of each line
     
     **Code writing**
     
     **The identifiers** is the name you give to a variable, function, class. etc should start with:
     - A letter o
     - A dollar sign $ o
     - An underscore _
     - Never with numbers or special characters
     
     
     Use **snake_case** in:
     
     - Archive:
      ```javascript
      my_javascript_file.js
    ```
     Use **UPPER_CASE** in:
     - Constant
     ```javascript
      const ONE_CONSTANT = 'I am a constant',
       PI = 3.141592653589793
    ```
     Use **UpperCamelCase** in:
     - Classes:
     
     ```javascript
     class ToBeHuman {
        constructor (name,gender) {
            this.name = name
            this.gender = gender
           }
        MyNameIs ()  {
           return `My name is ${this.name}`
           }
         }
      
    ```
    Use **lowerCamelCase** in:
    - Objects:
         
     ```javascript
     const oneObject = {
       name: 'Michael',
       email: 'mcljs15@gmail.com'
      }
    ```
    - Primitive:
           
     ```javascript
     let oneString = 'Hello World',
        oneNumber = 19,
        oneBoolean = true
    ```
    - Functions:
           
     ```javascript
      function helloWorld (name) {
       alert(`Hello world ${name}`)
     }
     helloWorld('Michael')
    ```
    - Instances:
            
     ```javascript
      const ajax = new XMLHttpRequest(),
      maik = new ToBeHuman('Michael','Man')
    ```
    
   **Reserved words**
   
      ```javascript
      A: abstract
      B: boolean, break, byte
      C: case, catch, char, class, const, continue
      D: debugger, default, delete, do, double
      E: else, enum, export, extends
      F: false, final, finally, float, for, function
      G: goto
      I: if, implements, import, in, instanceof, init, interface
      L: long
      N: native, new, null
      P: package, private, protected, public
      R: return
      S: short, static, super, switch, synchronized
      T: this, throw, throws, transient, true, try, typeof
      V: var, volatile, void
      W: while, with
    ```
   **Code ordering (recommendation)**
    
    1. IMPORT OF MODULES.
    2. DECLARATION OF VARIABLES.
    3. DECLARATION OF FUNCTIONS.
    4. CODE EXECUTION.

    **Data types in JavaScript**
    
    1.**Primitive:** The value is accessed directly.
    
    - string
    - number
    - boolean
    - null
    - undefined
    - NaN
    
    2.**Compounds:** The value reference is accessed.
    
    - object = {}
    - array = []
    - function (){}
    - Class {}
    - etc.
     
     
     

     

    

   **[⬆ Back to Top](#table-of-contents)**
    
4. ### Variables: var y let

    As var is declared in JavaScript:
    
      ```javascript
      <script>
    var hello  = "Hello World";
    console.log(hello)
      </script>
    ```
    As let is declared in JavaScript:
     ```javascript
      <script>
    let hello  = "Hello World";
    console.log(hello)
      </script>
    ```
    
   Important: The <script> </script> format is implemented in an html, we can also compile our code in the console of a web browser (Google Chrome, Mozilla Firefox, Brave, etc) also it indicates the line that I am executing if it is in HTML our script.
    
    Since ECMAScript6 (2015) we have block scope we have to generate it with let, if you declare a variable with the word var make global scope, if you do it with let scope it happens in the block scope ** Do not use more var, that is currently bad practice **
  
 
  
   


   **[⬆ Back to Top](#table-of-contents)**
    
5. ### Arrow Function

    Arrow Function: Con la misma quitamos la palabra function en nuestro codigo.

      ```javascript
        const saludar = nombre => console.log(`Hola ${nombre}`);
        saludar(“Michael”)
        print(Hola Michael)
       }
      ```

    Cuando recibimos mas de dos parametros tenemos que ubicar los parentesis () y no implicita*

        
          ```javascript
       const sumar = (a,b) => a + b;
        console.log(suma(9,9));

          print(18)
          ```
    Si la funcion tiene una sola linea de codigo podemos omitir las llaves, cuando una expresion en flecha tiene varias lineas de codigo hay que respetar la funcion.*/
        
         ```javascript
        const numeros =[1,2,3,4,5];

        numeros.forEach((el, index) => console.log(`${el} esta en la posicion       ${index}`));
        
        ```
     
        
      
   Arrow Function Tienen la capacidad de capturar el objeto donde se encuentra, por eso hay que tener mucho cuidado al declarar arrow function al declarar objetos literarios.
   
   POO (Programacion Orientada a Objeto)
    Clases - Modelos a seguir
    Objetos: Es una instancia de una clase
    - Atributos: Es una carecteristica o propiedad del objeto (son variables dentro de un objeto)
    Metodos - son acciones que un objeto puede realizar
 
 
 **[⬆ Back to Top](#table-of-contents)**
    
6. ### When to use a Class Component over a Function Component?

    If the component needs *state or lifecycle methods* then use class component otherwise use function component.
    *However, from React 16.8 with the addition of Hooks, you could use state , lifecycle  methods and other features that were only available in class component right in your function component.*


   **[⬆ Back to Top](#table-of-contents)**
    
7. ### What are Pure Components?

    *`React.PureComponent`* is exactly the same as *`React.Component`* except that it handles the `shouldComponentUpdate()` method for you. When props or state changes, *PureComponent* will do a shallow comparison on both props and state. *Component* on the other hand won't compare current props and state to next out of the box. Thus, the component will re-render by default whenever `shouldComponentUpdate` is called.


   **[⬆ Back to Top](#table-of-contents)**
    
8. ### What is state in React?

    *State* of a component is an object that holds some information that may change over the lifetime of the component. We should always try to make our state as simple as possible and minimize the number of stateful components.

    Let's create an user component with message state,


    ```jsx harmony
    class User extends React.Component {
      constructor(props) {
        super(props)

        this.state = {
          message: 'Welcome to React world'
        }
      }

      render() {
        return (
          <div>
            <h1>{this.state.message}</h1>
          </div>
        )
      }
    }
    ```

    ![state](images/state.jpg)

    State is similar to props, but it is private and fully controlled by the component. i.e, It is not accessible to any component other than the one that owns and sets it.


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### What are props in React?

    *Props* are inputs to components. They are single values or objects containing a set of values that are passed to components on creation using a naming convention similar to HTML-tag attributes. They are data passed down from a parent component to a child component.

    The primary purpose of props in React is to provide following component functionality:

    1. Pass custom data to your component.
    2. Trigger state changes.
    3. Use via `this.props.reactProp` inside component's `render()` method.

    For example, let us create an element with `reactProp` property:

    ```jsx harmony
    <Element reactProp={'1'} />
    ```

    This `reactProp` (or whatever you came up with) name then becomes a property attached to React's native props object which originally already exists on all components created using React library.

    ```
    props.reactProp
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What is the difference between state and props?

    Both *props* and *state* are plain JavaScript objects. While both of them hold information that influences the output of render, they are different in their functionality with respect to component. Props get passed to the component similar to function parameters whereas state is managed within the component similar to variables declared within a function.


   **[⬆ Back to Top](#table-of-contents)**
    
11. ### Why should we not update the state directly?

    If you try to update state directly then it won't re-render the component.

    ```javascript
    //Wrong
    this.state.message = 'Hello world'
    ```

    Instead use `setState()` method. It schedules an update to a component's state object. When state changes, the component responds by re-rendering.

    ```javascript
    //Correct
    this.setState({ message: 'Hello World' })
    ```

    **Note:** You can directly assign to the state object either in *constructor* or using latest javascript's class field declaration syntax.


   **[⬆ Back to Top](#table-of-contents)**
