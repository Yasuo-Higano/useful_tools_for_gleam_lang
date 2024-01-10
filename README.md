# Useful tools for Gleam language

## update_gleam_packages_for_now.sh

Script to run when the gleam language has been upgraded but the library package does not support the update and cannot compile.
Running this script in the root directory of the project will execute gleam fix, gleam update for the project in build/packages.
