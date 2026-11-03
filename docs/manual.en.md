# Podcast Studio — manual v1.48.1

## 01. Create your first podcast
Paste or import a short story on the Text tab. Open Voices and choose an engine: Piper uses local models, Edge is online, and My voice uses your separate local voice environment. Choose an MP3 destination under Audio and output. Music, ambience and cover artwork are optional.

Start with a short passage without background audio so you can judge pronunciation and pace. Use Audio preview for a sample and Generate MP3 for the full episode. Wait for completion and check the destination file. Save the project as well: an MP3 holds the finished sound, while a project preserves text and settings for further work.

## 02. Save, open and recover projects
Ctrl+S saves a project; Ctrl+O opens one. Projects hold text, settings and references to chosen media. Exporting text alone does not preserve all production settings. Session preferences are also saved automatically, but keep named project files for important episodes.

After opening, check that models, music, artwork and voice recordings still exist at their original locations. Moving them may require choosing the files again. Use Project bundles for portable copies of available source assets and takes. Keep a separate backup on another drive for important productions.

## 03. Editor and formatting
The compact toolbar includes file operations, undo, cut/copy/paste, search, case changes, headings, lists and alignment. Hover over an icon for its explanation. The Text menu includes spacing cleanup and joining broken lines. Select the relevant text before applying an operation.

Ctrl+Z undoes text edits, Ctrl+Y redoes them, and Ctrl+F opens search and replace. Ctrl+B and Ctrl+I add formatting markers. Formatting helps organize the script; bold or italic does not guarantee audible emphasis. Inspect the prepared spoken text and preview substantial changes. Paragraph boundaries help structure the narration, so avoid removing every blank line.

## 04. Text scanning, colours and wizard
Scan text identifies issues such as long sentences, references and unbalanced markers. Colours distinguish narrator, quotation, Bible reference, heading, formatting, attention point and marker error. An orange attention point is a suggestion to assess, not a compulsory correction.

Next attention point moves through findings. Turning Text colours off does not alter the script. The text wizard helps prepare narration: review changes and use available recovery controls if needed. Scanning cannot fully understand emotion or intent. Check names, abbreviations, numbers, quotations and transitions yourself. Save a project version before extensive editing.

## 05. Piper, Edge or My voice
Piper works offline after its program and voice models are installed. Choose a model suitable for the language. Voice character and naturalness depend strongly on the model. Edge TTS uses an online speech service; its voices are not downloadable offline models. Internet and a working Edge TTS installation are required.

The application can use another installed Python environment for Edge. My voice uses a separate local runtime, models and reference recording, and requires more computing resources than Piper. A recording alone is insufficient on a computer without that runtime. Compare engines using the same short text and a similar intended pace.

## 06. Choose and download Piper voices
Open Choose / download voices, find a model in the catalogue, download it and assign it to narrator or Bible voice. A model normally includes a .onnx file and its matching .onnx.json configuration. Keep these together.

The Piper executable path and voice model path are different settings. If synthesis fails, check both and run the installation check. Downloads require internet; synthesis can then work locally. Not every catalogue voice suits every language or narration style. Test a short passage first, keep models in a stable folder, and consult each voice's information and licence when using or distributing it.

## 07. Narrator and Bible quotations
The main narrator uses the selected main model. Bible quotations can use a second Piper model and their own pace. Mark a selection using the quotation control, or use [bijbel]text[/bijbel]. A greater-than sign at the beginning of a line can also indicate a quotation.

Keep opening and closing markers balanced and scan for marker errors. Edge uses the selected Edge voice at the pace of the respective role: two Piper model assignments do not create two separate Edge voices. Listen to transitions between narration and quotations. Voice matching can reduce loudness differences using new takes, while leaving locked clips unchanged.

## 08. Pace, pauses and natural narration
For role pace, 1 means normal. Lower values slow speech; higher values speed it up. Make small adjustments and judge flowing passages rather than isolated sentences. Excessively slow narration can become unnatural.

Automatic natural narration prepares related passages together. The engine controls some pauses within a passage, while paragraph pause controls separation between larger sections. Short, disconnected input lines can hurt continuity. Use narration/transition review to listen to neighbouring passages and assess pauses. Text, voice or language changes may invalidate an earlier narration plan. Scanning can improve structure, but does not guarantee human intonation.

