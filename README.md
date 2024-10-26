# FrontKanban: Task Management Tool for FrontAccounting ERP
Developed a Kanban-style task management module for FrontAccounting ERP.

- [GitHub Repository](https://github.com/shhivaam/Task-Management-Tool)

## Requirements
- FrontAccounting version 2.4.x

## Installation
1. Rename the folder `Task-Management-Tool-main` to `kanban` and copy it to the FA modules directory.
2. For FrontAccounting version 2.4.4 and later:
   - Install and activate the module normally.
3. For earlier versions:
   - Comment out lines 215 to 220 in `admin/inst_module.php`.
   - Install and activate the module.
   - Uncomment lines 215-220 in `admin/inst_module.php`.
