---
source:
  - recepgur07-bot.github.io/tr/framemate/kilavuz.md
  - video recorder/Sources/VideoRecorderApp/Localizable.xcstrings
layout: default
lang: en
title: FrameMate user guide
permalink: /en/framemate/guide/
alt_url: /tr/framemate/kilavuz/
description: Every FrameMate recording mode, what you hear, the shortcuts and the layout switches, with concrete examples. Written for VoiceOver users.
---
<!-- Source: tr/framemate/kilavuz.md (from pazarlama/uygulamalar/video-recorder/TANITIM-METNI.md). UI names and spoken messages are the en values in FrameMate's Localizable.xcstrings. Update both guides together. -->

# FrameMate user guide

FrameMate makes four kinds of recording on your Mac, and it tells you out loud what is happening in each one.

**Camera video.** You record yourself, as landscape video (YouTube, presentations) or portrait video (Reels, Shorts, TikTok). You choose the sound: your microphone alone, or the Mac's system sound as well. Frame Coach tells you by voice whether your face is in the frame, whether to move left or right, and whether you are too close or too far.

**Screen recording.** You record the whole screen or one window you pick. If you like, you can also show yourself in a small box over the screen. The box can sit in any of nine positions and come in three sizes. Your microphone and the system sound are optional. While you record, a shortcut can switch to just you, or to just the screen.

**Phone recording.** You record the screen of an iPhone or iPad connected by cable. The video can keep the phone's own proportions, be portrait or landscape, or put the phone on one side and you on the other. You can add the phone's sound to the video, listen to it live through your headphones, show yourself on screen, and switch the layout with shortcuts.

**Audio recording.** No picture, only sound: your microphone, the Mac's system sound and the phone's sound, together or one by one.

Every button, setting and state in the app is spoken by VoiceOver, so you can always find out which microphone, which sound and which layout is on without seeing the screen.
{: .lead}

This guide is written so you can use FrameMate without seeing it. For each mode it explains what you can choose, what you will hear when you press a key, and what the finished video will look like. Names of buttons and settings are exactly as they appear in the app. Move between sections with the VoiceOver headings rotor, or jump to a section from the list below.

<nav class="toc" aria-labelledby="toc-heading" markdown="1">
<h2 id="toc-heading">On this page</h2>

