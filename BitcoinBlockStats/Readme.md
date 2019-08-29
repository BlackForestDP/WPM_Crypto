#BlockStats

This files in this folder contain Arrays with json objects created by calling 'bitcoin-cli getblockstats $height'
for every Block currently in the chain.

Each file contains the stats for 50k consecutive Blocks starting with the Block declared in the filename.
The file 'blockStats50000.dat' for example contains an Array of the stats of the Blocks 50000 up to 99999.
