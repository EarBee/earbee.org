---
title: "Music transcription software for Linux: what really runs"
description: "Looking for music transcription software on Linux? Nine tools that run there, how each one installs, which famous ones don't, and which I'd pick."
keyword: "music transcription software linux"
date: 2026-11-09
---

Looking for music transcription software on Linux? There's more than you might think, but less than on Windows or a Mac, and some of the well-known names don't run there at all. If you want one app made for working songs out by ear, with slowing down, loops, marks and video, try [EarBee](/), a free, open-source player for Linux, Windows and Mac. I make it, so weigh my opinion accordingly. I also build it on Linux, so Linux isn't an afterthought.

Below: what "transcription software" can mean, the tools that really run on Linux and how each one installs, the ones that don't, and which I'd pick.

## Is there software that can transcribe music?

Yes, but the phrase covers two different kinds of program:

- **Tools that help you do it by ear.** They slow the song down without changing the pitch, loop the passage you're stuck on, and help you find your way around it. You do the listening; they make it easier. Most of the tools below are this kind.
- **Tools that do it for you.** They listen to a recording and write out the notes or the chords. They save time, and they make mistakes you then have to find by ear. On Linux, AnthemScore is one.

And then there's writing it down. If you want sheet music at the end, you need a notation program too, such as MuseScore, or TuxGuitar for tab. They don't listen to anything: you type in what you've worked out.

## What to check on Linux

Whatever the tool, a few things matter more on Linux than elsewhere:

- **A real Linux version,** not one that only runs through a compatibility layer.
- **How it's packaged:** an AppImage runs on almost any distribution; a `.deb` or a distribution's own package fits in with the rest of your system; a tarball is up to you.
- **Who made the package.** Some tools come in packages made by their developers, others by volunteers in each distribution. Both can be fine, but the second kind may lag behind, or behave differently.

## The tools that run on Linux

### 1. EarBee

[EarBee](/) is made for one thing: working out music by ear. It slows a song or a video down without changing the pitch, shifts the pitch, and has an EQ. You loop a passage by dragging across the waveform, mark the sections of the song, and step through a phrase from the keyboard. It can find the beats and bars, and then loop the bar you're in. It can split a song into stems (the vocals, the drums, the bass, the guitar and so on), on your own computer, so you can hear one part alone or play along without it. Videos stay in sync at any speed, and you can paste a YouTube link.

