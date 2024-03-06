# Discount Calculator

This Python script contains a function named `calculate_discount` that calculates the final price after applying a discount.

## Usage

To use the `calculate_discount` function, follow these steps:

1. Import the function into your Python script:

    ```python
    from discount_calculator import calculate_discount
    ```

2. Call the `calculate_discount` function with the original price and discount percentage as arguments.

    ```python
    # Example usage:
    original_price = 100
    discount_percent = 20
    final_price = calculate_discount(original_price, discount_percent)
    ```

3. The `calculate_discount` function will return the final price after applying the discount.

4. Print or use the `final_price` variable as needed in your script.

## Example

```python
# Example usage of calculate_discount function
original_price = 100
discount_percent = 20
final_price = calculate_discount(original_price, discount_percent)
print("Final price after discount:", final_price)
