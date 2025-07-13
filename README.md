# C# Mastery

Welcome to **C# Mastery** – your comprehensive learning hub for mastering C# at a senior level. This guide is designed for .NET developers preparing for technical interviews, brushing up on advanced concepts, or transitioning to modern C# (.NET 6/7/8+).

## Latest C# Version Information
The documentation covers up to **C# 12.0** (released with .NET 8.0 in November 2023), including features like:
- Primary constructors
- Collection expressions
- Alias any type
- Default lambda parameters
- Interceptors (experimental)

## View the Learning Materials

### Option A: Read Markdown Files Directly

All documentation is organized in the `docs/` folder:

1. Open the `docs/` directory
2. Start with `index.md` for the recommended roadmap

### Option B: Build Interactive Documentation Website (Recommended)

Create a searchable, styled documentation site locally using **MkDocs** + **Material for MkDocs**.

## Prerequisites

### Python 3.8+ (for MkDocs)

- Download: https://www.python.org/downloads  
- **Important**: Check "Add Python to PATH" during installation  
- Verify installation:  
  ```bash
  python --version
  ```

### .NET SDK (for C# Development)
- Download latest .NET 8.0 SDK: https://dotnet.microsoft.com/download
- Verify installation:
  ```bash
  dotnet --version
  ```

### VS Code (Recommended Editor)

* Download: [https://code.visualstudio.com](https://code.visualstudio.com)
* Recommended extensions:
  - C# Dev Kit
  - Material Theme for MkDocs

### Git

* Download: [https://git-scm.com](https://git-scm.com)
* Verify installation:

  ```bash
  git --version
  ```

## MkDocs Installation and Setup

### 1. Install MkDocs and Material Theme

```bash
pip install mkdocs mkdocs-material
```

For enhanced features, install these additional plugins:

```bash
pip install mkdocs-minify-plugin mkdocs-redirects mkdocs-git-revision-date-plugin
```

### 2. Clone the Repository

```bash
git clone https://github.com/yourusername/CSharpMastery.git
cd CSharpMastery
```

### 3. Serve the Documentation Locally

```bash
mkdocs serve
```

Access your site at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

### Build Static Site for Deployment

```bash
mkdocs build --clean
```

* Outputs to the `site/` directory (ready for GitHub Pages or other hosting)

## Troubleshooting

| Issue                 | Solution                                                             |
| --------------------- | -------------------------------------------------------------------- |
| MkDocs not found      | `python -m pip install --upgrade mkdocs`                             |
| Material theme errors | `pip install --force-reinstall mkdocs-material`                      |
| Python not recognized | Reinstall Python with PATH enabled                                   |
| Broken links          | Run `mkdocs build --strict`                                          |
| .NET version mismatch | Update to latest .NET 8.0 SDK                                        |

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Open a Pull Request

## License

Open-source under the [MIT License](LICENSE)
