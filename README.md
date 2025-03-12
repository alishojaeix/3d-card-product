# 3d-card-product

# LeafKey, TopoKey, and PandaKey - 3D Keyboard Showcase

This project showcases three unique 3D keyboard designs using the `<model-viewer>` web component. The keyboards are presented in an interactive card layout, allowing users to view and interact with the 3D models. The project is built with HTML, CSS, and JavaScript, and it leverages the `model-viewer` library for rendering 3D models.

## Features

- **Interactive 3D Models**: Each keyboard model is displayed in a 3D viewer that allows users to rotate and zoom in on the model.
- **Dynamic Color Options**: Users can change the color scheme of the keyboards using the provided color options.
- **Responsive Design**: The layout is responsive and adapts to different screen sizes, with some cards hidden on smaller devices for better usability.
- **Smooth Animations**: The models fade in smoothly when loaded, and the camera orbit changes dynamically when hovering over the cards.

## Keyboards

1. **LeafKey**: A keyboard that brings the tranquility of the forest to your fingertips.
2. **TopoKey**: A custom illuminated keyboard with neon topology mapped out in every key.
3. **PandaKey**: A playful keyboard inspired by pandas.

## Technologies Used

- **HTML5**: Structure of the webpage.
- **CSS3**: Styling and animations.
- **JavaScript**: Interaction logic and dynamic model manipulation.
- **[Model Viewer](https://modelviewer.dev/)**: A web component for rendering 3D models in the browser.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/3d-keyboard-showcase.git
   ```
2. Open the `index.html` file in your browser to view the project.
3. Interact with the 3D models by hovering over the cards and clicking on the color options to change the keyboard's appearance.

## Code Structure

- **index.html**: The main HTML file containing the structure of the webpage and the 3D models.
- **style.css**: The CSS file containing all the styles for the webpage, including animations and responsive design.

## Customization

- **Change Models**: Replace the `.glb` files in the `src` attribute of the `<model-viewer>` tags to display different 3D models.
- **Add More Cards**: Duplicate the `.card` div structure in `index.html` and update the content and model source to add more keyboards.
- **Adjust Colors**: Modify the `--clr` and `--fclr` CSS variables in the `.card` class to change the background and text colors.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- The 3D models used in this project are sourced from [CodePen](https://codepen.io/RAFA3L/pen/VYZrvjM).
- The `model-viewer` library is provided by Google.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

---

Enjoy exploring the 3D keyboards! 🌿🎹🐼
