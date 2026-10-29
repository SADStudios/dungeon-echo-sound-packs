# Dungeon Echo sound packs

Public release assets for Dungeon Echo by S.A.D. Studios. This repository contains no app source, APK, signing material or credentials. No GitHub Actions workflows are required.

## Procedural delivery fixture

Release tag: `packs-v1` (pre-release). Three existing procedural test blends and artwork total 606,017 bytes. These are not Freesound recordings or the proposed Suno album.

The release includes schema-1 catalogue version 2, CREDITS.txt and SHA256SUMS.txt. Audio IDs, types and hashes remain unchanged from v0.1.14. Only paths change to flat, versioned asset names. No blanket open-source or Creative Commons licence is granted for studio assets by this repository; consult the per-track credits.

## App compatibility

Dungeon Echo v0.1.14 rejects HTTP redirects for both catalogue and blob requests. GitHub Releases delivery requires a focused app update allowing bounded, validated HTTPS redirects to GitHub asset hosts, while retaining Range headers, cancellation/Wi-Fi checks, exact size and SHA-256 verification. It is not a drop-in base URL for v0.1.14. No APK has been rebuilt for this hosting setup.

Download source must remain configurable. Downloads require explicit user action; installed verified blobs are reusable across scenes and offline. Missing audio must never be silently fetched or substituted. Backups store arrangements/preferences/references, not audio.

## Publishing rules

Upload audio/artwork first, then the catalogue. Preserve published assets and stable IDs; changed audio needs a new sound ID and versioned filename. Keep prior releases for existing scene references. Do not overwrite audio behind an existing hash/ID. Reverify source licences and audit actual audio before adding external recordings. No Suno album without actual files, metadata, artwork and redistribution permission.

## Verification scope

Local payload size and SHA-256 checks passed before upload. Live delivery verification is reported separately after publishing. Hosting tests do not establish Android or phone playback compatibility. v0.1.11 remains the approved app rollback; previous Library artifacts are retained.
