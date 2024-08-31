# Example Button Component

## Description

The Example Modal is a simple modal component that includes a trigger button that when pressed opens a modal overlay over the main content. It have a closing mechanism of an X that closes the modal. 
The content of the modal can be modified to fit your own purpuses aswell as the styling an logic. 
Its main purpose in this library is to showcase the structure of the library. 

## Usage Instructions

To use this component:
1. You either need to include the trigger button, or if you want to use your own button give your button the id of "openModal" to let the js script find and create a node. 
```html
<button id="openModal">Open Modal</button>
```

2. **Include the HTML**:
    ```html    
    <div id="myModal" class="modal">      
      <div class="modal-content">
        <span class="close">&times;</span>
        <p>This is a simple modal!</p>    
      </div>
    </div>
    ```

2. **Include the CSS**:
    Link the CSS file in your HTML:
    ```html
    <link rel="stylesheet" href="./components/Modals/exampleModals/exampleModals.css">
    ```
    Alternatively, you can copy the CSS and paste it into your own stylesheet.

3. **Include the JavaScript**:
    Add the JavaScript file in your HTML:
    ```html
    <script src="./components/Modals/exampleModals/exampleModals.js"></script>
    ```

## Example Integration

Here’s a complete example integrating the Example Modal component:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Components Library</title>
    <link rel="stylesheet" href="./components/Modals/exampleModals/exampleModals.css">
</head>
<body>
    <h1>Simple Web Components Library</h1>
   <button id="openModal">Open Modal</button>

    <div id="myModal" class="modal">
    
      <div class="modal-content">
        <span class="close">&times;</span>
        <p>This is a simple modal!</p>    
      </div>
    </div>
    <script src="./components/Modals/exampleModals/exampleModals.js"></script>
</body>
</html>