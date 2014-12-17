transcrypt-test
===============

To see the decrypted version of `code/credentials.json`, you need to run ./scripts/transcrypt.

When prompted, select the default cipher (aes-256-cbc).  Then enter the password.

After this setup, your local copy of the repo will transparently decrypt any encrypted files in the repo.  This has to be done for any clone of the repo you create.

To list encrypted files in the repo, run `./scripts/transcrypt -l`.
