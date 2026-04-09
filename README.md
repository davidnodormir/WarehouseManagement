# WarehouseManagement
A custom warehouse management system designed to optimize inventory workflows and stock tracking for a local business. The aim was to digitize and automate a slow, paper-based process.

Project Overview

A fundamental part of this project was understanding the needs of the business owner, who has no IT background, and translating them into a functional digital tool. For this reason, I built an initial version to gather feedback.

->First Version: Due to some unclear initial requirements, I created a simple table to track general stock information. This helped significantly in clarifying all the required fields needed to identify a product and its availability.

->Second Version: After clarifying the requirements, I built the second version with the goal of creating a tool that could manage all warehouse stock operations in the simplest way possible.

# User Experience & Workflow

The user experience flows through three main sheets:

1. Anagrafica (Product Registry)
This is the least frequently used sheet, and its purpose is to register all new products. Since the business often operates on the same pool of items, the user only needs to register a product once. It can then be easily recalled by its automatically generated ID.

2. Registro (Logbook/Operations)
This is the most used sheet; all daily operations pass through here. First, the operator selects a product from a drop-down list (populated by the Anagrafica registry), and the remaining fields are filled automatically. Then, they add the date, choose the type of operation (from a predefined list agreed upon with the operators), and set the quantity. The date and product ID are crucial for tracking all warehouse movements.

3. Resoconto (Dashboard/Report)
This final sheet is the core of the tool. It provides a real-time report of all goods available in the warehouse. The stakeholder requested visual alerts (conditional formatting with bright colors) to highlight when a product's stock (giacenza) falls below a minimum threshold. I also implemented a distinction between raw materials yet to be processed (grezzo) and goods ready for delivery. All the core mathematical and business logic is implemented here.

I kept the interface as intuitive as possible and was able to train the employees in less than an hour, successfully achieving the project's main objective.

Requirements: Microsoft Office 365
