This repository contains design tokens exported from Figma and transformed into various platform-specific formats using Style Dictionary.

What are Design Tokens?
Design tokens are the style values of your design system, such as colors, typography, spacing, etc., defined in a structured way. They help ensure consistency across platforms and improve collaboration between designers and developers.

Project Overview
This project uses Style Dictionary to take design tokens exported from Figma and transform them into formats that can be consumed by different platforms, such as CSS, JavaScript, JSON, SCSS, and more.

Directory Structure

├── tokens/                    # Design tokens exported from Figma
│   ├── colors.json             # Color tokens
│   ├── typography.json         # Typography tokens
│   └── spacing.json            # Spacing tokens
├── build/                      # Generated output files
│   ├── css/                    # CSS variables
│   ├── scss/                   # SCSS variables
│   ├── js/                     # JavaScript tokens
│   └── json/                   # JSON tokens
└── README.md                   # Project documentation

