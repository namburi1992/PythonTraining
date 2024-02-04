Certainly! Below is a beginner-friendly course content for teaching variables and data types in Python using Markdown.

### Module: Variables and Data Types

#### 1. Introduction to Variables
- **Definition**: A variable is a container that stores data values and gives them a name.
- **Why use variables?**: To store and manage information in a program.
- **Naming conventions**: Follows rules like starting with a letter, no spaces, and using underscores for multiple words.

#### 2. Data Types in Python
- **Common Data Types**:
  - **Integer (int)**: Whole numbers without decimals.
    ```python
    age = 25
    ```

  - **Float**: Numbers with decimals.
    ```python
    height = 5.9
    ```

  - **String (str)**: Text or characters enclosed in quotes.
    ```python
    name = "Alice"
    ```

  - **Boolean (bool)**: Represents either True or False.
    ```python
    is_student = True
    ```

#### 3. Declaring Variables
- **Syntax**:
  ```python
  variable_name = value
  ```

- **Examples**:
  ```python
  # Integer variable
  age = 25

  # Float variable
  height = 5.9

  # String variable
  name = "Alice"

  # Boolean variable
  is_student = True
  ```

#### 4. Type Conversion
- **Changing Data Types**:
  - **Implicit Conversion**: Automatically done by Python.
    ```python
    num1 = 5
    num2 = 2.5
    result = num1 + num2  # Implicitly converts num1 to float
    ```

  - **Explicit Conversion**: Done by the programmer using built-in functions.
    ```python
    num_str = "10"
    num_int = int(num_str)  # Explicitly converts string to integer
    ```

#### 5. Printing Variables
- **Using `print()` Function**:
  ```python
  # Printing variables
  age = 25
  print("Age:", age)
  ```
