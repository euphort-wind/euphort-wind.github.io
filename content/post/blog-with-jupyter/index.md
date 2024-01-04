---
title: 🇦🇽 Åland Islands 
date: '2023-12-30'
summary: Trip to Ålands
---

{{<gallery album="demo" view="card">}}

gallery_item:
  - album: demo
    image: chris.jpg
    caption: Write your image 1 caption here
  - album: demo
    image: dan.jpg
    caption: Write your image 2 caption here    

## Organize your notebooks

Place the notebooks that you would like to publish in a `notebooks` folder at the root of your website.

## Import the notebooks into your site

```bash
pipx install academic
academic import 'notebooks/**.ipynb' content/post/ --verbose
```

The notebooks will be published to the folder you specify above. In this case, they will be published to your `content/post/` folder.