**On Linux:** an AppImage for 64-bit PCs, from [the download section](/#download). Make it executable and run it; it updates itself when a new version is out. I use [Gear Lever](https://gearlever.mijorus.it/) to keep my AppImages in the app menu. There's no trial, no paid version and no account ([why](/#free)).

What it doesn't do: write out the notes or the chords for you, or open FLAC files.

### 2. Transcribe!

[Transcribe!](https://seventhstring.com/xscribe/overview.html), from Seventh String Software, is the long-standing paid tool for working out music by ear: slowing down, pitch shift, loops, markers, an EQ, video, and a spectrum view that suggests the notes. It's $39, paid once, after a 30-day trial ([its price page](https://seventhstring.com/xscribe/buy.html)).

**On Linux:** a tarball for 64-bit PCs, with a script that installs it in your home folder ([the Linux download page](https://seventhstring.com/xscribe/download_linux.html)). It needs GStreamer and GTK 3, and it "can only run on the X11 back end" ([its distribution notes](https://seventhstring.com/xscribe/linux_distros_86.html)). Those notes also list which distributions it's been tried on, and its developer advises against the Flatpak some distributions offer, since he doesn't make it and it "doesn't work properly".

### 3. Sonic Visualiser

[Sonic Visualiser](https://sonicvisualiser.org/), from Queen Mary University of London, is free software (GPL) for studying recordings closely. It slows playback down keeping the pitch, loops a selection, and lets you add labelled points and layers of notes. Its spectrograms are excellent, and plugins can add analysis such as beat tracking or note estimation. It's a research tool first, so there's a lot to learn before it feels quick, and it plays audio only.

**On Linux:** an AppImage, a `.deb` for Ubuntu, or the source code ([its download page](https://sonicvisualiser.org/download.html)). The analysis plugins are a separate download.

### 4. AnthemScore

[AnthemScore](https://www.lunaverus.com/) is the one here that does it for you: it turns a recording into sheet music, MIDI or MusicXML, then lets you correct the notes it got wrong. It costs $29, $39 or $99 once, depending on the edition; the free trial does the first 30 seconds of each song. I wrote more about it in [AnthemScore free alternative](/blog/anthemscore-free-alternative/).

**On Linux:** an AppImage ([its download page](https://www.lunaverus.com/download)). It was "tested on Ubuntu 20.04 and later", and the page warns that on some other distributions the licence may not work without root.

### 5. Audacity

[Audacity](https://www.audacityteam.org/) is a free audio editor, with a waveform, labels and loop playback. You can slow a passage down without changing its pitch, but it's an editor, and it feels like one when all you want is to listen. It's great for cutting a passage out to practise with.

**On Linux:** AppImages for 64-bit PCs and for ARM ([its Linux page](https://www.audacityteam.org/download/linux/)). Distributions offer their own packages too, which the page says "may have distribution-specific patches applied to them".

### 6. VLC

You may already have [VLC](https://www.videolan.org/vlc/). It keeps the pitch when you change the speed, plays almost any audio or video file, has a graphic equaliser, and has an A→B loop (turn on **View › Advanced controls**, then click the button at the start and at the end). There's no waveform, so setting a loop precisely means clicking at the right moment. Fine for a riff now and then.

**On Linux:** your distribution's package, or the Snap ([its Ubuntu page](https://www.videolan.org/vlc/download-ubuntu.html)).

### 7. Play it Slowly

[Play it Slowly](https://29a.ch/playitslowly/) is a small, simple Linux app: open a file, change the speed or the pitch, loop a part. It plays video too. It does that well, but it's old: its page dates from 2015, and [its code](https://github.com/jwagner/playitslowly) last changed in 2022.

**On Linux:** its page says to install it with your distribution's package manager, if it has it.

### 8. MuseScore Studio, for writing it down

[MuseScore Studio](https://musescore.org/) isn't a transcription tool in the listening sense: it's free notation software (GPL), the best-known one on Linux. Its official pages say nothing about turning a recording into notes, so you work the music out with one of the tools above, then write it down here. If you were searching for music notation software for Linux, this is probably the one you want.

**On Linux:** an AppImage (which its page recommends), a Flatpak, a Snap or your distribution's package ([its download page](https://musescore.org/en/download)).

### 9. TuxGuitar, for writing tab

[TuxGuitar](https://www.tuxguitar.app/) is a free, open-source (LGPL) tablature editor and player, and the usual free alternative to Guitar Pro. Like MuseScore, it doesn't listen to recordings: it's where you write down what you've worked out, as tab and standard notation, and hear it played back. It opens Guitar Pro files, along with Power Tab, TablEdit and MIDI, and it can save in Guitar Pro's older formats (GP3, GP4 and GP5), so you can share a tab with someone who uses Guitar Pro.

**On Linux:** a `.deb`, an `.rpm` or a tarball, for 64-bit PCs ([its releases](https://github.com/helge17/tuxguitar/releases)). Its developers ask you to download it only from its own site or that page. The old SourceForge page, which still turns up in searches, stopped at an older version.

## Side by side

| Tool             | Price   | On Linux as                     | Slower, same pitch | Video | Writes out the notes   |
| ---------------- | ------- | ------------------------------- | ------------------ | ----- | ---------------------- |
| EarBee           | Free    | AppImage                        | Yes                | Yes   | No                     |
| Transcribe!      | $39     | Tarball                         | Yes                | Yes   | No, but suggests them  |
| Sonic Visualiser | Free    | AppImage, `.deb`                | Yes                | No    | Estimates, by plugin   |
| AnthemScore      | $29–$99 | AppImage                        | Yes, in Pro        | No    | Yes                    |
| Audacity         | Free    | AppImage, distro packages       | Yes, as an edit    | No    | No                     |
| VLC              | Free    | Distro package, Snap            | Yes                | Yes   | No                     |
| Play it Slowly   | Free    | Distro package                  | Yes                | Yes   | No                     |
| MuseScore Studio | Free    | AppImage, Flatpak, Snap, distro | (Not its job)      | No    | You write them         |
| TuxGuitar        | Free    | `.deb`, `.rpm`, tarball         | (Not its job)      | No    | You write them, as tab |

## Which ones don't run on Linux?

Some of the best-known tools for practising with recordings have no Linux version. I checked each one's own site in November 2026:

- **Amazing Slow Downer:** Windows, Mac, iPhone and iPad, and Android ([Roni Music](https://www.ronimusic.com/slowdown.htm)).
- **Capo:** Mac, iPhone and iPad only ([Capo](https://supermegaultragroovy.com/products/capo/)).
- **Anytune:** Mac, iPhone and iPad, and Android ([Anytune](https://www.anytune.app/)).
- **Song Surgeon:** Windows and Mac ([Song Surgeon](https://www.songsurgeon.com/)).
- **Moises:** desktop apps for Windows and Mac, but also a web app that runs in the browser, so you can use it from Linux that way ([Moises](https://moises.ai/)).
- **Riffstation** never had a Linux version, as far as I can find, and it's gone now anyway ([what happened to it](/blog/free-riffstation-alternative/)).

You may get some of them running with Wine, but I haven't tried, and I wouldn't count on it for something you'll use every day.

## Which one would I pick?

- **You want one tool made for working songs out by ear:** EarBee, or Transcribe! if you'll pay for its note hints and you're on X11.
- **You want to see the music in detail** and don't mind learning: Sonic Visualiser.
- **You want the notes written out for you,** and you'll check them by ear: AnthemScore.
- **You only need a riff now and then:** VLC, which you probably have already.
- **You want sheet music at the end:** MuseScore Studio, next to whichever of the others you use for the listening.
- **You want guitar tab, or to share it with Guitar Pro users:** TuxGuitar.

Whichever you choose, the method matters more than the tool: a short passage, slowed down, looped until you can sing it, then played. Here's [how to slow down a song without changing the pitch](/blog/slow-down-a-song-without-changing-pitch/), and if you need something to start on, [eight easy songs to transcribe](/blog/easy-songs-to-transcribe/).

## Try EarBee

[EarBee](/) is a free, open-source player made for learning music by ear. It slows a song or a video down without changing the pitch, loops the passage you're working on, finds the beats and bars, separates the stems, and lets you mark the sections of a song as you go. Everything is in the download: there's [no trial, no paid version and no account](/#free). On Linux it's one AppImage that runs on any distribution: [download it here](/#download).
