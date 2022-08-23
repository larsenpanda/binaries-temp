Here's how you can get the rpk binary without doing a full install..
---------
Download these 2 files (again, must be rhel based, if you run debian let me know and i can get it for debian):
wget https://raw.githubusercontent.com/larsenpanda/binaries-temp/main/rpk
wget https://github.com/larsenpanda/binaries-temp/raw/main/opt-redpanda-libexec-rpk.tar.gz

The "rpk" file in the first command is just a shell script that calls the rpk file that is in the tarball.
