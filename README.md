
# Academic Portfolio

This is a personal academic portfolio built with [Jekyll](https://jekyllrb.com/). It showcases my academic work, projects, research, and more. The portfolio is fully customizable for anyone to use as a template for their own portfolio.

## Features

- Clean and simple design
- Easy to customize content (projects, research, blog, etc.)
- Mobile-friendly design
- Supports markdown for easy writing of blog posts and pages

## Requirements

Before you can run the project locally, make sure you have the following installed:

- **Ruby** (Version 3.x.x or higher)
- **RubyGems**
- **Bundler** (Run `gem install bundler` to install it)
- **Jekyll** (Can be installed through the Gemfile)

## Setup Instructions

### 1. Clone the Repository

Clone the repository to your local machine using Git:

```bash
git clone https://github.com/yourusername/academic-portfolio.git
cd academic-portfolio
```

### 2. Install Dependencies

Run the following command to install all the necessary Ruby gems for the project:

```bash
bundle install
```

This will install Jekyll, its dependencies, and other required gems.

### 3. Run the Site Locally

To start a local server and view the portfolio, run:

```bash
bundle exec jekyll serve
```

Once the server is running, you can open your browser and navigate to `http://127.0.0.1:4000/academic-portfolio/` to view your local version of the portfolio.

### 4. Customize the Portfolio

- **Content**: Edit the `.md` files inside the project to modify the portfolio content (e.g., `about.md`, `projects.md`, etc.).
- **Layout and Design**: Modify the `_layouts/` and `_includes/` files to change the structure and design.
- **Configuration**: Change site-wide settings in the `_config.yml` file (title, description, etc.).

### 5. Build for Production

Once you're ready to deploy your portfolio, you can build the static files by running:

```bash
bundle exec jekyll build
```

This will generate the static site in the `_site/` folder, ready for deployment.

## Troubleshooting

- **Missing Gems**: If you encounter any missing gems, try running `bundle install` again. If you are on Windows, you might also need to install the `wdm` gem:

```bash
gem install wdm
```

- **Permissions Issues**: If you have permission issues when installing gems, try using `sudo` on Linux/macOS:

```bash
sudo bundle install
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
