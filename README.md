# BTC WALLET APP - ICED RS
A simple cross-platform GUI application built with iced, a Rust GUI library focused on simplicity and type-safety, inspired by Elm.

## Features
Cross-platform support: Windows, macOS, Linux, and Web (WASM)

Reactive, type-safe UI programming model

Built-in widgets like buttons and text inputs

Easy to extend with custom widgets

Async actions support with futures

Responsive layout

## Getting Started
### **Step 1: Install Required Modules**
1. Add iced as a dependency in your Cargo.toml:
   cargo.toml
   ```bash
   [package]
   name = "inherit"
   version = "0.1.0"
   edition = "2021"
   
   [dependencies]
   clipboard = "0.5.0"
   iced = { version = "0.12.1", features = ["image", "advanced", "svg", "tokio"] }
   time = "0.3"
   ```
2. Verify installation:
   ```bash
   rustc -v
   ```

### **Step 2: Clone the Repository**

```bash
git clone <repository-url>
cd btc-wallet-iced-app
```

### **Step 3: Install Dependencies & RUN with Cargo**

```bash
cargo run
```


## How it Works
State: The Counter struct holds the application state (the current count and button states).

Messages: The Message enum represents user interactions (button presses).

Update: The update method modifies the state based on messages.

View: The view method builds the UI and connects buttons to messages.

This pattern follows the Elm architecture, making UI logic clear and type-safe.


### **Let's See, how it is working exactly!**
https://github.com/user-attachments/assets/65610021-fd49-4902-b424-7e1036015b74



## License
This project is licensed under the **MIT License**.
