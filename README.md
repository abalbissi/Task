## Project Description

I solved this task by making the following modifications to my WordPress project:

- Added custom code to the `functions.php` file located in `(wp-content/themes/hello-elementor)`.

- Created a new custom post type called "Project" with a custom icon.

- Implemented custom taxonomies for categorizing the projects.

- Added a shortcode for displaying the projects.

- Displayed the projects on the home page using the `[project-list]` shortcode.

## Running the Project

If you want to run this project on your own machine, follow these steps:

1. Clone this project.

2. Download and install XAMPP.

3. Place the project files inside the `htdocs` directory of your XAMPP installation.

4. Start the Apache and MySQL services using XAMPP.

5. Import the database backup using the import process in PHPMyAdmin.

## Note on Custom Post Types and Taxonomies

If you prefer to add custom post types with taxonomies without coding, you can use one of the following plugins:

- [Custom Post Type UI Plugin (CPT Plugin)](https://wordpress.org/plugins/custom-post-type-ui/)
- [JetEngine Plugin](https://wordpress.org/plugins/jetengine/)

In this project, I didn't use any plugins for this purpose.
