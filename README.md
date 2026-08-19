# Kobo Notes

Distraction-free note-taking on a Kobo Clara BW — a minimal text field the e-ink browser can handle, typed with a keyboard, tracked with phone photos.

**The problem:** e-ink readers are perfect for focused reading and writing —
no notifications, no apps — but the Kobo has no real way to type notes.

**The solution:** a single, permanent text field served as a minimal web page
the Kobo's limited browser can actually handle. Pair a keyboard, open the
page, and the e-reader becomes a typewriter. I photograph finished notes with
my phone to track my note-taking over time. The photos of the Kobo screen (I use my iPhone's built-in OCR if I want to copy text) keeps me enjoying the design of the process & device.

## Design constraints

The Kobo browser is extremely limited, so the page is deliberately primitive:

- One HTML file, no frameworks, no build step
- No JavaScript features the e-ink browser chokes on
- High-contrast, refresh-friendly layout for e-ink

The constraint *is* the project — building something useful inside a browser
that can barely render the modern web.

## Usage

Open the page on the Kobo, connect a keyboard, type.

**Live:** https://bryso7.github.io/kobo-notes/