## 09. Record and apply your own voice
Open Record my voice and choose the correct microphone. Speak normally in a quiet room with little echo, using your usual accent and rhythm. Start speaking promptly. Recording stops after the selected duration; use the controls to stop earlier if required.

Listen, stop playback and record again as needed. You can load an existing audio file and crop a useful section. Use the explicit apply/finish control to select the reference and complete the wizard: listening alone does not apply it. Avoid music, echo, other speakers and overload in the reference. Exact accent and voice similarity are not guaranteed by the model.

## 10. Pitch, warmth, clarity and recording checks
Voice controls provide pace and, depending on the engine, processing such as pitch, warmth and clarity. My voice also has model expression and fidelity settings. Change one control at a time and compare the same sentence. Save useful combinations as voice profiles.

Pitch changes perceived height; warmth affects bass and clarity affects treble. Large adjustments may sound artificial. These controls do not correct an accent or add fully human acting. Publish's recording check measures duration, average level, peak and silence, not noise, echo or similarity. Match voice sound creates new takes with shared tone processing and speech normalization. Originals remain available; export the updated montage afterwards.

## 11. Dutch, English and pronunciation dictionary
Interface language and speech language are separate. Language changes the interface after restart; it does not translate your article. Use a suitable engine/model for the spoken language. For My voice, mark passages with [nl]text[/nl] and [en]text[/en]. This can help with English passages inside Dutch narration.

An isolated English word may still sound Dutch depending on context and engine. The pronunciation dictionary stores targeted replacements. Use Save, then test a preview. Avoid broad replacement rules that accidentally affect other words. Accented letters should be processed as ordinary characters; do not create a separate rule for every accented word. Check source encoding and UTF-8 handling first if characters are corrupted.

## 12. Preview, progress, pause and stop
Audio preview creates a short sample using the available preview and background settings. Selection/cursor preview uses the relevant portion of the script. Make sure you know which section you are comparing with the full export.

Generate MP3 produces the full episode. First-time local voice generation may take longer while models load. Pausing takes effect at processing checkpoints; it cannot stop a running model calculation at an exact audio sample. Stop generation cancels where the underlying process allows it, and a process or network step may need time to finish. Stop sound controls playback. Stopping playback does not necessarily cancel a separate generation task. Wait for status confirmation before starting again.

## 13. Music, ambience, fades and levels
Choose optional background music and ambience under Audio and output. Keep them quiet enough for clear speech. More negative dB values reduce a layer's level. Check with headphones and at low listening volume.

Music ducking lowers the background during speech. Normalization helps manage output level but cannot repair an already distorted recording. Fade-in and fade-out gradually introduce and end background layers; they are not meant to cut off speech. Changes to an existing episode require a new montage export. Preview context and duration may differ from the full episode, so check the final MP3's beginning and ending too.

## 14. MP3, artwork and episode details
Choose an output location ending in .mp3. Check title, show name, author, number and description. Choose cover artwork if desired. Artwork visibility also depends on the player and publishing platform.

Publishing details and export includes Save and an editable description/show-notes field. Insert text outline uses headings or a short script extract; it is not an AI-written editorial summary. Review it and add sources or links yourself. A publishing package contains the MP3, optional artwork, metadata, show notes and separate caption/chapter files. It is not a full editable project backup. Export a modified montage to MP3 before creating its publishing package.

## 15. Audio timeline, takes and locks
After a complete generation, open the audio timeline. Blocks show role, duration, pause and selected take. Listen to blocks, generate alternatives and select the best fit. Some engines produce almost identical repeated takes.

Changing a take or pause first changes the edit decision. Export a montage MP3 to hear it outside the timeline. Audio edit history has its own undo/redo, separate from Ctrl+Z for article text. Locking protects an approved voice clip and pause. Unlock before modifying them. Background layers and final normalization can still change at export. Editing locked text requires reassessing the approved audio. Always check neighbouring transitions too.

## 16. Chapters, captions and promotional clips
Add a chapter title at a timeline block; clearing it removes the marker. Export chapters and captions for the current selected takes. Chapters are separate JSON data, not automatically embedded into every MP3 or shown in every player.

