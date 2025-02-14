# My personal website

## Overview
This repository contains the source code for my personal website, hosted on GitHub Pages with a custom domain purchased from Porkbun. Please, check how it looks [here](paulaluvini.com).

## Repository Structure
```
├── CNAME                    # Custom domain configuration
├── index.html               # Main webpage
├── styles.css               # Stylesheet for website design
├── mail.php                 # Handles contact form submissions
├── Paula_Luvini_CV.pdf      # My updated CV available for download
├── pics/                    # Folder containing images used on the site
└── README.md                # This file
```

## Custom Domain Configuration
- The `CNAME` file ensures that the website is accessible at your custom domain.
- Make sure the domain is correctly set up in Porkbun’s DNS settings:
  - Create a CNAME record pointing to `yourusername.github.io`
  - Add A records pointing to GitHub's IPs. Check Github's [instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) for more information.
