# LinkedIn Playback Technology<br />for [Video.js](https://github.com/videojs/video.js)

## Example
```html
<!DOCTYPE html>
<html>
<head>
  <link type="text/css" rel="stylesheet" href="../node_modules/video.js/dist/video-js.min.css" />
</head>
<body>
  <video
    id="vid1"
    class="video-js vjs-default-skin"
    controls
    autoplay
    width="640" height="264"
    data-setup='{ "techOrder": ["linkedin"], "sources": [{ "type": "video/linkedin", "src": "https://www.linkedin.com/posts/github_new-back-end-employee-of-the-month-activity-6968991348158865408-hQZV?utm_source=share&utm_medium=member_desktop"}] }'
  >
  </video>

  <script src="../node_modules/video.js/dist/video.min.js"></script>
  <script src="../dist/vjs.linkedin.min.js"></script>
</body>
</html>
```

See the examples folder for more

## How does it work?
Including the script vjs.linkedin.min.js will add the YouTube as a tech. You just have to add it to your techOrder option. Then, you add the option src with your YouTube URL.

It supports:
- Regular URLs: https://www.linkedin.com/posts/github_new-back-end-employee-of-the-month-activity-6968991348158865408-hQZV?utm_source=share&utm_medium=member_desktop

## License
The MIT License (MIT)