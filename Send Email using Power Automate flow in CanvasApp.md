- Created a canvas in powerapps maker portal and connnected with a datasource. Here, an excel file data has been used.
- After designing the app with views and forms, added a functionality to send email using power automate flow.
- Here, a button has been added on the screen and onclick of the button, an email will be sent to customer.

![canvasapp](https://github.com/user-attachments/assets/dfa63ee7-1876-4235-8688-1e21b6be7665)

- In the designer page, click on power automate icon on left menu bar and click create a new flow. This will redirect to a new power automate window.

![image](https://github.com/user-attachments/assets/cbb56520-b277-414f-8529-f4b6e45f911d)

- In the trigger, add all the inputs that will be received from the canvas app fields. In this case, Name, Email, invoice.

![image](https://github.com/user-attachments/assets/78d2e9ba-b7ec-48fc-bad2-90fd0a4f960c)

- Add the consequent steps for composing each field outputs from trigger and initializing them.

![image](https://github.com/user-attachments/assets/3e8b6403-0524-42b3-b8ca-760b1d2f0ac4)

- In the final step add an email connector to send email based on the initialized variables values.

![image](https://github.com/user-attachments/assets/6e7df3e8-81f1-4a43-93ec-c373e1fce303)

- Select the button on canvas app editor and change the property to OnSelect and write the power fx formula based on the textboxes' name.

![image](https://github.com/user-attachments/assets/2b9169f6-200e-4d63-90fb-ffedea051bed)

- And test by prewing the canvas app and clicking the button.




