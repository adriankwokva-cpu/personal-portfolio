# Adrian Kwok — Portfolio

## Run it locally
1. Install Node.js (LTS) from https://nodejs.org if you haven't.
2. In VS Code: File > Open Folder, pick this folder.
3. Terminal > New Terminal, then: npm install (once), then: npm run dev
4. Open http://localhost:4321

## The easy knobs (top of the <style> block, in :root)
All the things you'll most likely want to tweak live in one place now:

  --edge-outer: 4rem;    <- left margin of name / bio / projects heading
  --indent: 1.5rem;      <- EXTRA left space for links + project contents
                            (bigger = inner column pushed further right)

  --fs-name: 2.6rem;     <- "Adrian Kwok"
  --fs-subhead: 1.4rem;  <- Project 1 / 2 / 3
  --fs-projhead: 1.3rem; <- "Projects I'm Working On:"
  --fs-body: 1.15rem;    <- bio, links, descriptions, urls

Change a number, save, watch the browser update. rem = sizing unit (1rem ~ 16px).

## Spacing
Gap before "Projects I'm Working On:" -> h2 { margin: 8rem 0 2.5rem; } (first number).
margin/padding order is: top right bottom left.

## Fonts
Name + projects heading -> Lora. Three links -> Georgia. Everything else -> Arial.
