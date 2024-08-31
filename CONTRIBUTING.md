# Contributing to Simple Web Components Library

Thank you for your interest in contributing to the Simple Web Components Library! We welcome all kinds of contributions, whether it's adding new components, improving existing ones, or enhancing documentation. As stated in the [readme](readme.md) this project is mainly for new developers that want to get hand on experience with open source, but we of course doesn't stop anyone no matter how experienced they are to contribute! Please read our [Code of Conduct](CODE-OF-CONDUCT.md) before contributing.

Contributions can include new components, improvements to existing ones, or enhancements to documentation.

## How to Contribute

### 1. Fork and Clone the Repository

1. Fork the repository to your GitHub account by clicking the "Fork" button at the top right of the repo page.
2. Clone the forked repository to your local machine:

    ```bash
    git clone https://github.com/your-username/web-components-library.git
    ```

3. Navigate into the project directory:

    ```bash
    cd web-components-library
    ```

### 2. Create a New Branch

Before making any changes, create a new branch for your work:

```bash
git checkout -b your-branch-name
```

Choose a descriptive branch name that reflects the work you're doing, such as `add-button-component` or `fix-modal-bug`.

### 3. Add a New Component

1. Navigate to the /components folder.
2. Check for already existing component type folder. For ex if you are adding a button, check for a Buttons folder. If it exists then navigate to that folder and in other case create a new folder.
```bash
mkdir /components/Buttons
```
3. Create a new folder with the name of your component (e.g., exampleButton).
4. Inside your component folder, create the following files (use your own component name):
- `exampleButton.html`: Contains the HTML structure.
- `exampleButton.css`: Contains the styling for the component.
- `exampleButton.js`: Contains the JavaScript functionality.

Example structure:
```css
/components/Buttons/exampleButton
├── exampleButton.html
├── exampleButton.css
└── exampleButton.js
```

4. Follow these guidelines:
- HTML: Use semantic HTML and ensure the component is accessible (e.g., use aria attributes when necessary).
- CSS: Use BEM (Block Element Modifier) methodology for naming classes, and ensure the styles are responsive.
- JavaScript: Write clean, modular, and well-documented code. Ensure your component works across different browsers.

### 4. Test Your Component

1. Include your new component in the index.html file for testing and demonstration.
2. Open index.html in a web browser to verify that your component works as expected.

### 5. Commit and Push Your Changes

1. Stage your changes:

```bash
git add .
```

2. Commit your changes with a descriptive message:
```bash
git commit -m "Add Button component"
```

3. Push your branch to your forked repository:
```bash
git push origin your-branch-name
```

### 6. Create a Pull Request

1. Go to the original repository on GitHub.

2. You’ll see a prompt to create a pull request for your newly pushed branch. Click the "Compare & pull request" button.

3. Provide a clear and descriptive title for your pull request.

4. In the description, explain what your component does, and mention any relevant issues.

5. Submit the pull request.

### 7. Address Feedback

A project maintainer (me) will review your pull request. You might be asked to make changes or improvements. Please address the feedback and push any updates to your branch. A big part of open source is to communicate via github (or the likes of). 

### Coding Standards
- Indentation: Use 2 spaces for indentation.
- Naming: Use descriptive names for files and classes.
- Comments: Comment your code where necessary, especially for complex logic.
- Formatting: Ensure consistent formatting. You can use tools like Prettier or ESLint to help maintain code quality.

### Issues and Suggestions
If you encounter any problems or have suggestions for improvements, feel free to open an issue in the GitHub repository. Please search for existing issues before creating a new one to avoid duplicates.

### License
By contributing to this project, you agree that your contributions will be licensed under the MIT License.