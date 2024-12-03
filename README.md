The `.plugin.swcrc` file contains the configuration to use the `@swc/plugin-noop`.

Running `swc ./input.js -o output.js --config-file .plugin.swcrc` will trigger SWC to parse the `input.js` file with the plugin, and it will fail.

Running `swc ./input.js -o output.js` will trigger SWC to parse the `input.js` file without the plugin, and it will succeed.
