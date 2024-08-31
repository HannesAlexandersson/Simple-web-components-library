### Documentation information

## Name of component
So you have added a component to the library? Awesome! Now its time to write the documentation. You have named the component when you created the files. Use that name here. 

## Description of component
Here you can describe the component, what its purpose is and details about it.

## Usage instructions
Here you can (if needed) describe how to use the component. If it requires some special actions before usage. 

### Example documentation

# Example Button Component

## Description

The Example Button is a simple button component with a blue background and white text. It includes CSS that scales the button down to 95% when clicked. A simple click handler is attached in the JS file that shows an alert saying "Button clicked!" when the button is clicked.

## Usage Instructions

To use this component:

1. **Include the HTML**:
    ```html
    <button class="example-button">Click Me</button>
    ```

2. **Include the CSS**:
    Link the CSS file in your HTML:
    ```html
    <link rel="stylesheet" href="./components/Buttons/exampleButton/exampleButton.css">
    ```
    Alternatively, you can copy the CSS and paste it into your own stylesheet.

3. **Include the JavaScript**:
    Add the JavaScript file in your HTML:
    ```html
    <script src="./components/Buttons/exampleButton/exampleButton.js"></script>
    ```

## Example Integration

Here’s a complete example integrating the Example Button component:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Components Library</title>
    <link rel="stylesheet" href="./components/Buttons/exampleButton/exampleButton.css">
</head>
<body>
    <h1>Simple Web Components Library</h1>
    <h2>Example Button Component</h2>
    <button class="example-button">Click Me</button>
    <script src="./components/Buttons/exampleButton/exampleButton.js"></script>
</body>
</html>