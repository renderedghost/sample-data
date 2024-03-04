# Sample Data for Prototypes

This repository is a curated collection of sample images and text data organized in named folders, ideal for use in design prototypes.

Whether you're a designer, developer, or content creator, this resource aims to provide a diverse set of assets to kickstart your creative projects.

## Getting Started

### Prerequisites

Before you begin, ensure you have Git installed on your Mac. If not, you can install it by following these steps:

1. Open the Terminal.
2. Install Homebrew by running the following command:

   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

3. Once Homebrew is installed, install Git with Homebrew by executing:

   ```sh
   brew install git
   ```

### Installation

To clone the repository to your desktop, follow these steps:

1. Open the Terminal.
2. Change the current working directory to the location where you want the cloned directory.

   ```sh
   cd ~/Desktop
   ```

3. Clone the repository to your desktop by running:

   ```sh
   gh repo clone renderedghost/sample-data
   ```

4. After cloning, you will have a `sample-data` folder on your desktop containing all the assets.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**: Fork the repository by clicking on the 'Fork' button at the top right corner of this page. This creates a copy of the project in your GitHub account.
2. **Clone the Fork**: On your desktop, open Terminal and run the following git command to clone your fork:

   ```sh
   git clone https://github.com/your-username/sample-data.git
   ```

3. **Create a Branch**: Navigate into the cloned directory, and create a branch for your feature or fix using:

   ```sh
   git checkout -b feature/AmazingFeature
   ```

4. **Make Changes**: Add or modify the sample data. Please ensure text files are named meaningfully following the existing naming convention (e.g., `event--name.txt` for event names). For folders containing images, name them descriptively to reflect the contained images.
5. **Commit Your Changes**: After making changes, stage your changes and commit them with a clear commit message:

   ```sh
   git add .
   git commit -m "Add some AmazingFeature"
   ```

6. **Push to the Branch**: Push your changes using:

   ```sh
   git push origin feature/AmazingFeature
   ```

7. **Open a Pull Request**: Go to your repository on GitHub and open a pull request with a comprehensive description of your changes.

### Naming Conventions

- **Text Files**: Use descriptive names in , using **kebab--case** if necessary (e.g., `submission--abstract.txt`).
- **Image Folders**: Name folders descriptively, reflecting their content, using **kebab--case** if necessary (e.g., `event--poster/`).

## Supplementary Notes

### Loading Images and Text into Microsoft's Content Reel Plugin for Figma

To use the assets in Figma with the Content Reel plugin:

1. **Install Content Reel**: Open Figma, go to the Community tab, search for ["Content Reel" by Microsoft](https://www.figma.com/community/plugin/731627216655469013), and install the plugin.
2. **Add Assets to Content Reel**:
   > Read [Content Reel documentation](https://contentreel.design/) to load content to Figma.
   - For images: Drag and drop image files from your local `sample-data` folder into the Content Reel panel in Figma.
   - For text: Open a text file, copy its content, and then paste it into the Content Reel text section.
3. **Apply Assets**: Select a frame or text element in your Figma file, then apply the desired asset from the Content Reel panel.
