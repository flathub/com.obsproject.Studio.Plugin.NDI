# [obs-ndi](https://github.com/obs-ndi/obs-ndi) Flatpak

Network A/V in OBS Studio with NewTek's NDI technology in a Flatpak.

## Notes
Make sure that `--system-talk-name=org.freedesktop.Avahi` is set in OBS Studio permissions. Otherwise obs-ndi will not be able to see other devices or send to the network, since NDI on Linux rely on the Avahi daemon for network discovery (find other NDI device on the network).

