# Using lxSplit on Linux
* It is available in the linux mint software repo
* To split a big file into smaller pieces of 15 MB each, run the following command:

  lxsplit -s hugefile.bin 15M

  Output size can be given in (M)egabytes, (k)ilobytes and (b)ytes.
* To merge (join) the already split pieces into the original big file, run this command:

  lxsplit -j smallfiles.bin.001

  All resulting files (from either splitting or joining) will be placed in the current directory.
