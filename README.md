# **From 2D to 3D Visualization** 🔄

## **Overview** 🌐

**"From 2D to 3D Visualization"** is an interactive visual project created using Processing, where a 2D image is transformed into a 3D representation. The image is split into a grid of tiles, each of which is converted into a 3D sphere with a height based on the brightness of the corresponding pixel in the original image. This results in a stunning mosaic that gives depth to a simple 2D image. The entire structure rotates dynamically, creating a mesmerizing effect for the viewer. 🔄

---

## **Features** ✨

- **Image to 3D Conversion**: The 2D image is processed and transformed into a 3D grid of spheres. 🖼️➡️🔵  
- **Brightness Mapping**: The brightness of each pixel is used to determine the height (z-axis) of the corresponding 3D sphere. 🌞🔺  
- **Dynamic Rotation**: The mosaic rotates continuously along the y-axis, creating an immersive experience. 🔄💫  
- **Customizable Tile Size**: The number of tiles (100 by default) can be adjusted to modify the grid density. 🔲🔳  

---

## **Requirements** 🛠️

- **Processing**: This project requires the [Processing IDE](https://processing.org/download/). 💻  
- **Image**: The project uses a 2D image named `medusa.jpg.jpg`, which should be placed in the same folder as the code. The image is resized to fit the canvas dimensions (900x900 pixels). 🖼️  

---

## **Installation** 📥

1. Download and install the [Processing IDE](https://processing.org/download/). 🔽  
2. Create a new project and paste the code into the main editor. 📂  
3. Download or use any 2D image (make sure it’s named `medusa.jpg.jpg`) and place it in the project’s `data` folder. 🗂️  
4. Run the project. 🚀  

---

## **Code Explanation** 📝

### **`setup()`**

- The canvas is set up with a size of 900x900 pixels and a 3D rendering mode (`P3D`). 🖥️  
- The image (`medusa.jpg.jpg`) is loaded and resized to fit the canvas. 🔄  

### **`draw()`**

- The background is set to a light gray color (`#f1f1f1`). 🎨  
- A grid of spheres is created, with each sphere’s height determined by the brightness of the corresponding pixel in the image. 🔴🔵🟢  
- The structure is rotated continuously to create a dynamic visual effect. 🔄✨  

---

### **Key Functions:**

- **`img.get(x, y)`**: Gets the color of the pixel at the given (x, y) position from the image. 🖼️  
- **`brightness(c)`**: Returns the brightness of the color `c`, which is used to map the z-axis (height) of the spheres. 🌞🔋  
- **`sphereDetail(3)`**: Sets the sphere detail (level of smoothness) to 3. 🏀  
- **`map()`**: Maps the brightness value (0-255) to a range for the z-axis (-100 to 100) and the size of the spheres. 📏  

---

## **How it Works** 🔍

1. The image is loaded and resized. 🖼️🔄  
2. The image is divided into a grid of tiles (100x100 by default), and each tile is processed to create a sphere. 🔲🟡  
3. The sphere’s size and height (z-axis) are based on the brightness of the pixel at the corresponding location. 🌟🔼  
4. The entire structure is rotated along the y-axis, creating a dynamic 3D mosaic. 🔄💫  

---

## **Screenshots** 📸
![image](https://github.com/user-attachments/assets/a21c3414-4663-4efa-afd8-3dc1f679bdc9)


---

## **License** 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