SRT and VTT follow block timings, with estimated timing inside longer blocks. Review captions before publishing; they are not word aligned. Promotional clip exports 1–120 seconds from a chosen start time, as MP3 or MP4 with cover artwork. A separate SRT is included; captions are not burned into the video. Choose a complete excerpt and listen to its start and end. Use normal MP3 export for the full episode.

## 17. Final audio check and guided completion
Final audio check finds long silences, possible clipping and, when block data is available, large level differences. Select a listening point to hear the surrounding sound. A warning prompts review; it does not prove that the episode is unusable.

The check cannot judge intended pronunciation, meaning or emotion. Listen to the beginning, middle, end, quotations and difficult names. Watch for repetitions, cut sentences and take transitions. Guided completion provides six steps with project-saved checkboxes. These are your confirmations, not an automatic quality guarantee. Re-export after changes and save the final project before uploading.

## 18. Library, templates and project bundles
The episode library stores project/edit snapshots and a copy of the finished MP3. Search by title, open a snapshot and maintain a status. Removing an entry does not delete its files. Voice clips and other sources remain references to existing files, so keep those available.

For moving work, use a project bundle containing available models, recordings, music, artwork and takes. Software installations, licences and the My voice runtime are not automatically included. Episode templates save repeated choices such as voices, pace, music, artwork, show name and intro/outro. They do not automatically replace the article or output path. Name templates clearly and check intro/outro transitions in the full episode.

## 19. Publishing and platforms
Open Publish > Upload to podcast host. Each destination explains its available workflow. A host stores your audio and normally supplies an RSS feed; listening platforms receive episodes through that feed after show submission.

Transistor has a direct connector: enter show ID/slug and API key, upload a draft, then inspect it on the dashboard. Publishing requires a separate confirmation. The key stays in memory for that window. An uncertain creation response blocks automatic repetition to avoid duplicate drafts; check the dashboard. Other hosts use publishing packages and their websites. Save your destination and host RSS feed with the project and copy the feed for submission. Selecting a destination does not publish anything. Platform accounts and availability are managed by the provider.

## 20. Themes, windows and interface language
Open View > Layout and colour theme. Choose from sixteen preview palettes: Pearl & blue, Midnight blue, Honey & paper, Lagoon, Forest evening, High contrast, Lavender, Peach blossom, Rose quartz, Sage garden, Summer sky, Dunes & heather, Coral & sea, Plum evening, Petrol studio and Cocoa & copper. Click Apply on a card; scroll to see all choices. Application colours change immediately and the preference is saved locally for the next launch. Text and voice settings are unaffected.

Window borders, system messages and Windows file dialogs follow Windows settings. Themes change colour and readability, not control placement. Resize the main and auxiliary windows and adjust available split panes. Larger/smaller letters changes editor display. Language offers Dutch/English; restart for consistent existing labels. It does not translate podcast text or choose the speech language. F1 opens this searchable manual, which can also be saved as Markdown/text.

## 21. Troubleshooting
No sound: check the output file, playback device, Windows volume and preview completion. Wrong voice: check engine, role assignment and whether you are hearing an old MP3. Edit decisions require re-exporting.

Piper fails: check executable and model/configuration paths. Edge online errors: check internet and use Install / update Edge TTS. HTTP 403 is an online-service response; changing a Piper model will not fix it. Corrupted accents or UTF-8 errors: check the source and current application version instead of removing all accents. Slow My voice generation can involve model loading and substantial computation. Test a short passage. Save the project and record the complete error, engine and relevant text if a problem persists. Avoid repeatedly starting while an earlier task is still running.

## 22. Shortcuts and keeping your work safe
Ctrl+O opens a project. Ctrl+S saves it. Ctrl+Z / Ctrl+Y undo/redo text edits. Ctrl+F opens find/replace. Ctrl+B / Ctrl+I insert formatting markers. F1 opens the manual. Menus and icon tips expose other operations.

Keep both project and finished MP3. For important work, also keep a project bundle and test opening it elsewhere before deleting sources. Online engines and publishing hosts receive text/audio when you use those functions. Local Piper/My voice generation uses installed models. Bundles may contain private recordings and scripts, so choose where you save or share them. Application licensing and the terms for voices, music and publishing services are separate matters.


