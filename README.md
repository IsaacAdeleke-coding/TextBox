# TextBox Class Project

This project demonstrates a simple `TextBox` class in C++. The `TextBox` class encapsulates a private string value and provides methods to set and get the text, following basic principles of encapsulation in object-oriented programming.

## Project Structure

The project is organized into three main files:

- **TextBox.hpp**: Contains the class declaration with private and public members.
- **TextBox.cpp**: Implements the class methods, such as setting and getting the value.
- **main.cpp**: Contains a sample usage of the `TextBox` class, demonstrating how to create a `TextBox` object, set a value, and retrieve it.

## Usage

1. **Initialize a `TextBox` object**: Create an instance of `TextBox`.
2. **Set Value**: Use the `setValue` method to assign a string to the `TextBox`.
3. **Get Value**: Retrieve the stored text using the `getValue` method.

### Example
The following example shows how to use the `TextBox` class in `main.cpp`:

```cpp
#include <iostream>
#include "TextBox.hpp"

int main() {
    TextBox textBox;
    textBox.setValue("Hello, World!");
    std::cout << textBox.getValue() << std::endl;
    return 0;
}
```
### Expected Output
Hello, World!


Compilation Instructions

To compile and run the project, use the following commands in a terminal:
```cpp
g++ main.cpp TextBox.cpp -o TextBoxApp
./TextBoxApp
```
This will compile main.cpp and TextBox.cpp into an executable named TextBoxApp and run it.

### Project Setup in Xcode

1: Open Xcode and create a new project, selecting Command Line Tool.
2: Add TextBox.hpp and TextBox.cpp to the project.
3: Write your main.cpp file as shown in the example above.
4: Use Product > Build and Product > Run to compile and test the program in Xcode.


### License

This project is open-source and available for modification and use under the MIT License.


