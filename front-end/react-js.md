#### Differentiate between Virtual DOM and Real DOM.
> Difference
  - Virual DOM
    - Changes can be made easily.
    - Minimal memory wastage.
    - JSX element is updated if the element exists.
    - Cannot update HTML directly.
    - Faster updates.
  - Real DOM
    - Changes can be expensive.
    - High demand for memory and more wastage.
    - Create a new DOM everytime an element gets updated.
    - Able to directly manipulate html.
    - Slow updates.

#### What is React?
> React
  - React is a widely used JavaScript library that was launched in 2011 by the developers of Facebook. It is primarily used as frontend development.
  - React uses component-based approach which ensures to help users to build compenents that process high reusability.
  - React is well for developing and desining complex mobile user interfaces and web applications.

#### What is the meaning of Virtual DOM?
> Virtual DOM
  - Virtual DOM is a simple JavaScript object that is the exact copy of the corresponding real DOM.
  - It can be cosidered as node tree that cosists of elements, their attributes and other properties.
  - Using the render function in React, it creates a node tree and updates it based on the changes that occur the data model.
  - These changes are usually triggered by the users or the actions caused by the system.

#### What are the some of the important features of React?
> Important feature
  - React makes use of single directional data flow model.
  - It deals with complete server-side data processing and handling.
  - React uses virtual DOM that has many advantages of its own.

#### What is the meaning of JSX?
> JSX
  - JSX is the abbreviation of JavaScript XML. It is a file that is used in React to bring out the essence of JavaScript in React and use for its advantages.
  - It even includes bringing out HTML and the easy syntac of JavaScript. This ensures HTML file will have high readabilty with higher performance.
  - Example :
    -           render(){
    -                      return(
    -                        <div>
    -                         <h1>Hi, I am Tufahel</h1>
    -                       </div>
    -                       );  
    -                     }

#### Can browsers read a JSX file?
> JSX and Browser
  - No, a browser can't read JSX file directly.
  - Browser can only read the objects given by JavaScript.
  - Now, to make a browser read the JSX file, it needs to be transformed to a JavaScript object using JSX transformers. Only then it can be fed into the browser for further use in the pipeline

#### Why is React widely used today / advantages?
> React provides users with ample number of advantages. Some of them are:
  - With react, UI testing becomes very easy.
  - React can integrate with Angular and other framework easily.
  - The high readability index esures easy understanding.
  - React can be used for both client-side and server-side requirements.
  - It boosts application performance and overall efficiency.

#### Are there any disadvantages to using React / limitations?
> Some limitations are:
  - Writing code is complex as it uses JSX and inline template formatting.
  - Beginners might find it tough to cope with its sytaxes and methods.
  - The library consists a huge repository of information, which might be overwhelming.
  - React is simple library not a complete framework hence calls for dependencies.