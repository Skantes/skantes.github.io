---
layout: post
title: "Introducing early access VLCBenchmark"
thumbnail: "/assets/benchmark-icon.png"
date: 2021-04-02
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

This app is developped and released in early access by [Videolabs](https://videolabs.io) a company that was founded by [VideoLAN's](https://videolan.org) 
president to have full time developpers work on VLC.


## Why ?

[//]: develop more
[//]: maybe add storyline / implicate reader

As of right now, there isn't any android benchmark application focused on video, with the expertise that [VideoLAN](https://videolan.org) can offer.

This benchmark is either for professionnals in fields related to smartphones, or regular users that want to thoroughly test their device.

Furthermore, getting hardware decoding to work perfectly on all the different android phones out there with VLC-Android can be quite difficult without specifications from the manufacturer. Having specific results on their devices may provide incentive for Android manufacturers to work with [Videolabs](https://videolabs.io) and [VideoLAN](https://videolan.org), and help us improve VLC on their devices.

<p class="image" align="center">
  <img src="/assets/main-page.png" style="width:300px;" alt>
</p>
<p align="center" style="color:#777777">
    <em>Main page</em>
</p>
<br>

## How does it work ?

The benchmark will play video samples using the VLC-Android Media Player App, as it a widely used media player on Android.
It is hence a requirement to install VLC-Android to run the benchmark.

We host a list of video samples encoded according to many different parameters, such as codec, resolution, fps, and bit depth.
The app will run each sample using vlc-android in software and hardware decoding, testing playback, playback speed, and image quality.

You can find the video samples on the [VideoLAN FTP](https://streams.videolan.org/) and the specs [here](https://docs.google.com/spreadsheets/d/1xaD0JO8hr7fWD8PPSC8ALCCfuuhIObs0d-sWqiYMDwY/edit?usp=sharing).

### Tests

Playback: This test will look for problems while playing the sample, is it slow, is it stuck, etc.

Image Quality: This test will look for imperfection in the image (artifacts, green lines, etc).

Speed: This test will converge on to the maximum playback speed.

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

At [bench.videolabs.io](https://bench.videolabs.io) you can find benchmarks uploaded by users.

It will present benchmark results from many models and brands

<p align="center">
    <img src="/assets/benchmark-site-main.png" style="width:800px;"/>
</p>
<p align="center" style="color:#777777">
    <em>Best results on the main page</em>
</p>

Users will be able to checkout the benchmarks that they uploaded, with the results from the test, and information about their devices

<p align="center">
    <img src="/assets/benchmark-site-pixel3-bench.png" style="width:800px;"/>
</p>
<p align="center" style="color:#777777">
    <em>User Benchmark</em>
</p>

<p align="center">
    <img src="/assets/benchmark-site-pixel3-infos.png" style="width:800px;"/>
</p>
<p align="center" style="color:#777777">
    <em>Device information</em>
</p>

It will also be possible to get average results for a specific model.

## Download the app

You can find the app on the [Play Store](https://play.google.com/store/apps/details?id=org.videolan.vlcbenchmark).


## Contacts

You can contact us:
* By email at: <contact.vlcbenchmark@gmail.com>
* On twitter at: [@TheSkantes](https://twitter.com/TheSkantes)

You can find the project's source on the [VideoLAN gitlab](https://code.videolan.org/videolan/vlc-bench).
