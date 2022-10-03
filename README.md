# DeckText
Introducing DeckText! It's a theme for Decky's CSS Loader plugin that bumps up the size of the Steam Deck's UI text and some controls, making everything more accessible for people with diverse needs. Pairs nicely with the dyslexia font provided by the Fonts theme. Currently it modifies: 

- Main Menu
- QuickAccess Menu
- Virtual Keyboard
- Header and Footer 
- The Settings pages
- The In-game Menu

In addition, there are still some areas that are only partially complete:
- The Controller config page proved very challenging to tweak and still needs a lot of love. If it is making things worse for you, turn off the "In-Game Menus" module. 
- Only part of the Library is done so far, and none of the Home or Store pages.
- The QuickAccess Friends list is done, but not the main Friends page from the Steam menu.
- Probably other things I haven't noticed yet.

This theme is modular and split up by interface area, so you can enable only the parts you want. I have not tried it with other themes, but since this mostly only modifies the UI's font-size CSS rules for various elements, it should play nice with other custom themes. No promises, though! This cannot change the text size of any of your games. 

Bear in mind, I'm no front-end developer. I just know enough to be dangerous! So if you see that I've done something foolish, please let me know! Feedback and PRs are welcome. If you post an issue, please provide a screenshot illustrating the problem you are referencing.

## Future Plans
- Finish adjusting the sizing for Library, Home, Store, and Friends pages.
- Add sizing sliders for each module so you can customize the theme to meet your personal preferences.
- Increase the contrast ratio of some of the icons and text in a few places that are still difficult to see regardless of size.
- Outside of the scope of CSS Loader, and probably a separate project, but I'd also like to put together a KDE config for Desktop Mode as well. 

## Screenshots

### Settings Page (note the larger header and footer text as well)
![Steam Deck Settings page with DeckText theme applied](/screenshots/settings.jpg)

### Steam Menu
![Steam Deck Main Menu with DeckText theme applied](/screenshots/steam.jpg)

### Quick Access Menu
![Steam Deck Quick Access Menu with DeckText theme applied](/screenshots/qam.jpg)

### Virtual Keyboard (DEX theme shown, but should work with all the default themes)
![Steam Deck virtual keyboard with DeckText theme applied](/screenshots/vkeyboard.jpg)

### News Post
![Steam Deck virtual keyboard with DeckText theme applied](/screenshots/news.jpg)
