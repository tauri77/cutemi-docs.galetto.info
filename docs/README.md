
# Install and Setup

## VIA WordPress

[filename](_media/install.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

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

[filename](_media/first.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

1. Go to your Wordpress admin panel
2. Go to MediaInfo
3. Click on "Add New MediaInfo"
4. Click on "Select local video" 
5. Select a video file. This will generate the full mediainfo. (Alternatively, without video file, you can paste the mediainfo into the textarea)
6. Click on "Autocomplete fields from mediainfo"
7. Click on "Publish"

## Adding Links

[filename](_media/add-links.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

When editing a mediainfo, go to "Links" section and paste a link in the "Link" field. Wait while the link data is obtained, if the link is a link source recognized by the plugin it should autocomplete the other link fields, if it is not from a recognized source select "Generic" as "Link source ".

If a link is "Generic" the Link field is used for the users. If is other recognized link source then will use the "Extracted ID" field to generate link to user.

To add more links click on the "+" button.

### Links with reCaptcha <sup>(PRO)</sup>

[filename](_media/reCaptcha.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

**First configure the API KEYS to be used in Settings > Cute MediaInfo > reCaptcha.**

Generate the keys on https://www.google.com/recaptcha/admin/create.

With the [PRO Addon](https://galetto.info/product/cute-mediainfo-pro/) you can protect links individually by adding them in the mediainfo edit, or protect all links for a link source.

To protect all links for a link source:
1. Go to MediaInfo > Link Sources
2. Go to edit the link source to protect links
3. Select the captcha version to use and save

### Check links status <sup>(PRO)</sup>

[filename](_media/link-checker.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

With the [PRO Addon](https://galetto.info/product/cute-mediainfo-pro/) you can check a link in the edition of a mediainfo.

To check if link is offline:
1. Go to MediaInfo edition
2. Scroll to the link
3. Click on the green button in the status field. If offline is detected, the status field changes to "offline".

### Link override <sup>(PRO)</sup>

With the [PRO Addon](https://galetto.info/product/cute-mediainfo-pro/) you can override a link in the edition of a mediainfo.

To override a link:
1. Go to MediaInfo edition
2. Scroll to the link
3. Fills the override field with the url that will be shown to the user. Ex: https://adf.ly/xXyY

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

[filename](_media/styling.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

To edit the style of a profile:
1. Go to Settings > Cute MediaInfo
2. Go to Profiles tab
3. Find the profile to edit and click on "Customize Profile"
4. Then click on "Styles"

### Layout

[filename](_media/layout.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

To edit the layout of a profile:
1. Go to Settings > Cute MediaInfo
2. Go to Profiles tab
3. Find the profile to edit and click on "Customize Profile"
4. Then click on "Layout (Blocks/Headers)"

### Showing data

[filename](_media/data.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

To edit the layout of a profile:
1. Go to Settings > Cute MediaInfo
2. Go to Profiles tab
3. Find the profile to edit and click on "Customize Profile"
4. Then click on "Data to Show"

# Screenshots <sup>(PRO)</sup>

Only available with the [PRO Addon](https://galetto.info/product/cute-mediainfo-pro/).

First make sure that the screenshots module is enabled in Settings > Cute MediaInfo > Advanced Settings.

## Adding Screenshots

Each capture has 4 fields:
- **Media ID**: The ID of the image uploaded as wordpress media
- **Thumb URL**: The thumbnail URL
- **Full Size URL**: The URL of the image in full size
- **Link to Image**: The URL with the image link. Ex: imgur link

### From File

[filename](_media/screenshot-file.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

WP media image fields:

- **Media ID**: 1234
- **Thumb URL**: *(empty)*
- **Full Size URL**: *(empty)*
- **Link to Image**: *(empty)*

Only the **Media ID** reaches. From the **Media ID** the plugin deduces the full size and miniature URL.

### From external image

[filename](_media/screenshot-external.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

External image fields:

- **Media ID**: *(empty)*
- **Thumb URL**: https://thumbs4.imagebam.com/97/70/66/ME5N060_t.jpg
- **Full Size URL**: https://images4.imagebam.com/17/46/42/ME5N060_o.jpg
- **Link to Image**: https://www.imagebam.com/view/ME5N060

If you leave the **Link to Image** empty, it will work too, but no link will be shown.

If you leave the **Full Size URL** empty, it will work too, but the image will not be displayed in full size.

If you leave the **Thumb URL** empty, it will work too, but the thumbnail use the full URL. (not recommended if the image has a large size)


### Generating Screenshots

[filename](_media/screenshot-generate.mp4 ':include :type=mp4 width=98% preload="none" poster="_media/cover.png" controls')

You can generate screenshots from the edition (as long as the video is playable in the browser). To do this:

1. Click on "Select local video" and select the video file.
2. At the bottom of the screenshots section, some screenshots should be generated automatically. These are not uploaded yet, you can download it with the down arrow buttons, or upload it and add it to the screenshots with the up arrow button.
3. You can also generate new captures from the player that appears below. To do this, at the time of playback you want, click on the camera icon, then another capture will be generated, which will be added along with the automatic ones (which is not uploaded yet, you can download or upload it).

