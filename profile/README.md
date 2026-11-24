# shiftcode

## Public Packages

Our packages are published to the GitHub npm registry.
Installing them requires authentication, even for public packages.

<details>
<summary>How to install</summary>

1. Create a [personal access token (classic)](https://github.com/settings/tokens/new?scopes=read:packages&description=npm%20read%20packages) with the `read:packages` scope.
2. Point the `@shiftcode` scope to the GitHub registry in the `.npmrc` of your project:

   ```ini
   @shiftcode:registry=https://npm.pkg.github.com
   ```

3. Add your token to your user-level `~/.npmrc`:

   ```ini
   //npm.pkg.github.com/:_authToken=YOUR_TOKEN
   ```

   In GitHub Actions, use `${{ secrets.GITHUB_TOKEN }}` with `permissions: packages: read` instead.

</details>



### [sc-ng-commons-public](https://github.com/shiftcode/sc-ng-commons-public)

| Package                                                                                                   | Latest                                                                                                                                              | Changelog                                                                                             |
|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| [`@shiftcode/ngx-components`](https://github.com/shiftcode/sc-ng-commons-public/pkgs/npm/ngx-components)  | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-ng-commons-public?filename=libs%2Fcomponents%2Fpackage.json&label=&color=blue) | [CHANGELOG](https://github.com/shiftcode/sc-ng-commons-public/blob/main/libs/components/CHANGELOG.md) |
| [`@shiftcode/ngx-core`](https://github.com/shiftcode/sc-ng-commons-public/pkgs/npm/ngx-core)              | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-ng-commons-public?filename=libs%2Fcore%2Fpackage.json&label=&color=blue)       | [CHANGELOG](https://github.com/shiftcode/sc-ng-commons-public/blob/main/libs/core/CHANGELOG.md)       |

### [sc-commons-public](https://github.com/shiftcode/sc-commons-public)

| Package                                                                                                                     | Latest                                                                                                                                                              | Changelog                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [`@shiftcode/airtable-mapper`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/airtable-mapper)                     | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fairtable-mapper%2Fpackage.json&label=&color=blue)           | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/airtable-mapper/CHANGELOG.md)           |
| [`@shiftcode/airtable-syncer`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/airtable-syncer)                     | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fairtable-syncer%2Fpackage.json&label=&color=blue)           | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/airtable-syncer/CHANGELOG.md)           |
| [`@shiftcode/branch-utilities`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/branch-utilities)                   | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fbranch-utilities%2Fpackage.json&label=&color=blue)          | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/branch-utilities/CHANGELOG.md)          |
| [`@shiftcode/cdk-utilities`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/cdk-utilities)                         | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fcdk-utilities%2Fpackage.json&label=&color=blue)             | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/cdk-utilities/CHANGELOG.md)             |
| [`@shiftcode/eslint-config-recommended`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/eslint-config-recommended) | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Feslint-config-recommended%2Fpackage.json&label=&color=blue) | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/eslint-config-recommended/CHANGELOG.md) |
| [`@shiftcode/eslint-plugin-rules`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/eslint-plugin-rules)             | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Feslint-plugin-rules%2Fpackage.json&label=&color=blue)       | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/eslint-plugin-rules/CHANGELOG.md)       |
| [`@shiftcode/iac-utilities`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/iac-utilities)                         | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fiac-utilities%2Fpackage.json&label=&color=blue)             | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/iac-utilities/CHANGELOG.md)             |
| [`@shiftcode/inversify-logger`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/inversify-logger)                   | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Finversify-logger%2Fpackage.json&label=&color=blue)          | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/inversify-logger/CHANGELOG.md)          |
| [`@shiftcode/lambda-utilities`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/lambda-utilities)                   | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Flambda-utilities%2Fpackage.json&label=&color=blue)          | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/lambda-utilities/CHANGELOG.md)          |
| [`@shiftcode/logger`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/logger)                                       | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Flogger%2Fpackage.json&label=&color=blue)                    | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/logger/CHANGELOG.md)                    |
| [`@shiftcode/nest-logger`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/nest-logger)                             | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fnest-logger%2Fpackage.json&label=&color=blue)               | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/nest-logger/CHANGELOG.md)               |
| [`@shiftcode/publish-helper`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/publish-helper)                       | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Fpublish-helper%2Fpackage.json&label=&color=blue)            | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/publish-helper/CHANGELOG.md)            |
| [`@shiftcode/utilities`](https://github.com/shiftcode/sc-commons-public/pkgs/npm/utilities)                                 | ![version](https://img.shields.io/github/package-json/v/shiftcode/sc-commons-public?filename=packages%2Futilities%2Fpackage.json&label=&color=blue)                 | [CHANGELOG](https://github.com/shiftcode/sc-commons-public/blob/main/packages/utilities/CHANGELOG.md)                 |
