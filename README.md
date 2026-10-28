# Alex Shade

**I explore how things work, find possibilities in unexpected places, and turn ideas into something I can try.**

Some days that means software. Other days it means a camera, a piece of wood, an old machine, or a question I brought home from a hike. I like building and troubleshooting technology, especially when it solves a problem I can actually point to.

[Explore my public projects](#start-with-something-real) · [The person behind them](#how-i-got-here) · [Beyond the screen](#beyond-the-screen) · [Work with me](https://leveleverythingcompany.github.io/#hire)

## How I got here

At about ten, I was already exploring Windows 95-era computers, looking at the hardware and trying to understand what made everything work. The equipment has changed. That habit has stayed with me.

Today my interests cross software, local AI, photography, tools, local history, and practical making. I notice something, wonder whether it could work differently, and follow the question far enough to try it.

I'm the creator behind **The Level Everything Company**, an independent creator brand in Southern Indiana. This profile is my personal portfolio; [the company website](https://leveleverythingcompany.github.io/) brings together services, public projects, and field notes. The older names Wommper1, Alex Shade Productions, and Alex Shade Photography are still part of the work you'll find here.

## Start with something real

The four projects below are public. A release means there is a package to try, not that every feature has passed real-device testing. Platform requirements and limitations are in each repository.

### Southern Indiana Lore — notice the stories around you

A local-history and folklore explorer: an Android app with bundled site data, location-based alerts, narration, and field notes, plus a browser atlas for people without Android.

- **Why it exists:** help people notice places and stories they might otherwise pass by.
- **My part:** project idea, direction, AI-assisted development, and hands-on exploration and testing. Historical claims need sources; the site's confidence labels are part of the experience.
- **In the repository:** Kotlin, Jetpack Compose, Room/SQLite; a separate HTML/CSS/JavaScript web atlas.
- **Status:** Android v1.0.1 released; browser atlas beta. Android tried on an S25 Ultra; other devices and real iPhone use remain unverified in the project documentation. The map is schematic, not a navigation map.
- **Try or help:** [Open the atlas](https://wommper1.github.io/southern-indiana-lore/) · [Android download](https://github.com/Wommper1/southern-indiana-lore/releases/tag/v1.0.1) · [Source, screenshots & contributing](https://github.com/Wommper1/southern-indiana-lore)

### WaveForgeVideo — a smaller route through an everyday video task

A desktop front end for FFmpeg: trim, rotate, resize, convert, or extract audio from one clip.

- **Why it exists:** make focused video jobs accessible through one window.
- **My part:** creative direction and AI-assisted building, testing, and refinement of the workflow.
- **In the repository:** Python, Tkinter, FFmpeg/ffprobe integration, pytest, and Windows packaging scripts.
- **Status:** v1.1.0 released; developed and tested on Windows 11. FFmpeg is a separate install. Previews are still frames; this isn't a multi-clip editor.
- **Try or help:** [Windows download](https://github.com/Wommper1/WaveForgeVideo/releases/tag/v1.1.0) · [Screenshot, instructions & source](https://github.com/Wommper1/WaveForgeVideo) · [Documented walkthrough](https://leveleverythingcompany.github.io/field-notes.html#waveforge-walkthrough)

<img src="https://raw.githubusercontent.com/Wommper1/WaveForgeVideo/main/docs/screenshot.png" width="680" alt="WaveForgeVideo's actual desktop interface, showing trim controls, previews and export settings">

### DualCast — one Windows mix, two playback devices

An experiment in sending system audio to two outputs, with separate volume and synchronization delay controls.

- **Why it exists:** explore sharing audio across two Bluetooth devices.
- **My part:** project direction and AI-assisted development, with the remaining hardware questions kept visible.
- **In the repository:** C#, WPF, .NET 10, NAudio, audio-routing logic and automated tests.
- **Status:** v1.0.1 pre-release. The verification record documents automated checks and a Windows launch test; two-device streaming and long-session drift still need real hardware acceptance tests. Hardware must support two active playback connections.
- **Try or help:** [Pre-release & requirements](https://github.com/Wommper1/DualCast/releases/tag/v1.0.1) · [Source & first-run guide](https://github.com/Wommper1/DualCast) · [Testing gaps](https://github.com/Wommper1/DualCast/blob/master/VERIFICATION.md)

### VRChat Universal Translator — following a conversation across languages

Local speech recognition and English captions for VRChat audio, with a desktop overlay and experimental SteamVR and local-network phone views.

- **Why it exists:** explore ways to make conversations easier to follow across languages.
- **My part:** concept, product direction, and AI-assisted development and troubleshooting. I don't claim every component or line of code as work I wrote unaided.
- **In the repository:** C#, WPF, .NET, NAudio process capture, Whisper.net and local speech models.
- **Status:** v1.1.5 pre-release for Windows 11 x64. CPU processing; initial model download required. Headset, phone and full live-session acceptance checks remain open. The default branch includes newer development changes than this release. Independent project, unaffiliated with VRChat Inc.
- **Try or help:** [Windows pre-release](https://github.com/Wommper1/VRChatUniversalTranslator/releases/tag/v1.1.5) · [Source, sample interface & quick start](https://github.com/Wommper1/VRChatUniversalTranslator) · [Verification record](https://github.com/Wommper1/VRChatUniversalTranslator/blob/main/VERIFICATION.md)

## What I bring, and what I'm developing

| Area | Where to look / how to read it |
| --- | --- |
| Software and application development | Four public applications above, with source and documentation. AI-assisted independent work; not a claim of professional engineering tenure. |
| AI and local language models | I experiment with local AI and use AI tools to research, build and troubleshoot. The translator provides public evidence of local speech-model integration; other experiments are not presented as released products. |
| Troubleshooting and practical solutions | Setup guides, diagnostics, known limits and verification records show the problems the projects address and what still needs testing. |
| Marketing and customer-facing technology | Around 11 years across sales, marketing and customer-facing work, including mobile technology, B2B conversations, radio/digital advertising and store leadership. [My work background](https://leveleverythingcompany.github.io/story.html#experience). |
| Photography, video and creative media | Photography and visual storytelling are part of my practice; WaveForgeVideo is one public tool. A selected photography portfolio is still to come. |
| Electronics and making | Hands-on interests and personal projects, described below. These are not trade qualifications or claims of licensed work. |
| Exploration and historical research | Southern Indiana Lore connects outdoor discovery with sourced history and clearly labeled uncertainty. |

## Beyond the screen

I spend hours outside: hiking, exploring historic places, wandering small towns, collecting firewood, and noticing things that lead to another question.

I've made a wooden handle for a fire poker, repurposed old bricks into a miniature outdoor fireplace, and added lighting to improve an outdoor space. I also experiment with a Dremel, wood-burning techniques, and old or unusual equipment. These are personal making examples, not professional trade credentials or construction instructions.

I want this portfolio to show that physical work alongside the software. Photos and build notes will give those projects their own evidence; I won't substitute a stock image for something I've actually made.

## How I work with AI

I bring the questions, choose a direction, use AI assistance to explore and build, and keep checking the result. A successful build is one piece of evidence. Device tests, useful feedback, documented limits, and changes after something breaks matter too.

Repository tests and verification logs describe particular checks on particular versions. They are not proof that every feature works everywhere or that I independently wrote and validated every line.

## Connect with me

- **A project, professional opportunity or collaboration:** [wommper1@gmail.com](mailto:wommper1@gmail.com). Tell me what you're trying to do and what a useful result would look like.
- **Freelance inquiries:** [Work with Alex](https://leveleverythingcompany.github.io/#hire).
- **Try a build or contribute:** start with the relevant repository's README, contribution guide and issue tracker. Share the app version, device, expected result and steps to reproduce a problem; remove private information from logs and screenshots.
- **Security concerns:** follow that project's SECURITY.md rather than posting details publicly.

[Read my story](https://leveleverythingcompany.github.io/story.html) · [Notes from the workbench](https://leveleverythingcompany.github.io/field-notes.html) · [Company GitHub](https://github.com/LevelEverythingCompany)

The Level Everything Company is currently an independent creator brand, not a registered LLC or corporation.
