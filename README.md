# Rust-based Text Summarizer

Rust-based text summarizer that reads a file, processes it using a basic TF-IDF scoring algorithm, and outputs a concise summary. Built for integration with the Wiki-brief Rust backend.

---

## Features

- Summarizes `.txt` files using Term Frequency–Inverse Document Frequency (TF-IDF)
- Extracts and scores sentences by relevance
- Selects top 10 most informative sentences

---

## Build and Run

Ensure [Rust is installed](https://www.rust-lang.org/tools/install).

### 1. Build the Project

```bash
cargo build
```

### 2. Run the Summarizer and target a text file in root directory

```bash
cargo run -- example.txt
```

If no filename is provided, it defaults to `example.txt`.

---

## Example

Given `example.txt` (about turtles), the output might be:

```bash
Summary:
Turtles are reptiles of the order Testudines, known for their distinctive shells formed from their ribs and other bones. They breathe air and lay their eggs on land, even though many species live in or near water. ... [etc.]
```
