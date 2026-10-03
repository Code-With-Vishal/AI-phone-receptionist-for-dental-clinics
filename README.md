# Front Desk AI: concept site

Single-page concept site for **Front Desk AI by Samarth AI Studio**, an AI phone receptionist for dental practices. It answers every call, books into the practice calendar and texts the patient.

Open `index.html` in a browser. Everything is in that one file. Scripts load from cdnjs and jsdelivr (three.js r128, GSAP 3.12.5 + ScrollTrigger, Lenis 1.1.13) and fonts from Google Fonts (Bricolage Grotesque, Hanken Grotesk).

## What's on the page

| Section | Buyer question | Interaction |
| --- | --- | --- |
| Hero | What is it? | Clay desk phone rings, mint headset answers, appointment card slides out. Drag to rotate. |
| Problem | Where do calls slip through? | "While you were out" message slips in a sticky stack that peels back. The phone counts missed calls. |
| How it works | How does it work? | Pinned sideways run through 4 steps. The phone turns a corner, then rings, answers, prints the time and files the card into a clay calendar. |
| Benefits | What will it handle for us? | Six cards dealt out of the clay card stack. Tilt with glare, tap to flip. |
| Proof | Does it work? | Cylinder carousel turned by scroll or drag. Honest demo cards only. |
| Comparison | Why not just use voicemail? | Draggable divider between the same call handled two ways. |
| Pricing | What does it cost? | Monthly/yearly toggle flips every card. |
| FAQ | What else should we know? | Accordion. The short answer is always visible. |
| Demo | What happens in the demo? | Slot picker. Booking prints your time on the clay card and files it into the calendar. |

Phones get swipe carousels with dots, a bottom CTA bar and no scroll hijacking. Reduced motion stacks the sideways sections and turns off the idle loops. Without WebGL, every stage shows a drawn SVG version of the same scene.

## Before launch: placeholders to confirm

Search the file for `[VERIFY]` and `[ADD`.

- **Prices:** Starter $297/mo, Practice $497/mo, Group $997/mo, the yearly rates and the setup fees are all placeholders.
- **HIPAA position:** BAA, encryption and data retention (FAQ).
- **Supported calendars / practice software:** benefits card and FAQ.
- **Insurance handling:** what it can answer, per practice.
- **Setup timeline:** "about a week" is a placeholder.
- **Demo line number** and **recorded call link:** proof cards.
- **Real results:** add only with the practice's permission.
- **Booking form:** it is page UI only and does not send anything yet. Connect the `submit` handler in the `initBooking` block to Calendly or an n8n webhook.
