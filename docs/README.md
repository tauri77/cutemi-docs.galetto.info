
# Install and Setup

## VIA WordPress

[filename](_media/install.mp4 ':include :type=mp4 width=98% controls')

1. After your download log into your WordPress admin interface
2. After login click on&nbsp; Plugins from the left&nbsp; hand menu
3. Click on &ldquo;Add new&rdquo;
4. Click on &ldquo;Upload&rdquo;
5. Browse to the directory you downloaded the plugin to and click &ldquo;Install Now&rdquo;
6. After Wordpress has finished unpacking the file click on &ldquo;Activate Plugin&rdquo;
7. After the plugin has been activated click on "Run Wizard" (or Go to Settings > Cute MediaInfo > Wizard)
8. In the wizard select the options that you want to be available. We recommend that you do not select all the languages, there are many and it could slow down the video editing with poor connections.


## VIA FTP

1. After your download unzip plugin from your download .zip
2. Open your FTP client
3. Browse to /wp-content/plugins/ server
4. Upload cute-mediainfo folder into this directory
5. Go to your wordpress admin panel
6. Go to plugins and activate Cute MediaInfo plugin
7. After the plugin has been activated click on "Run Wizard" (or Go to Settings > Cute MediaInfo > Wizard)
8. In the wizard select the options that you want to be available. We recommend that you do not select all the languages, there are many and it could slow down the video editing with poor connections.


# Using Cute MediaInfo

## Creating First MediaInfo

[filename](_media/first.mp4 ':include :type=mp4 width=98% controls')

1. Go to your Wordpress admin panel
2. Go to MediaInfo
3. Click on "Add New MediaInfo"
4. Click on "Select local video" 
5. Select a video file. This will generate the full mediainfo. (Alternatively, without video file, you can paste the mediainfo into the textarea)
6. Click on "Autocomplete fields from mediainfo"
7. Click on "Publish"

## Adding Links

[filename](_media/add-links.mp4 ':include :type=mp4 width=98% controls')

When editing a mediainfo, go to "Links" section and paste a link in the "Link" field. Wait while the link data is obtained, if the link is a link source recognized by the plugin it should autocomplete the other link fields, if it is not from a recognized source select "Generic" as "Link source ".

If a link is "Generic" the Link field is used for the users. If is other recognized link source then will use the "Extracted ID" field to generate link to user.

To add more links click on the "+" button.


## Using a MediaInfo 

The created MediaInfo can be used as a block or shortcode.

### VIA Block

1. On Block editor add a block "Cute MediaInfo"
2. Choose how you want the video information to be displayed by selecting the profile
3. Click on "Select MediaInfo" and search the mediainfo entry. 
4. Select an entry from the search results list. This complete the MediaInfo ID field.
5. Ready!

### VIA Shortcode

The shortcode for Cute Mediainfo is "mediainfo" and the parameters are "id" and "profile"

>[mediainfo profile=summary id=1234]


# Configuration

The plugin configuration can be found in Settings > Cute MediaInfo in the administration panel


## Profiles

Profiles determine the way information is displayed.

The same mediainfo can be shown with different profiles in different places. For example, with profile "summary" in a widget, and with profile "full" in a post.

Each profile has different **styles**, **layouts** and **data to show**.

- **Styles**: Determine the colors, dimensions and fonts.
- **Layouts**: Determines if a block of information is displayed, how it is displayed and where. Examples of blocks are "Videos", "Audios", "Links".
- **Data to show**: Determine what information and where to show it. For example, whether or not to show the bitrate, and if it is shown, to show in text, icon or both. And then show it before or after bitrate mode, etc.

Effect of customizing **Styles**:

![styles](_media/styles_circles.png ':size=98%')

Effect of customizing **Layouts**:

![layouts](_media/layouts.png ':size=98%')

Effect of customizing **Data to show**:

![data to show](_media/data.png ':size=98%')

### Styling

[filename](_media/styling.mp4 ':include :type=mp4 width=98% controls')

To edit the style of a profile:
1. Go to Settings > Cute MediaInfo
2. Go to Profiles tab
3. Find the profile to edit and click on "Customize Profile"
4. Then click on "Styles"

### Layout

[filename](_media/layout.mp4 ':include :type=mp4 width=98% controls')

To edit the layout of a profile:
1. Go to Settings > Cute MediaInfo
2. Go to Profiles tab
3. Find the profile to edit and click on "Customize Profile"
4. Then click on "Layout (Blocks/Headers)"

### Showing data

[filename](_media/data.mp4 ':include :type=mp4 width=98% controls')

To edit the layout of a profile:
1. Go to Settings > Cute MediaInfo
2. Go to Profiles tab
3. Find the profile to edit and click on "Customize Profile"
4. Then click on "Data to Show"

