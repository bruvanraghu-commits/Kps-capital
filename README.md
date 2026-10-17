# KP Sanghvi Venture Capital

Static landing page for the KP Sanghvi Group venture capital platform.

## Files

- `index.html` is the main Venture Capital page.
- `where-we-invest.html` is the sector page.
- `assets/kps-logo.png` is the logo.

Everything else (styles, animation, the stage tabs script) is inside the two HTML files. The only external request is Google Fonts (Jost).

## Change the hero banner

Open `index.html` and find `<body data-hero="flow">`. Change the value to one of:

- `flow` for Flow Lines (current)
- `seed` for Seed to Legacy
- `globe` for Golden Globe
- `constellation` for Constellation

## Publish with GitHub Pages

1. Push these files to the root of a repository.
2. In the repository, open Settings, then Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then Save.

The site will be live at `https://<your-username>.github.io/<repository-name>/` within a minute or two.
