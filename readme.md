# Fanuc-point-save

## Overview

Teaching points can be memorized and recalled.

## point_save

In the TP program, with the additive instruction Sakijikko Point Logic 0.00s  
Call point_save.

### Argument 1

Specify in order from the teaching point 1,2,3,4... and specify in integer system.

### Argument 2

None or 0 for individual axis moves, 1 for linear moves.  
1 for a linear move.

## point_load

The location information registered with point_save is recalled and the  
The return operation is performed.

## Configuration Change

Some operations can be changed by changing the CONST value in the .kl file.

## Update History

## License

Released under the Apache 2.0 License.
