# Local Installation

## What is Local Installation?

Local installation of a package occurs directly within a specific project you are working on. This means that the package files will be installed in the `node_modules` folder of your project. Additionally, a new line will be added to the `package.json` file under the `dependencies` section to reflect this installation.

## Why Use Local Installation?

Local installation is beneficial for dependencies that are specific to a particular project. It ensures that each project uses the versions of packages it needs without risking conflicts with other projects that might require different versions of the same packages.

## How to Install a Package Locally?

To install a package locally, you can use the following command with npm:

```bash
npm install <package-name>
