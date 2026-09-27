---
source: recepgur07-bot.github.io/tr/memora/kilavuz.md
layout: default
lang: en
title: Memora user guide
permalink: /en/memora/guide/
alt_url: /tr/memora/kilavuz/
description: Every Memora feature, step by step, with the exact button and setting names. Written for VoiceOver users.
---
<!-- Source: tr/memora/kilavuz.md (from pazarlama/uygulamalar/memora/TANITIM-METNI.md). UI names are the en values in Memora's Localizable.xcstrings. Update both guides together. -->

# Memora user guide

This guide covers every Memora feature using the exact button and setting names you hear in the app. Move between sections with the VoiceOver headings rotor, or jump straight to a section from the list below.
{: .lead}

<nav class="toc" aria-labelledby="toc-heading" markdown="1">
<h2 id="toc-heading">On this page</h2>

1. [First launch and permissions](#first-launch)
2. [The main screen](#main-screen)
3. [What you hear in the list](#in-the-list)
4. [Rotor actions](#rotor)
5. [Descriptions](#descriptions)
6. [Search](#search)
7. [When you open a photo](#detail)
8. [Working with a whole day](#day-header)
9. [Selecting several items and tools](#selection)
10. [Safe deletion](#deletion)
11. [Text in photos and scanning](#scanning)
12. [Settings](#settings)
</nav>

<h2 id="first-launch">1. First launch and permissions</h2>

The first time you open the app, it asks for access to Apple Photos. You can give full access to your whole library; with limited access, only the photos you choose are listed. You can change your choice later with the **Update photo selection** button in the app.

[Back to top](#icerik){: .top}

<h2 id="main-screen">2. The main screen</h2>

At the top of the screen, **Settings** is on the left, and **Search** and **Start selection** are on the right. Just below are three rows that narrow your library:

- **Scope:** All, Photos, Videos, Screenshots, Favorites or one of your albums. Each one tells you how many items it has.
- **Go to date:** Today, Yesterday, Last 7 days, This month, Last month, A specific day and Date range. You can also go down through Years, Months and Days to reach only the days that have items; each step tells you how many items it holds.
- **Sorting and tags:** Sort the list by Newest, Oldest or By name; in the Videos scope, Longest and Shortest also appear. If you choose a tag, only the items with that tag are shown.

While text scanning is running, a temporary **Index status** row (for example 1,250 / 4,000) appears below these rows and disappears when scanning is done.

[Back to top](#icerik){: .top}

<h2 id="in-the-list">3. What you hear in the list</h2>

When you move to an item, VoiceOver reads the following, in this order:

1. Its type: Photo, Video or Screenshot
2. The date and time it was taken
3. Its orientation: Portrait, Landscape or Square
4. For a video, its duration
5. The name you gave it, if any
6. Its first two tags, and how many more there are
7. "Contains text" if there is text in the photo
8. Your note and description
9. "Favorite" if it is a favorite
10. Last, the text in the photo itself

**Settings > Accessibility > Automatic reading** decides how much of that text is read. The default is Short, which is 500 characters. When Automatic reading is Off, the text is not read, and for notes and descriptions you only hear "Has a note" or "Has a description".

[Back to top](#icerik){: .top}

<h2 id="rotor">4. Acting on a photo without opening it</h2>

On an item, turn the rotor to Actions and swipe up or down with one finger. First you hear **Select**, which puts the item into selection mode, and then, by default, the actions below.

<details markdown="1">
<summary>All actions and what they do (9 actions)</summary>

1. **Share:** Sends the item to the system share sheet. The name you gave becomes the name of the shared file, unless the receiving app changes it.
2. **Rename:** Give the item your own name, up to 120 characters. The original file name in Photos does not change. If another item already uses the same name, Memora tells you; you can save with the numbered name it suggests or keep the same name anyway.
3. **Add to favorites** or **Remove from favorites**.
4. **Text in the photo:** Along with the action name you hear "Contains text" or "Not scanned". On the screen that opens, VoiceOver reads the text directly (with VoiceOver off, the **Read text** button reads it aloud). You can put it on the clipboard with **Copy text**, and if it has not been scanned yet, scan it right away with **Analyze text**. This action does not appear for videos.
5. **Delete from Photos:** Opens the delete confirmation.
6. **Tags:** Choose from your existing tags or create a new one. A tag name can be 1 to 40 characters; an item can have up to 50 tags.
7. **Details:** The device it was taken with, resolution, duration, source file name, location, source size, and whether the item is on the device or only in iCloud.
8. **Add note** or **Edit note:** Write your own note about the item.
9. **Create description** or **Edit description:** Opens the description screen; the action name tells you whether the item already has a description.
</details>

You can reorder these actions and turn off the ones you do not want in **Settings > Accessibility > Rotor actions**. Actions you turn off are still available in the menu that opens when you touch and hold an item.

[Back to top](#icerik){: .top}

<h2 id="descriptions">5. Descriptions</h2>

A Memora description is a short estimate that names the objects it recognizes with confidence and the number of people in the photo. It is created on your device and can be wrong. For a longer, sentence-by-sentence description, you can use another app.

- If there is no saved description, creating one starts automatically when the screen opens. If there is a saved description, it is read first; a new one is created only when you ask.
- If you like the result, choose **Add description**. To put it in place of an existing description, the button is called **Save this, replacing the old one**. If you do not like it, choose **Create again**.
- **Describe with another app:** Sends the photo to the system share sheet, where you can pick an installed app such as Be My Eyes or ChatGPT. You send the photo to that app yourself; Memora does not.
- **Write a description yourself:** Type your own description. If there is copied text on the clipboard, for example a description you got from another app, the **Paste from clipboard** button below the field adds it in one tap.
- Descriptions you add are read in the list and included in search. For videos, only the cover frame is described. Items stored only in iCloud cannot be described until they are downloaded to the device.

[Back to top](#icerik){: .top}

<h2 id="search">6. Search</h2>

The **Search** button on the main screen opens the search screen.

- It searches the names, tags, notes and descriptions you added, and the text in your photos.
- Search always covers your whole library; the scope, date or tag filter on the main screen does not narrow it.
- Results come as list rows with the same rotor actions. Tapping a result opens its detail screen.
- The screen tells you how many items have had their text analyzed (for example 3,200 / 4,000), so you know how much of your library search covers.
- The **Clear search** button clears the text; focus stays in the search field.

[Back to top](#icerik){: .top}

<h2 id="detail">7. When you open a photo</h2>

Double-tap an item to open its detail screen.

- At the top you hear the counter "Item position, Item 4 of 123." Swipe up or down with one finger on it to move to the next or previous item; the new item's information is read as you move. The **Previous item** and **Next item** buttons do the same.
- The screen has Share, favorite, Rename, Tags, Add note or Edit note, Create description or Edit description, Text in the photo, Details and Delete buttons.
- Videos have **Play**, **Back 10 seconds** and **Forward 10 seconds** controls.
- Items stored only in iCloud show a **Download content** button; once downloaded, the item is also included in the next text scan.

[Back to top](#icerik){: .top}

<h2 id="day-header">8. Working with a whole day</h2>

Move to a day header, for example "September 14, 2026, 11 items, Expanded", and turn the rotor to Actions to get these actions for the whole day. Double-tap the header to collapse or expand the day.

- **Select all these results:** Selects the whole day in one step and switches to selection mode.
- **Share:** Sends the day's items in a single share; up to 100 items.
- **Name selected items:** Gives every item of the day a common name. If "Number in order" is on, it numbers them starting from the oldest, for example Holiday 1, Holiday 2.
- **Add tags:** Adds a tag to the whole day at once.
- **Add to favorites:** Adds the whole day to your favorites.
- **Delete from Photos library:** Opens the delete confirmation for that day's items.

[Back to top](#icerik){: .top}

<h2 id="selection">9. Selecting several items and tools</h2>

Press **Start selection** to turn on selection mode.

- Each item reads "Selected" or "Not selected"; the top of the screen shows how many items are selected.
- At the start of the list are **Select all these results** and **Clear selection**; day headers have a **Select group** button.
- For selections of up to 500 items, the total size is calculated and shown automatically; for larger selections a **Calculate size** button appears.
- The bottom toolbar has **Share** (up to 100 items), **Add to favorites** and **Delete from Photos library**.

The **More actions** section of the list has these tools:

- **Create PDF:** Up to 50 images. Arrange the page order with the Move up and Move down actions. No searchable text layer is added to the PDF.
- **Compress photos:** Up to 50 photos. Makes JPEG copies at Small, Medium or High quality. The originals do not change, and location and camera information is not added to the copies. Videos, Live Photos, RAW, HDR and animated images cannot be compressed.
- **Name selected items:** Gives a common name; if "Number in order" is on, it numbers them starting from the oldest. **Remove name from selected items** removes the names in one go.
- **Add tags:** Adds a tag to everything you selected. **Remove tag from selection** removes a tag from these items only.

When the PDF is ready, the share sheet opens by itself; for compressed copies, press the **Share** button. From the share sheet you can send them or save them to Files.

[Back to top](#icerik){: .top}

<h2 id="deletion">10. Safe deletion</h2>

Deleting in Memora always asks twice. First Memora opens its own confirmation, which says what will be deleted and that this is not removing a tag or taking the item out of an album. If you confirm, the Apple Photos system confirmation follows. Deleted items go to the Recently Deleted album in the Photos app; how long they stay there depends on Apple Photos, and you can recover them from there.

After a deletion, VoiceOver focus does not jump to the top of the screen; it moves to the next item, or to the previous one if there is no next. If you cancel, focus stays where it was.

[Back to top](#icerik){: .top}

<h2 id="scanning">11. Text in photos and scanning</h2>

- On a new install, the scan scope is "All photos". You can change it to "Screenshots only" or "Off" in **Settings > Search and indexing > Analysis scope**. Narrowing the scope does not delete text that was already found.
- Scanning only moves forward while Memora is open. It pauses in Low Power Mode, when the device is hot or when it is locked, and resumes by itself when conditions improve. These are not errors.
- Videos are not scanned. Photos stored only in iCloud cannot be scanned until they are downloaded to the device.
- The Search and indexing screen shows how many items are done and why scanning is waiting. The **Pause indexing**, **Resume indexing** and **Reset and rescan the index** buttons are here. Resetting only deletes the text that was found and starts scanning from the beginning; it does not touch your names, tags or photos.

[Back to top](#icerik){: .top}

<h2 id="settings">12. Settings</h2>

### Appearance

- **View:** List, Grid or Automatic. With Automatic, the list is used while VoiceOver is on.
- **Date grouping:** Day, Month or No grouping.
- **Grid density:** 2, 3, 5 or 8 items per row in the grid. You can also change it on the library screen by pinching with two fingers, or with the VoiceOver actions "More per row" and "Fewer per row".

### Accessibility

- **Automatic reading:** How much of the text in a photo is read in the list: Off, Short (500 characters), Long (2000 characters) or Full text. Notes and descriptions are cut to the same limit. The full text is always on the Text screen.
- **Text layout:** Whether the Text screen shows the text as a Single block (the default) or Line by line. In Line by line, each line is its own element, read by swiping right.
- **Announce text presence** and **Read tags:** Whether you hear this information in the list.
- **Read notes in the list** and **Read descriptions in the list:** When on, you hear the text itself; when off, only "Has a note" or "Has a description".
- **Video:** Play videos while swiping, Play sound in silent mode, Repeat video.
- **Rotor actions:** Turn actions on or off, and reorder them with the **Move up** and **Move down** actions.

### Search and indexing

The analysis scope (All photos, Screenshots only, Off) and the scan status.

### Tags

Create tags, correct their names or remove them from your library. If you rename a tag to the name of another existing tag, the two tags are merged. Removing a tag does not delete any photos.

### Memora data

This data is not your photos; it is what you wrote in Memora and your preferences.

- **Export Memora metadata:** Saves the names and tags you added, and the matching information that shows which photo they belong to, in a single file. Photos, the text in photos, notes, descriptions and settings are not included in this file.
- **Import Memora file:** Restores that file on a new device and shows you what will change first. When there is a conflict, you choose "Keep current data" or "Use changes from the file". You can link records that did not match to a photo yourself from the "Unlinked records" screen.
- **Backup:** Your names, tags, notes and descriptions are included in your device's iCloud backup. The text in photos is not backed up; it is scanned again on a new device.
- **Delete all Memora data:** Deletes Memora's names, tags, settings and index. It does not touch your photos, files you exported or your Apple purchase history.

### Privacy and support

Explains what Memora does and does not do with your data; the privacy policy and support page open from here.

### Help

- **Support the Developer:** Optional support purchases do not unlock any features; they are simply a thank you. You can also support the app for free by leaving a rating on the App Store.
- **Feedback:** Opens a screen for writing an email to the developer. Shaking the device opens the same screen.

[Back to top](#icerik){: .top}

[View Memora on the App Store](https://apps.apple.com/app/id6809805472){: .button}
