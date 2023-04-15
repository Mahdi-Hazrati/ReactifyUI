# ReactifyUI (Comming Soon !)

ReactifyUI is a collection of reusable and customizable UI components built using React. It provides developers with a set of easily adaptable building blocks for creating beautiful and functional user interfaces.

## Features

- A growing library of React components for common UI elements including buttons, forms, modals, and more.
- Highly customizable styles and props to fit your unique design needs.
- Simple and intuitive API that makes working with ReactifyUI a breeze.

## Usage

To use ReactifyUI in your React application, simply import the desired component from the library and render it inside your own components. For example:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';
import * as RUI from 'reactifyui';

const App = () => {
  return (
    <div>
      <RUI.Button color="primary">Click Me!</RUI.Button>
    </div>
  );
};

ReactDOM.render(<App />, document.getElementById('root'));
