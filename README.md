# warehousemanagement2.0
Developed by Berk EKIN for Education and Training Purposes. 
Github:https://github.com/berkekin

Overview:
Warehouse Management System v2.0 is a robust and user-friendly desktop application developed using C# and the .NET Framework. Designed to streamline and optimize warehouse operations, this system offers comprehensive tracking and management of inventory items, ensuring efficiency and accuracy in your workplace.

Features:
Inventory Management

View all inventory items in a structured DataGridView.
Add new items with details such as Item ID, Name, Quantity, and Location.
Update existing item details seamlessly.
Delete items with confirmation to prevent accidental removals.
Data Persistence

JSON-Based Storage: Inventory data is saved and loaded from a JSON file, ensuring data persistence across sessions.
Export to CSV: Easily export inventory data to CSV for reporting and analysis.
User Feedback System

Status Strip: Provides real-time feedback on operations like additions, updates, deletions, and errors.
Logging: Actions and errors are logged to a log.txt file for monitoring and troubleshooting.
Undo/Redo Functionality

Action History: Revert or reapply recent changes with undo and redo options, enhancing data integrity.
Search and Filter

Advanced Search: Filter inventory items based on Item ID, Name, and Location to quickly find specific products.
User Interface Enhancements

MenuStrip: Organized menus for File operations (Load, Save, Export, Exit), Edit actions (Undo, Redo), and Help (About).
Responsive Design: Controls adjust gracefully to window resizing, ensuring a consistent user experience.
DataGridView Customization: Supports column sorting and reordering for personalized data views.
About Dialog

Provides application details, version information, and developer credits for user reference.
Technologies Used
Programming Language: C#
Framework: .NET Framework
IDE: Visual Studio
Data Serialization: Newtonsoft.Json (JSON.NET)


Usage
Viewing Inventory

Upon launching, the DataGridView displays all existing inventory items.
Adding an Item

Fill in the Item ID, Item Name, Quantity, and Location in the respective input fields.
Click the Add Item button to add the new item to the inventory.
Updating an Item

Select an item from the DataGridView to load its details into the input fields.
Modify the desired fields and click the Update Item button to save changes.
Deleting an Item

Select an item from the DataGridView.
Click the Delete Item button and confirm the deletion when prompted.
Searching and Filtering

Use the search fields at the top to filter items by Item ID, Name, or Location.
Click the Search button to apply filters.
Exporting Data

Navigate to File > Export to CSV to export the current inventory view to a CSV file.
Undo/Redo Actions

Use Edit > Undo or Edit > Redo to revert or reapply recent changes.
Viewing Logs

Check the log.txt file in the application directory for detailed logs of actions and errors.
