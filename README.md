# unity-xmlTextureSlicer

Since `TextureImporter.spritesheet` is deprecated, this editor script now uses `ISpriteEditorDataProvider` for sprite slicing. It supports Kenny's 2D assets (XML + PNG).
>**Note:** This editor script was generated with the assistance of ChatGPT.

## How to Use

1. **Import the Unity Package**  
   Download and import the provided `unitypackage` into your Unity project.

2. **Add PNG and XML to Assets**  
   Place the `.png` and `.xml` files into your project's `Assets` folder.

3. **Configure the PNG File**  
   In the **Inspector** window for the `.png` file:  
   - Set **Texture Type** to `Sprite (2D and UI)`  
   - Set **Sprite Mode** to `Multiple`  

4. **Access the Sprite Splitter**  
   From Unity's main menu, navigate to `Tools > Sprite Splitter`.

5. **Load PNG and XML Files**  
   In the **Sprite Splitter** window, drag the `.png` and corresponding `.xml` files into the input fields.

6. **Split the Sprites**  
   Click the `Split Sprites` button to process the slicing.

7. **Check the Result**  
   In your `.png` file's subdirectory, you will find the sprites sliced according to the XML specifications!
