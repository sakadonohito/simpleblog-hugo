# TechMemo-Hugo

**TechMemo-Hugo** is a minimalist and clean theme for [Hugo](https://gohugo.io/), designed for IT professionals, developers, and tech enthusiasts who want to maintain a personal blog or documentation site.

## Features
- Responsive design optimized for mobile and desktop.
- Simple and clean layout for technical content.
- Syntax highlighting for code snippets.
- Easy customization with CSS and SCSS support.

## Installation

1. Add the theme to your Hugo site:
   ```bash
   git submodule add https://bitbucket.org/your-username/techmemo-hugo.git themes/techmemo-hugo
   ```

2. Update your site's `config.toml` file:
   ```toml
   theme = "techmemo-hugo"
   ```

3. Start the Hugo server:
   ```bash
   hugo server -D
   ```

## Usage

### Creating New Content
Create a new post:
```bash
hugo new posts/my-new-post.md
```
Edit the generated Markdown file under `content/posts/` and add your content.

### Customization
Customize the theme by editing the `static/css/style.css` file or by adding your own SCSS files in the `assets/` directory.

## Contributing
Feel free to submit issues or pull requests if you find bugs or have feature suggestions.

## License
This theme is licensed under the [MIT License](LICENSE).
