# Syncfusion Blazor Server DataGrid - Exporting Customization

## Overview

This sample demonstrates export customization scenarios in the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) for Blazor Server applications. The implementation focuses on modifying export behavior beyond the default Grid export workflow, including changing exported file names, exporting data without grouping information, and applying external filter criteria only during export operations. These customization techniques are useful when exported documents must follow business-specific rules that differ from the data currently displayed in the Grid. The sample provides a reference implementation for tailoring DataGrid export behavior while maintaining a standard user experience for end users.

## Key Features

- Demonstrates customization of Syncfusion DataGrid export operations.
- Shows how export output can use a custom file name instead of the default generated name.
- Demonstrates exporting data without grouped records.
- Shows how additional external filtering logic can be applied exclusively during export operations.
- Uses sample data and Grid configuration stored within the repository implementation.

## Prerequisites

* Visual Studio 2022 or Visual Studio Code
* .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file: `ExportingCustomization.sln`
3. Restore NuGet packages.
4. Set the startup project to: `ExportingCustomization` 
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the directory containing `ExportingCustomization.csproj`.

```bash
dotnet restore
```

```bash
dotnet run
```
4. Open the URL displayed by the ASP.NET Core application in your browser.

## Project Structure

`Pages/` — contains the Blazor page that implements DataGrid export customization scenarios.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Syncfusion DataGrid exporting documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/excel-exporting

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
