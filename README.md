
# GPG Public Key

You can use my public key to verify things I sign

## Importing my identity

    curl https://raw.github.com/GEverding/identity/master/geverding.asc | gpg --import

## Verifying signatures

    curl https://me.com/thingisigned.txt | gpg --verify

    gpg --verify < fileisigned.txt


