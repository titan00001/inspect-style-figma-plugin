# **Inspect Style - Figma Plugin**

Inspect and export style tokens from any Figma page — 
fill colors, typography, and component usage — in one click.

**2,600+ users · 44 likes · Figma Community**

→ [Install on Figma Community](https://www.figma.com/community/plugin/1314863667125003624/inspect-style)

## What it does
- Extracts all fill colors used on the current page with hex values and usage counts
- Lists typography styles with font family, size, weight, line height
- Shows which components use each style — useful for auditing design systems
- Works on any Figma file, no setup required

## Stack
TypeScript · React · TailwindCSS · Webpack · Figma Plugin API

## Overview:
Inspect Style is a versatile Figma plugin designed to simplify style inspection within your Figma projects. With a focus on ease of use and efficiency, this plugin enables users to quickly analyze and gather information about the styles utilized on the current page of their Figma files.

## Key Features:
- **Style Inspection**: Easily inspect and gather details about styles used in the current Figma page.
- **Efficient Workflow**: Streamlined functionality for a swift and efficient style exploration process.
- **User-Friendly Interface**: Intuitive interface designed for both beginners and experienced Figma users.
- **Detailed Information**: Obtain comprehensive information about each style, including hex codes, usage statistics, and more.

## How to Use:
- Open your Figma project.
- Navigate to the desired page.
- Run the "Inspect Style" plugin.
- Explore and analyze the style information presented.


## Installation:
- Visit the Inspect Style GitHub repository.
- Clone or download the repository.
- Load the plugin in Figma using the "Development" section in the Figma Plugins panel.
- Run the plugin on your Figma project.

## Contributing:
We welcome contributions from the Figma community. Feel free to fork the repository, make improvements, and submit pull requests.

## Issues and Bug Reports:
If you encounter any issues or have suggestions for enhancements, please submit them through the GitHub Issues section.

## License:
This Figma plugin is open-source and distributed under the MIT License.

Explore and inspect styles effortlessly with the Inspect Style Figma plugin!

## Credits

This project template has been borrowed from [bricks-cloud/figma-plugin-tailwindcss-template](https://github.com/bricks-cloud/figma-plugin-tailwindcss-template). Special thanks to the original contributors for providing a solid foundation.

### Technologies Used:
- Typescript
- React
- Tailwindcss
- Webpack
- Yarn


#### **To run in dev mode**:
1. Install [Node.js](https://nodejs.org/en/) and [Yarn](https://classic.yarnpkg.com/en/docs/install).
2. Run `yarn install` in the repository's root directory.
3. Run `yarn run dev` to start building.
4. Right Click in Figma -> "Plugins" -> "Development" -> "Import plugin from manifest..."
5. Click on "+" -> import plugin from manifest -> Select ```./dist/manifest.json``` file to import the plugin
6. Click on "Run" to start the Figma plugin in development mode.

The plugin will help in creating/extracting a list of style elements used in the current page of Figma, providing valuable insights into your design workflow.
