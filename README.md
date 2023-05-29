# Cute Name Project

https://cloudcomputing-382017.lm.r.appspot.com/

# Introduction

The CC-Functions Svelte application is an in-browser terminal that empowers developers with a minimalistic yet powerful set of commands, bringing the convenience of a command-line interface to the web. Designed for efficiency and ease of use, this application allows you to perform essential file system operations such as listing files, moving, copying, and removing them, all within your browser environment.

Powered by Svelte, a modern JavaScript framework, CC-Functions delivers a responsive and intuitive user interface, enabling seamless interaction with the terminal commands. Whether you're a beginner learning the basics or an experienced developer looking for a lightweight tool, this application provides a familiar command-line experience directly in your browser.

## Key Features:

- Minimalistic command set including commands like ls, mv, cp, and rm.
- Browser-based terminal interface for executing commands.
- Effortless file system operations for managing files and directories.
- Integration with Google Cloud Functions for seamless backend operations.
- Deployment on Google Cloud Platform using App Engine for easy scalability.

Under the hood, the CC-Functions application leverages serverless architecture powered by Google Cloud Functions. This allows you to harness the flexibility and scalability of cloud computing while executing the necessary backend operations for your file system commands. Additionally, the application can be seamlessly deployed using Google Cloud Platform's App Engine, ensuring a robust and scalable hosting environment.

With CC-Functions, you can streamline your development workflow, manage files efficiently, and perform essential operations directly within your browser. Whether you're working on personal projects, collaborating with a team, or exploring new coding techniques, this in-browser terminal provides a convenient and powerful solution.

## Installation

Ensure that you have Node.js and npm (Node Package Manager) installed on your machine. You can download and install them from the official Node.js website: https://nodejs.org

- **Clone the repository by running the following command in your terminal:**
 ``` git clone https://github.com/mineamihai2001/CC-functions.git```
 - **Navigate to the client folder using the following command:**
 ```cd CC-functions/client```
 - **Install the project dependencies by running the following command:**
 ```npm install```
  - **Once the installation is complete, you can start the development server by running the following command:**
  ```npm run dev```

This command will launch the application locally, and you should be able to access it in your web browser at http://localhost:5713.

Note: If the default port 5713 is already in use on your machine, the development server will automatically try to use the next available port.

Congratulations! The CC-Functions Svelte application is now installed and running locally on your machine. You can start exploring and using its features within your browser.

## Usage
Once you have the CC-Functions Svelte application installed and running, you can start using its in-browser terminal to perform file system operations. Follow these steps to get started:

Open your web browser and navigate to the URL http://localhost:5713 (or the appropriate URL if you have configured a different port).

The application will display a terminal interface in your browser, resembling a command-line environment. You'll see a command prompt where you can enter commands like: 


- ```ls```

	List the files and directories in the current directory, use the ls command.This will display a list of files and directories in the current location.

  
- ```mv filename path/to/source path/to/destination```  
		
	Move or rename a file or directory, use the mv command followed by the source and destination paths. For example:


- ```cp path/to/source path/to/destination```
Copy a file or directory, use the cp command followed by the source and destination paths

- ```rm path/to/file```
Remove a file or directory, use the rm command followed by the path to the file or directory

## API Integration
The CC-Functions Svelte application leverages the power of Google Cloud Functions to execute various file system commands such as ls, mv, cp, and more. Each command corresponds to its own specific Google Cloud Function, allowing for modular and scalable execution of operations.


Google Cloud Functions is a serverless execution environment that allows you to run individual functions in response to events. In the context of your CC-Functions application, these functions are responsible for handling the logic and execution of the file system commands.

## Styling
The CC-Functions Svelte application embraces a clean and visually appealing user interface inspired by the popular Gruvbox theme found in Neovim. To achieve this aesthetic, the application leverages the power of Tailwind CSS, a utility-first CSS framework that enables rapid styling and customization.

## Testing
Testing is an essential part of ensuring the stability and reliability of your CC-Functions Svelte application. In this project, we utilize Jest, a popular JavaScript testing framework, to write and execute tests for our components and functionality.

## Deployment
The CC-Functions Svelte application is deployed using Google App Engine, a fully managed serverless platform provided by Google Cloud Platform. App Engine allows for easy deployment and scaling of applications, providing a reliable infrastructure for hosting your Svelte application.

## Contributors
- **Lucaci Alexandru**

- **Minea Mihai**

- **Sbarcea Vladimir**

- **Smoc George**

## Licence
**Faculty of Computer Science. Alexandru Ioan-Cuza University Iasi**
