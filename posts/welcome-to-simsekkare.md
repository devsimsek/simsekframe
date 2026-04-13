# Welcome to simsekframe (aka. kare)
**kare** is my photo portfolio. Simple as that. No algorithm. No ads. Just photos I took because I wanted to see what would happen when I pointed my camera at something interesting.

The site itself is built on **[TypeGrid](https://github.com/devsimsek/TypeGrid)** — my own open source static portfolio system with a JSON headless API and a TUI CLI for managing everything. You can find the spec and tools at [github.com/devsimsek/TypeGrid](https://github.com/devsimsek/TypeGrid). It lets me curate albums, generate WebP thumbnails, handle SEO, and keep everything keyboard-first without ever leaving the terminal.

## The Gear

I don't have a single "main" camera. I rotate through a few depending on mood, light, or whatever project I'm messing with:

### **Sony a7 Series**
From m4 to m2. My full-frame with great af and perfect dynamic range. It's heavy though.

### **Canon EOS R10**
My go-to for most things. APS-C mirrorless with solid autofocus and enough dynamic range to handle whatever I'm throwing at it. Reliable when I need the shot to just work.

### **Sony NEX-3**
Pure nostalgia. This is the same camera I used back in middle school. Kit 18-55mm lens is objectively terrible, but there's something freeing about shooting with glass that doesn't pretend to be perfect.

### **HONOR ELP-NX9**
The wildcard. Wide-angle action cam vibes. Great for capturing environments or anything where I need to squeeze more into the frame than physics should allow.

### **Lenses (varies)**
I swap lenses constantly — primes, zooms, vintage glass, whatever catches my eye. The specific combo usually depends on whether I'm chasing structures or faces. No favorites, just tools.

## What I Shoot

**Structures** — buildings, bridges, concrete, glass, anything with geometry that makes me stop walking and think "huh, that's interesting". Urban decay, brutalism, reflections. The kind of stuff that looks better in B&W.

**Portraits** — people, obviously. Not the posed studio kind. More like moments where someone's expression or the way light hits their face makes the whole frame click. Natural light, minimal setup.

Everything else is fair game. If it looks good through the viewfinder, it belongs here.

## The Process

**Rapid RAW**, not Lightroom. Lightroom feels like it wants to be a database when all I need is quick edits and export. Rapid RAW is faster, less opinionated, and doesn't try to organize my life for me. Also, its not adobe :)

From there, photos go straight into **TypeGrid CLI**. I curate albums, set primaries, tag lenses/cameras, let it generate thumbnails and metadata. The frontend renders everything instantly because there's no build step — just JSON → Alpine.js.

It's a workflow that matches how I actually work: shoot → edit → publish → done. No ceremony.

## Why kare

Instagram killed the joy of just sharing photos. Pixelfed was better but still slow. I wanted something that was mine, fast, and didn't get in the way.

TypeGrid made that possible. The site is 100% static, keyboard-navigable, and scales with however many photos I end up taking. Right now it's sparse because I'm still shooting more than curating, but that's the point — infrastructure first.

***

**Currently live albums:** 26" Red, 26" Green, Flight, BW, Portrait, Experiments. More coming as I get out and shoot.

Got questions about the gear, process, or TypeGrid? Ask away. (In mastodon @devsimsek@universeodon.com)