# Change Log
All notable changes to this project will be documented in this file.

## [0.0.4] - 10/05/2017 - Fourth Release
### Added
  * New *fuse-uninstall* role to uninstall Fuse Standalone instances

### Changed
  * Renamed variables from uppercase to lower case (JAVA_HOME, FUSE_HOME)
  * fuse-standalone playbook
    * Optimized upload Fuse binary tasks to inventory hosts.
    * Define an A-MQ Master/Slave topology
  * Documentation

### Removed

### Pending
  * Handlers to refresh URL feature repositories in runtime
  * Role to check health and status of each Fuse instance. Apply restart actions.
  * Apply some Ansible best practices

## [0.0.3] - 28/04/2017 - Third Release
### Added
  * Deploy bundles using *osgi:install* commands
  * Undeploy bundles using *osgi:uninstall* commands
  * New Ansible versions tested

### Changed
  * Playbooks: fuse-deploy-bundle.yaml, fuse-undeploy-bundle.yaml
  * Documentation

### Removed

### Pending
  * Handlers to refresh URL feature repositories in runtime
  * Role to check health and status of each Fuse instance. Apply restart actions.
  * Apply some Ansible best practices

## [0.0.2] - 27/04/2017 - Second Release
### Added
  * Templates to define another Maven Repository to resolve dependencies in Fuse
  * Reset some facts before or after where they are used to be defined in next executions
  * *fuse_client* variable to define Fuse Client to execute karaf commands
  * *features* and *features_undeploy* variables to define Features to install or uninstall
  * Tasks to deploy bundles, feature repositories and features
  * Tasks to undeploy bundles, features and feature repositories
  * Playbooks: fuse-install-os1.yaml

### Changed
  * Variable renamed *APP_HOME* to *app_home*
  * Playbooks: fuse-install.yaml, fuse-deploy-bundle.yaml, fuse-undeploy-bundle.yaml
  * Documentation

### Removed

### Pending
  * Handlers to refresh URL feature repositories in runtime
  * Apply some Ansible best practices

## [0.0.1] - 24/04/2017 - First Release
### Added
  * Initial version
  * Roles created: fuse-standalone, fuse-deploy-bundle, fuse-undeploy-bundle
  * Global variables in *groups_vars* folder
  * Playbooks: fuse-install, fuse-cd-apps
  * Documentation

### Changed

### Removed

### Pending
