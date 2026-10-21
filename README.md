# TV-HOME

TV-HOME is a modified version of [CleanYourTV](https://github.com/Gathin23/cleanyourtv), with changes made according to my personal needs. These include some minor UI changes and new features.

I made this project available as a ready-to-install APK for people who just want to try the launcher without building it themselves. Not everyone has a PC or computer, and some people aren't comfortable using ADB commands or disabling system apps because they're worried about accidentally breaking their family's TV.

Many Android TV devices don't offer a simple setting to choose a custom launcher as the default. Setting one up may require extra steps or tools, depending on the TV. This project makes the launcher itself easier to download and install; it does not automatically change the default launcher on every device.

## Installing TV-HOME

1. Download the TV-HOME APK from the project's Releases page.
2. Install it on your Android TV using the installation method supported by your device.
3. Open TV-HOME from your TV's apps list to try it.

## Making TV-HOME the default launcher

Most of the TV brands not provide a setting for choosing custem launcher as the default Home app; you can look into Launcher Manager and the XDA discussion linked below.

1. First, install TV-HOME and confirm that it opens correctly.
2. Read the [Launcher Manager XDA thread](https://xdaforums.com/t/app-firetv-noroot-launcher-manager-change-launcher-without-root.4176349/) carefully and check whether its instructions and app version support your specific TV and firmware.
3. Follow only the setup steps documented for your compatible device and Launcher Manager version. Some methods require Developer Options, USB debugging, ADB, or granting additional permissions.
4. If Launcher Manager offers a supported way to select a Home app, choose TV-HOME and test the Home button.

**Important:** Launcher Manager and custom-launcher methods do not work on every TV. Do not disable the stock launcher or run ADB commands unless you understand the effects and have a way to restore the original launcher. Disabling system apps can affect normal TV functions. If you are unsure, use TV-HOME as a regular app instead.

## Credits

TV-HOME is based on [CleanYourTV](https://github.com/Gathin23/cleanyourtv) by [Gathin23](https://github.com/Gathin23). Thanks to the original developer for sharing the source code.

For information about launcher management, see the [Launcher Manager discussion on XDA Developers](https://xdaforums.com/t/app-firetv-noroot-launcher-manager-change-launcher-without-root.4176349/).

## License

This project includes code based on CleanYourTV, which is licensed under the MIT License. Refer to the original project's [repository](https://github.com/Gathin23/cleanyourtv) for its license and copyright notice. Fonts or other assets may have separate licenses; see `FONT-LICENSE-OFL.txt` for the included font license.
