# Rust Tax Calculator - Getting Started

## Step 1: Initialize Rust project in existing directory
```bash
cargo init
```
This will create the Rust project files in your current directory instead of creating a new folder.

## Step 2: Understand the project structure
After running the command, you'll see:
```
.
├── .gitignore
├── Cargo.toml          <- New file
├── README.md
├── src/                <- New directory
│   └── main.rs         <- New file
└── rust-setup-guide.md
```

## Step 3: Run the default Hello World
The project already contains a Hello World program in `src/main.rs`. Run it with:
```bash
cargo run
```

## Step 4: Alternative - Build and run separately
```bash
# Build the project
cargo build

# Run the compiled binary
./target/debug/rust-tax-calculator
```

## Step 5: Build for production
```bash
cargo build --release
./target/release/rust-tax-calculator
```

## Useful Cargo Commands
- `cargo check` - Check code without compiling
- `cargo build` - Compile the project
- `cargo run` - Compile and run
- `cargo test` - Run tests
- `cargo clean` - Clean build artifacts

## Next Steps
Now you're ready to start building your tax calculator! You can modify `src/main.rs` to add your tax calculation logic.