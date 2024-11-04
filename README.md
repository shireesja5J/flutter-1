Creating a custom widget in Flutter can help you encapsulate functionality and styling, making your code cleaner and more reusable. Below is an example of how to create a custom button widget with specific styling and behavior.

Custom Button Widget
Let's create a custom button widget called CustomButton. This button will have rounded corners, a gradient background, and a shadow effect.
Steps to Create a Custom Button Widget
Create a new Dart file: Name it custom_button.dart.

Define the custom button widget:

Create a CustomButton class extending StatelessWidget.
Add parameters for label, onPressed callback, and gradient colors.
Build the widget using Container with GestureDetector.
Open main.dart: Import the custom button file.

Use the custom button:

Replace the body of your main app widget with an instance of CustomButton.
Pass the button label and onPressed logic.
Run the app: Use the command flutter run to see your custom button in action.
