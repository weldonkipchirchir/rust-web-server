
# Rust Web Server with Thread Pool

This project demonstrates a simple web server written in Rust using a thread pool for handling incoming connections concurrently.

## Features

- **HTTP Server**: Accepts HTTP requests and serves corresponding responses.
- **Thread Pool**: Utilizes a thread pool to handle multiple connections concurrently.
- **Static File Serving**: Serves static HTML files based on the requested URL.
- **Delayed Response**: Demonstrates handling long-running tasks by delaying the response for specific requests.

## Getting Started

### Prerequisites

- Rust programming language and Cargo build system installed on your system.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/weldonkipchirchir/rust-web-server.git
   ```

2. Navigate to the project directory:

   ```bash
   cd rust-web-server
   ```

3. Build the project using Cargo:

   ```bash
   cargo build --release
   ```

### Usage

1. Run the compiled binary:

   ```bash
   ./target/release/rust-web-server
   ```

2. Access the web server using a web browser or a tool like cURL:

   ```bash
   curl http://localhost:7878
   ```

## Configuration

- By default, the web server binds to `127.0.0.1` on port `7878`. You can change this configuration in the `main` function of the `src/main.rs` file.

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests for any improvements or fixes you'd like to see.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project is inspired by [The Rust Programming Language](https://www.rust-lang.org/)'s book.
