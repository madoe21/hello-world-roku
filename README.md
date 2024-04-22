# Hello World Roku Application

This is a simple Roku application that displays the text "Hello World" on the screen.

## Table of Contents

- [Requirements](#requirements)
- [Setup](#setup)
- [Development Guide](#development-guide)
- [Deployment](#deployment)
- [License](#license)

## Requirements

To run this project and deploy it on a Roku device, you'll need the following:

- A Roku device in developer mode
- Node.js and npm
- Visual Studio Code (or any other IDE of your choice)

## Setup

1. Ensure your Roku device is in developer mode. See the [Roku Developer Guide](https://developer.roku.com/en-gb/docs/developer-program/getting-started/developer-setup.md) for instructions.
2. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/madoe21/hello-world-roku.git
   ```

3. Navigate to the project directory:

   ```bash
   cd hello-world-roku
   ```

4. Install the dependencies:

   ```bash
   npm install
   ```

## Development Guide

1. Open the project in Visual Studio Code:

   ```bash
   code .
   ```

2. Edit the files in `source/` according to your requirements. The BrighterScript file `Hello.bs` contains the logic, and the XML file `HelloWorld.xml` contains the layout of the application.

## File Structure

```
HelloWorld/
├── source/
│   ├── components/
│   │   └── HelloWorld.xml
│   ├── images/
│   │   ├── background.png
│   │   ├── channel-poster_fhd.png
│   │   ├── channel-poster_hd.png
│   │   ├── channel-poster_sd.png
│   │   ├── splash-screen_fhd.png
│   │   ├── splash-screen_hd.png
│   │   └── splash-screen_sd.png
│   ├── fonts/
│   │   ├── Arial.ttf
│   │   └── ArialBold.ttf
│   ├── source/
│   │   └── Main.bs
│   └── manifest
├── .gitignore
├── bsconfig.json
├── LICENSE
├── package.json
└── README.md
```

## Configuration

- `bsconfig.json`: BrighterScript configuration - please change your Roku IP Adress and credentials here.

## Deployment

1. Configure the `bsconfig.json` file with the appropriate settings for your Roku device.
2. Run one of the following scripts to deploy the application to your Roku device:

   - `npm run build`: Builds the application - no deployment possible.
   - `npm run package`: Packages the application - manual deployment possible.
   - `npm run deploy`: Deploys the application to the Roku device automatically (according to `bsconfig.json`).

## Support
I appreciate everyone who supports me and my projects! For any requests and suggestions, feel free to provide feedback.

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/default-orange.png)](https://www.buymeacoffee.com/madoe21)