# Project-1
Bootcamp LetsUpgrade
To output the two product items below the main page title in the App component, you can follow the steps below:

Import the <Product /> component in the App.js file:

import Product from './Product';

Add the following code in the App component, replacing the placeholder text:
javascript

function App() {
  return (
    <div>
      <h1>My Demo Shop</h1>
      <Product title="Product 1" price={10} description="First product" />
      <Product title="Product 2" price={20} description="Second product" />
    </div>
  );
}

export default App;
In this code, we are passing the title, price, and description as props to the <Product /> component for each product item. The first product item will display the information specified in the props for title, price, and description, while the second product item will display the information specified for the second set of props.

With this code, you should see the two product items displayed below the main page title in the App component, using the <Product /> component and different data passed via props.