## 23. Menu structure and updates
The menu bar follows the workflow. Project contains opening, saving, library,
templates and bundles. Text contains editing plus Formatting and Prepare text.
Voices contains models, recording, profiles, tone and pronunciation. Audio contains
background layers, fades and listening. Production contains generation, recovery,
narration review, timeline, final checks and guided completion. Publish contains
metadata, promotional clips and platforms. View contains themes, editor display
and Language. Licence and installation checks are under Help.

Help > Check for updates opens the update centre. Enter an official HTTPS manifest
address and save it. Check reads the version information. A newer version enables
Open download page, which opens your browser only after your click. Nothing is
installed or replaced automatically. Save work and close the old application before
using an updated version.

The default source is https://raw.githubusercontent.com/cyberfirepulse/podcaststudio/main/update.json. It works once the publisher uploads the manifest and corresponding release. A previously saved custom address is preserved. A
failed request does not mean you are up to date. The example JSON manifest is for
the publisher: host a JSON with product PodcastStudio, version, channel stable,
download_url and optional notes on your own HTTPS endpoint. A newer version must
provide a real HTTPS download link. Local manifest checking is also available; it
is not an online check. Do not use CAMT's manifest, which belongs to another product.


## 24. Edit previously recorded sermons and podcasts
Open Project > Import existing recording and choose WAV, MP3, FLAC, M4A or OGG.
The source is copied into a work folder; the original file is preserved. Use
Initial setup / download model once. Internet is needed for software and model
files, then recognition runs locally with network connections blocked.

Choose nl, en or auto for language. Multilingual small is a practical starting
point. Tiny is smaller/faster with potentially more errors; medium requires more
time and storage. CPU is the default without extra GPU libraries. CUDA can use
your NVIDIA card with CUDA 12 and cuDNN 9; the existing My voice environment's
DLLs can be used. If GPU libraries are unavailable select CPU. Recognition and
voice generation have separate software environments.

Click Transcribe recording. Activity and recognized-minute progress are shown.
Stop cancels; interrupted recognition needs restarting. Audio is not uploaded.
The editor shows source timestamps, original recognized text and edited text.
Select a row to listen. Save text corrects the transcript without changing audio.
Edits are also saved on passage changes and closing. Scan passage highlights
attention points. Transfer the transcript to the main editor to use its other
text tools; the existing editor project is backed up first.

To change spoken words choose your synthesis voice under Voices, then Regenerate
speech for the selected passage (up to 600 characters). Other passages retain
original audio. Tone and recording quality may differ, so listen to transitions.
Small edge fades reduce clicks and surrounding silence is retained where possible.
Invisible joins and equal duration are not guaranteed. Use original audio restores
the recording without deleting edited text. Omit excludes the entire passage
interval from the new edit, not from the source. This is not a fine waveform editor.

Export edited MP3 produces a new MP3, separate SRT/VTT and edit metadata. Ordinary
studio background layers are not added again because your recording may already
contain music. Later export times shift after replacements/omissions. Source
editor timestamps remain tied to the recording; exported captions follow the new
edit, with estimated timing inside passages. Continue in the audio timeline after
export; use this recording editor to regenerate source passages.

Project > Resume recording edits opens the last transcript project, whose path is
also saved with the ordinary project. Use a Project bundle to move the transcript,
source copy and available replacements together. Text-only export is insufficient.
Recognition can get names, quotations and spelling wrong. Review and listen back.
Speakers are not automatically separated.


Interrupted model downloads preserve received data. Click install again to resume; keep PodcastStudio_Transcriptie.


## 25. Record your podcast directly
Open Audio > Record podcast live. This records a complete podcast, separately
from the short voice-cloning reference recorder. Choose your microphone. Refresh
microphones only lists inputs; it does not start capture. If required, Install
microphone software performs a small one-time online setup. Recording itself
needs no speech model or internet. The existing My voice runtime can be reused.

The script reader is a copy of the main editor text. Scroll or make temporary
changes while speaking; these do not replace the saved main script. Start recording
opens the microphone. The timer shows recorded audio duration and the meter shows
input level. High levels and detected interruptions produce messages.

