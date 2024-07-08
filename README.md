# Notepad++ User-Defined Language preset for .BMG language files
I yearn for the day when Notepad++ implements REGEX, so that I can do this better.

## Preview
![image](https://github.com/smileyhead/notepadpp-udl-bmg/assets/15932372/d3029cf0-4a56-4842-96fc-0c083e884609)

## Installation
1. Open Notepad++.
2. Go to <kbd>Language</kbd> -> <kbd>User Defined Language</kbd> -> <kbd>Open User Defined Language folder…</kbd>.
3. Download and place `bmg.xml` into this folder.

After this, <kbd>BMG</kbd> should be available in the <kbd>Language</kbd> menu.

## File format association
.BMG files are encoded and WBMGT decodes them into .TXT files. Naturally, I saw no point in associating the BMG UDL preset with the .TXT format by default, so you will have to select it from the <kbd>Language</kbd> menu every time you wish to view a file with the BMG syntax highlighting.

**If you wish to associate the UDL with the .TXT format, follow these instructions:**
1. In Notepad++, go to <kbd>Language</kbd> -> <kbd>User Defined Language</kbd> -> <kbd>Define your language…</kbd>. This will open the UDL preset for editing.
2. Make sure ‘BMG’ is selected under the `User language:` drop-down.
3. Type ‘txt’ into the `Ext.:` text-field. (Edits are saved automatically.)
4. Finally, close this window.
