# Coder Open in Coder Button Test

Use this repo to test adding an **Open in Coder** button to a GitHub README.

## Rendered button example

[![Open in Coder](https://raw.githubusercontent.com/coder/coder/main/docs/images/templates/open-in-coder.svg)](https://coder.example.com/templates/dev-template/workspace)

## 1) Basic button Markdown

```md
[![Open in Coder](https://coder.example.com/open-in-coder.svg)](https://coder.example.com/templates/dev-template/workspace)
```

## 2) Button with prefilled repo parameter Markdown

```md
[![Open in Coder](https://coder.example.com/open-in-coder.svg)](https://coder.example.com/templates/dev-template/workspace?param.git_repo=https://github.com/your-org/coder-open-in-button-test)
```

## Replace these values

- `https://coder.example.com` -> your Coder access URL
- `dev-template` -> your Coder template name
- `your-org/coder-open-in-button-test` -> your actual GitHub repo path

## Notes

- The rendered example above uses a public SVG so the button is always visible on GitHub.
- In production, use `https://YOUR_ACCESS_URL/open-in-coder.svg`.
- Your template should include a `git_repo` parameter if you want repo prefill.
- Git auth should be configured in Coder for private repos.
