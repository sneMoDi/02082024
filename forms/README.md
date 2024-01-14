## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
- The action attribute in the form tag specifies the URL to which the form data should be sent when the user submits the form. In your provided code, the form data is sent to http://localhost:3000/login when the user clicks the submit button.
2. What is the purpose of the _method_ attribute in the _form_ tag?
- The method attribute in the form tag specifies the HTTP method to be used when sending form data. In your code, the method is set to GET, which means that the form data will be appended to the URL as query parameters when the form is submitted.
3. What is the purpose of the _name_ attribute in the _input_ tag?
- The name attribute in the input tag provides a name for the form control. When the form is submitted, the data entered in this input field will be sent with the specified name as part of the form data. This is useful for identifying the input values on the server side.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
- The type attribute in the input tag defines the type of input control. In your code, you have two input fields with types text and password. The text type is for regular text input, and the password type is for password input, where the entered characters are typically masked for security.
5. What is the purpose of the _label_ tag?
- The label tag in HTML is used to associate a label with a form control, providing a better user experience. It helps screen readers and other assistive technologies understand the purpose of the associated input. In your code, label elements are used to label the username and password input fields.
6. What is the purpose of the _required_ attribute?
- The required attribute is used in the input tag to specify that the associated input field must be filled out before submitting the form. If a user tries to submit the form without entering data in a required field, the browser will prevent the form submission and prompt the user to fill in the required information. This helps in ensuring that essential information is provided by the user.

