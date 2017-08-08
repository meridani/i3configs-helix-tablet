My personal i3 + misc configs

modesetting: 
https://www.reddit.com/r/archlinux/comments/4cojj9/it_is_probably_time_to_ditch_xf86videointel/?compact=true
Need 20-intel.conf in xorg.conf.d

Move start_conky_maia to /usr/bin/ to remove bottom left conky

To backup the system mount something to /mnt/pendrive than run SyncToPendrive

Fix terminal fonts: Patched fonts
# clone
git clone https://github.com/powerline/fonts.git
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts

