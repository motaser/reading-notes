# Forms

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

**How Forms Work**  
A user fills in a form and then presses a button to submit the information to the server. A form may have several form controls, each gathering different information. The server
needs to know which piece of inputted data corresponds with which form element.

**<form>**
Form controls live inside a <form> element. This element
should always carry the action attribute and will usually have a method and id attribute too.

**<input>**
The <input> element is used to create several different form
controls. The value of the type vattribute determines what kind of input they will be creating.

**<textarea>**
The <textarea> element is used to create a mutli-line
text input. Unlike other input elements this is not an empty
element. It should therefore have an opening and a closing tag.

**<select>**  
A drop down list box (also known as a select box) allows
users to select one option from a drop down list.

**<button>**  
The <button> element was introduced to allow users more
control over how their buttons appear, and to allow other
elements to appear inside the button.

**<label>**  
When introducing form controls, the code was kept simple by
indicating the purpose of each one in text next to it. However, each form control should have its own <label> element as this makes the form accessible to vision-impaired users.
 
* Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
<form> element.
* Information from a form is sent in name/value pairs.
* Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
* HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

# Lists, Tables & Formsr

**list-style-type**
The list-style-type property allows you to control the shape
or style of a bullet point (also known as a marker).
It can be used on rules that apply to the <ol>, <ul>, and <li> elements.

**list-style-image**
You can specify an image to act as a bullet point using the
list-style-image property. The value starts with the letters
url and is followed by a pair of parentheses. Inside the
parentheses, the path to the image is given inside double
quotes.

**list-style-position**

Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points.

* In addition to the CSS p XX roperties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
* List markers can be given different appearances
using the list-style-type and list-style image
properties.
* Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
* Forms are easier to use if the form controls are
vertically aligned using CSS.
* Forms benefit from styles that make them feel more
interactive.

# Events
When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.


* Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
* Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
* When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
* You can use event delegation to monitor for events
that happen on all of the children of an element.
* The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.