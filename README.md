# Coder Open in Coder Button Test

Use this repo to test adding an **Open in Coder** button to a GitHub README.

## 1) Basic button

```md
[![Open in Coder](https://coder.example.com/open-in-coder.svg)](https://coder.example.com/templates/dev-template/workspace)
```

## 2) Button with prefilled repo parameter

```md
[![Open in Coder](https://coder.example.com/open-in-coder.svg)](https://coder.example.com/templates/dev-template/workspace?param.git_repo=https://github.com/your-org/coder-open-in-button-test)
```

## Replace these values

- `https://coder.example.com` -> your Coder access URL
- `dev-template` -> your Coder template name
- `your-org/coder-open-in-button-test` -> your actual GitHub repo path

## Notes

- Your template should include a `git_repo` parameter if you want repo prefill.
- Git auth should be configured in Coder for private repos.
