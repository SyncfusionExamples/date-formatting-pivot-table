# Syncfusion JavaScript Pivot Table – Date Formatting Example

This sample demonstrates how to **apply date formatting in the Syncfusion JavaScript Pivot Table (PivotView)** component. Date formatting helps display date fields in a user-friendly format, making reports easier to read and analyze.

## 📖 Overview

The Pivot Table (PivotView) is a powerful component for summarizing and analyzing large datasets. In this example:

- We generate a dataset with fields like `ProductID`, `City`, `Date`, `CustomerName`, `Sold`, and `InStock`.
- The **Date** field is formatted using the pattern `dd/MM/yyyy-hh:mm a` (e.g., `21/10/2025-08:15 PM`).
- The Pivot Table is configured with:
  - **Rows:** `Date`
  - **Columns:** `ProductID`
  - **Values:** `Sold` (Units Sold), `InStock` (Stock Available)
- Virtualization is enabled for handling large data efficiently.

## ✅ Key Features in This Sample

- **Date Formatting:**  
  The `formatSettings` property is used to apply custom date formats:
  ```javascript
  formatSettings: [{ name: 'Date', type: 'date', format: 'dd/MM/yyyy-hh:mm a' }]
  ```
- **Grouping and Sorting:**  
  Grouping is applied on `ProductID` with a range interval of 4.
- **Performance Optimization:**  
  Virtual scrolling and member editor limits are enabled for large datasets.

## 🛠 Prerequisites

- A modern browser (Chrome, Firefox, Edge)
- No build tools required; this is a pure HTML/JavaScript example.

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SyncfusionExamples/date-formatting-pivot-table
   ```
2. **Open the sample:**
   - Navigate to the project folder.
   - Open `Date_Formatting.HTML` in your browser.

## 📂 Project Structure

- `Date_Formatting.HTML` – Main sample file with Pivot Table configuration.
- `styles/material.css` – Syncfusion Material theme.
- `scripts/ej2.min.js` – Syncfusion JavaScript library.

## 📚 Learn More

- [Pivot Table Documentation](https://ej2.syncfusion.com/javascript/documentation/pivotview/getting-started)
- [Pivot Table Demos](https://ej2.syncfusion.com/javascript/demos/#/tailwind3/pivot-table/overview.html)

## 💬 Support

For questions or feedback, visit the [Syncfusion Support Portal](https://support.syncfusion.com) or [Community Forums](https://www.syncfusion.com/forums).

## 📜 License

This is a commercial product and requires a valid Syncfusion license.  
[View License Terms](https://www.syncfusion.com/license/studio/22.2.5/syncfusion_essential_studio_eula.pdf).
