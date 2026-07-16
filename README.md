# Marin Bricq - Academic Portfolio

Source code for my personal academic website, hosted at [mbricq.github.io](https://mbricq.github.io). 

This repository contains my portfolio, publications, and projects related to my PhD research in Mechanical Engineering and Bio-engineering at Politecnico di Milano. The site highlights my work on active inference, collaborative robotics, and the SERENA upper-limb cable-driven soft silicone exosuit.

## Local Development

This website is built using [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme. The easiest and cleanest way to run the site locally without configuring Ruby dependencies is by using Docker Compose.

### Prerequisites
* [Docker](https://docs.docker.com/get-docker/) installed and running.

### Quick Start
1. Clone the repository:
   ```bash
   git clone [https://github.com/MBricq/mbricq.github.io.git](https://github.com/MBricq/mbricq.github.io.git)
   cd mbricq.github.io

```

2. Start the local server:
```bash
docker compose up
```


3. Open your browser and navigate to `http://localhost:8080`.

The Docker container watches the directory, so the site will automatically rebuild whenever you save changes to your `.md`, `.bib`, or `_config.yml` files.

## Deployment

The site is automatically built and deployed via GitHub Pages using GitHub Actions. Any commit pushed to the main branch will trigger the custom deployment workflow and update the live website within a few minutes.

## Acknowledgements

This website is powered by the [al-folio](https://github.com/alshedivat/al-folio) theme, a beautiful and feature-rich Jekyll template designed for academics.

```
