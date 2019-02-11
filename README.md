# Post-Stack-Converter
Need to upgrade unity3d Post Processing Profiles from V1 to V2? These scripts might help.

Does not port all functions - some are not supported in V2 - see comments for details, needs more testing.

## Colour Grading
Colour grading now (mostly) works fairly accurately, however this asset now requires the SC Post Effects asset in order to work correctly (this is because we've got a dependency on a final LUT pass - which the existing PPv2 stack does not support on its own) - it should be relatively easy to re-implement a final LUT pass yourself and update this asset. 

The hard bit is in the LUT texture generation. This is however, left as an exercise to the reader.
