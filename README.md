
# Hugo-mock-landing-page-autodeployed

This repository automates the deployment of [hugo-mock-landing-page](https://github.com/nilla-moige/hugo-mock-landing-page) which is a hugo static website, GitHub Actions and GitHub Pages. Every time a change is pushed to the `main` branch, the site is automatically built and published.  

## Deployment URL

Once deployed, the website is accessible at:  

<https://nilla-moige.github.io/hugo-mock-landing-page-autodeployed/>

## Insights from Claude( summary of the YAML workflow)

It automates building and deploying a Hugo website to GitHub Pages

**Key Components**:

- Triggers on push to `main` branch
- Runs on Ubuntu 22.04
- Uses Hugo version 0.144.1 (extended)

**Steps**:

1. Checkout repo (includes themes and full git history)
2. Set up Hugo environment
3. Build static files with minification
4. Deploy to `gh-pages` branch

**Workflow Pattern**:
Push to `main` → Build with Hugo → Auto-deploy to `gh-pages` → Live on GitHub Pages

## Contact

For questions or feedback, reach out via [GitHub Issues](https://github.com/nilla-moige/hugo-mock-landing-page-autodeployed/issues).
