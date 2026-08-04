# Sector 5 RP - public assets

Public image assets for the Sector 5 RP FiveM server listing.

| File | Size | Used for |
|---|---|---|
| `s5-banner-wide.png` | 1920x480 | `sets banner_detail` **and** `sets banner_connecting` - THE ONE IN USE |
| `s5-banner-detail.png` | 1920x1080 | not used - see warning below |
| `s5-banner-connecting.png` | 1920x1080 | not used - see warning below |

## Do not switch to the 1920x1080 versions

FiveM renders `banner_detail` as a **wide short strip**, not 16:9. A 1920x1080 banner gets
sliced through its middle - logo cut off, text half-visible. This was confirmed from a
screenshot of the live listing on 2026-07-25, which is why the 1920x480 version exists.
The 16:9 files are kept only as source art.

These are referenced directly from `server.cfg` via raw.githubusercontent.com, so the URLs
must stay stable. **Do not rename, move, or delete these files** - it breaks the server listing.
Replace in place to update the artwork.

Server: cfx.re/join/jjpbdm
