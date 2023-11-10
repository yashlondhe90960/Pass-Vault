# Password vault made with Rust.

## Table of Contents


---

## 1. Introduction <a name = "intro"></a>

Password Vault is a cli password management tool written in Rust. It allows users to securely store and manage their passwords for various services. This manager uses JSON files to store the password entries.


## 2. Features < a name= "features">>/a>

- Add new password entries with service name, username and password.
- List all stored enties.
- Search for entries based on service name.
- Securely stores passwords in a JSON File.

## 3. Dependencies <a name= "dependencies"></a>

The project relies on Rust and Cargo for dependency management.

## 4. Usage <a name="usage"></a>

To run the program, execute the compiled binary. It will display a menu with options to perform various tasks.  

### Menu Options <a name="menu-options"></a>

1. **Add Entry**: Allows the user to add a new password entry by providing the service name, username, and password.
2. **List Entries**: Displays a list of all stored password entries.
3. **Search**: Allows the user to search for entries based on the service name.
4. **Quit**: Exits the program.


<!--https://github.com/yashlondhe90960/Pass-Vault-->
## 5. How to Build and Run <a name="how-to-build-and-run"></a>

To build and run the project, follow these steps:

1. Clone the project from [https://github.com/yashlondhe90960/Pass-Vault](https://github.com/yashlondhe90960/Pass-Vault).
2. Navigate to the project directory in the terminal.
3. Run `cargo build --release` to compile the project.
4. Run `./target/release/rusty_vault` to execute the compiled binary.

## 6. Contributing <a name="contributing"></a>

If you would like to contribute to this project, feel free to submit pull requests or open issues on the project's repository.
