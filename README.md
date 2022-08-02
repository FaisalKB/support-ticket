# support-ticket
## A demonstration of HTML containers in the form of a popular web support tool.

Forms are an important component of many websites. From signing up for a new user account to creating new blog posts or even submitting support tickets, forms show up in many different ways on modern web pages. This project showcases the use of HTML forms via a support ticket template. By using intuitive forms, you can allow for the collection of valuable information. A few examples of specific forms used within this projct include:

### Text Fields:
Self explanatory, these containers take in short text form users. These are excellent fields for names and other custom text.

### Text Area Fields:
Text area fields present the user with a multi-line input field so that they can enter an unlimited number of characters; or in our case, a slightly larger number of characters than what may be suitable for a simple text field. These are best used for collecting a longer message, details and complex information.

### Placeholder text:
The text field and text area field can both use the placeholder attribute to briefly describe the information that is expected in the field.

### Drop-Down List:
A drop-down list, also called a select menu list, is a toggleable menu that allows the user to choose one value from a predefined list. It tends to be more user friendly than a list of radio buttons when there is a long list of items.

### Buttons (Submit and Reset):
Buttons are similar to links, but they are really important to have in forms. Whereas a link is used to navigate the user to a new page or resource, a button toggles something in the interface—which makes buttons perfect for submitting or resetting the data in a form.

**Submit**: Submit buttons send the data in the form to the backend program that collects the data.

**Reset**: Reset buttons clear all of the data that has been changed in the existing form elements.

### Patterns using Regex:
The pattern attribute is used to supply patterns that the user's input must match in order to be valid.For example, the pattern 
**"\d{3}[\-]\d{3}[\-]\d{4}"** will warn the user if they are not providing a correct 10-digit phone number in the xxx-xxx-xxxx format.
