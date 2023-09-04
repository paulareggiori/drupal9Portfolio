# Drupal9 Portfolio website
This repository contains the files necessary to run a Drupal9 installation on my personal portfolio website.
I built it using a simple Drupal9 recipe from Lando. I used mostly my site building skills to create the views content types needed.
Some contrib modules were also used to make further layout changes [Exclude Node Title](https://www.drupal.org/project/exclude_node_title) and [Linked Field](https://www.drupal.org/project/linked_field).
Also, I used a free custom theme called [Showcase Lite](https://www.drupal.org/project/showcase_lite) with some minor modifications.

## Demo

https://github.com/paulareggiori/drupal9Portfolio/assets/33421643/43984936-266e-4967-8b2d-a7f0b8acbc38

Visit the live site (druapl8 version) here: https://www.preggiori.eu/
## Setup

1. First install Lando:
Install Lando for your OS: https://docs.lando.dev/basics/installation.html
2. Clone this repository
  git clone https://github.com/paulareggiori/drupal9Portfolio.git
3. Run cd drupal9Portfolio to enter the folder
4. Run lando start
5. Run lando db-import ./artifacts/full_database.sql --host database
6. Run lando drush cr && lando drush updb --no-post-updates -y
7. Run lando info to check the local host path or the lando url and enjoy browsing.

## Creator: Paula Reggiori

This repository has no intention on monetizing on its contents in any way, shape or form. The main goal is to expand and practice skills.
