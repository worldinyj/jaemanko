# Part 1–2 silent master | 2026-11-27

## Render result
- File: jaemanko_part1_2_1080p_silent.mp4 (delivered separately; binary not uploaded)
- 35,762,995 bytes; SHA256 f7bce854eb9a1de7f21ccd2dd41d813c673bb37e6e3a985a389155df69ce44a2
- FFprobe: 1920x1080, 24/1 CFR, 1257 frames, 52.375 seconds, H.264 yuv420p, SAR 1:1, BT.709 limited range, no audio stream.
- FFmpeg full decode PASS; duplicate/drop counters 0/0; moov precedes mdat (faststart).
- Input: s01–s10, each 736x384, 145 frames, 24fps, 6.041667s. S07 uses 115 frames (4.791667s) to stay within 4.8s. All other clips retain 145 frames.
- Central 94% crop then center aspect fill to 640x360; Lanczos scale to 1920x1080; unsharp=5:5:0.4:5:5:0.0. No creative color grading. Sampled crop QA at five times each for S03/S08/S09/S10: no visible star marks.
- libx264 CRF18 preset slow, yuv420p, -an, +faststart. FPS/timebase normalized to 24/AVTB between xfade steps.
- Fade in 0.5s; fade out 0.8s; all nine requested xfade durations passed as specified; offsets quantized to closest frame. End boundary exclusive.

## Sync table
| Clip | Start frame | End frame exclusive | Start s | End s | Incoming xfade | Requested s | Overlap frames |
|---|---:|---:|---:|---:|---|---:|---:|
| S01 | 0 | 145 | 0.000000 | 6.041667 | — | — | 0 |
| S02 | 123 | 268 | 5.125000 | 11.166667 | fade | 0.9 | 22 |
| S03 | 256 | 401 | 10.666667 | 16.708333 | fade | 0.5 | 12 |
| S04 | 382 | 527 | 15.916667 | 21.958333 | fadeblack | 0.8 | 19 |
| S05 | 493 | 638 | 20.541667 | 26.583333 | fade | 1.4 | 34 |
| S06 | 624 | 769 | 26.000000 | 32.041667 | fadewhite | 0.6 | 14 |
| S07 | 750 | 865 | 31.250000 | 36.041667 | fade | 0.8 | 19 |
| S08 | 851 | 996 | 35.458333 | 41.500000 | fade | 0.6 | 14 |
| S09 | 984 | 1129 | 41.000000 | 47.041667 | fade | 0.5 | 12 |
| S10 | 1112 | 1257 | 46.333333 | 52.375000 | fade | 0.7 | 17 |

Total 1450 - 30 trim - 163 overlap = 1257 frames. Previous subtitle draft untouched; narration, BGM, captions and visual acceptance pending. This is a silent Part 1–2 editing master, not a completed full memorial film. Existing film/ project not modified.
