# GitHub CodeSpaces

This workshop uses VSCode in browser through GitHub Codespaces. 
You can learn more about each:

- [Codespaces overview]()
- [VSCode](https://code.visualstudio.com/docs/getstarted/userinterface)

## Tips

- You can only have 2 codespaces active, you can see your active ones at [github.com/codespaces](https://github.com/codespaces)
- If any say that you have "uncommitted changes" it is important to go in to it and [commit](https://code.visualstudio.com/docs/sourcecontrol/overview#_commit) them. 

## Behind the Scenes

The codespace set up for the workshop has a 
[devcontainer](https://code.visualstudio.com/docs/devcontainers/create-dev-container) 
file in it. This file tells the codespace how to set everything up. In this template it does a few key things: 
- install python