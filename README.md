





<div align="center">
  
![Avee Player PC Banner](assets/avee-player-pc-banner.png)
# Avee Player for PC
### PoshDeluxe Edition / Windows Remastered

**The Avee desktop experience, pushed further.**

Bringing new life to the legacy Windows version of Avee Player
with continued development of its editor, visualizer compatibility,
and high-resolution video export.

[Features](#-the-next-chapter) ·
[Showcase](#-visualizer-showcase) ·
[Performance](#-early-export-results) ·
[Bug Reports](#-found-a-bug)

**Unofficial community modification by ChrisPosh**


------



<hr>

<h2 align="center">🖥️ PC Requirements & Tested Hardware</h2>

<p align="center">
  Tested configurations for Avee Player PC PoshDeluxe Edition.
  Performance depends on the preset, resolution, frame rate, and workload.
</p>

<table>
<tr>
<td width="50%" valign="top">

<h3>🔹 Low-Spec Configuration</h3>
<p><strong>Community Tester</strong></p>

<table>
<tr><th>Component</th><th>Specification</th></tr>
<tr><td>CPU</td><td>AMD FX-6300</td></tr>
<tr><td>GPU</td><td>NVIDIA GeForce GTX 960</td></tr>
<tr><td>RAM</td><td>12 GB</td></tr>
<tr><td>Status</td><td>Community tested</td></tr>
</table>

</td>
<td width="50%" valign="top">

<h3>🔷 Mid-Spec Configuration</h3>
<p><strong>Developer's PC</strong></p>

<table>
<tr><th>Component</th><th>Specification</th></tr>
<tr><td>CPU</td><td>Intel Xeon E5-2630 v4 @ 2.20 GHz</td></tr>
<tr><td>GPU</td><td>AMD Radeon RX 550 Series</td></tr>
<tr><td>RAM</td><td>Update with actual capacity</td></tr>
<tr><td>Preview</td><td>Reported smooth on tested projects</td></tr>
<tr><td>Status</td><td>Developer tested</td></tr>
</table>

</td>
</tr>
</table>

<hr>

### ⚡ Performance Notes

- The existing Windows application uses GPU-accelerated rendering.
- Real-time preview performance varies with visualizer complexity
  and the number of active effects and audio providers.
- High-resolution and high-FPS exports require additional
  processing resources.
- These configurations are reference points, not guaranteed
  minimum or recommended specifications for every project.

**More hardware compatibility testing is welcome.**

---







</div>

---

## The Next Chapter

Avee Player has long been associated with music visualization
on Android. PoshDeluxe Edition is focused on taking the legacy
Windows experience further.

Rather than replacing the original desktop interface with an
unrelated player, the project builds on the existing Windows
application and its rendering capabilities.

The objective is straightforward: make desktop-based visualizer
editing and video production more capable, more accessible,
and worth using on modern Windows PCs.

No traditional Android emulator is required for the intended
Windows workflow. The original Windows Avee installation is
currently required.

## ✦ The Next Chapter

### Native Windows Experience
Work directly with the legacy Windows application instead of
relying on a conventional Android emulator workflow.

### GPU-Accelerated Visualization
Build on the Windows application's existing GPU-accelerated
rendering pipeline. Actual performance depends on the hardware,
preset complexity, resolution, and CPU workload.

### High-Resolution Video Export
Explore higher resolutions, configurable frame rates, and
higher-bitrate output for demanding visualizer projects.

### A More Capable Editor
Editor improvements are in development, including hold-to-drag
interaction, element tags, themes, interface scaling, and other
quality-of-life features.

### Built for Further Development
Compatibility fixes, editor improvements, and export refinements
are being tested through community feedback and experimental builds.

## ◈ Visualizer Showcase

### Triangle Visualizer
![Triangle visualizer](screenshots/triangle-visualizer.png)

### Logo Visualizer
![Logo visualizer](screenshots/logo-visualizer.png)

*Captured from tester builds of the Windows application.*

## ⚡ Early Export Results

Early development tests have demonstrated promising export
performance on the developer's test system.

| Test | Resolution | Frame rate | Bitrate |
|---|---|---:|---:|
| Test 1 | 1280 × 720 | 60 FPS | Not recorded |
| Test 2 | 1920 × 1080 | 75 FPS | 30 Mbps |
| Test 3 | 2560 × 1440 | 100 FPS | 40 Mbps |

Reported export times:
- 1080p at 75 FPS: approximately 1 minute.
- 1440p at 100 FPS: approximately 3 minutes.

These are preliminary developer-reported results, not standardized
benchmarks. Export duration and playback performance will vary
by system, preset, audio, and rendering workload.

Demo recordings:
- [1080p / 75 FPS test](https://streamable.com/obscym)
- [1440p / 100 FPS test](https://streamable.com/k96m6s)

## 🛠️ Current Development Status

PoshDeluxe is an active experimental modification.
Features and compatibility are still being refined.

### Known Issues
- Broken effects, compositions, or audio providers may be treated
  as missing elements and fail to render.
- Templates saved by the Windows build may report version
  incompatibility when imported into the mobile version.
- Hold-to-drag editor interaction is still being implemented.
- Some editor operations may pause or behave inconsistently.

### Planned Features
- [ ] Hold-to-drag editor interaction
- [ ] Element tags
- [ ] Themes
- [ ] Interface scaling
- [ ] FPS counter
- [ ] Discord Rich Presence
- [ ] Export notifications
- [ ] Further preset and template compatibility improvements

Planned features are not necessarily available in current builds.

## 🚀 Installation

The original Windows Avee Player installation is required
for the current experimental workflow.

Release packages, supported Windows versions, installation
steps, and build-specific requirements will be documented
alongside each available release.

**Back up your existing installation and project files before
testing experimental builds.**

## 🐛 Found a Bug?

Please include the following information in your report:

- Build number
- Windows version and GPU
- Steps to reproduce the issue
- Affected preset or project file
- A short screen recording, if possible

For export problems, include your export settings and the
resulting video's resolution, frame rate, duration, and file size.

Please remove personal information from logs and shared files.

## Disclaimer

Original Avee Player by Daaw Aww.

Unofficial PoshDeluxe modification by ChrisPosh.

This is an independent community project and is not an official
Avee Player release. Avee Player and associated trademarks belong
to their respective owners.

Use and redistribution of original application files, code,
and assets remain subject to their applicable licenses and
permissions.
