## v2.2.0
- Added graceful sound unmute on logout/UI reload: PLAYER_LOGOUT now unconditionally calls UnmuteSoundFile so the default WoW level-up sound is never left muted after the addon unloads
- PLAYER_LOGOUT event registered at file load time (outside Init) so it fires even if initialization failed
- Synced ADDON_VERSION constant in core.lua with TOC version (was stuck at 2.1.21)

## v2.1.26
- Updated Interface versions to support latest WoW patches
- Added new interface version targets

- Re-added Vanilla toc
