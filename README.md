# Git hooks

Useful hooks for GIT.

## Install

Copy the hook files into your .git/hooks/ directory, set up the config file and
enable the hooks you want by renaming the sample hooks and adding the path to the
hook you want to use.

## Config

You can configure the hooks in git-hooks.config

## Available hooks

* pre-commit hook for PHP CodeSniffer - It will not allow you to commit if the PHP
file contains any coding standard violation.
