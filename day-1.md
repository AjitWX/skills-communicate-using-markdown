# Daily learning in Github

## Morning Planning
<img alt="Cannabis for breakfast" src="https://cdn12.picryl.com/photo/2016/12/31/marijuana-cannabis-weed-nature-landscapes-0183e8-1024.jpg"
width="200" align="right">

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
      
## Review for the day

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
