# QR Code Generator

## Description

This project is a simple QR Code Generator that converts a user-entered URL into a QR code image. It also saves the entered URL in a text file. The project uses Node.js along with `inquirer` for user prompts, `qr-image` for QR code generation, and the native `fs` module for file system operations.

## Features

1. **User Prompt for URL**: The project uses `inquirer` to prompt the user to enter a URL.
2. **QR Code Generation**: The entered URL is converted into a QR code image using the `qr-image` package.
3. **URL Storage**: The URL is also stored in a text file for reference.
