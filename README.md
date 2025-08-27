# Well, this is cosy … Welcome to my GitHub playground and skunkworks …

![skunkworks white border](https://github.com/user-attachments/assets/4bb7b537-96ab-498d-be80-734bfc2c4a4b)

![loop](https://github.com/charlierobin/charlierobin/assets/10506323/45c0166a-eaad-4a92-9fc7-4a71901c0dad)

### Retired but …

The home of various experimental projects, code fragments, ideas — some more half-baked than others, some even verging on being complete (and all driven by whatever my personal obsessions or needs were at the time) but perhaps with the occasional interesting nugget buried away in there somewhere or other.

## DockJuggler [▶︎](https://github.com/charlierobin/dockjuggler)

I love this app (although I’m not sure how it behaves on the later versions of macOS, as I still use it exclusively on Catalina). It’s designed for those of us fed up with a Finder Dock that spreads across the whole of our monitor width with STILL not enough room for our other apps.

(The original idea was that this would eventually end up working in conjunction with another app of mine, [Let’s Do Launch](https://github.com/charlierobin/launcher) — see below.)

It allows the user to manage various “versions” of their Dock, and then to switch seamlessly between them.

Whilst this works fine on the OS it was designed for, macOS Catalina, I don’t think I’ve ever tested it on a subsequent version, so I kind of have a hunch that this app is long overdue for an overhaul.

[User Guide & Reference Manual](https://github.com/charlierobin/dockjuggler/blob/main/DockJuggler_User_Guide.pdf)

## Find Missing iTunes/Music Tracks [▶︎](https://github.com/charlierobin/list-missing-apple-music-files-swift)

I don’t know what it is with my version of [Music](https://en.wikipedia.org/wiki/Music_(app)), but once in a while tracks just seem to “disappear”, ie: they are still listed in the browser, but when you try and play them, you get that annoying message about the file being missing, and would you like to try and locate it?

(And don’t get me started on its insistence on continuously launching “Determining Gapless Playback Information” processes against my whole music library, or its refusal for years now to crossfade song playback, no matter how many times everything has been wiped clean and re-installed. But those are rants for an entirely different day.)

So I messed around writing a couple of command line apps (one written in Swift, the other in Objective-C) to check for these “missing” files.

(Both to be run in the Terminal.)

## Cleaning Up Unity Project Folders [▶︎](https://github.com/charlierobin/clean-unity-projects)

Unity project folders get big — sometimes REALLY big — and given the infrequency with which I work on some of my Unity projects, I decided I needed a way of reclaiming the disk space from them by deleting all the temp stuff and yet keeping all the stuff required for re-opening and re-building the project in the future.

The result was this little Python app.

There’s also a [Golang version](https://github.com/charlierobin/cleaning-unity-projects-using-go), done just for the fun of it. The organisation of the Go version is slightly crazy, so I guess I would recommend with sticking with the Python version running in the Terminal. Having said that, I have used the latter version a couple of times and it seemed happy enough doing its job.

## Cinema 4D Export to Unity [▶︎](https://github.com/charlierobin/cinema4d-to-unity)

Going all the way back 2011: a set of Python plug-ins for Cinema 4D that facilitate some slightly more structured (and convenient) ways of managing and getting meshes out of Maxon’s Cinema 4D and into Unity. (And in fact into any other app that can take FBX files.)

The interaction between Cinema 4D and Unity has come along in leaps and bounds since back then, and I imagine a lot of people at this point stick with the official way it is done now … and yet for myself personally, I STILL find myself coming back to these plug-ins as the ideal way I want my modelling and meshing workflow to work. Go figure. Life moves in mysterious ways.

## Small, Far Away [▶︎](https://github.com/charlierobin/small-far-away)

Another suite of Cinema 4D plug-ins from way back, initially inspired some of the level of detail functionality that I was using in [Autodesk Maya](https://help.autodesk.com/view/MAYAUL/2025/ENU/?guid=GUID-79C7A942-0547-4AC4-8A4D-DCAC4ABB1EF2).

Cinema 4D has subsequently acquired [some of its own native LOD (level of detail) functionality](https://help.maxon.net/c4d/en-us/#html/OLOD.html?TocPath=Create%2520Menu%257CGenerators%257CLOD%257C_____0), which is nice, but there are still a couple of these plug-ins to which I frequently find myself returning.

(And yes, obviously, these plug-ins are named courtesy of [Father Ted](https://www.youtube.com/watch?v=MMiKyfd6hA0).)

## Let’s Do Launch [▶︎](https://github.com/charlierobin/launcher)

An app for managing "helper" launcher apps: you can drag apps to the left of the Finder Dock to make them persistent, and you can drag a folder to the right of the Dock to make it persistent there. So we Mac users have long been able to make ourselves a kind of "sub-menu" of apps by creating a folder of lesser used apps (either the apps themselves or aliases) and then dragging the folder to the right side of the Dock.

I wanted something a little different: custom icons on the left side of the Dock that when clicked (and **quickly** launched) displayed a floating menu of apps. I know that there are so many launcher/app manager apps out there, but after trying a few I quickly realised that none did it exactly the way I wanted it done, and so **Let’s Do Launch** was the result.

I finished it enough of it that for years I’ve been happy with the result, but there are a couple of areas where it needs work to count as finished. So along with **DockJuggler** I think this is another project that I’ve got to give a good going over/overhaul.

## Oscar the Grouch [▶︎](https://github.com/charlierobin/oscar-the-grouch-version-2)

Ahhh, heady days: the late 1980s and the very early 1990s, System 6 becoming System 7 (and then staying that way for years and years whilst [Apple flushed one “new” OS project after another down the corporate toilet](https://en.wikipedia.org/wiki/Copland_(operating_system))).

[MacUser magazine in the UK](https://en.wikipedia.org/wiki/MacUser) used to publish shareware floppy disks (you kids stop your snickering at the back) and I’m sure it was on one of those disks that I first encountered the magic that was Oscar the Grouch, a System 6/System 7 Macintosh system extension originally created by by Eric Shapiro and Ken Hornak.

So these two projects are my attempt to force back the remorseless ticking of the clock and relive the days of youth:

[Version 1](https://github.com/charlierobin/oscar-the-grouch-version-1) was my first crack at it. Oscar doesn’t come out of the trash as such: the idea is that you position and scale him so that he’s just off screen to the bottom right of your Dock, and then, when you empty your trash, he appears from off screen and does his thing.

(There’s new audio which I got from a Sesame Street clip on YouTube, and I used an AI audio site to split out Oscar’s singing from the background music, mainly as an experiment to see if it could be done. But it all ended up in the app’s preferences as a way for the user to very precisely customise what they want to hear.)

[Version 2](https://github.com/charlierobin/oscar-the-grouch-version-2) extended Version 1, using macOS Accessibility to get the position and scale of the Dock’s Trash icon. Using this info the app “guesses” a rough position where Oscar needs to appear, and then does the business.

The problem with version 2 is that because the macOS Trash no longer has a lid, the original Oscar animation looked strange, so I did a new one with the trash lid removed. Which, although it makes sense, stills seems kind of sacrilegious.

As a result, over the years, I’ve found that even though version 2 is the one most like the original, I actually prefer having version 1 installed on my Mac.

Both constantly poll known (hidden) trash locations to get an idea of when a trash been emptied.

[FSEventStream for Xojo apps](https://github.com/charlierobin/xojo-FSEventStream) was the start of replacing that with something a little better.

## Flying Toasters [▶︎](https://github.com/charlierobin/flying-toasters)

Another software trip down memory lane, this one a re-hashing of the old Flying Toasters screensaver from the [Berkeley Systems After Dark](https://en.wikipedia.org/wiki/After_Dark_(software)) collection.

I started to re-do the toasters’ wings and flapping animations, which in retrospect I now think was a mistake: I should have just stuck with the original graphics (like a few of the other versions out there did, for instance [Robert Venturini’s](https://github.com/robertventurini/FlyingToasters) much better version).

Still, it is what is: so what we have here is a straightforward [screensaver version](https://github.com/charlierobin/flying-toasters) (Intel only, though, and with added TIE fighters and X-Wing fighters for some reason), a [“live desktop” version](https://github.com/charlierobin/flying-toasters-live-desktop-xojo-opengl) (which over the years I’ve come to prefer), and [another desktop version](https://github.com/charlierobin/flying-toasters-original) which I think was just a test of some kind.

## Unity Input Manager Editor [▶︎](https://github.com/charlierobin/unity-input-manager)

Back in the days before Unity revamped handling user input, I found managing (and even just remembering) all the different input axes options and settings a real pain in the you-know-what.

So I wrote this app to help me maintain some simple input axis template libraries, and to help copy/paste input axes between different Unity projects or into new projects.

I imagine these days everybody is using the new input packages, but even so, for smaller projects and even just when messing around, I still find this app useful, so I cleaned it up a little and put it up here.

## Colour Picker for Xojo Apps [▶︎](https://github.com/charlierobin/xojo-simple-colour-picker-1)

What can I say? I found Xojo’s support for the standard macOS colour picker diabolical, and I also found that I really didn’t like the standard Apple system colour picker very much either. Even just thinking about it all makes me start to grind my teeth a wee bit.

So whilst I usually wholeheartedly subscribe to the philosophy of “if the system provides one, and the users are used to it, don’t go confusing them with your own version”, in this case I have started to roll my own version and I’m pretty unrepentant about it.

## Various Games, Screensavers, How-Do-You-Do-It-Example-Projects etc

There’s so much stuff on the boil (and all so dependent on what I’m in the mood to work on — and what I have the time to work on) that it’s hard to curate or document in any meaningful fashion. A Spectre-clone, something inspired by the old Mac game Apache Strike, Crystal Quest, the old ZX Spectrum Game Jetpac, a pirates game, versions of Space Invaders done just to try out Apple’s SpriteKit with Microsoft Visual Studio/C#, versions of Asteroids, corporate screensavers, etc etc … Where will it all end?

[Experiments, General Goofing Off & Other Dumpster Fires](https://charlierobin.com/standalone-video-gallery.html?video=gameplay-experiments.mp4)











