# tools

Downloads for the apps and tools I build. The builds live under
[Releases](https://github.com/Staiola/tools/releases), not in this repository.

Project pages: [staiola.studio/apps](https://staiola.studio/apps/)

Every download link below points at a specific release, because this repository
holds several apps and the newest release is not necessarily the one you want.

Everything here is signed with a Developer ID certificate and notarised by
Apple, so macOS opens it without a Gatekeeper warning.

## Kipowi

A player for video and audio that can also cut and export. Open a file, set an
in and out point, and write out exactly that part as MP4, MOV, GIF or audio. It
plays MKV, which macOS will not, with nothing extra to install. Single images
open in a small editor with background removal.

- **Download:** [Kipowi 0.5.0](https://github.com/Staiola/tools/releases/download/kipowi-v0.5.0/Kipowi.dmg)
- **Requires:** macOS 14 or newer. Universal for Apple silicon and Intel
- **Page:** [staiola.studio/apps/kipowi](https://staiola.studio/apps/kipowi)

The release also carries `Kipowi-0.5.0-Sources.tar.xz`, the matching source
archive for the open-source media components the app bundles — VLC, VLCKit,
FFmpeg and LAME. You do not need it to run Kipowi; it is published because those
licences require the corresponding source beside the binary. `SHA256SUMS.txt`
lists the checksums for both files.

### Installing

Open the disk image, quit any running copy of Kipowi, and drag it to
Applications.

## ExpressionGate

A macOS audio plugin you control by how loud you play. Quiet playing gives you
one set of effects, playing harder gives you another, and digging in gives you
a third. You set the three volume levels yourself and pick what each one does,
so the sound changes without you touching a pedal.

- **Download:** [ExpressionGate 1.11.3](https://github.com/Staiola/tools/releases/download/expressiongate-v1.11.3/ExpressionGate-1.11.3.pkg)
- **Formats:** Audio Unit (aufx), VST3 and Standalone app
- **Requires:** macOS 11 or newer
- **Page:** [staiola.studio/apps/expressiongate](https://staiola.studio/apps/expressiongate)

### Installing

Open the `.pkg` and follow the installer. It places `ExpressionGate.component`
in `/Library/Audio/Plug-Ins/Components` and the standalone app in
`/Applications`.

If your host was already running, quit and reopen it so it rescans plugins.
Logic Pro caches its plugin list, so it may need a full restart.

## FinderNotes

A scratchpad that appears when you press a key and disappears when you are
done. It lives in the menu bar, and it answers sums.

- **Download:** [FinderNotes 1.1](https://github.com/Staiola/tools/releases/download/findernotes-v1.1/FinderNotes-1.1.dmg)
- **Page:** [staiola.studio/apps/findernotes](https://staiola.studio/apps/findernotes)

## DK Dial

Danish radio as a physical panel in the menu bar. Six pads for the national
stations, and a dial that reaches into the archive.

- **Download:** [DK Dial 1.3.0](https://github.com/Staiola/tools/releases/download/dkdial-v1.3.0/DKDial-1.3.0.dmg)
- **Page:** [staiola.studio/apps/dkdial](https://staiola.studio/apps/dkdial)

### Installing a disk image

Open it, drag the app to Applications, and eject the image.

## Contact

jesper@staiola.studio
