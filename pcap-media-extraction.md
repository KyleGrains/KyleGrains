# PCAP Media Extraction

Local FFmpeg + Wireshark work for extracting media from packet captures.

## Scope

- RTP/RTSP media extraction from packet captures
- RTMP and HTTP-FLV stream extraction
- HLS, MPEG-DASH, and MPEG-TS media extraction
- RTP payload handling for common VoIP/audio codecs
- H.263, H.264, and H.265 video payload handling

## Local Work

The current implementation lives in local FFmpeg and Wireshark worktrees and is being sorted for publication.

- FFmpeg-side work: custom `pcapsdp` / `pcaprtp` paths and media handling
- Wireshark-side work: `pcaptool`, RTP/VoIP stream discovery, RTMP/FLV extraction, and support documentation

## Notes

The project documentation includes support notes for RTMP, HTTP-FLV, HLS, MPEG-DASH, MPEG-TS, RTSP/RTP, and VoIP/RTP codec handling.
