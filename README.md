# LZ4 checkpoints

Builds LZ4 mapping file for random access

With the mapping file you can resume the LZ4 decompressor reading state at the position
of the checkpoint.

In this way you can get LZ4 random access for a very large files.

