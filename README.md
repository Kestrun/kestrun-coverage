
# Coverage

This repository contains coverage reports, badges, and visualizations for the Kestrun project.

## Overview

- **Coverage Reports:** Generated Cobertura XML files are available in the `docs/` directory, providing detailed line and branch coverage statistics for the codebase.
- **Badges:** SVG badges for line, branch, method, and combined coverage are included for use in documentation, dashboards, or CI/CD pipelines.
- **Visualization:** The `index.html` page offers a modern, animated interface for viewing coverage status and progress.

## Directory Structure

- `docs/`
- `Cobertura.xml`: Main coverage report in Cobertura format.
      - `badge_*.svg`: Coverage badges for various metrics.
      - `class.js`: JavaScript for interactive coverage visualization.
      - `icon_*.svg`: Icons for UI elements.
      - `index.html`: Landing page for coverage visualization.
- `README.md`: This file.
- `CNAME`: Custom domain configuration for GitHub Pages.

## Usage

To view the coverage dashboard, open `index.html` in your browser or visit the published GitHub Pages site (if configured).

Badges can be embedded in your project documentation as follows:

```markdown
![Line Coverage](docs/badge_linecoverage.svg)
![Branch Coverage](docs/badge_branchcoverage.svg)
```

## Coverage Summary

- **Line Coverage:** ~71%
- **Branch Coverage:** ~67%
- **Lines Covered:** 4560 / 6414
- **Branches Covered:** 1607 / 2402

(See `docs/Cobertura.xml` for full details.)

## License

Some files (e.g., `class.js`) include third-party code under MIT or WTFPL licenses. See file headers for details.
