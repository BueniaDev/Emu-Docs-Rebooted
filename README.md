# Emu-Docs-Rebooted

The Emu-Docs archive was an archive of emulation-related documentation and test ROMs designed to assist anyone with understanding the underlying architecture of multiple consoles and/or systems. Unfortuantely, it appears that the original Github repository was taken down, presumably for unknown reasons. That is why, in order to benefit the up-and-coming emulator developers that need a one-stop source of comprehensive documentation for the systems that they want to emulate, I am hosting an unofficial mirror of the Emu-Docs repository on my Github.

### Resources to Archive

http://emu-docs.org/

http://www.zophar.net/documents/

https://github.com/franckverrot/EmulationResources

### Documentation Guidelines (just copying this text from the old repository)

1. If you're adding specific CPU/chip documentation, please put the appropriate documentation under "Shared Components". Inside the console's directory, create a relative symbolic link to the folder you created in "Shared Components". e.g. in the NES folder, there's a relative symbolic link to "CPU 65xx" in "Shared Components"

2. Consoles in the root directory should be named by the full name e.g. "Playstation 2" instead of "PS2"

3. Test ROMs are welcome and should be placed under a folder called "test_roms" in the console's directory. Documentation about certain games or ROM hacking should be placed under a folder called "game_documentation". SDKs/DDKs should be placed under a folder called "SDK" or "DDK".

4. Inside each folder, there should be a README.md describing the files in that directory
