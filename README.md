# Inventory Management System

## Overview
A console-based inventory management system that allows users to track products, manage stock levels, and process sales/purchases.

## Key Features
- **Inventory Tracking**: Add, view, and manage product details
- **Sales Processing**: Record sales and automatically update stock levels
- **Purchase Orders**: Add new stock from suppliers
- **Stock Monitoring**: View current inventory levels
- **Automatic Cleanup**: Remove out-of-stock items

## System Functions

### 1. Add New Items
- Store product details including:
  - Item name
  - Unique ID
  - Quantity in stock
  - Price per unit

### 2. Sell Items
- Process customer purchases
- Automatic quantity deduction
- Calculate total sale price
- Remove items when stock reaches zero

### 3. Purchase from Suppliers
- Restock inventory items
- Add quantities to existing products

### 4. Check Stock
- View complete inventory list with:
  - Product details
  - Current quantities
  - Unit prices

## Technical Implementation
- Linked list data structure for efficient inventory management
- Console-based interface for easy operation
- Real-time stock updates

## Usage Instructions
1. Run the program
2. Select from main menu options:
   - 1: Add new inventory items
   - 2: Process sales
   - 3: Process supplier purchases
   - 4: View current stock
   - 5: Exit system

3. Follow on-screen prompts for each operation

## Limitations
- Console interface only (no GUI)
- No data persistence between sessions
- Basic error handling

## Future Enhancements
- Add database connectivity for data persistence
- Implement barcode scanning support
- Generate sales reports
- Add multi-user support with authentication

This system provides essential inventory management capabilities for small businesses or retail operations needing basic stock control functionality.
