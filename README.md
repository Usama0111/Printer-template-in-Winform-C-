# Printing Test Project

This repository contains a Windows Forms application in C# that demonstrates how to print a simple receipt. The application sets up a custom paper size, defines the content to print, and sends the print job to the default printer.

## Features

- Customizable paper size for receipts
- Hardcoded values for company name, date, items, total, and thank you message
- Draws strings on the print document using `Graphics` object
- Event-driven printing using the `PrintPage` event

## Getting Started

### Prerequisites

- Visual Studio (any edition)
- .NET Framework (the version compatible with your project setup)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/printing-test-project.git
    ```
2. Open the solution file (`.sln`) in Visual Studio.
3. Restore any NuGet packages if needed.

### Running the Application

1. Build the project in Visual Studio.
2. Run the application by pressing `F5` or selecting `Debug -> Start Debugging`.
3. Click the button to send the print job to the default printer.

## Code Overview

### Form1 Class

#### Constructor

- Initializes the components and sets up the `PrintPage` event handler.
- Defines the custom paper size for the receipt.
- Centers the form on the screen.

#### printDocument1_PrintPage Method

- Handles the `PrintPage` event.
- Defines hardcoded values for the receipt content (company name, date, items, total, etc.).
- Draws the strings on the print document using `Graphics` object.

#### button1_Click Method

- Handles the button click event.
- Sends the print job to the default printer and closes the form.

#### Form1_Load Method

- Handles the form load event (currently optional).

## Customization

- Modify the hardcoded values in `printDocument1_PrintPage` method to customize the receipt content.
- Adjust the paper size and layout as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Contact

For any questions or suggestions, feel free to create an issue or contact the repository owner.

