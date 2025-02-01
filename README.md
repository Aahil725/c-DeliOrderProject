# Deli Order Application 

This project is a Deli Order Application created as part of a group project for a C# programming course. It demonstrates the application of GUI design, form controls, validation, and inventory management in a desktop application.

## Project Overview

The Deli Order Application enables users to order items from a deli menu, validates inputs, and tracks inventory levels for the deli. The project includes a detailed implementation of various functionalities, such as user-friendly interfaces, validation logic, and inventory updates.

### Key Features

- **GUI Design:** Intuitive and visually appealing user interface for ease of use.
- **Order Processing:** Customers can select items, specify quantities, and place orders seamlessly.
- **Validation Checks:** Comprehensive input validation, including:
  - Product selection validation.
  - Range and numeric checks for quantities.
  - Customer information validation (name, phone, and address).
  - Delivery city validation.
- **Inventory Management:**
  - Tracks inventory for deli ingredients.
  - Updates inventory levels dynamically based on orders.
  - Ensures sufficient stock for fulfilling orders.
- **Error Handling:** Clear and concise error messages for invalid inputs.

## Technical Details

### Project Structure

1. **Order Form (First Program):**
   - Provides an interactive order placement interface.
   - Validates customer inputs and item selections.

2. **Inventory Form (Second Program):**
   - Manages inventory data, allowing for adjustments and tracking.
   - Updates inventory after each order is processed.

### Validator Class

The `Validator` class is a critical component that handles:
- Product selection validation.
- Quantity checks for acceptable ranges and numerical accuracy.
- Customer information verification.
- Delivery city validation.

### Long-Term Data Storage

- Vendor information edited in the form is stored in an XML file for long-term persistence.

## Technologies Used

- **C#:** Core programming language for the application.
- **Windows Forms:** GUI development framework for designing user-friendly interfaces.
- **XML:** Data storage for vendor information.

## How to Use

1. **Run the Order Form Application:**
   - Input customer details.
   - Select deli items and specify quantities.
   - Place the order to update inventory.

2. **Manage Inventory Using the Inventory Form:**
   - Adjust ingredient stock levels.
   - Monitor inventory changes after orders are processed.

## Contribution

This project was developed as a collaborative effort in a group setting. Contributions were divided among members, with a focus on coding, testing, and validation.

## License

This project is for educational purposes and is not intended for commercial use.

---
