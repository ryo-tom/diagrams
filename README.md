# diagrams

This repository is dedicated to managing diagrams created with the [Draw.io Integration extension for VS Code](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio). By using `.drawio.svg` as the primary format, ensuring diagrams are lightweight, version-control friendly, and previewable directly on GitHub.

---

## 📂 Directory Structure

- The repository organizes diagrams into directories based on related groups or topics.
- `_exports/`: Reserved for additional exports, if needed (e.g., `.png`, `.pdf`).

---

## 📋 File Types Managed

| File Type         | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `.drawio.svg`      | Primary format: lightweight, version-control friendly, and GitHub-previewable. |
| `.drawio`          | Not used because it is not previewable on GitHub.                          |
| `.drawio.png`      | Not used due to larger file size.                                          |
| `.drawio.pdf`      | Used sparingly for documentation or external sharing, if needed.           |

---

## 🚀 Usage

### 1. Create and Edit Diagrams

1. Install the [Draw.io Integration extension](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) in VS Code.
2. Open or create `.drawio.svg` files in the `/diagrams` directory.
3. Edit your diagram directly in VS Code.

### 2. Save as `.drawio.svg`

- Always save diagrams in `.drawio.svg` format. This ensures:
  - **Previewability**: Diagrams can be viewed directly on GitHub.
  - **Lightweight Files**: Smaller size than `.png` or `.pdf`.
