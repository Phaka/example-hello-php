# Hello World in PHP

A minimal "Hello, World!" implementation in PHP. PHP is a widely-used programming language that powers much of the web. While originally designed as a template language for web pages, PHP has evolved into a full-featured programming language that can be used for web development, command-line scripting, and general-purpose programming.

## Installation

### macOS
Using Homebrew:
```bash
brew install php
```

### Linux
Ubuntu/Debian:
```bash
sudo apt-get update
sudo apt-get install php-cli
```

Fedora/RHEL:
```bash
sudo dnf install php-cli
```

### Windows
Download the PHP installer from the official Windows downloads at [windows.php.net](https://windows.php.net/download/).

## Running

Execute the script directly with the PHP CLI:
```bash
php main.php
```

Or make it executable and run:
```bash
chmod +x main.php
./main.php
```

## Code Explanation

The program demonstrates PHP's basic syntax. It begins with a shebang line for direct execution on Unix-like systems, followed by the PHP opening tag `<?php`. The script uses the `echo` statement, which is one of PHP's basic output functions. The `\n` character adds a newline to the output, which is particularly important when running PHP from the command line rather than generating web output.
