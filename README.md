


		 ---===[  Qubes Security Pack ]===---


This git repository is a central place for all security-related info
about the Qubes Project. It includes the following sections:

1. Qubes Security Bulletins (QSBs/)
2. Various Qubes-related signing keys (keys/)
3. Warrant and other canaries/annoucements (canaries/)

The files contained in this repository can be verified in two ways:
1. By verifying the git commits tags (git tag -v)
2. Additionally, we provide GPG detached signatures for the majority
of files included here (e.g. each individual QSBs, canaries, other
announcements).

All the keys used by the Qubes Project, including the keys used to
sign files and commits in this repository, are signed by the Qubes Master
Key. Even though this key is also included in this repo, you should
make sure to obtain the master key fingerprint using some other
channel, as you can be sure that if you were getting a falsified Qubes
Security Pack it would contain a falsified master key as well.

More on signature verification and keys can be found in the following
Qubes wiki page:
https://wiki.qubes-os.org/wiki/VerifyingSignatures

