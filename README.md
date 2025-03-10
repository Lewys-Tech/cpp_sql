# MySQL C++ Integration with Dev C++

This repository demonstrates how to work with MySQL using C++ header libraries. It provides a simple example of integrating MySQL into your C++ projects using the Dev C++ IDE. To get started, you will need to connect MySQL using the "libmysql.dll".

---

## Overview

This project shows you how to:
- Include MySQL headers in your C++ code.
- Connect to a MySQL server using the MySQL C API.
- Set up your development environment in Dev C++ with "libmysql.dll".

---

## Prerequisites

- **Dev C++ IDE:** Ensure you have the Dev C++ IDE installed.
- **MySQL Server:** Install MySQL server on your machine.
- **MySQL Connector/C:** This provides the necessary headers and libraries.
- **libmysql.dll:** Download or locate the `libmysql.dll` file, which is essential for connecting to MySQL.

---

## Setup

1. **Configure Dev C++:**
   - Add the path to the MySQL header files (e.g., `mysql.h`) in your project settings.
   - Link against the MySQL library by ensuring your linker settings include the path to the MySQL libraries.

2. **Place libmysql.dll:**
   - Copy the `libmysql.dll` file to your project directory or a system directory where it can be easily found during runtime.

3. **Project Files:**
   - Ensure your source code files include the necessary MySQL headers using `#include <mysql.h>` (or similar based on your installation).

---

## Building and Running

1. **Open the Project:**
   - Launch Dev C++ and open the repository project.

2. **Compile:**
   - Build the project ensuring that the include paths and linker settings are correctly configured.

3. **Run:**
   - Execute the generated binary. Make sure `libmysql.dll` is in the same directory as the executable (or in a path recognized by your system) so that the application can load it at runtime.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **MySQL Team:** For providing the MySQL C API.
- **Dev C++ Community:** For tools and support in C++ development.