Pause excludes paused time; Resume continues. Stop and save finalizes the WAV.
Audio streams to disk instead of accumulating in RAM. A normal stop retains a
work-folder copy automatically. A periodically updated WAV header helps recovery,
but unexpected power loss may still lose recent audio. Keep backups. Recording
is limited to four hours or the WAV format limit, whichever comes first.

Listen plays the recording; Stop playback only stops sound. Save as WAV copies
to your chosen filename. Save as MP3 converts without adding music or generated
speech. Edit this recording opens import with the WAV already selected for local
transcription and editing (topic 24). Recording and voice cloning are separate.
Stop before closing the recorder. Closing the main app while recording asks to
stop and save first. The last recording path is remembered and can be bundled.
Recording controls were tested using a simulated microphone; test a short clip
with your own device and Windows microphone permissions on first use.

Model download now displays received MB and reconnection attempts and refreshes
requests. The complete small model was actually downloaded, integrity-checked
and tested on Dutch speech offline using the NVIDIA GPU on this computer.


## 26. Equalizer, rumble filter and speech compression
Audio > Equalizer and speech dynamics offers six bands: 100, 250, 700, 1800, 4000
and 9000 Hz, each from -12 to +12 dB. Start with small adjustments. Too much bass
can sound muddy; high-frequency boosts may emphasize sibilance. Presets include
Neutral, Warm narrator, Clear speech, Soft and calm, Compact radio voice and
Less muddy. They are starting points, not automatic repairs.

Enable equalizer activates processing. Reset to neutral clears bands/options and
disables it. The 80 Hz high-pass filter can reduce rumble, not arbitrary noise or
echo. Gentle compression reduces level differences using fixed settings; it does
not repair distortion. Preamp sets the level before processing. Leave headroom
when boosting bands; the final limiter remains in place.

Voice only processes the speech track before background music. Full final mix
also affects music/ambience. An imported recording may already contain music on
the same track, which EQ cannot separate. Subsequent normalization can compensate
average level changes. EQ does not change pitch or pace.

Choose a file and start time for a sample of up to 15 seconds. Compare with and
without processing. A raw montage WAV is preferred when available. Standalone
files are always processed as a whole regardless of the scope selector. Reapplying
EQ to an already processed MP3 stacks effects; use raw sources where possible.

Save retains settings in the project and active montage; re-export the montage.
An open timeline also receives the change. Montage undo/redo restores montage EQ;
open and save the EQ dialog to reuse that choice for future generation. Templates
store EQ too. Standalone EQ export creates a new MP3 and preserves the source.
Live WAV remains dry; live Save as MP3 uses saved EQ. Transcript edit export captures
current EQ. Effects are post-processing, not real-time microphone monitoring.


## 27. Using the graphical equalizer
The redesigned equalizer has a smooth curve and six coloured points. Drag a
point vertically to adjust its gain; centre frequencies remain fixed at 100,
250, 700, 1800, 4000 and 9000 Hz. Numeric fields track changes and accept direct
entry. Double-click a selected point to reset its band; Up/Down adjusts 0.5 dB.

The curve shows the combined EQ-band response, not a moving audio spectrum.
Overlapping bands can shift a point relative to its own gain value. The rumble
filter, preamp and compressor are excluded from this band graph. EQ processing
uses 44.1 kHz for consistent plotting/output. Disable EQ to bypass processing.

Choose a preview file and start time, then Play a sample of up to 15 seconds.
Original/With EQ switches at the same position; pause/resume or seek on the bar.
Matching preview audio is cached. Editing a band stops playback: click Play
again to hear new settings. This is not real-time microphone monitoring.

Editing a preset marks it Custom. Reset to neutral clears options. Save and apply
retains settings and marks the montage for re-export; your source is preserved.
An existing MP3 changes only when re-exported. Export MP3 processes the selected
file directly into a new edited MP3.

## 28. Voice, room and sound effects (v1.44)
Open Audio > Voice, room and sound effects. Drag a round dial vertically, scroll, or use arrow keys. Double-click resets its default; numeric entry provides exact values.

