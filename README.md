# Manga

A CLI Tool(BashScript) To Browse and Read/Download Manga. Scrapes From <a href="https://mangabuddy.com">Mangabuddy</a> , FZF/Rofi as a Menu & Feh as a Manga Reader/Image Viewer.

# Showcase

![preview](/assets/preview.gif)

## Dependencies

1. curl
2. cat, grep, head, tail, awk, sed , wc
3. fzf
4. rofi (optional menu)
5. feh (Manga Reader)
6. Imagemagick (Optional-[To convert jpgs into pdf])

## Installation

Launch the script the usual way if using from Terminal.

		./manga

However, if you wish to use Rofi as a Menu and want to bind a custom keyboard shortcut to the script than run the following command mentioned below.

		sudp cp manga /usr/bin/manga

# Manual

 	USAGE:
		manga [SEARCH_QUERY]
		manga [OPTIONS]

 	EXAMPLE:
		manga One Piece , manga "Black CLover"
		manga --rofi

 	OPTIONS/FLAGS:

		--rofi To Launch Manga with Rofi Run Launcher
  	MISC:
		Download Folder : $HOME/Documents/Manga
		There are no -h,--help Flags For HELP !
