# Portfolio Assignment Instructions

This is a template for you to start building your professional portfolio. It is also part of your journey at MAE and will be reviewed, as needed, by your instructor and the Undergraduate Program Office.

## Getting Started

1. Accept the assignment through the GitHub Classroom link you were provided.
2. After accepting, your personal portfolio repository will be created.
3. Clone your repository to your local machine:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

## Personalizing Your Portfolio

### Homepage
- `index.md`: Replace the placeholder text with a welcome or pitch paragraph about yourself.
- `assets/images/profile-pic.jpg`: Replace the placeholder with a portrait of yourself.

### Projects
- In the `_projects` folder: Use the provided example pages (e.g., `2022-trig-analysis.md`) to build one page per project.
- Each project has a main (square) project image, set in the page's top matter by the `image` variable.
- All images are in `assets/images`. Delete the ones you don't need.
- It is useful to name the page with a leading date. This will determine the order of projects on your main portfolio gallery.

### CV
- `assets/CV.pdf`: Replace this placeholder with your own PDF CV.

## Running the Site Locally

To test your changes locally:

```bash
bundle exec jekyll serve
```

Once everything looks good, commit and push your changes:

```bash
git add .
git commit -m "Completed portfolio"
git push origin main
```

Your portfolio will be live at:

```php
https://<your-username>.github.io/<your-repo>/
```

## Using Other Jekyll Themes

You can customize your portfolio by using other Jekyll themes. Here are some good places to find themes:

- [Start Bootstrap](https://startbootstrap.com/themes/jekyll/)
- [Jekyll Themes](https://jekyllthemes.io/)
- [Jekyll Theme](http://jekylltheme.org/)
- [Jekyll Themes on GitHub](https://github.com/topics/jekyll-theme)

To use a different theme:

1. Find a theme you like from one of the sources above.
2. Follow the theme's installation instructions, usually involving updating the `_config.yml` file and adding the theme's files to your repository.
3. Customize the theme as needed to fit your portfolio content.

## Choosing the Skin

Some Jekyll themes come with multiple skins (color schemes). To choose a skin:

1. Open the `_config.yml` file.
2. Look for the `skin` or `color_scheme` setting.
3. Change the value to the desired skin name. Refer to the theme's documentation for available skin options.

Example:

```yaml
skin: dark
```

This will apply the dark skin to your portfolio site.

Happy theming!