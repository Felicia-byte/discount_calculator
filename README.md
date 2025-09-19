# discount_calculator

This project provides a simple Python script that calculates the final price of an item after applying a discount. The script prompts the user to enter the original price and a discount percentage. If the discount percentage is 20% or higher, the discount is applied; otherwise, the original price is returned.

## Features

- **User Input**: Prompts for original price and discount percentage.
- **Conditional Discount:** Applies discount only if it is 20% or higher.
- **Error Handling:** Handles invalid (non-numeric) input gracefully.
- **Reusable Function:** The core logic is encapsulated in the `calculate_discount` function.

## Usage

1. Clone this repository or download the `discount_calculator.py` file.
2. Run the script using Python 3:
   ```bash
   python discount_calculator.py
   ```
3. Enter the original price and the discount percentage when prompted.

## Example

```
Enter the original price: 100
Enter the discount percentage: 25
Discount applied! Final price: 75.00
```

```
Enter the original price: 50
Enter the discount percentage: 10
No discount applied. Original price: 50.00
```

## Function Reference

```python
def calculate_discount(price, discount_percent):
    """
    Calculates the final price after applying a discount.
    If the discount is 20% or higher, applies the discount.
    Otherwise, returns the original price.
    """
```

## Requirements

- Python 3.x

## License

This project is open source and available under the [MIT License](LICENSE).
