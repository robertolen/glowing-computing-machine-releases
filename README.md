# glowing-computing-machine releases

Public release binaries for internal defi SOLUTIONS desktop tools built from the private
`glowing-computing-machine` repo. Source code is not published here — only signed/built
installers and electron-updater metadata, one release channel per app:

| App | Release channel |
|---|---|
| Attestor | `attestor` |

Each app's releases are tagged `v<version>` and scoped by an electron-builder `channel`
so multiple apps can safely share this one repo without their auto-updaters colliding.
