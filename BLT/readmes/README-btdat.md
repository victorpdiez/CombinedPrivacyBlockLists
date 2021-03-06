The [update-btdat.sh script](https://github.com/bongochong/CombinedPrivacyBlockLists/blob/master/BLT/update-btdat.sh) is meant to automate the process of creating and updating an IP block list for your BitTorrent client (if you use one that prefers DAT lists), on GNU/Linux and other Unix-like Operating Systems (like OS X).

**Checklist for use**:
1. Make sure that you have [`p7zip` + `p7zip-plugins (or p7zip-full)`](http://p7zip.sourceforge.net/), [`perl`](https://www.perl.com/about/), and [`wget`](https://www.gnu.org/software/wget/) installed on your system.
2. Open a terminal in or `cd` into your `BLT` directory.
3. Launch the script (`sh update-btdat.sh` should do).
4. Watch the output of the script.
5. Move the resulting block list (`combined-final-win.dat`) to a directory of your choosing (or leave it in place), and configure your torrent client to utilize it.
6. Run the script as often as you like to keep your BitTorrent IP block list up to date.
7. Enjoy the magic of having a comprehensive and up-to-date IP block list that provides you with considerable protection against malicious activity on BitTorrent sites.


**Notes**:
- If you don't know what you are doing and you deviate from the instructions, then you are being dumb.

- The Windows version can be found here: https://github.com/bongochong/CWP-Utilities
