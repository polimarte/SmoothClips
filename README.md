# SmoothClips
This code extracts stable video segments. It analyzes motion using optical flow, calculating standard deviation and relative change. A threshold defines smoothness, filtering out shaky parts. Overlapping segments are removed. Using ffmpeg, it extracts smooth segments into separate clips, ideal for applications needing stable footage.
