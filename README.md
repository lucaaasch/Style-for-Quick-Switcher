# Show More Files

[![GitHub tag (Latest by date)](https://img.shields.io/github/v/tag/lucaaasch/Show-More-Files)](https://github.com/ebullient/obsidian-snippetor/releases) ![GitHub all releases](https://img.shields.io/github/downloads/lucaaasch/Show-More-Files/total?color=success)

Show More Files (SMF) allows you to display all types of files in Obsidian, which are disabled by default. 

**Complementary Plugins**
	You don't need any community plugin to use SCF
## Preview

<img width="250" alt="image" src="https://github.com/lucaaasch/Show-More-Files/blob/main/Preview.png?raw=true">

## Installing SMF

1. Open `Settings` -> `Appearance` -> `CSS Snipets`
2. Open the snippets folder 📁 on the right 
3. **Drag** the file "Show More Files.css" into the folder
3. Reload the CSS Snipets in Obsidian 🔄
4. Turn on "Show More Files" in Obsidian by toggling the switch
## About the snippet usage

  In order to display the file types you want, you **must first configure** the CSS file. 

1. Open the file "Show More Files.css" (Visual Studio Code recommended)
2. Through the line [data-path$=".example1"] you can choose to show the files whose type “.example1”, it is a matter of replacing there with the file extension you choose.
   
And that's it, the chosen file type will be displayed. If you want to add more, you must copy above [data-path$=".example1"] followed by a comma, in which you will replace with the other file types. 

- In the same file there are 3 such lines, if you want more, then add more. 

### If you want to customize the style
 
In the CSS file it is specified what each line of code does so that you can change it to your liking, it is quite simple

- Page to find the HEX of any color: https://htmlcolorcodes.com 


***Thank you for reading, I hope this snippet is useful to you and if you want you can leave me a ⭐ to let me know that it was useful to you 😊***