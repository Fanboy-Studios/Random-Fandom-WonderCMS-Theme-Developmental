# Random Fandom WonderCMS Theme Developmental
The unstable, buggy, developmental version of Random Fandom WonderCMS Theme!

# Demo
Not Available Yet.

# Download and Setup
1. Add "https://github.com/Fanboy-Studios/Random-Fandom-WonderCMS-Theme-Developmental" to your themes.
2. Activate the theme.
3. For updates, check the themes for updates, if there's any then you can apply them.
4. You may have to clear your browser cache in order to see the changes.

# Features
1. A "title logo" can be used in place of simple text, by placing a
   title_logo.png file into themes/randomfandomdev/img/.
   - Note that the theme ships with the assumption that you will use
     a title_logo.png. If you do not, you'll need to make a minor
     CSS change that is marked in the theme's css file.
2. Each navigation menu item can be replaced with an icon. To do so,
   place icons named ~pagename~.png into themes/randomfandomdev/img/menu/.
   - By default, the theme ships with the "home" page replaced with
     a small home icon.
   - There is also an option to completely remove the home navigation,
     since the "title logo" serves the same pupose. Look in the CSS to
     find how to remove it.
3. Link entries are placed for any /favicon.(png|jpg|gif|ico) found.
4. Theme properties can be set via a config.txt file or via the wCMS
   Settings tab, depending on your preference. I prefer config.txt as
   it makes it easier for me to move site from dev to prod environments,
   but many users may prefer the convenience of the Settings tab. A
   nice compromise it to use config.txt for production and the Settings
   tab for dev/test. This theme supports that in the sense that the
   existence of a config.txt will trump any values stored in Settings.
5. Supports meta properties for og:xxx.
6. Optional social media links/logos can be placed in the footer.

# How to fix your site if it breaks due to your modifications to this theme. (At least most of the time.)
0. YOU WILL LOSE SITE DATA, WHICH MAY INCLUDE YOUR POSTS, PICTURES, AND OTHER IMPORTANT FILES. MAKE A BACKUP!
1. Delete the "cache.json" and "database.js" files from your WonderCMS "data" folder.
2. Delete the folder for this theme in the WonderCMS "themes" folder. Don't delete the whole "themes" folder itself though.
3. Refresh your webpage.

# How to fix your site's admin panel if the 3.1.0 WonderCMS update broke it.
0. Access your files via your hosting file management panel, or via FTP.
1. Go to your "data" folder.
2. Open "database.js" for editing.
3. Change the theme (probably on line 4) to "default"
4. Save "database.js" and refresh your website page. You should be able to login and update the theme for my patches (if they're available).
   Please note that my theme is a fork of the Adivvyo theme, but heavily modified. This means patches for broken updates may take longer to push.
5. You may then reapply the theme.
