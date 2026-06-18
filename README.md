## Uninstall apps

A simple workflow for uninstalling apps in your macOS using [Alfred](https://www.alfredapp.com/).

### Usage

1. Download the **Uninstall Apps** workflow from the [releases page](https://github.com/hildersantos/alfred-workflows-uninstall-apps/releases).
2. Double-click the downloaded `.alfredworkflow` file to install it in Alfred.
3. Configure the trigger for uninstalling apps (defaults to `un`).
4. Profit.

### How it works

The workflow works by searching for app files in your `/Applications` and `~/Applications` folder and running a simple script to send the selected app to the bin.

Keep in mind that this app just moves the app to the bin; it doesn't delete it completely. I've chosen to keep the workflow like this to revert any unexpected removal.
