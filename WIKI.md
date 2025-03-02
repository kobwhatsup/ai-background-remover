# Project Summary

The AI T-shirt Background Removal project is an innovative web application designed to help users quickly and efficiently remove backgrounds from their T-shirt images. Utilizing advanced AI algorithms, this tool enables easy editing of product images for e-commerce platforms, social media posts, and other applications where background removal is essential. Users can upload their images, process them, and download the edited versions, thus simplifying the workflow in image editing and enhancing the visual appeal of their products.

---

# Project Module Description

## Functional Modules

1. **Image Uploading**: Users can upload their T-shirt images to the platform using a user-friendly interface.

2. **Background Removal**: The application utilizes a canvas-based algorithm to detect and remove the background from the image, making white or light-colored pixels transparent.

3. **Image Preview**: Users can view both the original and processed images side-by-side to compare results.

4. **Download Functionality**: After processing, users can download the edited images with the background removed.

5. **User Accounts**: The application supports user authentication and tracks usage quotas for image processing.

---

# Directory Tree

```bash
/data/chats/5qpco/workspace
+-- ai_tshirt_background_removal_class_diagram.mermaid
+-- ai_tshirt_background_removal_sequence_diagram.mermaid
+-- ai_tshirt_background_removal_system_design.md
+-- background_removal_feature_prd.md
+-- react_template
|   +-- README.md
|   +-- eslint.config.js
|   +-- index.html
|   +-- package.json
|   +-- postcss.config.js
|   +-- src
|   |   +-- App.jsx
|   |   +-- components
|   |   |   +-- BackgroundRemover.jsx
|   |   |   +-- ControlPanel.jsx
|   |   |   +-- ImagePreview.jsx
|   |   |   +-- LanguageSelector.jsx
|   |   +-- hooks
|   |   |   +-- useBackgroundRemoval.js
|   |   +-- index.css
|   |   +-- main.jsx
|   |   +-- services
|   |   |   +-- ImageProcessor.js
|   |   +-- utils
|   |       +-- LanguageContext.jsx
|   |       +-- imageUtils.js
|   |       +-- translations
|   |           +-- en.js
|   |           +-- zh.js
|   +-- tailwind.config.js
|   +-- template_config.json
|   +-- test-import.js
|   +-- vite.config.js
+-- uploads
    +-- 截屏2025-03-01 12.56.19.png
    +-- 截屏2025-03-01 13.42.16.png
    +-- 截屏2025-03-01 13.47.21.png
    +-- 截屏2025-03-01 18.05.08.png
    +-- 截屏2025-03-01 18.05.12.png
```

---

# File Description Inventory

- **ai_tshirt_background_removal_class_diagram.mermaid**: Class diagram of the project.
- **ai_tshirt_background_removal_sequence_diagram.mermaid**: Sequence diagram outlining the interactions.
- **ai_tshirt_background_removal_system_design.md**: Documentation of system architecture and design decisions.
- **background_removal_feature_prd.md**: Product requirements document detailing features and specifications.
- **react_template/**: Contains the main project files including source code.
  - **src/**
    - **App.jsx**: The main application component.
    - **components/**: Contains reusable components for the application.
      - **BackgroundRemover.jsx**, **ControlPanel.jsx**, **ImagePreview.jsx**, **LanguageSelector.jsx**.
    - **hooks/**: Custom hooks for handling business logic.
      - **useBackgroundRemoval.js**: Hook for background removal functionality.
    - **main.jsx**: Application entry point.
    - **services/**: Contains the services for handling image processing.
      - **ImageProcessor.js**: Service responsible for processing images.
    - **utils/**: Utility functions including language management and image utilities.
    - **index.css**: Global styles for the application.
  - **package.json**: Manages project dependencies and scripts.
  - **vite.config.js**: Configuration file for Vite.
  - **tailwind.config.js**: Configuration file for Tailwind CSS.

---

# Technology Stack

- **React**: JavaScript library for building user interfaces.
- **Vite**: Build tool that enhances the development experience with fast reloading.
- **Tailwind CSS**: Utility-first CSS framework for styling components.
- **JavaScript**: Programming language used for application logic.
- **HTML**: Markup language for structuring web pages.

---

# Usage

### Installation

1. Install dependencies:
   ```bash
   pnpm install
   ```

### Development

1. Start the development server:
   ```bash
   pnpm run dev
   ```

### Building

1. Build the project:
   ```bash
   pnpm run build
   ```

### Running Tests

1. Lint source files:
   ```bash
   pnpm run lint
   ```

--- 


# INSTRUCTION
- Project Path:`/data/chats/5qpco/workspace/react_template`
- You can search for the file path in the 'Directory Tree';
- After modifying the project files, if this project can be previewed, then you need to reinstall dependencies, restart service and preview;
