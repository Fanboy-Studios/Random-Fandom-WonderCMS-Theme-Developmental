# Random-Fandom-WonderCMS-Theme-Developmental
Random Fandom Theme WonderCMS Edition. Developemental Version! This build may not be functional at times.

# Demo
(Has yet to be made...)

# Download and Setup
1. Download the ZIP file.
2. Create folder named "yourthemenamehere" in WonderCMS themes folder.
3. Unzip all folders and files from zip file in to created folder.
4. The theme will be visible in theme list of WonderCMS settings.

# Features
1. A "title logo" can be used in place of simple text, by placing a
   title_logo.png file into themes/"yourthemenamehere"/img/.
   - Note that the theme ships with the assumption that you will use
     a title_logo.png. If you do not, you'll need to make a minor
     CSS change that is marked in the theme's css file.
2. Each navigation menu item can be replaced with an icon. To do so,
   place icons named ~pagename~.png into themes/"yourthemenamehere"/img/menu/.
   - By default, the theme ships with the "home" page replaced with
     a small home icon.
   - There is also an option to completely remove the home navigation,
     since the "title logo" serves the same pupose. Look in the CSS to
     find how to remove it.
3. Link entries are placed for any /favicon.(png|jpg|gif|ico) found.
4. Theme properties can be set via a config.txt file or via the wCMS
   Settings tab, depending on your preference. You may prefer config.txt as
   it makes it easier for you to move sites from dev to prod environments,
   but many users may also prefer the convenience of the Settings tab. A
   nice compromise it to use config.txt for production and the Settings
   tab for dev/test. This theme supports that in the sense that the
   existence of a config.txt will trump any values stored in Settings.
5. Supports meta properties for og:xxx.
6. Optional social media links/logos placed in footer.
 
