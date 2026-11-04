# Reefcode website

Upload everything in this folder to your GitHub repository: `index.html` plus the `images` folder.

## Photos

Each photo slot on the page loads a file with a fixed name from `images/`. To change a photo, replace the file and keep its name. If a file is missing, that slot is simply hidden, so the page never shows a broken image.

| File | Where it appears | Shape | Now |
| --- | --- | --- | --- |
| `host-portrait.jpg` | Your host, main photo | 4:5 portrait | LinkedIn photo; swap for the podcast portrait |
| `host-freedive.jpg` | Host photo strip, left | Tall | Freediving photo |
| `host-dive.jpg` | Host photo strip, middle | Wide | Scuba portrait |
| `host-blue-corner.jpg` | Host photo strip, right | Tall | Blue Corner beach photo |
| `science-reef-survey.jpg` | Science | 4:3 | Reef survey dive |
| `solutions.jpg` | Solutions | 4:3 | Missing, hidden for now |
| `people-team.jpg` | People | 4:3 | Marine Ecology Week team photo |
| `format-conversation.jpg` | 40 min Conversations | 16:9 | Missing, hidden for now |
| `format-field-notes.jpg` | 20 min Field Notes | 16:9 | Missing, hidden for now |

Keep each photo under about 500 KB (1600 px on the long side is plenty) so the page loads fast on phones. Photos are cropped to fit their slot, so keep the subject near the centre.

## Pitch form

The guest pitch form works now: until it's connected, it opens the visitor's email app with the pitch filled in. To have pitches arrive straight in your inbox instead:

1. Go to web3forms.com, enter the email address where you want pitches, and copy the access key they email you.
2. In `index.html`, find `PASTE_YOUR_ACCESS_KEY_HERE` near the bottom and replace it with your key, keeping the quote marks.
3. Upload the changed file. Send yourself a test pitch from the live site.
