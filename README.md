# Survey-Form
Build a Survey Form
Objective: Build an app that is functionally similar to https://survey-form.freecodecamp.rocks

User Stories:

You should have a page title in an h1 element with an id of title
You should have a short explanation in a p element with an id of description
You should have a form element with an id of survey-form
Inside the form element, you are required to enter your name in an input field that has an id of name and a type of text
Inside the form element, you are required to enter your email in an input field that has an id of email
If you enter an email that is not formatted correctly, you will see an HTML5 validation error
Inside the form, you can enter a number in an input field that has an id of number
The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error
For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label"
For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
Inside the form element, you should have a select dropdown element with an id of dropdown and at least two options to choose from
Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute
Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute
Inside the form element, you are presented with a textarea for additional comments
Inside the form element, you are presented with a button with id of submit to submit all the inputs
Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!

Note: Be sure to add <link rel="stylesheet" href="styles.css"> in your HTML to link your stylesheet and apply your CSS

Get Help
Tests
Passed:You should have an h1 element with an id of title.
Passed:Your #title should not be empty.
Passed:You should have a p element with an id of description.
Passed:Your #description should not be empty.
Passed:You should have a form element with an id of survey-form.
Passed:You should have an input element with an id of name.
Passed:Your #name should have a type of text.
Passed:Your #name should require input.
Passed:Your #name should be a descendant of #survey-form.
Passed:You should have an input element with an id of email.
Passed:Your #email should have a type of email.
Passed:Your #email should require input.
Passed:Your #email should be a descendant of #survey-form.
Passed:You should have an input element with an id of number.
Passed:Your #number should be a descendant of #survey-form.
Passed:Your #number should have a type of number.
Passed:Your #number should have a min attribute with a numeric value.
Passed:Your #number should have a max attribute with a numeric value.
Passed:You should have a label element with an id of name-label.
Passed:You should have a label element with an id of email-label.
Passed:You should have a label element with an id of number-label.
Passed:Your #name-label should contain text that describes the input.
Passed:Your #email-label should contain text that describes the input.
Passed:Your #number-label should contain text that describes the input.
Passed:Your #name-label should be a descendant of #survey-form.
Passed:Your #email-label should be a descendant of #survey-form.
Passed:Your #number-label should be a descendant of #survey-form.
Passed:Your #name should have a placeholder attribute and value.
Passed:Your #email should have a placeholder attribute and value.
Passed:Your #number should have a placeholder attribute and value.
Passed:You should have a select field with an id of dropdown.
Passed:Your #dropdown should have at least two selectable (not disabled) option elements.
Passed:Your #dropdown should be a descendant of #survey-form.
Passed:You should have at least two input elements with a type of radio (radio buttons).
Passed:You should have at least two radio buttons that are descendants of #survey-form.
Passed:All your radio buttons should have a value attribute and value.
Passed:All your radio buttons should have a name attribute and value.
Passed:Every radio button group should have at least 2 radio buttons.
Passed:You should have at least two input elements with a type of checkbox (checkboxes) that are descendants of #survey-form.
Passed:All your checkboxes inside #survey-form should have a value attribute and value.
Passed:You should have at least one textarea element that is a descendant of #survey-form.
Passed:You should have an input or button element with an id of submit.
Passed:Your #submit should have a type of submit.
Passed:Your #submit should be a descendant of #survey-form
