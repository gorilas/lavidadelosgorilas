# La vida de los gorilas

A simple static Spanish poetry/aphorisms website, "En la jungla de Internet desde 2001".

## Project Structure

- `index.html` — Main page with a collection of Spanish aphorisms/poems
- `home.html` — Hosting provider placeholder page (not the main content)
- `favicon.ico` — Site favicon

## Running the Site

The site is served via Python's built-in HTTP server on port 5000:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a static site deployment with `publicDir: "."`.
