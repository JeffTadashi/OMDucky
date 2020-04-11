OMDucky
=============
Hello! This is a collection of scripts for O.MG Cable and Rubber Ducky. There should be a version for both systems, see `omg.txt` files vs `ducky.txt` files.

All of the details of how the script works, I've commented in the script files directly. Notably, see any `~~` double-tilde line comments for strings that you need to modify per your own needs.

Some of these scripts are based on ideas of others, I will have links/shoutouts in the comments of those scripts as well.

The "wip" directory for scripts that are not fully testing, and I'm still working on.


Notable Differences:
===========
- Since April 1st firmware, the majority of issues were fixed, and the syntax between O.MG and Rubber Ducky is almost exactly the same.
- Some syntax differences:
    - O.MG can set VID, PID, MAN and PRO fields, Rubber Ducky cannot
    - Rubber Ducky I recommend a delay before first command is sent (`DELAY 2222`)
    - Otherwise, the two script versions should be exactly the same
    - This generally means: Rubber Ducky scripts will work as-is in O.MG, although they might not be fully optimized


Useful Links
=========
O.MG Firemware - https://github.com/O-MG/O.MG_Cable-Firmware

