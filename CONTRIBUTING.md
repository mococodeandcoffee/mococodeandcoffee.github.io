# Contributing to Moco Code & Coffee

## Adding Your Project to the Gallery

Want your project featured on the [Project Gallery](https://mococodeandcoffee.github.io/project-gallery/)? Great! Here's how:

### 1. Fork and clone the repo

Fork this repository on GitHub, then clone your fork locally:

```
git clone https://github.com/YOUR-USERNAME/mococodeandcoffee.github.io.git
cd mococodeandcoffee.github.io
```

### 2. Add your project to `_data/projects.yml`

Open `_data/projects.yml` and add an entry for your project at the end of the file:

```yaml
- name: Your Project Name
  author: Your Name
  description: A short description of what your project does.
  link: "https://your-project-url.com"
  image: /assets/img/projects/your-image.png
```

**Required:** `name`, `author`, `description`, `link` (URL to your project or repo), `image` (see step 3)

### 3. Add an image (optional)

Add a screenshot or logo to `assets/img/projects/` and reference it in your entry:

```yaml
image: /assets/img/projects/your-image.png
```

Images work best at a 16:9 ratio.

### 4. Preview your changes locally

```
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/project-gallery/` to see your project in the gallery.

### 5. Open a pull request

Push your changes to your fork and open a pull request against the `main` branch of this repo. Include a brief description of your project in the PR.

---

Questions? Reach out via the [contact page](https://mococodeandcoffee.github.io/contact/) or find us at a meetup!
