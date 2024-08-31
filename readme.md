# Simple Web Components Library

This is an open-source collection of reusable web components built using HTML, CSS, and JavaScript. The goal is to provide a library of customizable components for developers to use in their projects and to encourage developers to contribute to open source. Contributors are welcome to submit their own components!

As a student at Yrgo's web-developer class we are tasked to make contributions to the open source scene. One way of doing this is to actually have an open source project of my own. So this project is specifically targeting developers that are new to open source. This is a project that they should feel absolute safe about creating issues and pull requests, since the main goal is not to create the best ever components but the act of contributing itself!

## Getting Started

1. Fork the repository and clone it locally.
2. Navigate to the `/components` folder, either find the component type your adding or if it doesnt exist yet, add your own component type folder.
3. Add your component folder to the component type folder, For example if you are adding a button component, add a folder in the Buttons folder and name it as descriptive you can to match your component.
4. Each component should have an `HTML`, `CSS`, and `JavaScript` file.
5. use the index.html file in the root to showcase the components if needed.

## Dependencies

Atm there are no dependencies attached to this project. So in other words there is no installation needed.

## Showcasing the components

If you want to showcase the components to get an idea of how they look and what they do you can run them locally. After you have forked and cloned the repo you can start an development server on you local machine in your prefered way. I'll provide one way of doing it: 

1. **Start a Server**: Run the following command in your CLI to start a local development server:
    ```bash
    php -S localhost:4000
    ```
2. **Open in Browser**: Navigate to the following URL in your browser:
    ```plaintext
    localhost:4000
    ```

3. **View the Components**: This will run the `index.html` file and display the components you have included there.

## Example

The `exampleButton` in the `Buttons` folder serves as a template to demonstrate the intended file structure. It shows basic styling and interaction and how to showcase the component in the `index.html` file.


Its located at 
```css
/components/Buttons/exampleButton
├── exampleButton.html
├── exampleButton.css
└── exampleButton.js
```
To use the component, include it in your html: 
```html
<button class="example-button">Click Me</button>
```

also you need to include the css, either by including the stylesheet: 
```html
<link rel="stylesheet" href="./components/Buttons/exampleButton/exampleButton.css">
```
or by simply copy the actual css and paste it into your own stylesheet. 

Dont forget to include the javascript: 
```html
<script src="./components/Buttons/exampleButton/exampleButton.js"></script>
```

## Folder Structure

The folder structure is based on types of components. Each component type consists of the different versions of the component. For example the Buttons component type might have several different versions of buttons. So it might look like: 

```css
/components/exampleButton1
├── exampleButton.html
├── exampleButton.css
└── exampleButton.js
/components/exampleButton2
├── exampleButton2.html
├── exampleButton2.css
└── exampleButton2.js
/components/exampleButton3
├── exampleButton3.html
├── exampleButton3.css
└── exampleButton3.js
```

## Documentation

### **Component-Specific Documentation**

For each component, you can include a README file or other documentation directly within the component’s folder to provide specific details about that component. This documentation can explain the component’s purpose, usage, and any specific instructions related to that component.

**Example Documentation in `/components/Buttons/exampleButton/README.md`:**

## How to Contribute

1. Check out the [CONTRIBUTING.md](CONTRIBUTING.md) for detailed instructions.
2. Look at the open issues and select one. Issues labeled "good first issue" is always good issues to start with if you are new to open source.

## License

This project is licensed under the MIT License.

#### IMPORTANT
It isn’t the quality, style, or even functionality that matters in this project. We are **NOT** aiming to build the best and coolest component library. What's important is that anybody should learn and gain confidence to start contributing to open source. Please keep in mind that I am also very much in a learning state. I have never started a component library nor opened up a repo for contributions before. There might be things that aren’t best practices or could be improved. If you find something that should be changed, please contribute by letting me know!
