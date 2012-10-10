# Writing Not eXactly C code in Notepad++

[Muntoo](https://github.com/muntoo) has written [a great post](http://muntoo.wordpress.com/2011/07/13/nxc-syntax-highlighting-in-notepad/) about syntax highlighting NXC code in Notepad++. While his method works rather well, it involves sacrificing the C language, and adding NXC-specific keywords. This method used to work best due to

Since version 6.2, Notepad++ has improved support for User Defined Languages. I have utilized this support to create a special user defined language file, which you can import into Notepad++ in order to add Not eXactly C as one of the avalible languages.

## Use

1. Download a [zip of the master branch](https://github.com/bungeshea/npp-nxc/zipball/master) to your computer
2. Launch Notepad++
3. Select Language > Define your language&hellip;
4. Click the Import&hellip; button and choose the `userDefineLang_Not_eXactly_C.xml` file from inside the zip you downloaded earlier
5. Open a `.nxc` file, or select Not eXactly C from the Language menu to enable syntax highlighting

# External Links

* [Writing NXC code in Notepad++ « Spillerrec's Blog](http://spillerrec.wordpress.com/2011/03/05/writing-nxc-code-in-notepad/)
* [NXC Syntax Highlighting in Notepad++ « Muntoo's Blog](http://muntoo.wordpress.com/2011/07/13/nxc-syntax-highlighting-in-notepad/)
