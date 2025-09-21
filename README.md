## Blazor WebAssembly (Blazor WASM)
A simple **Blazor WebAssembly** application using .NET 8.0. This project demonstrates basic interactive UI components (counter example with increment and decrement), Razor components, and server-side rendering using Blazor. If you navigate from one page to another, you’ll notice that the page does not refresh. This is an important feature of Blazor applications.

## 🌐 Blazor WebAssembly (WASM)

- How it works:
  - The app runs entirely in the browser.
  - The .NET runtime and your app are downloaded as WebAssembly and executed client-side.

- Pros:
  - Works offline or with intermittent connectivity (can use PWA features).
  - Scales well because most processing happens on the client.
  - Serverless hosting options (e.g., GitHub Pages, static web hosts).

- Cons:
  - Larger initial download size (because the .NET runtime and DLLs must be sent to the browser).
  - Some .NET libraries (e.g., those needing full server access) may not work.
  - Slower initial load compared to Blazor Server.

Use Case:
  - Public-facing websites or apps where offline support or low server costs are important.
  - Progressive Web Apps (PWAs).

---

## 📁 Repository Structure

| Folder/File | Description |
|-------------|-------------|
| `BlazorServerApp.sln` | Solution file that includes the project. |
| `BlazorServerApp.csproj` | The project file with dependencies and settings. |
| `Program.cs` | Entry point—configures the web app, adds services, routing, etc. |
| `appsettings.json` | Configuration settings (e.g. for logging, etc.). |
| `Properties` | Project properties (AssemblyInfo etc.). |
| `wwwroot` | Static assets: CSS, JavaScript, images. |
| `bin/`, `obj/` | Build output and intermediate files. |
| `Components/` | (If present) Razor components for modular UI pieces. |

---

## 🚀 Getting Started

These instructions will help you get a local copy up and running.

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) installed.
- A code editor or IDE that supports .NET and Blazor (e.g. Visual Studio, VS Code).
- (Optional) Git, for cloning the repo.

### Clone & Run

```bash
git clone https://github.com/rashedulalam46/blazor-server-app.git
cd blazor-server-app
dotnet restore
dotnet build
dotnet run
```

By default, the app will run on https://localhost:5001 (or another port shown in console). Open the browser and go to https://localhost:5001 to view it.

## 🔍 Features

- Counter component with Increment and Decrement buttons (interactive server mode).
- Razor pages/components for modular UI.
- Server-side rendering (Blazor Server) with real-time UI updates.

## ⚙ Configuration
- All configuration settings are held in appsettings.json and appsettings.Development.json.
- Logging and environment settings follow standard .NET practices.

## 🧪 Usage Examples

- Navigate to the /counter page: you’ll see the counter.
- Click Increase to increment the count.
- Click Decrease to decrement the count.

## 📦 Dependencies

.NET 8.0 SDK

Blazor (Server) 8.0 components

## 📄 License

Specify your license here (MIT, Apache, etc.) or if you don’t have one, you might want to add one for clarity.

🛠 Contributing & Issues

Feel free to open issues or submit pull requests. For major changes, it’s best to open an issue first to discuss what you’d like to do.

## 🙋 Author
[Rashedul Alam](https://github.com/rashedulalam46)

