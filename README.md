# PritStik website

Recreation of the original PritStik website optimised for mobile and modern browsers.

The [original website](http://web.archive.org/web/20040816015951/http://www.seniordads.fsnet.co.uk/mrr/pritstik/default.html) was created in [Macromedia Dreamweaver](https://en.wikipedia.org/wiki/Adobe_Dreamweaver) and hosted on [Freeserve](https://en.wikipedia.org/wiki/Freeserve) on [The Senior Dads](https://www.youtube.com/@seniordads9594) website from 2000 onwards. The website made use of Dreamweaver features such as libraries and macros. Although the website made use of (at the time, new) CSS, it also used a lot of &lt;[FONT](https://www.w3schools.com/tags/tag_font.asp)&gt; tags as a fallback for older browsers. Despite this, the website was optimised for dialup internet access in an age when that was the default for most users of the internet in the UK.

This recreation preserves the look and the content of the original website, but removes the &lt;FONT&gt; tags and Dreamweaver directives within the HTML, further optimises the HTML and CSS, and reconfigures the generation of the website as a [Jekyll](jekyllrb.com/) instance on [GitHub Pages](https://pages.github.com), with added HTML and CSS compression. As a result, the HTML of the largest page is only 5KB and the CSS is 4KB, so you'll probably spend more time loading the images than the page itself! In addition, some wonky links and broken images have been fixed.

And! This recreation includes something that was not possible in the original website: a [favicon](https://alephnaughtpix.github.io/pritstik/favicon.ico)!

## Updates

### v0.4 (2023-03-14)

* Added the original MP3 files, taken straight from the original MP3.com DAM CD-A/ROM of *Murder in the Recording Studio*. That means that these are the original 128kbps stereo MP3s that were uploaded to MP3.com in 2000. (The bitrate restriction was imposed by MP3.com) As these MP3s were used as the source for CD-Audio, that means these are as good a quality as if you had bought the album from mp3.com in 2000! (The versions I've seen from file-sharing sites are likely to be sourced from an MP3.com DAM CD as well, but still...)
* Added download links to the MP3s from the songs pages.

### v0.3 (2023-03-13)

* Added lightbox style gallery feature. This uses [SimpleLightbox](https://simplelightbox.com). (The first Javascript in this website!)
* Applied that gallery feature to the front and inside cover art of the CD on the CD page, so that you can now see the full sized cover art from the original PSD files for the cover art.

### v0.2 (2023-03-12)

* Added a "video" section for songs pages.
* Added link to a new "lyric video" for "[PritStik (1987)](https://alephnaughtpix.github.io/pritstik/music/songs/pritstik1987.html)".
* Changed the "listen" links code in the CD page to link to the video section of the page if there is a video.
* Cleaned up some of the CSS files.
* Added a small watermark at the bottom of each page, linking back here.

### v0.1 (2022-09-23)

* Initial re-creation of the original site using the original assets from the [Wayback Machine archive site](http://web.archive.org/web/20040816015951/http://www.seniordads.fsnet.co.uk/mrr/pritstik/default.html).
* Site converted to [Jekyll](jekyllrb.com/) 3.9.2 for easier maintainance, and deployment to [GitHub Pages](https://pages.github.com)
* Links to "streaming" of songs disabled as those haven't worked for over 20 years!
* Missing images restored.
* Fixing of local links within site.
* Deployment to GitHub Pages at [https://alephnaughtpix.github.io/pritstik](https://alephnaughtpix.github.io/pritstik)

## Notes

* Apparently as a result of adding the GitHub Pages extension to the project, the generated site contains a file "assets/css/styles.css". This file is 75KB in size, but it's not used anywhere by the website. ¯\_(ツ)_/¯
