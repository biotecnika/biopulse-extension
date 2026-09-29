# BioPulse for Canva — Chrome extension releases

Force-installed for the "BioPulse Extension Users" group via Google Admin console
(Chrome browser → Apps & extensions → Groups → add by URL).

- Extension ID: `nhngponlfgiahnjnemncpobdojkhebjk`
- Update URL: `https://raw.githubusercontent.com/biotecnika/biopulse-extension/main/update.xml`

To ship an update: bump the version in manifest.json, re-pack with the same private key
(kept offline, never in this repo), upload the new .crx here and update the version and
codebase in update.xml. Chrome picks it up within a few hours.
