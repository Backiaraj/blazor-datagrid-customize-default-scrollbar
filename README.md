# Blazor DataGrid — Customize Default Scrollbar

A sample Blazor application demonstrating how to customize the appearance of scrollbars in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component using CSS styling.

## Overview

This project showcases techniques for styling the default scrollbar rendered inside the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component. Instead of relying on browser defaults, you can apply custom CSS to create a cohesive and branded scrollbar experience that aligns with your application's theme.

The sample includes:
- A functional DataGrid with sample order data
- Custom scrollbar styling using CSS pseudo-elements
- Scrollbar styling for webkit browsers (Chrome, Safari, Edge)
- Responsive layout with fixed dimensions

## Features

- **Custom Scrollbar Styling** — Override default scrollbar appearance with custom colors, shapes, and border-radius using CSS pseudo-elements
- **Thumb Customization** — Style the draggable scroll handle with background colors and rounded corners for a modern look
- **Track & Button Styling** — Customize the scrollbar track background and scroll buttons to create a unified visual design
- **Live DataGrid Example** — Pre-built sample with 75 rows of realistic order data (OrderID, CustomerID, OrderDate, Freight, ShipCountry)
- **Easy to Extend** — Simple CSS-based approach that's easy to modify and adapt to different themes and brands
- **Responsive Layout** — Responsive design with a fixed-height grid that demonstrates scrollbar behavior in real-world scenarios
- **Blazor Components** — Built with enterprise-grade Blazor DataGrid and Navigation components
- **Zero Configuration** — Works out of the box with minimal setup—just clone, restore, and run

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-customize-default-scrollbar.git
cd blazor-datagrid-customize-default-scrollbar
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/scrolling

**Online example**: https://blazor.syncfusion.com/demos/datagrid/default-scrolling?theme=fluent2