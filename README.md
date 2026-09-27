# VideoFrame

Edit talking-head video. Your footage never leaves your computer.

Import a recording and it plays immediately. Transcription and analysis run on
your own machine while you work — the editor stays usable and the video keeps
playing. VideoFrame finds the long pauses, filler words, false starts and
repeated takes, shows you **the exact words it would remove**, and removes
nothing until you agree.

This repository holds the downloads. The source is elsewhere.

## Download

The latest build is on the [releases page](../../releases).

Signed and notarised by Apple, so it opens without a warning — no
right-click-Open, no "damaged" dialog.

Download the `.dmg`, open it, drag VideoFrame to Applications. Nothing else to
install: FFmpeg and a speech model ship inside the app, so a recording can be
imported and transcribed straight away.

**Apple Silicon only** (M1 and later) for now.

## What it does

- **Finds what is worth cutting** — long pauses, filler words, false starts,
  exact repetitions and probable repeated takes. Pauses are measured from the
  audio rather than guessed from the transcript.
- **Shows you the words, not a summary** — every proposed removal appears as
  your own transcript with the cut words struck through. Accept the safe ones in
  a click; uncertain cuts always come to you individually.
- **Takes instructions in plain words** — "clean up the dialogue but keep it
  conversational", "my face is too dark in the second clip". It says what it
  cannot do rather than accepting the request and disappointing you at export.
- **Captions previewed on your own footage** — nine styles, editable and
  positionable, with per-word emphasis so a viewer watching on mute still gets
  the point.
- **A manual editor when you want one** — dismiss the suggestions and you have
  a timeline, trim, split, reorder, volume, colour and export.

## Privacy

Nothing is uploaded. Transcription, analysis, preview and rendering all run on
your computer, and your original recording is never modified — editing is
non-destructive.

Pull out your network cable and it still works. That is the whole argument.

## What it is not

Named plainly, because the app itself declines these rather than approximating
them:

- No vertical or short-form clips, no automatic shorts
- No B-roll, stock footage or multicam
- No colour grading as a craft — four corrective controls, not wheels and curves
- Conversations are cleaned as one audio stream, so no per-speaker control
- Horizontal 16:9, up to about an hour, exported at 1080p

It is built for videos where the words carry the meaning: talks, lessons,
presentations, demos, interviews, podcasts, team updates. A music video is not
what this is for, and it will tell you so.
