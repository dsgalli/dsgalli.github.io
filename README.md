# Video pages

Every file in the `_videos` folder is one shareable page.

`_videos/demo-reel.md` becomes **https://dsgalli.github.io/demo-reel/**

A file looks like this:

```
---
title: Demo Reel
video: https://vimeo.com/123456789/abcdef1234
---
```

- **title**: shown under the video and in the browser tab.
- **video**: paste the normal link from Vimeo or YouTube (unlisted Vimeo links work too).
- Optional: `vertical: true` for a 9:16 video, `image:` a thumbnail link for email previews,
  and any text below the second `---` shows as a short description.

## Change a video (the link you already sent keeps working)

1. Open the file in `_videos` on github.com and click the pencil (Edit).
2. Replace the link after `video:` with the new Vimeo or YouTube link.
3. Click **Commit changes**. The page updates within a minute or two.

## Add a new video

On github.com, open `_videos`, click **Add file → Create new file**, name it
`something.md` (that name becomes the link), paste the block above, and commit.

Don't rename a file once you've shared its link: the name *is* the link.
The pages are hidden from search engines, so only people you send the link to will find them.
