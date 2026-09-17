# d1.17k VFX Portfolio

A fast, minimal portfolio site designed around showing the work rather than turning the page into a social-media feed.

## How to add work

Open `videos.js` and add entries:

```js
{
  title: "Artist — Track",
  category: "VFX / Music Video",
  src: "https://your-host.com/video.mp4",
  poster: ""
}
```

The site intentionally does not store large video files inside the website repository. Host the videos on a video/storage service and paste the direct MP4 URLs into `videos.js`.

## Recommended setup

For a professional portfolio:
- Website: this site
- Video storage/delivery: Cloudinary, Bunny Stream, Vimeo, or similar
- Discovery: Instagram/TikTok/YouTube
- Bio link: point directly to this portfolio

That gives you a clean portfolio while social platforms remain the places where people discover you.

## Deploy

This is a static site, so it can be deployed to GitHub Pages, Netlify, Vercel, Cloudflare Pages, or similar.

Replace:
- `d1.17k` with your brand/name if desired
- `you@example.com` with your email
- the Instagram URL with your actual profile
