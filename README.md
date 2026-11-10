🛒 Clothes Store Database Manager
Python Status

An interactive and lightweight Python command-line application designed to simulate real-time inventory and pricing management for an e-commerce platform. This project demonstrates core programming principles including dynamic memory lists, conditional logic, user-input processing, and formatted data display.

🚀 Features
The codebase is organized into 4 structured modules that seamlessly handle the lifecycle of product records:

Part_1 - Database Initialization: Creates the in-memory store catalog holding starter products and their respective retail prices.

Part_2 - Real-time Registration: An interactive portal prompting users to input new merchandise and prices, immediately updating the active catalog database.

Part_3 - Safe Rollback/Deletion: Automatically and safely removes the most recently added product from the lists to handle quick input corrections.

Part_4 - Targeted Product Search & Removal: Enables users to look up any specific item. If found, it drops both the item and its price, rendering a freshly updated list of the store's stock.

🛠️ Core Concepts Demonstrated
Advanced List Operations: Implementing dynamic list manipulations via .append(), .pop(), and .index() methods.
Collection Pairing & Iteration: Utilizing Python's built-in zip() and range() helpers to map parallel arrays together safely.
Interactive CLI UX: Streamlining user prompts, case-insensitive string parsing (.lower()), and clean monetary output formatting (US$ 0.00).

📁 How to Run and Interact
Ensure you have Python 3 installed.
Open the notebook and run each cell in sequence.
Follow the interactive console instructions to register, inspect, and remove products dynamically.
