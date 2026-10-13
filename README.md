# Credits Reel Maker

Make 9:16 scrolling-text reels (rolling credits style) in the browser and download them as MP4.

- Rich text editor: Title, Heading, Normal, Small, bold, italic, colours
- Fonts, background colours, background image with darken slider
- Built-in background music (original tracks in `music/`) or your own song
- 1080p, 2K or 4K MP4 download

## Files

```
index.html          the app
music/
  lofi-study.mp3
  soft-piano.mp3
  calm-pad.mp3
  upbeat-pop.mp3
```

The music tracks were made for this tool and are free to use in your reels.

## Put it online with GitHub Pages

1. Create a new repository on GitHub, for example `reel-maker`.
2. Upload `index.html` and the whole `music` folder (keep the folder name).
3. Go to **Settings → Pages**.
4. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
5. After a minute your link is ready:
   `https://<your-username>.github.io/reel-maker/`

## Notes

- Use Chrome or Edge for the fastest download.
- If you open `index.html` straight from your computer, the browser blocks the music files,
  so the app generates the music live instead. On GitHub Pages the MP3 files are used.
- If your browser can't make H.264/AAC video itself, the app downloads a one-time
  converter (about 32 MB) so the MP4 plays everywhere with sound.
