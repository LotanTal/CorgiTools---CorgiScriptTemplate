# Corgi Script Template

Corgi Script Template is a Unity Editor extension that allows you to create, save, and load script templates for rapid script creation. 
This tool is particularly useful for developers who need to frequently create scripts with similar structures or boilerplate code.

## Features

- **Create Script Templates**: Easily create and save script templates for reuse.
- **Load and Edit Templates**: Load saved templates for editing or creating new scripts.
- **Customizable Folder Path**: Save scripts in your preferred folder within the project.
- **Simple UI**: Intuitive user interface built with Unity's UIElements.

## Installation

1. Clone or download the repository and place the `CorgiScriptTemplate` folder in your `Assets/` directory.
2. Open Unity and navigate to `CorgiTools` > `Corgi Script Template` to open the tool.

## Usage

### Creating a New Template

1. Open the Corgi Script Template window (`CorgiTools` > `Corgi Script Template`).
2. Click on `Create New Template`.
3. (Optional) Load an original script to use as a base by selecting a `TextAsset` file.
4. Enter the template content in the `Script Content` field.
5. Enter a name for your template in the `Template Name` field.
6. Specify the folder path where scripts created from this template should be saved.
7. Click `Save Template` to save your new template.

### Loading and Using a Template

1. Open the Corgi Script Template window (`CorgiTools` > `Corgi Script Template`).
2. Select a template from the list of saved templates.
3. Enter a name for the new script in the `Enter New Script Name` field.
4. Click `Create Script` to generate a new script based on the selected template.

### Deleting a Template

1. Open the Corgi Script Template window (`CorgiTools` > `Corgi Script Template`).
2. Select a template from the list of saved templates.
3. Click `Delete Template` and confirm the deletion in the dialog box.

### Template Placeholders

- `#SCRIPTNAME`: This placeholder in the template content will be replaced with the actual script name when creating a new script.
- `#//`: This sequence is used to comment out lines in the template.


Developed by Lotan Tal. Inspired by the need for rapid script creation and templating in Unity projects.
