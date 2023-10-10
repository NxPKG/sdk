# NxPKG SDK

The NxPKG JavaScript SDK lets you programmatically create NxPKG projects to be opened in a new window or embedded in your docs, example pages, or blog posts.

## Documentation

Check out our SDK documentation on developer.nxpkg.khulnasoft.com:

- [SDK overview](https://developer.nxpkg.khulnasoft.com/platform/api/javascript-sdk)
- [Options reference](https://developer.nxpkg.khulnasoft.com/platform/api/javascript-sdk-options)
- [Controlling embeds](https://developer.nxpkg.khulnasoft.com/platform/api/javascript-sdk-vm)

## Reporting issues

- Issues with the SDK can be filed at https://github.com/nxpkg/sdk/issues
- Other issues with NxPKG can be filed at https://github.com/nxpkg/core/issues

## Development

We use `npm` and Node 16+.

```sh
# Install dependencies
npm install

# Start a development server to explore examples
npm start

# Run unit tests
npm test

# Run end-to-end tests with mock server
npm run test:e2e

# Run end-to-end tests against nxpkg.khulnasoft.com
NXPKG_SERVER_ORIGIN=https://nxpkg.khulnasoft.com npm run test:e2e

# Generate the 'bundles' and 'types' folders
npm run build
```
