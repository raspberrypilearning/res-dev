## Video and animations

Videos and animated gifs can be added to project steps.

They should always be enclosed in `--- no-print ---` tags with an image or text fall back inside `--- print-only ---` blocks.

Online streaming services should be avoided due to filtering in school.

Videos and gifs should be placed into the images folder. Try to keep the file size as small as possible. Resolutions larger than 1000px wide should be avoided, and videos should be no longer than a couple of minutes long.

--- no-print ---
<video width="640" height="360" controls>
<source src="images/ngtgyu.mp4" type="video/mp4">
Your browser does not support mp4 video, try FireFox or Chrome
</video>
--- /no-print ---

--- print-only ---
You avoided neing rickrolled
--- /print-only

This video was added using the following syntax

```markdown
--- no-print ---
<video width="640" height="360" controls>
<source src="images/ngtgyu.mp4" type="video/mp4">
Your browser does not support mp4 video, try FireFox or Chrome
</video>
--- /no-print ---

--- print-only ---
You avoided neing rickrolled
--- /print-only
```
