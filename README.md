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
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`CustomDefaultScrollbar.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-customize-default-scrollbar
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/scrolling

**Online example**: https://blazor.syncfusion.com/demos/datagrid/default-scrolling?theme=fluent2