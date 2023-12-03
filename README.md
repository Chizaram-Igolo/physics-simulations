# Interactive Pulley with Matter.js

This project demonstrates the creation of an interactive pulley using the Matter.js physics engine. The pulley consists of two boxes connected by a constraint, and user interaction is facilitated through mouse control.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [License](#license)

## Getting Started

To get started with the interactive pulley, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/matterjs-pulley.git
   cd matterjs-pulley
   ```

2. **Open `index.html`:**

Open the `index.html` file in your preferred web browser.

3. **Interact with the Pulley:**

   - Use the mouse to interact with the pulley.
   - Drag the boxes or experiment with different interactions.

## Usage

The interactive pulley is designed to showcase the capabilities of Matter.js in creating dynamic and interactive physics simulations. Users can manipulate the pulley system by dragging the connected boxes.

## Customization

Feel free to customize the pulley simulation to meet your specific requirements. Here are some customization options:

- Adjust Box Properties:
  - Modify the properties of **`boxA`** and **`boxB`** (e.g., size, position, density).
- Change Pulley Length: - Adjust the **`length`** property of the **`pulley`** constraint to change the length of the connection between the boxes.
- Explore Additional Features:
  - Matter.js provides various features for physics simulations. Explore the [Matter.js documentation](https://brm.io/matter-js/docs/) for more options.

## Dependencies

This project relies on the Matter.js library for physics simulations. The library is included using the CDN link in the **`index.html`** file:

```bash
<script src="https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.17.1/matter.js"></script>
```

## License

This interactive pulley project is licensed under the MIT License.
