# Package Express - Shipping Calculator

This is a simple console application written in C# that calculates the estimated shipping cost for a package based on its weight and dimensions.

## How It Works

1. The program welcomes the user and prompts them to input the package's weight.
2. If the package's weight exceeds 50 units, an error message is displayed, and the program terminates.
3. If the weight is acceptable, the user is prompted to enter the package's width, height, and length.
4. The program checks if the total dimensions (width + height + length) exceed 50 units.
   - If they do, an error message is displayed, and the program terminates.
5. If the dimensions are acceptable, the program calculates the shipping cost using the formula:
   
   `Shipping Cost = (Width * Height * Length * Weight) / 100`

6. The result is displayed as the estimated total in dollars.

## Example Output
```
Welcome to Package Express. Please follow the instructions below.
Please enter the package weight: 40
Please enter the package width: 10
Please enter the package height: 12
Please enter the package length: 11
Your estimated total for shipping this package is: $528.00
Thank you!
```

## How to Run the Program

1. Clone or download the repository.
2. Open the project in your favorite C# IDE (such as Visual Studio or Visual Studio Code).
3. Compile and run the program.

## Requirements
- .NET SDK installed on your machine.
- Basic knowledge of running console applications in C#.

## License
This project is licensed under the MIT License.

