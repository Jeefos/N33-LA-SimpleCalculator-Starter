# SimpleCalculator

A simple console-based calculator application built with C# (.NET Framework 4.7.2). It supports basic arithmetic operations and includes unit tests.

## Features

- Add, subtract, multiply, and divide two numbers
- Supports both symbol (`+`, `-`, `*`, `/`) and word (`add`, `subtract`, `multiply`, `divide`) operators
- Exponentiation (`exp`)
- Input validation for numeric values
- Unit tests for core functionality

## Project Structure

- [`SimpleCalculator`](SimpleCalculator/): Main calculator application
  - [`Program.cs`](SimpleCalculator/Program.cs): Entry point and user interface
  - [`CalculatorEngine.cs`](SimpleCalculator/CalculatorEngine.cs): Implements calculation logic
  - [`InputConverter.cs`](SimpleCalculator/InputConverter.cs): Converts string input to numeric values
  - [`App.config`](SimpleCalculator/App.config): Application configuration
- [`SimpleCalculator.Test.Unit`](SimpleCalculator.Test.Unit/): Unit tests
  - [`CalculatorEngineTest.cs`](SimpleCalculator.Test.Unit/CalculatorEngineTest.cs): Tests for [`SimpleCalculator.CalculatorEngine`](SimpleCalculator/CalculatorEngine.cs)
  - [`InputConverterTest.cs`](SimpleCalculator.Test.Unit/InputConverterTest.cs): Tests for [`SimpleCalculator.InputConverter`](SimpleCalculator/InputConverter.cs)

## Getting Started

### Prerequisites

- Visual Studio 2017 or later
- .NET Framework 4.7.2

### Building

Open [`SimpleCalculator.sln`](SimpleCalculator.sln) in Visual Studio and build the solution.

### Running

1. Start the project (`F5` or `Ctrl+F5` in Visual Studio).
2. Follow the prompts in the console to enter numbers and an operator.

### Testing

Unit tests are located in the [`SimpleCalculator.Test.Unit`](SimpleCalculator.Test.Unit/) project. Run tests using Visual Studio's Test Explorer.

## Usage Example

```
Enter the first number: 5
Enter the second number: 3
Enter the operator (+, -, *, /): *
5 * 3 is equal to: 15
```

## License

This project is provided for educational purposes.
