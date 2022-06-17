# Bitshift Variations Humanized

An attempt to make Robert Miles's Code Golf Song "Bitshift Variations in C Minor" into more readable code, provide raw audio output, a raw wav file, and a usable midi file for all to use and remix.

## Original Video explaining the original program
https://youtu.be/MqZgoNRERY8

# Contents of the Project
- [`bitshift-variations-extracted`](https://github.com/Bitshift-Variations-Humanized/bitshift-variations-extracted)
  - A Rust program to determine the point at which the original code loops, and extract it into both a raw output file and a .wav file
- [`bitshift-variations-rusted`](https://github.com/Bitshift-Variations-Humanized/bitshift-variations-extracted)
  - A Rust program that both recreates the original song byte-by-byte (tested with the results of the previous repository), and also provides an alternative implementation of the instrument function that outputs note information instead of a sample. The `extract-notes` binary inside also provides extraction of the complete song into a midi file (Currently Flawed). Also provides a 'humanized' version of the original C code in the `c` subfolder.
