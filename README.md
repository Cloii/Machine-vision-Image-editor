# Shape Detection Project

This project is a C++/CLI application that utilizes OpenCV for shape detection in images. The application provides a user interface for loading images, detecting shapes, and displaying the results. The project aims to demonstrate the integration of OpenCV with .NET and provide a straightforward shape detection tool.

---

## Features

- Image loading and display
- Shape detection (circles, triangles, rectangles, and squares)
- User interface for selecting images and viewing results
- Conversion between .NET Bitmap objects and OpenCV Mat objects
- Background worker for performing shape detection

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | C++/CLI |
| Computer Vision | OpenCV |
| Framework | .NET Framework |
| UI | Windows Forms |
| Package | OpenCvSharp4.Windows |
| Package Manager | NuGet |

---

## Getting Started

### Prerequisites

- Visual Studio 2019 or later
- .NET Framework 4.7.2 or later
- NuGet Package Manager

### Installation

1. Clone the repository from GitHub.
2. Open the solution file in Visual Studio.
3. Install the required NuGet package:
   ```
   Install-Package OpenCvSharp4.Windows
   ```
4. Build the solution using **Build > Build Solution** or `Ctrl+Shift+B`.
5. Run the application using **Debug > Start Debugging** or `F5`.

---

## Usage

1. Launch the application.
2. Use the interface to load an image from your file system.
3. Run shape detection to identify circles, triangles, rectangles, and squares.
4. View the annotated results directly in the application window.

---

## Contributing

Contributions are welcome. Feel free to fork the repository and open a pull request with your proposed changes.

---

## License

This project is open source. You are free to fork, build on, and modify it as needed.
