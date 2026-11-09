# ftm-media

Public image hosting for **Follow the Money** posts.

This repository is public **by necessity**: Post Planner's servers fetch each
post's image by URL when it publishes, so the files have to be reachable
without authentication. Only finished, already-approved post images live here.

The generator itself — day files, captions, drafts, sources — is in the private
`ftm-studio` repository and is never published.

One folder per publishing day. Files are written by `npm run publish-media`
in `ftm-studio`; nothing here is edited by hand.
