# CSharpMastery

Welcome to **CSharpMastery** – your comprehensive learning hub for mastering C# at a senior level. This guide is designed for .NET developers preparing for technical interviews, brushing up on advanced concepts, or transitioning to modern C# (.NET 6/7/8+).

## View the Learning Materials

### Option A: Read Markdown Files Directly

All documentation is organized in the `docs/` folder:

1. Open the `docs/` directory
2. Start with `index.md` for the recommended roadmap

### Option B: Build Interactive Documentation Website (Recommended)

Create a searchable, styled documentation site locally using **MkDocs** + **Material for MkDocs**.

## Prerequisites

### Python 3.8+

- Download: https://www.python.org/downloads  
- **Important**: Check "Add Python to PATH" during installation  
- Verify installation:  
  ```bash
  python --version

### VS Code (Recommended Editor)

* Download: [https://code.visualstudio.com](https://code.visualstudio.com)

### Git

* Download: [https://git-scm.com](https://git-scm.com)
* Verify installation:

  ```bash
  git --version
  ```

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/CSharpMastery.git
cd CSharpMastery
```

### 2. Set Up Python Environment

```bash
python -m pip install --upgrade pip
pip install mkdocs mkdocs-material mkdocs-minify-plugin
```

### 3. Build and Serve the Documentation

```bash
mkdocs serve
```

Access your site at: [http://127.0.0.1:8000](http://127.0.0.1:8000)


## Troubleshooting

| Issue                 | Solution                                                             |
| --------------------- | -------------------------------------------------------------------- |
| MkDocs not found      | `python -m pip install --upgrade mkdocs`                             |
| Plugin errors         | `pip install --force-reinstall mkdocs-material mkdocs-minify-plugin` |
| Python not recognized | Reinstall Python with PATH enabled                                   |
| Broken links          | Run `mkdocs build --strict`                                          |

## Advanced Usage

### Build Static Site

```bash
mkdocs build --clean
```

* Outputs to the `site/` directory

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Open a Pull Request

## License

Open-source under the [MIT License](LICENSE)
