# Interlaced Video Before Upscaling: The 540-Line Ceiling, Measured

Five deinterlacers measured against a known 1080p reference: vertical frequency response, the exact null at 540 lines (field Nyquist), whether to deinterlace before or after upscaling, and why the filter that reports success may have done nothing at all.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-interlaced-video-upscale/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
