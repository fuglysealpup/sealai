# Sealai LLC — Website

Official website for [Sealai LLC](https://www.sealai.org), hosted via GitHub Pages.

## Deployment

This site is automatically deployed via GitHub Pages. Any push to `main` will update the live site.

## Custom Domain

The `CNAME` file configures GitHub Pages to serve this site at `www.sealai.org`.

### DNS Setup (GoDaddy)

Add these records in GoDaddy DNS:

| Type  | Name | Value                    |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| CNAME | www  | yourusername.github.io   |

Replace `yourusername` with your GitHub username.
