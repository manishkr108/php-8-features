# php-8-features
PHP 8 introduced several new features and improvements that can greatly enhance code quality, readability, and performance. 

PHP 8 introduced several new features and improvements that can greatly enhance code quality, readability, and performance. Below are some of the standout new tricks and best practices you can leverage in your PHP 8 projects:

<h1>1. Named Arguments</h1>

Named arguments allow you to pass values to a function based on the parameter name, making the code more readable and less error-prone, especially with functions that have many parameters.
function createOrder($product, $quantity, $price, $discount = 0) {
    // Your logic here
}

createOrder(
    product: 'Laptop',
    quantity: 2,
    price: 1500,
    discount: 100
);

