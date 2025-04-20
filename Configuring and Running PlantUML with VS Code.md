PlantUML is a popular open-source tool for creating UML diagrams and other visual models. If you’re a software developer, you may find yourself wanting to use PlantUML to create diagrams in your code documentation or other technical writing. Luckily, with the help of Visual Studio Code, configuring and running PlantUML is easy.

Here’s a step-by-step guide to help you get started with PlantUML in Visual Studio Code:

# Step 1: Install the PlantUML Extension

The first step is to install the PlantUML extension in Visual Studio Code. Open the Extensions sidebar by clicking on the Extensions icon in the left-hand sidebar, or by pressing `Ctrl+Shift+X` on Windows or `Cmd+Shift+X` on Mac. Search for PlantUML in the Extensions Marketplace, then click "Install."
![[Pasted image 20250420121703.png]]
## Step 2: Configure the PlantUML Extension
![[Pasted image 20250420121720.png]]
Next, you’ll need to configure the PlantUML extension. Open the VS Code Settings by clicking on the gear icon in the lower-left corner of the window, or by pressing `Ctrl+,` on Windows or `Cmd+,` on Mac. On the left click on extensions and open plantUML configurations. Then scroll down to the Render option and select PlantUMLServer from the dropdown and inside the server option add the official plantUML server address.
![[Pasted image 20250420121759.png]]
## Step 3: Create a PlantUML File
Now that you have the extension installed and configured, you can create your first PlantUML file. In the VS Code file explorer, create a new file with the extensions “`.wsd` `.pu` `.puml` `.plantuml` `.iuml`”. This will ensure that VS Code recognizes it as a PlantUML file.
## Step 4: Write Your Diagram Code
In your new PlantUML file, you can write your diagram code using the PlantUML syntax. For example, you might create a class diagram like this:

```
@startuml  
class Car {  
-make: string  
-model: string  
-year: int  
+start()  
+stop()  
}  
@enduml
```

## Step 5: Preview Your Diagram
To preview your PlantUML diagram, open the Command Palette by pressing `Ctrl+Shift+P` on Windows or `Cmd+Shift+P` on Mac. Type "PlantUML" in the search bar, then select "Preview Current Diagram" or just right-click on the code and select the same. This will open a new tab in VS Code with your diagram rendered as a PNG image.![[Pasted image 20250420122022.png]][^1]

[^1]: Alt + D to preview the diagram
![[Pasted image 20250420122153.png]]
## Step 6: Export Your Diagram
Once you’re satisfied with your diagram, you can export it as an image file. Open the Command Palette again and select “Export Current Diagram.” Choose a file format (PNG, SVG, or PDF), then select a destination folder. Your diagram will be saved as an image file in the selected folder.

That’s it! With these simple steps, you can configure and run PlantUML in Visual Studio Code to create professional-looking diagrams for your code documentation and technical writing