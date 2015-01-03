TTF-to-PNG
==========

Create all character's PNG files from a .ttf file.

## What

You can get all characters in a `.ttf` font file as `.png` images. It is useful to obtain icon's `.png` from an icon font.

## Installation

### ImageMagick

There are a lot of ways for installation. 

- Homebrew

		brew install imagemagick

- Cactuslab's installer

	- [ImageMagick installer for Mac OS X](http://cactuslab.com/imagemagick/)

### FontTools

	pip install fonttools

### TTF-to-PNG

    git clone https://github.com/sl2/TTF-to-PNG.git

## Usage

1. Install `.ttf` font by fontbook.

2. Execute following command.

	    ./ttf2png.py [INSTALLED_FONT_PATH] [FONT_SIZE] 

	- You can find `INSTALLED_FONT_PATH` by the executing following command.

			convert -list font

		Output:
		
			Font: Verdana
			  family: Verdana
			  style: Normal
			  stretch: Normal
			  weight: 400
			  glyphs: /Library/Fonts/Verdana.ttf <-INSTALLED_FONT_PATH

3. Check under the `./images` dir.

## Environment

- OSX : 10.10
- Python : 2.7.8
	- It may work on other version's OSX or Python.

## License

- MIT

