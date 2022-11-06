# Getting Started

## New to ProPresenter?

Learn to navigate the interface.

Video:
[Quick video if you prefer to watch and learn (<10 Min)](https://www.youtube.com/watch?v=s8ILR4lAJYA)

Read:
[Read about the interface from ProPresenter documentation](https://learn.renewedvision.com/propresenter/interface)

# Building

## Songs

Always check if a song is in the library first.
If you don't know if the song you need has been imported, follow the steps for [Existing Song](/README.md#importing-an-existing-song) first, then if not found then follow [New Song](/README.md#importing-a-new-song).

:warning: :warning: *_NOTE:_* Songs will need to be imported TWICE because ProPresenter applies an audience look across all arragements. For example, if a song is need for both worship and altar it should be imported twice each with a seperate arragenment and audience look. Otherwise, if we imported a song once and created two arrangements then you can only apply one audience look once, which is wrong for our broadcast needs.  

Worship Song - To be broadcasted to online services, so it has lower-thirds themes applied.

Altar Song - NOT to be broadcasted to online services. No lower-thirds themes applied.

---

### Importing an Existing Song:

Quick steps: ctrl+f -> select library -> type song name

---

### Importing a New Song:

If not in the library, then `⌘ cmd+f`, switch to SongSelect, and type the song name. Click on any of the results to preview the lyrics of the song. Once you find the song you'd like, click the import button at the bottom.

For a more detailed walkthrough, [read this documentation](https://learn.renewedvision.com/propresenter/working-with-files#import-songselect).

When you import, the template theme needs to be applied.
Below are the settings, we follow at the time of writing (11/2022):

- Slides delimited by: **_Line Break_**
- Delimiters per slide: **_1_**
- Size: **_1920x1080_**
- Template: Sanctuary Lyrics > **_No Text Box White Font_**
- Library: **_Songs_**
- Playlist: Whichever playlist you are currently building for, usually Sunday for Sunday church service.

For a more detailed walkthrough, [read this documentation](https://learn.renewedvision.com/propresenter/working-with-files#import-file).

---

### Adjusting the arrangement of a song

The worship band presets the arragement for all songs. Song arragements can be accessed from the church dropbox, if you need access talk to Pastor Lisa. 

To change the arrangement of a song, `click` the 3 boxes in the top-right corner. The left drop-down is where you access arragements. If the type of arragement you need does not exist, `click` create a new arrangement. Drag and drop the boxes to build the type of arrangement you need.

Learn more about groups and arrangements [here](https://learn.renewedvision.com/propresenter/working-with-slides#groups-and-arrangements). 

---

### Setting the Audience Looks of a song

As previously said, Worship arrangement will be broadcasted and Altar is not to be broadcasted. To achieve this, different audience looks are used. 

#### Worship Arrangement

Select all the lyrics, `⌘ cmd+a`, then `right-click` Add Action > Audience Look > Songs - Single Line.

#### Altar Arrangement

Select all the lyrics, `⌘ cmd+a`, then `right-click` Add Action > Audience Look > Not in Livestream

---

## Sermons

The best way to build a sermon is to build off an existing sermon. Below is the guide to how to build quickly, followed by an explanation of how the builds work, such as which themes and audience looks are used. Building from scratch is not recommended unless you really know what you are doing as this could introduce errors and cause the build to not work for online services. (And not explained for this reason.)

---

### Build Guide

Summary: Duplicate an old sermon. Replace necessary images. Delete old verses. Quick edit any quotes and main title verses, and copy-paste more slides if needed. Add bible verses.

The best way to build sermons is to build using an existing sermon.

> TIP: Try to find a sermon that has the type of items you need. For example, if your sermon needs quotes, and main title points, find a sermon with all those items. It allows you to use quick-edit to modify the text, instead of building a quote slide from scratch.

Make sure you are in presentations library, then find a sermon to use as a template. `Right-click` the sermon file, `click` duplicate, or copy, then paste. `Right-click` the duplicate sermon and `click` rename to the new sermon title with date.

> New Sermon Series? Then you probably need to replace the background images. [Go here to read how to replace the images.](/README.md#replacing-the-background-images)

- Delete all previous bible verses. Select multiple slides by holding down `⌘ cmd` and `click` the slides, then press the `⌫ delete` button. 

- Quotes: `Right-click` and `click` quick edit. Replace the text with the new quote. (Copy-Paste the slide if more quotes slides are needed.) Check the correct audience look is selected: `right-click` > Edit Actions > Audience Look > Quotes 

- Title Points: `Right-click` and `click` quick edit. Replace the text with the new title point. (Copy-Paste the slide if more quotes slides are needed.) Check the correct audience look is selected: `right-click` > Edit Actions > Audience Look > Major Points (#) Line(s) 

>If your text is not readable with the default text theme and given background you will need to modify the text. Read more how this was fixed in the [FAQ/Troubleshoting](/README.md#replacing-the-background-images). 

- Verses: `Click` the Bible icon in the Toolbar, or `ctrl+b`. Type the verse(s) needed, verify the bible version. 

> On the rare occasion, a bible verse is requested but not available in ProPresenter (e.g. NCV), then copy-paste the verse requested. Otherwise, check if the pastor/presentor wants to use that exact version or if they would like another version to be used.

**Make sure the correct bible theme is selected.** If you do not see the theme you need, you may need to update the theme. Don't know how to do that? [Follow the step-by-step here](/README.md#how-to-update-the-bible-theme).

In the bottom-left, `click` Save As... -> Copy to selected presentation. (Saves it to the sermon presentation you have selected.)

- Check Verses: 
   1. Check the correct audience look is selected: `right-click` > Edit Actions > Audience Look > Verses
   2. Click through each slide and make sure no text is cut off in the broadcast view. If it is, then you need to reflow it. In the top-left, `click` Reflow (or `ctrl+R`) and set your cursor, or click, the spot in text where you need to create a new slide. Hit `opt + enter` on your keyboard and a new slide should appear. Read more about reflow in [this documentation](https://learn.renewedvision.com/propresenter/working-with-slides#reflow-view).

- Speaker: 
  1. `right-click` > Themes > Sanctuary Lower Thirds > Pastor Mel (or speaker you need.)
  2. `right-click` > Edit Actions.. > Audience Look  > Sermon-Pastor Mel (or speaker you need.)

- Reorder your slides. Drag the slides to the correct order you need, following the sermon. 
- `Right-click` the sermon > Add To.. > Sunday (Or the appropiate playlist you need.)
- Update [Altar Call](README.md#altar-call-image) and [Sermon Bumper](README.md#sermon-bumper)

---

### Replacing the background images

Make sure to have the necessary images downloaded and open them in finder. Also, make sure you have the sermon presentation open in ProPresenter. Next, drag and drop the image into the appropiate slide.

> TIP: How do you drag and drop? Press and hold the mouse while you drag the file to the propresenter window and release once you are on top of the slide you would like to replace the image of.

For example, if it is the sermon title slide, drag and drop the new sermon title image into all the sermon title slides.

> TIP: After the first drag, you may get a prompt telling you this image already exists, would you like use existing or replace the image? Click Use Existing, but it doesn't really matter.

---

### Sermon Bumper

The sermon bumper is a 30-second video introducing the sermon series. To replace the previous video, use the same steps as replacing images.

Drag and drop the video you want from finder into ProPresenter. 

---

### Altar Call Image

The altar call sermon title is used as a privacy screen to block the broadcast seeing churchgoers as they prey at the altar. To replace the previous image, use the same steps as replacing images.

Drag and drop the image you want from finder into ProPresenter. 

---

## Updating Themes

The primary reason we update the themes is for bible verses, or for guest speakers.

### How to update the bible theme?

`click` Options in the top-right. In this example, the Sunday theme is an old version so we need to update it. `click` Edit as the bottom most option. Find the Sunday theme, and drag and drop the image. Center the image, and drag the image in the objects window to be the last item.

>If the text is hard to read, use Sunday - Version 2 theme. It should be the below Sunday but Sunday - Version 2 is the same as Sunday theme with the addition of a black transparency box to help darken the background image to help with readability. 

To nagivate back to the bible view, click the bible button or `ctl-b`.


### Guest Speakers

Unfortunately, adding guest nameplates are the worst. A theme needs to be created for EACH nameplate, then EACH guest needs their own audience look for broadcast. As more guest are added this has resulted in cluttering the themes, and audience looks. So clean up is often needed by deleting old nameplates and replacing them with new ones. Overall this results in just an overall painful process. A new, more efficient process is drastically needed, but until then below are the steps.

#### Create the Theme
1. Navigate to the lower-thirds themes and `click` edit
2. Duplicate (Copy/Paste) a nameplate slide, or use an old existing nameplate as a base
3. Drag and drop the new nameplate
4. Delete the old nameplate
5. `right-click` the slide icon on the left > rename the slide to the name (Naming scheme helps when creating the audience looks!)

#### Create the Audience Look
6. In the very top navigation bar: Screens > Edit Looks OR `shift + cmd + 1`
7. Duplicate (Copy/Paste) a nameplate look, or use an old existing nameplate as a base
8. On the projector column, click the paint swatches icon and select the theme of your nameplate. (Sanctuary Lower Thirds > Guest Nameplate)
9. Repeat step 8 for livestream column 

#### Applying the Nameplate to a Slide
10. Navigate to your desired slide (Little lost? Clicking the Show button at the top, might help.)
11. `right-click` the slide: Themes > Sanctuary Lower Thirds > Guest Nameplate
11. `right-click` the slide: Add Action > Audience Look > Guest Nameplate
 > If you cannot Add an Audience Look, then this slide already has an audience look. `right-click` the slide: _EDIT_ Action > Audience Look > Guest Nameplate

---

# FYI

## Scheduled Events

ProPresenter has a calendar feature you can schedule events to start automatically. Below are the 2 countdowns we have scheduled to start. [Read the documentation here.](https://learn.renewedvision.com/propresenter/other-features#calendar)

### 5 Minute Countdown

The 5 minute countdown will automatically start every Sunday at 10:24:58AM. 


### 5 Minute Countdown - Broadcast 

The 5 minute countdown will automatically start every Sunday at 10:19:58AM. 

### Changing the color

To change the color of a video or image, `right-click` > Inspector > Effects > `click` + > Adjust Color
Change the hue until the desired color is achieved. This is not an reliable solution as it cannot match all colors, just most. This is only meant to  help in a pinch. Read more about [effects here](https://learn.renewedvision.com/propresenter/working-with-media#effects-tab) or about [media properties](https://learn.renewedvision.com/propresenter/working-with-media#effects-tab). 

# Sanctuary Templates

Below are template images, Sanctuary uses for important events throughout the year. Download the template, and build the slide in ProPresenter following the example provided.
