To initialize your local repository use
---------------------------------------

    git clone https://github.com/Fake-suns/local_manifests.git -b evox .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j14 --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
