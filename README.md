# Gaurav Gawade Static Site

This repository contains the source for a small personal website. The files
have been organised for clarity and maintainability.

## Directory Structure

```
assets/          Static assets such as CSS files
  css/
public/          HTML pages served by the site
  blogs/
 docs/           Documentation or additional resources
```

## Setup

No build step is required. You only need a simple HTTP server to view the site
locally. Python's built‑in module works well:

```bash
python3 -m http.server --directory public
```

The site will be available at `http://localhost:8000`.

## Usage

Navigate to `index.html` for the homepage. Links between pages are relative and
should work when served from the `public` directory.

## Contributing

1. Fork the repository and create your branch.
2. Make changes with clear commit messages.
3. Submit a pull request explaining your changes.

## Deployment

Copy the contents of the `public` directory (and the `assets` directory) to your
web server's document root. Ensure the file structure is preserved.

## License

This project is licensed under the terms of the MIT License found in the
[LICENSE](LICENSE) file.
