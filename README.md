# tools

Downloads for the apps and tools I build. The builds live under
[Releases](https://github.com/Staiola/tools/releases), not in this repository.

Project pages: [jesperh.cv/apps](https://jesperh.cv/apps/)

## ExpressionGate

A macOS audio plugin you control by how loud you play. Quiet playing gives you
one set of effects, playing harder gives you another, and digging in gives you
a third. You set the three volume levels yourself and pick what each one does,
so the sound changes without you touching a pedal.

- **Download:** [ExpressionGate 1.0.1](https://github.com/Staiola/tools/releases/latest)
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
