# Fast React Pizza Co. Menu

![Fast React Pizza Co.](https://i.imgur.com/CUKU4hql.jpg)

This is a simple React application for displaying the menu of Fast React Pizza Co., showcasing the use of components, props, and JSX.

## Project Setup

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Installation

To install the necessary dependencies, run:

```bash
npm install
```

### Running the Application

To start the application, run:

```bash
npm start
```

This will start the development server and open the application in your default web browser. If it doesn't open automatically, navigate to [http://localhost:3000](http://localhost:3000).

### Building the Application

To build the application for production, run:

```bash
npm run build
```

This will create an optimized build of the application in the `build` directory.

## Project Structure

- `src/index.js`: Entry point of the application.
- `src/index.css`: Global styles for the application.
- `src/components`: Directory for React components.

## Components

### App

The main component that wraps the entire application. It includes the `Header`, `Menu`, and `Footer` components.

### Header

A simple header component that displays the name of the restaurant.

### Menu

The menu component that displays a list of pizzas. It includes a conditional rendering to show a message when the menu is empty.

### Pizza

A component that displays the details of a single pizza. It shows the name, ingredients, price, and an image of the pizza. If the pizza is sold out, it displays a "SOLD OUT" message.

### Footer

The footer component that checks if the restaurant is open based on the current time. If the restaurant is open, it displays the `Order` component.

### Order

A component that displays the opening hours and an order button when the restaurant is open.

## Data

The pizza menu data is stored in the `pizzaData` array, which includes the name, ingredients, price, photo name, and sold-out status for each pizza.

## Styling

The application uses a combination of CSS classes and inline styles. Global styles are defined in `src/index.css`.

## Acknowledgements

This project is part of the Ultimate React Course 2024: React, Next.js, Redux & More by Jonas Schmedtmann.

## License

This project is licensed under the MIT License.

## Usage

To use the application, simply clone the repository, install the dependencies, and start the development server as described above.

Feel free to customize and expand the application as needed. Enjoy building with React!
