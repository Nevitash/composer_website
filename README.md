# Composer Website _(composer_website)_

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Blazor Web application deployment for the Composer platform.

Composer Website provides the hosted web portal and interactive client app for Composer, rendering shared Razor UI components across modern browsers.

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

To accompany native desktop and mobile MAUI clients, Composer Website delivers identical functionality directly through web browsers using modern Blazor server/WebAssembly rendering pipelines and shared component libraries.

## Install

Requires .NET 8 or newer:

`ash
dotnet restore Cmposer.Website/Cmposer.Website.csproj
`

## Usage

Start the local web server:

`ash
dotnet run --project Cmposer.Website/Cmposer.Website.csproj
`

Navigate to https://localhost:7142 or http://localhost:5242 in your browser.

## Maintainers

[@Nevitash](https://github.com/Nevitash)

## Contributing

PRs accepted. Please open an issue first to discuss large features or layout adjustments.

## License

[MIT](LICENSE)
