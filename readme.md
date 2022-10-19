# ISU Profile Plugin

## Description

Show/hide Personal Profile Pages(custom posts).
Manage your Personal Profile Pages and enable or disable Directory gutenberg block.

## Installation

1. Upload the plugin files to the `/wp-content/plugins/` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

### Install via composer

`composer require iastate/wordpress-profile-plugin`

## Development

### Versioning

Releases for this project should follow [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Steps when releasing:

- Update isu-profile-cpt.php with the new release version, ie `1.0.1`.
- Commit (or merge) and push master to origin.
- Tag `1.0.1` (the new release version), and push to origin. The tag is what composer uses to define a new release.