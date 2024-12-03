The `.plugin.swcrc` file contains the configuration to use the `@swc/plugin-noop`.

Running `npm run build` will trigger SWC to parse the `input.js` file with the plugin, and it will fail.

Running `npm run buildWithoutPlugin` will trigger SWC to parse the `input.js` file without the plugin, and it will succeed.
