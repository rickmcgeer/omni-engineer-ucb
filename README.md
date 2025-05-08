# UCB Fork
 
The UCB  fork  is a derivative of the LBL fork, and is preconfigured to work with [BearBorg](https://bearborgberkeley.edu/). It is designed to be used in a Berkeley-deployed Jupyter server, where authentication information is provided to the server on spawn.
To get started you must get an account on a UCB-hosted JupyterHub that supports Omni Engineer UCB (also known as OmniBear)
 
This fork also includes a tool `format_omni_markdown.py` to format saved Markdown chat logs from Omni Engineer for easy reading.   

# 🧠 Omni Engineer: An AI-Powered Developer Console

An intelligent assistant designed to enhance your development workflow with advanced AI capabilities.


## 🔍 Overview

Omni Engineer is a console-based tool that integrates AI capabilities into your development process. It offers smart responses to coding queries, file management, web searching, and image processing functionalities, now with enhanced features for a more robust development experience.

Omni Engineer is a spiritual successor to [Claude Engineer](https://github.com/Doriandarko/claude-engineer), built from extensive usage of hand-made AI tools, trial and error, and user feedback. This new script allows for more control via simplicity while introducing powerful new features like multi-file editing and chat session management.

## 🌟 Features

- AI-Powered Responses with Streaming Output
- Advanced File Management (Add, Edit, Create, Show Content)
- Multi-File Editing Support
- Web Searching with DuckDuckGo Integration
- Image Processing (Local Files and URLs)
- Undo Functionality for File Edits
- Conversation Save & Load
- Syntax Highlighting for Code
- Diff Display for File Changes
- AI Model Selection and Switching

## 🖥️ Commands

- `/add <filepath>`: Add files to AI context
- `/edit <filepath>`: Edit existing files
- `/new <filepath>`: Create new files
- `/search`: Perform web searches
- `/image <filepath/url>`: Add images to context
- `/clear`: Clear AI memory
- `/reset`: Reset the session
- `/stop`: Stop the output of the Assistant chat. Must press return after entering. 
- `/diff`: Toggle diff display
- `/history`: View chat history
- `/save`: Save current chat
- `/load`: Load a previous chat
- `/undo <filepath>`: Undo last file edit
- `/help`: Display available commands
- `/model`: Show current AI model
- `/change_model`: Change the AI model
- `/show <filepath>`: Display content of a file



## 📚 Usage

After launching the console, enter commands or questions as needed. The AI will respond accordingly, assisting with various development tasks. Use the `/help` command to see a list of available commands and their descriptions.

## 🤖 AI Models

Omni Engineer utilizes OpenRouter to access a variety of AI models. The default model is set to "openai/gpt4o" for general assistance and "google/gemini-2.0-flash-lite" for code editing. You can view the current model with `/model` and change it using `/change_model`. Currently supported models are:
- openai/gpt4o
- openai/gpt4o-mini
- google/gemini-pro
- google/gemini-flash
- google/gemini-2.0-flash-lite
- google/gemini-2.0-flash

## 🔧 Advanced Features

- **Multi-File Editing**: Edit multiple files in a single session.
- **Real-time Diff Display**: See changes as they're made with the diff feature.
- **Syntax Highlighting**: Improved code readability with syntax highlighting.
- **Image Context**: Add both local and URL-based images to your AI context.
- **Flexible Model Selection**: Switch between different AI models for various tasks.

## 🐛 Issue Reporting

Please use the issue tracker only for reporting actual bugs in the code. This helps keep the issue tracker focused on improving the project's stability and functionality.

## 🤝 Contributing

Contributions to Omni Engineer are welcome! Please feel free to submit pull requests, create issues for bugs, or suggest new features.

## ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Doriandarko/omni-engineer&type=Date)](https://star-history.com/#Doriandarko/omni-engineer&Date)


## Copyright

*** Copyright Notice ***

omni-engineer-ucb (omni) Copyright (c) 2025, The Regents of the University of California, through Lawrence Berkeley National Laboratory (subject to receipt of any required approvals from the U.S. Dept. of Energy) and Pietro Schirano.  All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

(1) Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

(2) Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

(3) Neither the name of the University of California, Lawrence Berkeley National Laboratory, U.S. Dept. of Energy, Pietro Schirano nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

You are under no obligation whatsoever to provide any bug fixes, patches, or upgrades to the features, functionality or performance of the source code ("Enhancements") to anyone; however, if you choose to make your Enhancements available either publicly, or directly to Lawrence Berkeley National Laboratory, without imposing a separate written license agreement for such Enhancements, then you hereby grant the following license: a non-exclusive, royalty-free perpetual license to install, use, modify, prepare derivative works, incorporate into other computer software, distribute, and sublicense such enhancements or derivative works thereof, in binary and source code form.


NOTICE.  This Software was developed under funding from the U.S. Department of Energy and the U.S. Government consequently retains certain rights.  As such, the U.S. Government has been granted for itself and others acting on its behalf a paid-up, nonexclusive, irrevocable, worldwide license in the Software to reproduce, distribute copies to the public, prepare derivative  works, and perform publicly and display publicly, and to permit others to do so.