**Adjust passage:** select an existing montage audio clip. Set speed, pitch, warmth, clarity, volume and the following pause. Preview original/adjusted audio, then Apply to this passage. A new take preserves the source. Repeated adjustments use the original baseline to avoid stacking. This operates on the whole selected audio block, not arbitrary selected words. Lock an approved take and export the montage again.

**Room and echo:** dry studio, warm living room, small hall, auditorium, church and echo presets offer amount, size and decay controls. These simulate acoustics and cannot remove existing reverb. Use modest amounts for intelligible speech. The tail ends at the end of the episode.

**Sound effects:** choose a doorbell, gravel or passing car, or import your own WAV/MP3. Included sounds are synthetic examples; use your own recordings for realism. Set start time, duration, volume, stereo position and fades. Left-to-right/right-to-left create movement. Click Insert / update, then Save. Up to 32 sounds are supported. At selected passage fills that clip's current start time. Times remain fixed seconds: recheck after speed or montage changes.

Preview first 15 seconds uses the indicated source file, not an automatically rebuilt montage. Prefer a dry source to avoid applying already mixed effects twice. Export audio file with effects makes a new MP3. Saved effects also apply during generation and montage export. Save a named project through Project > Save; use a project bundle to include source files. Processing is offline post-production, without live microphone effects monitoring.

## 29. Track mixer and volume automation (v1.45)
Open Audio > Track mixer and volume automation. The voice occupies the first lane. Add music and sounds as coloured, separate tracks. Each extra track holds one source file; add multiple sounds on separate tracks. New sounds play once by default. Voice audio comes from current montage takes or a chosen standalone source. The mix ends with the voice.

Enable Use track mixer in final mix. It replaces the old music, ambience and sound-cue mix to avoid duplicate audio. Voice room effects and EQ remain available; manual volume automation replaces old automatic ducking. Import existing background copies music/ambience and sound cues. Check imported settings: old cue pan and fades are not copied. Imported old background music retains looping.

Select a track to set Start, Source offset and Duration in seconds. Without Repeat, playback is limited to available source audio. Drag a clip horizontally to move it; drag its right edge to change duration. Update track commits the fields. Play and Save also commit the selected track fields. Enable Repeat only when needed. A doorbell normally plays once.

Track volume dB controls the whole track. Double-click inside its coloured block to add a point; drag points vertically for volume or horizontally for time. Right-click deletes a point. Exact time/dB fields with Add / update point are also available. Point levels add to the track gain, with smooth dB ramps between them and held values before the first/after the last point. Point times are relative to the track start. Points beyond a trimmed clip remain stored but do not sound until it is extended again.

For example, a -12 dB track with points at 0 s / 0 dB and 5 s / -18 dB fades from -12 to -30 dB over five seconds. Add a later pair of points for an ending fade. -60 dB is nearly silent; Mute is fully silent.

Audition this track plays the selected track alone. Solo restricts combined playback to marked tracks; Mute takes priority. Click the ruler or type the playhead time, then Play from playhead. The mix is prepared before playback, rather than mixed live. Edits stop the preview; press Play again. Preview and export use the same automation. Limiting or final normalization can affect the resulting loudness.

Save stores tracks, points and enablement in the montage/current settings. Save a named project too; project bundles include source assets. Export mix creates a new MP3; montage export also uses saved automation. Original source files remain untouched. Up to 32 extra tracks and 100 points per track. Recheck fixed times after narration speed changes.

Sound audition: Audio > Voice, room and sound effects now offers Audition sound first, at a separate audible preview level independent of low background gain. Audition adjustments uses your selected volume, duration, fades and stereo settings. Samples last up to 15 seconds. If even the raw audition is silent, check the Windows volume mixer and speaker/headphone output. Gravel footsteps is a six-second synthetic demonstration sound.

## 30. One workspace with embedded panels (v1.46)
Main tools now open inside the main window. Text/Voices/Audio and output stay in the upper-left area. Voice/effects, EQ, recording, transcript editing and help open as right-side tabs. Passages/takes and the track mixer open in the bottom area. You can see text, a voice tool and the montage together. These are fixed dock areas with tabs; free drag-and-drop docking or detaching is not supported yet.

