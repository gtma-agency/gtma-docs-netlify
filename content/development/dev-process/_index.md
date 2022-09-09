---
title: "WP Development Process"
date: 2021-01-06T08:16:08-08:00
lastmod: 2021-01-06T08:16:08-08:00
weight: ""
---

### Structure
- Install WordPress
- Set Permalinks
- Make sure search engine bots are discouraged if staging site is online
- Install Plugins
	- ACF
	- Gravity Forms
- Add Custom Post Types
- Add Custom Taxonomies
- Add Custom columns/sorting as needed
- Add Custom filtering with the custom taxonomies.
- Define widget areas
- Stub out Widgets and Shortcodes
- Stub out Page Templates

### Custom Fields
- Create Field Groups for each content block and build out

### Pull Fields into templates
- Pull content block data to template and add basic html structure

### Build nav menu structure
* Add Menu Locations
* Modify nav walker as needed
* Create html structure

## Style
### Set up site variables in `_variables.scss`
- Add theme-colors() from the theme’s color palette
	* Add names so they correspond with the options created in the background color field defined in `basis.php`

- Add fonts
- Add icon sets

## Add Global Styles
- Typography
- Form elements/validation
- Table
- Lists

### Style Header
- Brand
- Navigation
- For mobile first and on up

### Style Footer
- Widget areas
- Mobile and on up

### Style Content Blocks
- Section
- Hero
- Divider
- Post Grid
- Feature
- Custom blocks

### Style Page Templates
Blog Index
Blog Single
Custom Post Types

### Create Integrations
- Marketing automation tools, newsletter signups etc

## Insert Content
## QA/QC
