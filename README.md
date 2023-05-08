
# TOMB

  

Syntax highlighting for the TOMB smart contract language.



**How to install:**

 1. Go to .vscode\extensions   
     - **Windows**: *%USERPROFILE%\.vscode\extensions*
     - **Linux/Mac**: *~/.vscode/extensions*
 2. Create Folder (name it what you want, mines is called vscode-tomb)
 3. Download the zip file and extract its contents into the newly created folder or clone the repo into the newly created folder.
 4. Go into the newly created folder.
 5. Make sure you have js-yaml  and vsce installed.
       - npm install -g @vscode/vsce (-g if you want to install globally)
       - npm install js-yaml
 6. Once the above installed, type 'npm run package'.
 7. You should now have a '.vsix' file labeled tomb-0.0.2 (versions may be different as updates happen)
 8. You can install the .vsix file by doing 1 of the following:

	-	**Command line:** ```code --install-extension extension_name.vsix``` 
	-	**Visual Studio Code:** Click the Extension view -> Click  `...` at the top right of the extension view -> Click `install from Vsix`... -> find `extension_name.vsix` and install. 

9. Tomb files should now have proper syntax highlighting.

  

## Features

  

- Syntax highlighting

  

## Planned features

  

- IntelliSense

- Smart contract debugger

  
  

## Known Issues

  

- In a struct definition there needs to be a blank like between the member name plus colon and type.

