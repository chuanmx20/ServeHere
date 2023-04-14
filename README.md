# Serve here!
It's a little macOS toolbar kit, with which you can easily share your directory with others on the same LAN.

![demo](assets/demo.gif)

## Basic introduction
Implemented in `applescript`. The main FTP service is provided by [directory-serve](https://www.npmjs.com/package/directory-serve)
If you have already installed [nodejs](nodejs.org), it will install [directory-serve](https://www.npmjs.com/package/directory-serve) and run it if is not installed and straightly run it if is already installed. Else it will run the pre-installed unix tool `serve`.

## Installation
**Compile for your own**
1. Download the source code by git clone
2. Double click the `serve-here.scpt` to open it with `Script Editor`
3. Click File->export and export it to application and move it to ~/Applications (optional to move)
4. Drag the application you exported into toolbar pressing opt + cmd

**Install release**
1. Download the release application
2. Move it to ~/Applications (optional)
3. Drag it to toolbar pressing opt + cmd

## Usage
1. Click to run
2. Scan with your mobile device of type the address that is shown in `terminal` into the browser to access the web page
3. Press ctrl+c in `terminal` to shut the process down