# tools

Downloads for the apps and tools I build. The builds live under
[Releases](https://github.com/Staiola/tools/releases), not in this repository.

Project pages: [jesperh.cv/apps](https://jesperh.cv/apps/)

## ExpressionGate

A macOS Audio Unit by Dwan Audio. It follows the input envelope and uses three
draggable thresholds, LOW, MID and HIGH, to trigger different effect chains.
Play softly for one sound, harder for another.

- **Download:** [ExpressionGate 1.0.0](https://github.com/Staiola/tools/releases/latest)
- **Formats:** Audio Unit (aufx) and Standalone app
- **Requires:** macOS 11 or newer
- **Page:** [jesperh.cv/apps/expressiongate.html](https://jesperh.cv/apps/expressiongate.html)

The installer is signed with a Developer ID certificate and notarised by Apple,
so macOS will open it without a Gatekeeper warning.

### Installing

Open the `.pkg` and follow the installer. It places `ExpressionGate.component`
in `/Library/Audio/Plug-Ins/Components` and the standalone app in
`/Applications`.

If your host was already running, quit and reopen it so it rescans plugins.
Logic Pro caches its plugin list, so it may need a full restart.

## Contact

jesper@staiola.studio
