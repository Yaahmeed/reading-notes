# Foundations  

## Why these topics matter as it relates to this this module  

- HTML forms and JS Events are important in order to get data from a user, and to make our page more dynamic.  

### HTML Forms  

1. HTML forms are important for web development because they allow users to eter data for processing and storage, or used to immediately update the interface in some way.  
2. Keep it simple and focused. Only ask for the data you need.  
   User interface matters.  
3. 5 form elements are:  
    - `<form>` - the form itself (parent tag)  
    - `<fieldset>` - tag to begin the field where information will go, or section the form  
    - `<legend>` - where you can ask for information  
    - `<input>` - in input field for the user  
    - `<label>` - to label the input field  

### JS Events  

1. An event in JS is cause and effect. Something happens on the webpage (typically user input) and the code reacts. ie: The user presses a "menu" button, the page changes to display a menu.  
2. When using `addEventListener()` you need to provide the NAME of the event and a FUNCTION to handle the event.  
3. The event object is a parameter specified with a name such as `event`, `evt`, or `e`, which, when called, is automatically passed to the event handlers to provide extra features and information. This way we can target a specific element.  
4. In capturing, the browser checks so see if the element's outer most ancestor has a click event hanlder registeres on it for the capturing pase, and runs it if so.  
Then it moves on the the next element inside the html and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was clicked.  
Bubbling is the exact oppposite. The browser checks to see if the direct parent of the clicked element has a click event handler registered on it, and runs it if so.  
Then it moves on to the next immediate ancestor element and does the same thing, and then the next one, and so on until it reaches the html element. (Resource: Mdn WebDocs)  
Basically, "capturing" works from the outside of your HTML document in, and "bubbling" works from the inside of your HTML document out.

## Things I want to know more about  

- Storing data input in an HTML form.
