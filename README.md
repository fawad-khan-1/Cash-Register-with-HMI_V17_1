# Siemens PLC & HMI Cash Register System

This project implements a PLC-controlled Human-Machine Interface (HMI) for a fictional fast-food restaurant cash register. It was developed as part of a university industrial automation course using the Siemens HMI platform.

The project combines PLC ladder logic with a two-screen HMI application. The HMI provides the user interface for placing customer orders, displaying quantities and the calculated bill, selecting dine-in or takeout orders, and allowing a manager to modify food prices.

The completed project was originally implemented and tested using PLC and HMI equipment available in the university automation laboratory.

## Project Features

- PLC programming using Ladder Logic
- Siemens HMI development
- Two-screen HMI application
- HMI buttons for placing customer orders
- Display of food items and quantities ordered
- Dine-in and takeout order selection
- Automatic sales tax calculation for dine-in orders
- Display of the calculated food bill
- Manager interface for changing food prices
- HMI buttons and text I/O fields linked to PLC logic
- Physical PLC and HMI implementation

## HMI Operation

The cash register application uses two HMI screens.

### Customer Order Screen

The first screen provides the main cash register interface.

It allows the operator to:

- View food items
- View the quantity ordered
- Place a customer's order
- Select dine-in or takeout
- View the calculated food bill

For dine-in orders, the program applies a 6.25% sales tax. Takeout orders do not have the sales tax applied.

### Manager Price Screen

A button on the first screen allows access to a second HMI screen.

This screen allows the manager to change the prices of food items using input fields.

A navigation button on the second screen returns the user to the main ordering screen.

## PLC and HMI Integration

The project began with the cash-register control logic implemented using Ladder Logic.

The PLC logic was then linked to the HMI application so that the program's inputs and outputs could be controlled and displayed through HMI elements such as buttons and text I/O fields.

This replaced the physical breadboard buttons and program-window displays used in an earlier wired version of the cash register exercise with an HMI-based user interface.

## Technologies

- Siemens TIA Portal V17
- Siemens PLC
- Siemens HMI
- Ladder Logic
- PLC/HMI Integration
- HMI Buttons
- Text I/O Fields
- Industrial Automation

## Project Structure

The repository contains the original Siemens TIA Portal V17 project files used for the PLC and HMI implementation.

The main project can be opened using Siemens TIA Portal V17 or a compatible version.

## Hardware Testing

The project was originally implemented and tested using Siemens PLC and HMI hardware available in a university automation laboratory.

Because the required HMI hardware is not currently available to me, the original hardware configuration cannot presently be reproduced on my personal PLC setup.

## Original Lab Documentation

The repository includes a PDF copy of the original laboratory report written when the project was completed.

The report documents:

- The purpose of the HMI project
- The relationship between the Ladder Logic program and HMI
- The two-screen HMI design
- Customer ordering functionality
- Dine-in and takeout operation
- Sales tax calculation
- Manager food-price configuration
- HMI buttons and text I/O fields
- The original learning outcomes

The original report is included to preserve documentation of the project as it existed when it was developed.

## Demonstration

The completed HMI application was implemented and tested using physical Siemens PLC and HMI equipment in the university automation laboratory.

The following video was recorded when the original project was completed and demonstrates the HMI application operating on the laboratory equipment:

[View the Siemens HMI Demonstration](demo/Siemens-HMI-Demo.mp4)