# My first module

--vv--

# Drupal root directory
- index.php
- core directory
- sites directory
- modules, themes, profiles directories

![Module directories](lesson-1/slides/images/files-drupal-root.png) <!-- .element: style="width: 30%;" -->

--vv--

# Module directory
- Custom modules in `modules/custom`
- Module directory = module name

![Module directories](lesson-1/slides/images/files-root-modules.png) <!-- .element: style="width: 30%;" -->

--vv--

# Module directory
- MODULE.info.yml
- src
- config
- MODULE.*.yml
- MODULE.install
- MODULE.module

![Module directory content](lesson-1/slides/images/files-module.png) <!-- .element: style="width: 20%;" -->

--vv--

# Name space
- module name = name space
- Configuration
- Routes
- Services
- Content entity
- URLs
- CSS classes/id's 
- Procedural function names

--vv--

# Exercise
Create a new Drupal module in which we will collect some general helpers that can be used in different projects.

- Create a new Drupal module.
- More exercise details in: <br>_exercises/1 first module/exercise.php_

--vv--

# Tips
- Use the project or customer name as prefix of all your custom modules (e.g. od_ for Open Drupal).
- Use Drupal Console or Drush 9 to generate a module: <br>http://drupalconsole.com, http://www.drush.org/index.html