Drag the vertical or horizontal divider to resize areas. Ratios are saved with settings. View > Reset workspace restores the default split. Large tools have horizontal/vertical scrollbars to reach controls outside the visible area. Mixer playback, stop, save and export controls remain pinned at the bottom.

Reopening the mixer, EQ, effects or passage menu activates its existing tab instead of duplicating it. Close panel closes only that tool. Save first: reopening restores saved settings, not unsaved edits from a closed panel. Wait for running audio work to finish before closing. Stop and save a live recording first. File choosers, confirmations and some smaller utilities remain separate dialogs.

## 31. v1.47 workspace: tracks, rotary controls and eight-band EQ

### Overview
The unified track workspace opens at startup and through Audio > Track mixer and volume automation. Text remains left, the selected clip/track inspector is on the right and a single timeline is below. Normal timeline, effects and EQ commands share this workspace. Takes and chapters (advanced) retains the older detailed take/chapter tools.

Four lanes hold Voice (teal), Music (purple), Ambience (ochre) and Effects (coral). Background lanes can contain several clips; overlapping clips add together. Click a lane header for whole-track settings or a coloured clip for its own settings. Gains at the two levels add: -6 dB clip and -12 dB lane equals -18 dB before limiting.

Fit all shows the entire project without horizontal scrolling and adapts when resizing. Headers remain fixed on the left. +/− or the slider zoom around the playhead; Zoom to selection focuses on a clip. Ctrl+wheel zooms; plain wheel scrolls vertically. A horizontal scrollbar appears in detail mode. Click the ruler to place the playhead. Final audio ends with the voice, even if backgrounds extend further.

### Clips and voice
Music +, Ambience + and Effect + import WAV/MP3/FLAC/M4A/OGG. Clips start at the playhead with repeat off. Their initial duration is limited to the remaining narration duration. The sound library lets you audition before adding. Its independent audible preview level is not reduced by the mix gain. Included doorbell, gravel and car files are synthetic examples.

Drag background clips horizontally to move them, or drag the right edge to trim. Start, Source offset and Duration provide exact seconds. Without Repeat, audio stops when the source ends even if the block is longer; Repeat fills the requested duration. Fades can be applied per clip or lane. Remove clip removes the selected background clip without deleting its source.

M/S mean Mute/Solo. Multiple solo lanes are allowed and Mute takes priority. Clip-level mute/solo exists for backgrounds too. Small coloured transport buttons and rotary controls keep the interface compact. Drag knobs vertically, scroll, use arrow keys, type exact values, or double-click to reset.

Voice clips are existing montage passages/takes. Selecting one reveals its settings and highlights matching text when the passage is present literally. Selecting text inside a known passage selects the whole passage; arbitrary word boundaries are not automatically cut. Speed, pitch, warmth, clarity, volume, stereo position, pause and source trim are available. Apply makes a new take while retaining the source; repeated edits use the original adjustment baseline. Unlock approved takes before editing/reordering. Dragging a voice clip reorders passages while retaining their chapter association. Recheck background times after length/order changes.

Load voice imports an existing recording into a new single-passage montage with a local WAV working copy. Its initial text is the filename; use the existing transcription workflow for spoken text. The original recording is unchanged.

### Automation
Choose Volume line or Stereo line. Double-click to add a point; drag horizontally for time and vertically for value; right-click removes it. Exact point fields are also available. Volume is -60 to +12 dB; pan is -1 left, 0 centre, +1 right. Lane points use episode time; clip points use local time. On voice, double-clicking the line edits the overall voice lane.

Automation gain adds to fixed gain, with smooth dB ramps and held end values. -60 dB is nearly silent; Mute is fully silent. Stereo points interpolate position. For music at -12 dB, points at 0 s/0 dB, 5 s/-18 dB, 25 s/-18 dB and 30 s/0 dB lower it under speech and bring it back. Duck during speech additionally lowers backgrounds when an audible voice is present. Ducking dB controls response strength, not an exact guaranteed attenuation. Use it on the whole music lane for predictable results.

### Eight-band parametric EQ
The right-hand EQ tab belongs to the current lane/clip/voice selection. Enable EQ bypasses the full EQ; Band enabled controls an individual band. The graph is a calculated combined response, not a live spectrum. Choose a point or band button 1–8. Drag horizontally for frequency and vertically for gain; scroll on the graph for the selected Q.

