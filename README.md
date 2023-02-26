# Wallhaven.sh

This script downloads a random wallpaper from wallhaven according to the given contraint

Usage: wallhaven [-c -p -q -r -s -t -h searchterm ]

All wallpapers are downloaded to $HOME/Pictures/Wallhaven

Options:
-c : Category:
		001 for People
		010 for Anime
		011 for Anime + People
		100 for General
		101 for General + People
		110 for General + Anime
		111 for General + Anime + People

 -p : Purity:
		100 for SFW
		010 for Sketchy aka Lewd
		110 for SFW and Sketchy

 -q : Minimum Quality / Resolution a wallpaper should be in:
		1920x1080
		3840x2160 etc etc 
      All available resolution can be found on wallhaven.cc 

 -r : Aspect Ratio:
		landscape (finds wallpapers in landscape orientation)
		portrait (finds wallpapers in portrait orientation)
		16x9
		9x18 etc etc"
      All available resolution can be found on wallhaven.cc 

 -s : Sort value:
		relevance
		random
		date_added
		views
		favourites
		toplist
		hot

Search Term: (no flag needed)
	Can be any search term that wallhaven accepts

-h : Shows this fucking help menu

}

## If the flags arent used, then these are the defaults that the script uses

category = 111
purity = 100
resolution = 1920x1080
ratio = 16x9
sort value = random


