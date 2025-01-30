# React VS Code Snippets

This repository contains a collection of useful **VS Code snippets** for React development. These snippets are designed to boost your productivity by providing quick templates for commonly used React components and patterns.

## 📌 Features
- Predefined React snippets for faster development
- Includes functional components, hooks, and common patterns
- Easy integration into **Visual Studio Code**

## 🚀 Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the **snippets** folder in VS Code:
   - Open VS Code
   - Go to **File > Preferences > User Snippets**
   - Select `javascript.json` or `typescript.json` (based on your preference)
3. Copy and paste the snippets from this repository into the selected file.

## 🔥 Usage
- Type the snippet shortcut in your VS Code editor
- Press `Tab` or `Enter` to expand the snippet

## 📂 Snippet Examples
| Shortcut | Description |
|----------|------------|
| `fcc` | Creates an arrow component with CSS |
| `fcs` | Creates a functional component with Sass |
| `acs` | Creates an arrow component with Sass |
| `comp` | Creates a simple component |
| `compt` | Creates a component with a Tailwind classname |

### Example Usage
```jsx
// Using the 'fcc' snippet
import './Example.css';

const Example = () => {
  return (
    <div className='example'>Example</div>
  );
};

export default Example;
```

## 🤝 Contributing
Feel free to submit pull requests with new snippets or improvements!

## 📜 License
This project is licensed under the MIT License.

---
Happy Coding! 🎉
