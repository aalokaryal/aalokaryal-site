# aalokaryal.com.np

Personal portfolio and CV website for **Aalok Aryal**, Electrical Engineering student at Tribhuvan University, Institute of Engineering (Pulchowk Campus).

🔗 **Live site:** [aalokaryal.com.np](https://aalokaryal.com.np)

**Status:** This project is under active development. Content, features, and design are subject to change as the site continues to evolve.


## About

This site showcases my academic projects, experience, and skills as an electrical engineering student with a focus on power systems and renewable energy — including hydropower and transmission line design work, and other academic and hobby projects. 

## Built With

- [Hugo](https://gohugo.io/) — static site generator
- Custom-adapted layout based on [hugo-profile](https://github.com/gurusabarish/hugo-profile) by Gurusabarish (theme files live at the project root, not as an external `themes/` dependency)
- Hosted on **GitHub Pages**, deployed via **GitHub Actions**
- DNS managed through **Cloudflare**

## Development

To run locally:

```bash
hugo server -D
```

Then visit `http://localhost:1313`.

## Deployment

Pushing to `main` automatically triggers a GitHub Actions workflow (`.github/workflows/hugo.yml`) that builds the site with `hugo --minify` and deploys it to GitHub Pages.

## Contact

- Email: aalokaryal9@gmail.com
- LinkedIn: [linkedin.com/in/aalokaryal](https://linkedin.com/in/aalokaryal)
- GitHub: [github.com/aalokaryal](https://github.com/aalokaryal)