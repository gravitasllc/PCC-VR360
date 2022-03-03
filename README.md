# PCC - 360° Media  
Pristina City Center - Interactive Virtual Tour VR 360°


360° media, consisting of 360° videos and images, is a great way for developers to enhance traditional apps with immersive content. You can embed a 360° video into a travel app to provide viewers with an Underwater scuba diving tour as they plan a vacation, or into a home-building app that takes prospective buyers on a virtual walkthrough of their home before it’s built.

Although 360° media supports true stereoscopic VR playback through compatibility with VR platforms like Google Cardboard, it can also be displayed in a simple “magic window” that can be viewed from desktop browsers and mobile apps without any special VR hardware.

You can create 360° media in either mono or stereo format. Images and video generally need to be stored in the equirectangular-panoramic (equirect-pano) format, which is a common format supported by many capture solutions.

Mono 360 uses a single pano.	Stereo 360 uses two stacked panos.

360° images can be stored as png, jpeg, or gif. We recommend you use jpeg for improved compression.
For maximum compatibility and performance, image dimensions should be powers of two (e.g., 2048 or 4096).
Mono images should be 2:1 aspect ratio (e.g. 4096 x 2048).
Stereo images should be 1:1 aspect ratio (e.g. 4096 x 4096).
360° videos

360° videos should be stored as mp4s encoded with h264.
Mono videos should be 2:1 aspect ratio.
Stereo videos should be 1:1 aspect ratio.
Some older devices cannot decode video larger than 1080p (1920x1080). If maximum compatibility and quality is a priority, we recommend that developers provide both a monoscopic 1920x1080 video and a stereo video at 2048x2048 or higher.
