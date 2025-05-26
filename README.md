# EurKEY with Dashes (macOS)

The original EurKEY layout doesn’t include en-dashes or em-dashes in the expected positions.  
This version adds them, so you can now type:

- `-`: hyphen/minus  
- `Alt + -`: en-dash (–)  
- `Shift + Alt + -`: em-dash (—)

This is the macOS version, based on:  
https://github.com/jonasdiemer/EurKEY-Mac

It overrides the characters with keycode 27 at index 3 and index 4 in the `keylayout` file.
