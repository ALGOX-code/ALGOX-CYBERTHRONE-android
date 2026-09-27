# ALGOX-CYBERTHRONE Android v2.0.0

This build packages the offline ALGOX web workspace and curated historical security references in a local SQLite database. The assistant is local rules-based guidance, not a generative language model. CISA KEV reference data may refresh over HTTPS when online and is cached locally for offline browsing. Database records are reference data and cannot change app code or model behavior.

## Installation

The package is signed with a newly generated signing key because the previous APK signing key was not available in the source repository. Android treats it as a different signer from the old APK; uninstall the prior ALGOX APK before installing this build. Back up the signing key stored locally at `work/android-signing/algox-release.p12` together with its private password record at `work/android-signing/signing.local.json`. Keep both private and do not commit them to GitHub. Future releases need this exact key to upgrade the app in place.

Package: `com.algox.cyberthrone`
Version: `2.0.0` (version code 2)
Minimum Android: 8.0 (API 26)
Target Android: API 35