Each band provides frequency 20–20,000 Hz, gain -18 to +18 dB and Q 0.15–18. Low Q is broad; high Q is narrow. Bell, low shelf, high shelf, high-pass and low-pass types are available. Pass filters offer 12/24/48 dB per octave; gain does not set their cutoff. Graph and audio use identical coefficients.

Presets are editable and can be saved under a personal name. Without EQ/With EQ audition the selected item with other processing unchanged. Match A/B loudness normalizes samples to the same loudness target, without changing exports. Samples restart at the selection beginning. Comparisons on very short/silent material may be less meaningful.

Existing six-band EQ settings migrate to six of the eight new bands on first workspace import. Existing general rumble/compression settings remain separate processing and are not plotted in the new EQ curve. Compare a short sample when migrating an old project.

### Room, playback and saving
Room offers reverb amount, size, decay, echo and dry-to-church presets. It adds acoustics rather than removing existing reverb. Tails end at clip/episode boundaries. Modest settings preserve speech intelligibility.

Play starts at the playhead; Pause resumes and Stop ends playback. Clip preview auditions the selected passage/clip/lane. Mixing is prepared before playback rather than monitored live. Edits stop stale audio. Content edits enable the track mixer; disable Mixer enabled to bypass it. Individual selection audition can preview settings independently.

Save stores tracks, points, EQ and settings and applies modified voice drafts as new takes. Project Save (Ctrl+S) also preserves unapplied passage settings for the next montage export. Use a named project and a project bundle to include sources. Export MP3 writes a new mix with metadata/cover; source overwrite is refused. Ordinary montage export uses saved processing too. Closing a dirty workspace asks about saving; application close retains settings in automatic recovery.

An enabled mixer replaces the old background mix to prevent duplication. Old settings migrate where possible. Fixed background times need checking after narration changes. Styling follows the approved colour/layout concept within the existing Windows/Tk interface.

## 32. Project management and support (v1.48.1)

Project > New project (Ctrl+N) starts empty text and an empty montage. Voice models, custom-voice references and general preferences remain available. Music, ambience, artwork, previous output and project metadata are disconnected; original source files are not deleted.

Ctrl+S saves the current named project to its existing location. An untitled project first asks for a filename. Project > Save project as (Ctrl+Shift+S) creates a separate project file and continues in that copy. Source media remain references; export a project bundle for a portable copy with available sources.

An asterisk in the title and the status line indicate unsaved changes. The full project location is shown in the status line. Before new, open and close, choose Yes to save, No to continue without saving changes to the project file, or Cancel to stay. Cancelling the filename dialog also cancels the project switch.

Recent projects retains up to twelve project locations. A missing entry can be removed from this list without deleting source files. The episode library remains available separately.

Automatic saving provides recovery and does not replace deliberate project saves. If an earlier session differs from the saved project, choose to recover the session, open the last saved project, or start empty. For an untitled session, recover or start empty. Recovery does not overwrite the previously saved project. Choose Save or Save as afterwards.

Project > Relink missing project files lists missing references. Locate each file or search a folder for unique matching filenames. Clip timings, EQ, effects and automation points are preserved. Resolve duplicate names manually. An ONNX voice needs its matching .onnx.json file. Save the updated project afterwards.

Help > About Podcast Studio shows the version, build, publisher and contact. Contact and support includes cyberfirepulse@gmail.com and the GitHub product page. Report a problem creates an editable report with general system and version information, without automatically including scripts, recordings, source paths or license keys. Review it before saving or composing an email. Nothing is sent automatically.

Help > License details displays the edition, last status, validity dates where supplied, installation ID and verification information. The customer build enforces license verification; text and projects remain accessible without appropriate activation, but licensed production features may be blocked. License agreement and Privacy and online services are separate Help entries.

Local and online speech are different routes. Edge sends text to the speech service; publishing sends selected output to the host. Downloads, updates and activation use the internet. Review the privacy overview before sharing personal content. Updating requires an accessible, valid update manifest from the publisher. The app reports an unavailable source and does not silently replace itself.