1. [Before you start: permissions](#permissions)
2. [Getting to know the app: modes and status announcements](#overview)
3. [Camera recording and Frame Coach](#camera)
4. [Screen and window recording](#screen)
5. [Layout switches: "Full-screen video", "Full-screen screen", "Full-screen phone"](#layouts)
6. [Recording your phone screen](#phone)
7. [Audio-only recording](#audio)
8. [While you record: shortcuts and what you hear](#shortcuts)
9. [When the recording ends](#finish)
10. [Settings](#settings)
11. [Troubleshooting](#troubleshooting)
</nav>

<h2 id="permissions">1. Before you start: permissions</h2>

This section explains which permissions FrameMate needs on your Mac and how to grant them.

macOS asks for your approval before an app can use the camera, the microphone or screen recording. FrameMate only asks for what the recording you are about to make needs:

- **Camera permission:** needed for camera recording, for adding yourself to a screen recording, and for recording a phone screen. Your Mac treats a connected phone like a camera, which is why phone recording also needs this permission.
- **Microphone permission:** needed whenever you record with your microphone.
- **Screen Recording permission:** needed to record the screen, a single window, and **the sound playing on your Mac**. It is not needed when you only record your camera or only your microphone.
- **Accessibility permission:** optional. It makes the Cmd+I status announcement and the global shortcuts work reliably from any app, and it lets pressed shortcut keys appear in a screen recording. Basic recording does not need it.

The first time you open FrameMate, a four-step welcome appears: "Step 1 of 4: Welcome to FrameMate", "Step 2 of 4: Recording Modes", "Step 3 of 4: We Need a Few Permissions" and "Step 4 of 4: How It Works". Step 3 has a separate button for each permission: **Grant camera access**, **Grant microphone access** and **Request screen recording permission**. When you press one, macOS opens its own permission dialog. VoiceOver reads it, and you choose Allow. The dialog sometimes ends up behind the FrameMate window. If you do not hear it, press Cmd+Tab to move between windows.

Two things to watch:

- **After you grant Screen Recording permission, you must quit FrameMate completely and open it again.** When you grant it, the app announces "Screen recording permission granted — restart the app for the change to take effect." Until you restart, the screen picture and the system sound cannot be recorded.
- If you refused a permission by mistake, or FrameMate is not in the list, open **System Settings > Privacy & Security > Screen Recording**. If FrameMate is missing, press the add (plus) button, pick FrameMate from the Applications folder, and turn on the switch next to it.

You can check at any time whether you are ready. The status line says something like "Ready status: Microphone ready. Screen recording is not needed right now. Camera ready." For the first 7 days every recording feature is unlimited and you do not need an account. After that, FrameMate Pro is needed to keep recording.

[Back to top](#icerik){: .top}

<h2 id="overview">2. Getting to know the app: modes and status announcements</h2>

This section covers the four recording modes, and how to hear the state of everything with one key.

The Recording Mode list has four options. You can open the list with the Space bar and pick with the arrow keys, or use the shortcuts directly:

- **Camera** (Cmd+1): records your camera. You choose landscape or portrait, pick the microphone, and can add the Mac's system sound. Frame Coach works here.
- **Screen** (Cmd+2): records the whole screen or the single window you pick. Microphone and system sound are optional. You can show yourself in a small box over the screen, choosing its position from nine and its size from three.
- **Audio** (Cmd+3): records no picture. It records the microphone, the system sound and the phone's sound, separately or together.
- **Phone Screen** (Cmd+4): records the screen of an iPhone or iPad connected by cable. It offers five video layouts, phone sound, and showing yourself.

When you choose a mode, VoiceOver says its name, for example "Mode selected: …". The app remembers your last mode and starts with it next time.

**Hear the state of a recording with one shortcut.** Press Cmd+I while FrameMate is in front, or Cmd+Option+B from any other app:

- **Before the recording starts**, it reads out the settings of the next recording. In Camera mode, for example: "Landscape video, Camera MacBook Camera, microphone MacBook Microphone, system sound off, Frame Coach is on." In Screen mode: "Source full screen, screen …, microphone …, system sound on, cursor highlight on, camera box on." In Phone Screen mode, it tells you whether the phone is connected, which layout is chosen, and the sound settings. If a permission is missing it adds "Missing permissions: …" at the end.
- **While you are recording**, it reports the state of the recording that is running: "Recording. Phone Screen, 1 minute 5 seconds. Layout Side by side. Phone sound on. Microphone on." If you paused, it begins with "Recording paused." Since you cannot watch the live picture, this is very useful: you can confirm which sounds and which layout are active without stopping the recording.

To start recording, press the **Start Recording** button, or use **Cmd+Option+R**, which works from any app. If a countdown is on, you hear "Recording starts in 3 seconds…" counting down, and then "Recording started". In Settings you can also turn on sound effects for recording started, stopped and paused.

[Back to top](#icerik){: .top}

<h2 id="camera">3. Camera recording and Frame Coach</h2>

This section covers recording yourself as landscape or portrait video, choosing the microphone, and keeping yourself in the frame without seeing it, with Frame Coach.

When you choose Camera mode (Cmd+1), you have these settings:

- **Video orientation:** two choices. Landscape 1920 by 1080 (Cmd+Shift+Y) suits computer screens, presentations and YouTube. Portrait 1080 by 1920 (Cmd+Shift+D) suits phone-first content such as Reels, Shorts and TikTok. When you choose, you hear "Landscape video selected. 1920 by 1080." or "Portrait video selected. 1080 by 1920."
- **Camera:** your Mac's own camera, an external webcam, or your iPhone's rear camera through Continuity Camera. If no camera is found, the app says "No camera found. Connect one."
- **Microphone:** the MacBook microphone, an external microphone or a headset microphone. The **Microphone channel** setting offers Automatic, Mono and Stereo. For speech, Mono often gives a cleaner, clearer sound.
- **Include system audio:** adds whatever is playing on your Mac, such as music, videos or app sounds, to the recording. If you only want your own voice, keep it off. Turning it on needs Screen Recording permission.

### Frame Coach: stay in the middle of the frame

When you sit in front of the camera, you cannot tell without looking whether your face is in the middle of the picture. Frame Coach watches your camera image and gives you spoken guidance to correct your position.

Turn Frame Coach on and off with **Cmd+D**, or with **Cmd+Option+O** when you are in another app. When it turns on you hear "Frame Coach is on".

Frame Coach watches the camera and tells you the most important correction first. Some of the things you might hear:

- "Face not detected, look at the camera": the camera cannot see your face.
- "You are partly out of frame, move slightly right" or "…move slightly left": your face is touching the edge of the picture.
- "Too close, move back so your shoulders and chest are visible", or "Frame is too far, move closer."
- "Raise the camera slightly" or "Lower the camera slightly": suggestions for the camera angle or how you sit.
- "Low light, illuminate your face."
- "Frame is good": everything is fine, you are ready to record.

If more than one person is in front of the camera, it first says how many it sees: "One person visible", "Two people visible" or "Three people visible". With more than three it says "More than three people are visible, guidance is based on the three most prominent people." The guidance also names the person: "Person on the left is partly out of frame, move slightly right", "Person on the right is too high in frame, sit a little lower" or "You are too far apart, move closer together." The rules for one or two people apply automatically; you do not need to set anything.

**An important rule:** Frame Coach stays silent once recording has started, because its own voice would end up in the video. So you set up your frame during preparation, before you start. When the recording ends, Frame Coach speaks again.

You can change how Frame Coach behaves in Settings:

- **Feedback frequency:** Minimal (it speaks only when you drift clearly), Balanced, or Frequent (it reports every few seconds).
- **Repeat same warning:** how many seconds pass before the same warning is repeated.
- **How guidance is delivered:** Automatic (a VoiceOver announcement if VoiceOver is on, the app's own voice if not), VoiceOver, app voice, or Silent.
- **Guidance voice:** Off, Direction tones only, or Direction tones and speech. With direction tones and headphones, the ear the sound comes from tells you which way to move: if you hear it in your right ear, move right; if in your left ear, move left. In Mono mode the sound always comes from the middle.
- **Play center confirmation:** a short confirmation sound plays when your face sits exactly in the center, so you know you found the spot.
- **Show guidance text on screen:** also writes the spoken guidance on the screen.

### Auto reframe

Turn it on and off with **Cmd+Shift+A**. When it turns on you hear "Auto reframe on". When you record alone and lean or move around in your chair, the software balances the picture and keeps your face in the middle of the frame. The correction is applied to the finished video.

[Back to top](#icerik){: .top}

<h2 id="screen">4. Screen and window recording</h2>

This section covers recording your Mac screen or one window, the sound options, and how to show yourself on the screen.

When you switch to Screen mode (Cmd+2), you first choose where the picture comes from:

- **Full screen:** records your whole Mac screen. If you use more than one display, you pick the one you want from Screen selection.
- **Window:** records only one app's window. You pick it from Window selection. The window must be open and in front. A minimized window is recorded as black (see [Troubleshooting](#troubleshooting)).

Then you choose the sound:

- **Microphone:** for your own voice and commentary.
- **Include system audio:** adds everything playing on your Mac, such as videos, music or app sounds. Turn it on if, for example, you are demonstrating a program and want its sound heard. If your own voice is enough, leave it off. System sound level and microphone level are set separately, so your voice does not get buried under background sound.
- The sound coming out of the Mac's speakers can get back into the microphone. If you record the microphone and system audio together, headphones prevent the echo.

Visual aids:

- **Highlight Cursor** (Cmd+Shift+C): adds a clear ring around the mouse pointer and marks where you click, so viewers can follow where you click. When it is on you hear "Cursor highlight on".
- **Show keyboard shortcuts:** briefly shows the shortcuts you press, such as Cmd, Control and Option, over the video. This needs Accessibility permission.

### Camera box: you, anywhere on the screen

If you turn on **Camera Box** while recording the screen, your camera appears as a small box over the screen picture. It works like the presenter you see in a corner of a TV news broadcast or a game stream.

In the camera box you set:

- **Camera for the camera box:** the Mac camera, an external camera or an iPhone camera.
- **Camera box position:** nine positions: Top Left, Top Center, Top Right, Center Left, Center, Center Right, Bottom Left, Bottom Center and Bottom Right. You can take a corner, the middle of an edge, or the exact center. Pick a spot that does not cover anything important on the screen. Many people use Bottom Right or Bottom Left.
- **Camera box size:** Small, Medium or Large.

With the camera box on, your video shows the screen and you together. While recording, a shortcut can also switch to just you or just the screen. The next section explains that.

When you pick a position or size, VoiceOver reads the result, for example "Output preview. Camera box at Bottom Right position and in Medium size." You hear immediately where the box will land. With the camera box on, Frame Coach also works for how you sit in that box. You cannot turn the camera box on or off once recording has started, but you can enlarge or reduce yourself while recording.

[Back to top](#icerik){: .top}

<h2 id="layouts">5. Layout switches: "Full-screen video", "Full-screen screen", "Full-screen phone"</h2>

This section explains how to change the shape of the picture with shortcuts while you record the screen or the phone.

If the camera box is on during a screen or phone recording, one shortcut can change the layout of the picture while you record. The names can be confusing, so here is what each one means for the person watching:

- **Default layout** (Cmd+Option+G):
  - **What it looks like:** think of a tutorial or a game stream. Your computer screen fills the whole frame, and you are in a small box in the position you chose.
  - **When to use it:** press it whenever you want to return to your normal starting view. (In a phone recording with a side-by-side layout, this key goes back to that side-by-side layout, and the announcement is "Side by side".)
- **Full-screen video** (Cmd+Option+V):
  - **What it looks like:** like a news presenter who comes on alone and speaks straight to the audience. Your computer screen or phone is hidden completely. Viewers see only your camera, which means only you, across the whole frame.
  - **When to use it:** when you want to address the audience directly without showing the screen: an introduction, a summary, or a goodbye.
- **Full-screen screen** (Cmd+Option+E):
  - **What it looks like:** like putting a presentation slide on its own. The camera box is hidden. Viewers do not see you, only your Mac screen.
  - **When to use it:** when you are showing a small line of text, the corner of a table, or any important detail the camera box might cover.
  - **In a phone recording:** the same option is called **Full-screen phone**. The camera box is hidden and the video shows only your phone screen.
- **Side by side** (for the side-by-side layouts of a phone recording):
  - **What it looks like:** like a TV talk show with the screen split in two. The phone screen fills one half, and you appear large in the other half.

When you press a layout key, the name of the layout is announced: "Full-screen video", "Full-screen screen", "Full-screen phone", "Default layout" or "Side by side". A short confirmation sound follows, and that sound does not go into the video. If you press the same key again, you do not leave that layout; you only hear where you are again. To go to another layout, press its shortcut. To return to where you started, press **Cmd+Option+G**.

Three important rules:

- **The change does not show in the live preview on the screen. It shows in the finished video.** No source is cut off while you record. The switch happens in the video as a smooth quarter-second transition.
- If the camera box is off for the recording, these keys do not work. When you press one, the app says "This recording has no camera box. Turn the camera box on before recording starts." The shortcut that turns the camera box on or off (**Cmd+Option+K**) can only be used before recording starts.
- You can also use these shortcuts before recording starts. That lets you choose how the recording will **begin**. For example, pressing Cmd+Option+V before recording makes the recording open with the camera full screen. If you forget which layout you are in, **Cmd+Option+B** tells you straight away.

**An example lesson recording:** Set the camera box to Bottom Right and Medium size. Before you start, press Cmd+Option+V (you hear "Full-screen video"). Start recording, introduce yourself and summarize the lesson. Then press Cmd+Option+G to go to the default layout (you hear "Default layout"); your Mac screen fills the frame and you are in the corner. When you want to show a detail on the screen, press Cmd+Option+E to hide yourself ("Full-screen screen"). To finish, press Cmd+Option+V again and say goodbye with just you on screen.

[Back to top](#icerik){: .top}

<h2 id="phone">6. Recording your phone screen</h2>

This section explains how to connect an iPhone or iPad by cable and record it, the layout options, and the sound settings.

This mode sends the screen of your iPhone or iPad to your Mac through a cable and records it. It does not work wirelessly; the device must be connected to the Mac by cable.

**Getting ready:**

1. Connect your phone to the Mac with the cable.
2. Unlock the phone. While it is locked, no picture reaches the Mac.
3. If the phone asks "Trust This Computer?", tap Trust and enter your passcode.
4. In FrameMate, choose Phone Screen as the Recording Mode (Cmd+4). On the status line you first hear "… found, connecting.", and then "… ready." If the device is not ready yet, you hear "No phone connected. Connect the cable and unlock the phone." or "The phone isn't ready yet. Wait until the picture arrives."
5. If more than one device is connected to the Mac, choose the one to record from **Phone selection**.

**Video layout options:**
There are five layouts. Your choice is remembered next time:

1. **Keep phone aspect ratio:** adds no borders or black bars and records at the phone's own proportions. This is the best choice for videos that show only the phone, such as an Instagram story or an app demo.
2. **1080 by 1920 portrait:** the standard portrait size for Reels, YouTube Shorts and TikTok. The phone screen sits in the middle of the portrait frame.
3. **1920 by 1080 landscape:** the standard landscape size for YouTube or computer presentations. A portrait phone screen stays in the middle, with empty space on both sides.
4. **Side by side, camera on the right:** the frame is split in a landscape video. The phone screen is on the left at full height, and you are on the right in large size.
5. **Side by side, camera on the left:** the phone screen is on the right, and you are on the left in large size.

The side-by-side layouts **need the Camera Box to be on**. If it is off, the app warns you and the video falls back to a centered landscape layout.

**Sound settings and important rules:**

- **Record phone audio:** adds the music, video and app sound playing on the phone to the recording. If it is off, the video is silent, apart from your microphone.
- **If you use VoiceOver on the phone:** VoiceOver's speech counts as phone sound and goes into the recording. This should be a deliberate choice. If you are making a VoiceOver tutorial, leave it on. If you do not want VoiceOver's voice in the video, turn **Record phone audio** off.
- **Hear Phone Through Speakers** (Cmd+Shift+H): with the phone connected by cable, its sound comes to the Mac and does not play from the phone itself. Keep this on if you want to hear what you are doing on the phone; otherwise you hear nothing from it. This setting is only for your listening. It does not change what goes into the recording.
- **Listening with headphones:** if you have headphones on your Mac and Hear Phone Through Speakers is on, everything from the phone, including VoiceOver's speech if you use it on the phone, comes through your headphones. What goes into the recording is set separately by Record phone audio. So three things are independent: whether the phone's sound goes into the recording, whether you listen to the phone, and whether your microphone goes into the recording. You can listen to the phone through headphones and put only your own voice in the video, or only the phone's sound.
- **Always wear headphones to prevent echo.** If the phone's sound plays from the Mac's speakers while your microphone is on, the phone sound enters the microphone and echoes. FrameMate warns you: "The microphone is recording while phone audio plays through the speakers. Use headphones to avoid echo." If the Mac's system sound is also on, the phone sound can enter the video twice. In that case, turn the system sound off.

**Changing the layout while you record:**
The layout shortcuts work the same way in a phone recording. If you chose a side-by-side layout: **Cmd+Option+V** makes you full screen, **Cmd+Option+E** spreads the phone alone across the frame ("Full-screen phone"), and **Cmd+Option+G** returns to the side-by-side layout ("Side by side"). The details are in [Layout switches](#layouts).

**Things you may run into:**

- **If the phone picture is completely black:** VoiceOver's screen curtain may still be on. Tap the screen three times with three fingers to turn it off. If the phone went to sleep, wake it. FrameMate reports the black picture while you record by saying "phone screen looks black".
- **If you rotate the phone to landscape or portrait:** the app announces "Phone rotated to landscape. Fitting the picture to the recording canvas." (or "…to portrait…") and re-fits the picture to the video frame you chose.
- **If the cable comes out:** the recording is stopped safely and what you recorded so far is kept: "Phone disconnected. Stopping the recording."
- If no picture arrives at all, unlock the phone, confirm the trust prompt, and unplug and reconnect the cable.

[Back to top](#icerik){: .top}

<h2 id="audio">7. Audio-only recording</h2>

This section covers recording without a picture, such as a podcast, a meeting or voice notes.

When you do not need a picture, for a podcast, a lecture or a voice note, use Audio mode (Cmd+3):

- Choose your **Microphone**. If you also want the sound playing on your Mac, or the other side of a meeting, turn on **System sound**. At least one of the two must be on to start; otherwise the app says "Select a microphone or enable system audio for recording."
- **Microphone channel:** choose Automatic, Mono or Stereo.
- To start, press **Start Audio Recording**, or use **Cmd+Option+5**. Press the same key again to stop.
- When you finish, the file is saved as an **M4A** audio file.

If you also want the phone's sound, connect the phone by cable, pick it, and turn on phone sound. The sound of your Mac, the sound of the phone and your microphone can go into the same recording together.

While recording, you can press **Cmd+Option+B** at any time to hear the state: "Microphone …, system sound on." You can pause with **Cmd+Option+P** and continue with the same key.

[Back to top](#icerik){: .top}

<h2 id="shortcuts">8. While you record: shortcuts and what you hear</h2>

This section covers the global shortcuts you can use while recording, even when you are in another app, and what each one says back.

FrameMate's global shortcuts work when the app is in the background or when you are working in another program. When you press one, the app tells you out loud what it changed:

- **Cmd+Option+R:** starts or stops the recording. When it starts you hear "Recording started". When you stop, you hear "Recording stopped. Preparing file" and then "Recording finished, file ready".
- **Cmd+Option+5:** starts or stops an audio recording.
- **Cmd+Option+P:** pauses the recording ("Recording paused.") or resumes it. The paused part is not in the video, and the recording continues cleanly from where it left off.
- **Cmd+Option+V, E, G:** change the layout of the picture (see [Layout switches](#layouts)).
- **Cmd+Option+K:** before recording starts, turns the camera box on or off ("Camera box on", "Camera box off").
- **Cmd+Option+S:** turns the system sound on or off. You hear "System sound on" or "System sound off".
- **Cmd+Option+F:** turns the phone sound on or off.
- **Cmd+Option+M:** turns the microphone on or mutes it. If you need to cough while talking, or have a quick word with someone next to you, you can mute the microphone without stopping the recording and turn it back on afterwards.
- **Cmd+Option+B:** summarizes the state of the recording.
- **Cmd+Option+O:** turns Frame Coach on or off (Frame Coach is silent during recording anyway).

Shortcuts you can use when the FrameMate window is in front: Cmd+1 to Cmd+4 for the mode; Cmd+Shift+Y and Cmd+Shift+D for video orientation; Cmd+Shift+C for cursor highlight; Cmd+Shift+A for auto reframe; Cmd+Shift+H for hearing the phone through the speakers; Cmd+Shift+O to open the last recording; Cmd+Shift+F to show it in Finder; Cmd+D for Frame Coach; Cmd+I to hear the settings summary.

**An important rule:** while you record, a shortcut can only change what was chosen for that recording from the start. For example, if you did not turn the phone sound on when you started, then pressing Cmd+Option+F during the recording makes the app say "This recording has no phone audio. Turn phone audio on before recording starts." A new sound track cannot be added to a video that has already started. The same rule applies to the microphone, the system sound and the camera box. If you press a key that has no meaning for that recording, for example a layout key while you record only audio, FrameMate stays quiet while it is in the background, and explains why it did not work when its window is in front.

**Safety measures:**

- If you pause, do not forget it. **Cmd+Option+B** reminds you with "Recording paused."
- If the microphone is unplugged, the recording pauses by itself and you hear "Microphone disconnected. Recording paused — reconnect the microphone and press Resume."
- If disk space runs low, you hear "Disk space is running low." If it gets critically low, the recording is stopped and saved safely so the file is not damaged.
- If your Mac is about to go to sleep, the recording is likewise finished and saved safely.

[Back to top](#icerik){: .top}

<h2 id="finish">9. When the recording ends</h2>

This section covers how to reach your file after the recording stops, and how to check and rename it.

When you stop the recording, your video file is prepared. The window stays open meanwhile, and when it is done you hear "Recording finished, file ready". The window then offers:

- **Open Last Recording** (Cmd+Shift+O): opens the file in your Mac's default player right away, so you can listen to or watch it at once.
- **Show in Finder** (Cmd+Shift+F): opens Finder with the folder and the file selected.
- **Rename:** lets you give the file a new name. You do not type the extension; it is added automatically. When it is done you hear "Renamed: …".
- **Save As:** copies the recording to another folder.

Screen, camera and phone recordings are saved as standard **MP4** at 1080p, and audio recordings as **M4A**. You choose the folder where recordings are collected in the **Default recording folder** setting.

[Back to top](#icerik){: .top}

<h2 id="settings">10. Settings</h2>

This section covers how to adjust recording times, sound effects and the way the app runs, to suit your habits.

The Settings window has these options:

- **Countdown duration:** how many seconds after you press Start Recording the recording begins, for example 3 seconds.
- **Maximum recording duration:** you can record without a limit, choose a ready-made length, or set a Custom limit between 5 seconds and 60 minutes. When the time is up, the recording stops safely by itself.
- **Recording end warning:** in the last 3, 5 or 10 seconds before the time runs out, it gives a countdown sound and a spoken warning. It does not cut the recording short.
- **Remind me of recording duration regularly** and **Reminder style:** announces the elapsed time at regular intervals. With Voice announcement (VoiceOver), VoiceOver says the time. With Sound effect, only a short tick plays. If you record with the built-in microphone, wear headphones or turn the reminder off so it does not leak into the microphone.
- **Sound effect:** short confirmation sounds for recording started, stopped and paused, and when you press a shortcut. These effects do not go into the video.
- **Live layout:** controls the notices when the layout changes during a recording: "Announce live layout changes" and "Play a sound for live layout changes".
- **Hide window when recording starts** and **Show window when recording stops:** keeps FrameMate's own window out of your screen recording.
- **Show in Dock** or **Run in menu bar only** sets where the app lives. There is also **Launch at Login**.
- **Default recording folder:** the folder where all your video and audio recordings are saved.
- **Quick Help:** a short usage guide inside the app. Links to **Help and Support**, the Privacy Policy and the Terms of Use are on the same screen.

[Back to top](#icerik){: .top}

<h2 id="troubleshooting">11. Troubleshooting</h2>

This section covers the problems you are most likely to meet, and how to fix them.

- **Camera, microphone or screen recording does not work:** in **System Settings > Privacy & Security**, check that the permissions are on.
- **FrameMate is not in the Screen Recording list:** press the add (plus) button in Screen Recording, pick FrameMate from the Applications folder, turn on the switch and restart the app. The permission dialog can sometimes be behind other windows.
- **System sound does not get into the video:** check the Screen Recording permission, and make sure you quit FrameMate completely and reopened it after granting it.
- **No picture from the phone:** unlock the phone, confirm the "Trust" prompt, and unplug and reconnect the cable.
- **The phone's sound started playing from the phone itself:** unplug the cable and plug it in again.
- **The recorded window or screen is black:** make sure the window is open and in front, and not minimized or transparent. Check that the display is not asleep. If this happens while you record, FrameMate says "The screen looks completely black and is being recorded that way. Make sure the display is awake." The warning does not stop the recording, because you might really be recording a black window.
- **A sound or the camera is missing from the video:** before you start, read the notes under the matching switch. Sources that are not ready are named. A shortcut that cannot work also says why when you press it.
- **Announcements and shortcuts do not work reliably:** allow FrameMate in System Settings > Privacy & Security > Accessibility.

If you need help with anything else, use the Help and Support link in the app, or the Support page on this site.

[Back to top](#icerik){: .top}
