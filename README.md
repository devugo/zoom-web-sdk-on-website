VIDEO CONFERENCING USING ZOOM WEB SDK
=======================================


## Overview
This project utilizes Zoom web SDK to integrate a video conferencing app into a website.

## Site Preview Images
[View on Load]("https://cdn.hashnode.com/res/hashnode/image/upload/v1611423799852/MgN1X1b-L.png")

## How to run locally
- Run `git clone https://github.com/devugo/zoom-web-sdk-on-website.git` on your terminal/cmd to clone the project from GitHub.

- On `line 69`, change the **url** of the request to your signature app url.
Want to know how to create a signature generator app? Check out this [blog post]("https://blog.devugo.com/how-to-integrate-zoom-web-sdk-to-a-website"). The blog post explains how every bit of code here was written.
- Set your `apiKey` on `line 45`.
- Change `meetingNumber` to your zoom meeting number on `line 46` and `line 64`
- Set `role` value on `line 65`, set '1' if host and '0' if visitor.
- Set `userName` on `line 47`.
- Set meeting `password` on `line 49` if applicable.
- Run `index.html` on a browser.

And that's all that needs to be done. Remember to check out this [article]("https://blog.devugo.com/how-to-integrate-zoom-web-sdk-to-a-website") if you find anything unclear.