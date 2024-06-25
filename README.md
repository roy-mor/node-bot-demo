# node-bot-demo
## "Practical AI: Building an LLM-Powered Organizational Bot in Node.js in Under One Hour"

Source code of demo at Node.TLV 2024 (VSCode Notebook)



Author: Roy Mor

This project uses VSCode Notebook to store and run the code (source code is saved in the `.nnb` file, i.e. "node notebook")

## How to use

1. Clone the repository
2. Make sure you have an API key from OpenAI ([details here](https://platform.openai.com/docs/quickstart))
4. Create a .env file in the project's root folder with the value `OPENAI_API_KEY=[YOUR_KEY]`
5. Install, or make sure Jupyter Notebook extensions are installed on your VSCode IDE (sometimes also called VSCode Notebook). More info [here](https://code.visualstudio.com/docs/datascience/jupyter-notebooks), [here](https://github.com/microsoft/vscode-nodebook) and [here](https://marketplace.visualstudio.com/items?itemName=donjayamanne.typescript-notebook)
6. Load the file `demo.nnb` into VSCode
7. Run each cell, starting from the first one which install packages and pre-requisites.
   Alternatively, you can run `npm install` in the project's root folder. You will need to install [Chroma (Chroma DB)](https://docs.trychroma.com/getting-started) using Docker and run the Chroma docker container (see the first cell in the notebook)

   
   
