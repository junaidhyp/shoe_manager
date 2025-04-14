# shoe_manager
A simple Python program to manage and analyze shoe inventory data from a text file.

# Shoe Inventory Manager

This Python program reads shoe inventory data from a file and organizes it into objects for easy management and reporting. It's designed to help retail managers view and analyze product data efficiently.

## 📦 Project Overview

The application reads data from a text file named `inventory.txt`, which contains information about shoes, and processes it into a list of `Shoe` objects. Each object holds details such as product name, code, country of origin, cost, and quantity in stock.

The program provides methods to access this data easily and can be extended for additional reporting or inventory management functionality.

---

## 🧩 Features

- **Object-Oriented Design:**  
  A `Shoe` class models each item in the inventory with attributes and methods.

- **Class Methods Include:**
  - `get_cost()` – Returns the cost of the shoe.
  - `get_quantity()` – Returns the available quantity.
  - `__str__()` – Returns a formatted string representation of a shoe's details.

- **File Handling with Error Control:**
  - Reads inventory data from `inventory.txt`.
  - Handles file not found errors gracefully.
  - Skips header row during reading.
  - Validates and processes each line into a `Shoe` object.

- **Inventory Storage:**
  - All `Shoe` objects are stored in a global list called `shoe_list`.

---

## 📂 File Structure

