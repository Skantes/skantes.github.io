---
layout: post
title: "Introducing VLCBenchmark"
date: 2021-01-20
---

<p class="image" align="center">
  <img src="/assets/benchmark-icon.png" style="height:200px; width:200px;" alt>
</p>
<p align="center" style="color:#777777">
    <em>VLCBenchmark logo</em>
</p>
<br>

VLCBenchmark is an open-source benchmark application focused on testing android devices' video capabilities using the VLC Media Player Android App.

It will rate Android devices according to their capacity to play videos, and then publish the results on our [website](https://bench.videolabs.io), so that people can consult devices' scores.


## Why ?

[//]: develop more
[//]: maybe add storyline / implicate reader

As of right now, there isn't any android benchmark application focused on video, with the expertise that [VideoLAN](https://videolan.org) can offer.

This benchmark will help users who wish to watch videos on their mobile to know before a purchase what their future Android device can do.

Furthermore, it is also to give an incentive for Android manufacturers to work with [VideoLAN](https://videolan.org), and help us improve VLC-Android on their devices.


## How does it work ?

[//]: for technical people -> link to samples / sample specs
We host a list of video samples encoded according to many different parameters, such as codec, resolution, fps, and bit depth.
The app will run each sample using vlc-android in software and hardware decoding, testing playback, and image quality.


[//]: as there isn't much 
### Playback

This test will look for problems while playing the sample, is it slow, is it stuck, etc.

### Image quality

This test will look for imperfection in the image (artifacts, green lines, etc).

### Speed

This test will converge on to the maximum playback speed

### Results

These tests are then summed up to rate the Android device.


<p align="center">
    <img src="/assets/result-page.png" style="width:300px;"/>
</p>
<p align="center" style="color:#777777">
    <em>Result page</em>
</p>

Once finished these results can be uploaded and shared on the main [website](https://bench.videolabs.io).

## The website

## Download the app

You can find the app on the [Google Store]().

[//]: recap why / how + opening to the rest ...
## Conclusion



## Contacts

You can contact us:
* By email at: <contact.vlcbenchmark@gmail.com>
* On twitter at: [@TheSkantes](https://twitter.com/TheSkantes)

You can find the project's source on the [VideoLAN gitlab](https://code.videolan.org/videolan/vlc-bench).
