

Starting:
---------
    curl https://raw.githubusercontent.com/dan3850/local_manifest/main/extras.xml > .repo/local_manifests/extras.xml
    curl https://raw.githubusercontent.com/dan3850/local_manifest/refs/heads/main/gitlab.xml > .repo/local_manifests/lmi.xml
    curl https://raw.githubusercontent.com/dan3850/local_manifest/refs/heads/main/lmi.xml > .repo/local_manifests/gitlab.xml
    repo sync
