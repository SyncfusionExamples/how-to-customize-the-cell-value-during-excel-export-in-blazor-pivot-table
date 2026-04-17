# 🔄 Blazor Pivot Table: Custom Excel Cell Value Export

[![License](https://img.shields.io/badge/license-SEE%20LICENSE-blue.svg)](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf)
[![.NET](https://img.shields.io/badge/.NET-7.0-512BD4.svg)](https://dotnet.microsoft.com/)
[![Visual Studio](https://img.shields.io/badge/Visual%20Studio-2022-5C2D91.svg)](https://visualstudio.microsoft.com/)
[![Syncfusion](https://img.shields.io/badge/Syncfusion-Blazor%20PivotTable-FF6B35.svg)](https://www.syncfusion.com/)

> **Customize cell values during Excel export** — Learn professional techniques for enhancing Pivot Table data formatting and applying custom transformations when exporting to Excel using Blazor and Syncfusion components.

## 📊 Overview

This example demonstrates how to customize cell values in a Blazor Pivot Table during Excel export operations. Apply custom formatting, data transformations, and conditional logic to enrich exported data with dynamic calculations and styled output.

## ✨ Key Features

- ✅ **Cell Value Customization**: Transform and format cell values during export
- ✅ **Blazor Integration**: Seamless Syncfusion Pivot Table component usage
- ✅ **Custom Formatting**: Apply number, date, and text formatting rules
- ✅ **Data Transformation**: Real-time calculations and logic during export
- ✅ **Export Functionality**: Direct Excel export with customized outputs

## 🛠 Technology Stack

- **Framework**: ASP.NET Core Blazor (Server-Side)
- **Language**: C# 11+
- **.NET Version**: 7.0+
- **UI Components**: Syncfusion.Blazor.PivotTable v23.1.44
- **Excel Engine**: Syncfusion.Blazor components

## 📦 Installation & Quick Start

### Prerequisites
- Visual Studio 2022 or VS Code
- .NET 7.0 SDK or later
- Syncfusion license (community edition available)

### Setup Steps
1. Clone this repository
2. Open `CustomizingCellValue.sln` in Visual Studio 2022
3. Restore NuGet packages: `Right-click Solution → Restore NuGet Packages`
4. Build the solution: `Ctrl+Shift+B`
5. Run the project: `F5`

The application launches at `http://localhost:5001`

## 🚀 Usage

1. Interact with the Pivot Table UI
2. Configure rows, columns, and value fields
3. Modify cell data as needed
4. Click **Export to Excel** to download
5. Open the Excel file to see custom-formatted cell values

## 🧩 Project Structure

```
├── Pages/
│   ├── Index.razor          # Main Pivot Table UI
│   └── FetchData.razor      # Data source
├── Data/
│   ├── WeatherForecast.cs   # Data models
│   └── WeatherForecastService.cs
├── appsettings.json         # Configuration
└── Program.cs               # Startup setup
```

## 💡 Configuration

Modify `appsettings.json` and `appsettings.Development.json` to customize:
- Logging levels
- Environment-specific settings
- Export paths

## 🆘 Troubleshooting

**Pivot Table not rendering?**
- Verify Syncfusion packages installed
- Check browser console for errors

**Export not working?**
- Ensure export directory has write permissions
- Confirm Syncfusion license is valid

## 📚 Resources

- [Syncfusion Blazor Pivot Table Docs](https://blazor.syncfusion.com/documentation/pivot-table/getting-started)
- [ASP.NET Core Blazor Guide](https://learn.microsoft.com/en-us/aspnet/core/blazor/)
- [Project Repository](https://github.com/SyncfusionExamples/)

## 📄 License

This project is licensed under the **Syncfusion Community License**. See [Syncfusion License](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf) for details.

## 🆘 Support

Need help? Check the troubleshooting section or visit [Syncfusion Support](https://www.syncfusion.com/support/)
