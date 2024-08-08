Vidal Service Discovery for Angular
===

# Use It

Install this library :

    npm install @vidal-community/ng2-discovery

## Angular compatibility

You have to use the `ng2-discovery` version that is compatible with your version of [Angular](https://github.com/angular/angular).

You need `@angular` dependencies in your application to use this library.

Here is the compatibility matrix:

Please use the ng2-discovery branch corresponding to your Angular version.

| ng2-discovery | Angular  | Branch to develop |
|---------------|----------|-------------------|
| ^1            | <=4      | N/A               |
| ^2            | >=6      | N/A               |
| ^3            | >=8.2.0  | N/A               |
| ^4            | >=10.1.0 | N/A               |
| ^5            | >=11.2.0 | N/A               |
| ^12           | >=12     | N/A               |
| ^13           | >=13     | N/A               |
| ^14           | >=14     | N/A               |
| ^15           | >=15     | N/A               |
| ^16           | >=16     | angular16         |
| ^17           | >=17     | angular17         |

See compatible versions on [npm semver calculator](https://semver.npmjs.com).

# Build It

    npm install

# How to build and publish

To publish a pre-release, run:

    npm run build-and-publish-prerelease
    
To publish a release, run:

    npm run publish-<major/minor/patch>
    
It will increase version with chosen strategy, then build and package your 
local workspace, and finally publish it on `npm`.

Then you may use it (for testing purpose) in any project, installing it running:

    npm install @vidal-community/ng2-discovery@<VERSION>
