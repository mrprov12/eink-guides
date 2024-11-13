# einkGuides

![einkGuides](https://eink-guides.info/favicon.ico)  
**Accumulated eInk Device Knowledge**  
A comprehensive guide for eInk devices, including tips, tutorials, and resources for users who want to maximize their eInk device experience.

## Table of Contents
- [About the Project](#about-the-project)
- [Live Website](#live-website)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## About the Project

This project aims to provide an accessible knowledge base for eInk devices, including information on device usage, customization, and advanced features like jailbreaking and document management. The site serves as a single resource to help users get the most out of their eInk devices, whether they are new to eInk or experienced enthusiasts.

## Live Website

Visit the site at: [www.eink-guides.info](https://www.eink-guides.info)

## Features

- **Detailed Guides**: Step-by-step tutorials for setting up, customizing, and enhancing eInk devices.
- **Jailbreaking Information**: Instructions and considerations for users interested in jailbreaking their eInk devices.
- **Navigation Menu**: Simple navigation to different sections of the site.
- **Responsive Design**: Optimized for both desktop and mobile browsing.

## Getting Started Locally

To get a local copy up and running, follow these steps:

### Prerequisites

You'll need [Git](https://git-scm.com) and [Jekyll](https://jekyllrb.com) installed on your local machine.

### Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/eink-guides.git
   cd eink-guides
   ```
2. **Install Dependencies**
Make sure Jekyll is installed, then run:
```
bundle install
```

3. **Run the Local Server**
Start the server to preview the site locally:
```
bundle exec jekyll serve
```

4. Open your browser and go to http://localhost:4000 to view the site.

## Usage
This site is intended to be a resource for users looking to learn about and customize their eInk devices. The site covers topics such as:

Basic Setup: Getting started with your eInk device
Advanced Features: Jailbreaking and custom templates
Device Compatibility: Information on which guides apply to specific eInk devices
Helpful Links: Direct links to external resources and communities
Customization
You can customize this site by modifying the files in the _layouts and _config.yml files. The theme and navigation can be adjusted by editing _config.yml.

### Adding Pages

To add a new page, create a Markdown file (e.g., `new-feature.md`) in the root directory, then add a link to it in `_config.yml` under `header_pages` if your theme supports this feature:

```yaml
header_pages:
  - index.md
  - new-feature.md
```

### Changing the Theme
To update the theme, modify the remote_theme value in _config.yml. This site currently uses the pages-themes/slate theme, but other GitHub Pages themes are available.

### Contributing
Contributions are what make this community resource a valuable asset for eInk device users. To contribute:

1. Fork the Project

2. Create your Feature Branch

```
git checkout -b feature/NewFeature
```

3. Commit your Changes
```
git commit -m "Add NewFeature"
```

4. Push to the Branch
```
git push origin feature/NewFeature
```

5. Open a Pull Request

If you want to contribute, please make a PR and request a review from `mrprov12`.

### License
Distributed under the MIT License. See LICENSE for more information.

### Contact
For any questions or suggestions, please open an issue on this repository.
