# Drupal contrib environment
This repo provides a Drupal contrib environment based on the Drupal recommended project. It will prefer source install for Drupal projects, including core. It also includes useful tooling and scripts to support development.

## Usage

### Checking out a project
The project is already configured to install projects via Composer, preferring the `source` install method for Drupal project. This will get the Git repository for the project. Any other dependencies will be installed with the `dist` method. If you need to work on a project that is not in the `drupal` project space, use the Composer `require` command with the `--prefer-install=source` option.

## Local environment
A DDEV config file is included. Running `ddev` start should spin up an appropriate development environment using DDEV and Docker.
