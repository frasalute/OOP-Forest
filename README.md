# Forest of Random Trees with Object Oriented Programming


Exercise done following tutorial for training purposes. 

This project generates a forest scene using OpenCV, NumPy, and Object-Oriented Programming (OOP) techniques. 
Each tree is dynamically created with randomized properties, such as height, scale, and color, for a realistic and varied visualization.

### Features

- **Dynamic Tree Generation**: Each tree is generated with random height, scale, and color.
- **Customizable Scene**: Easily adjust the number of trees, canvas size, and ground level.
- **Scalable Objects**: Trees are drawn with scalable trunks and leaves.
- **Efficient Image Manipulation**: Utilizes NumPy arrays for pixel-based rendering and OpenCV for drawing shapes.

### Dependencies

Ensure the following libraries are installed:
- **OpenCV (cv2)**
- **NumPy**

Install via pip:
```
pip install opencv-python numpy
```

### How It Works

1. A blank image canvas is created using NumPy's `np.zeros()`.
2. A `Tree` class is defined to generate trees with randomized properties like height, scale, and color.
3. Trees are drawn on the canvas using OpenCV's drawing functions such as `cv.circle` and `cv.line`.
4. The forest scene is displayed in a window using `cv.imshow()`.

### Usage

1. Clone the repository:
```
git clone https://github.com/frasalute/forest-scene-generator.git
cd forest-scene-generator
```
2. Run the script:
```
python forest_of_trees.py
```
3. Adjust parameters like `width`, `height`, `n_trees`, and `ground_level` in the script for customization.

### Customization

- **Canvas Dimensions**: Modify `width` and `height` to adjust the size of the scene.
- **Number of Trees**: Change `n_trees` to control the number of trees in the scene.
- **Ground Level**: Set `ground_level` to position the ground where trees are rooted.

### Output

A window displaying a randomized forest scene with dynamically generated, scalable trees.

### Contributing

Contributions are welcome! If you would like to improve this project:
1. Fork the repository.
2. Create a new branch:
```
git checkout -b feature/your-feature-name
```
3. Commit your changes:
```
git commit -m "Add a new feature"
```
4. Push your branch:
```
git push origin feature/your-feature-name
```
5. Open a pull request.

### License

This project is licensed under the MIT License - see the LICENSE file for details.