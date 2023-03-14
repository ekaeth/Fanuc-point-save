# Fanuc-point-save

## Overview

Teaching points can be memorized and recalled.

## point_save

TP プログラムにて、付加命令ｻｷｼﾞｯｺｳ ﾎﾟｲﾝﾄﾛｼﾞｯｸ 0.00s で、  
point_save を呼び出します。

### Argument 1

Specify in order from the teaching point 1,2,3,4... and specify in integer system.

### Argument 2

各軸動作の場合には無しまたは 0、  
直線動作の場合には 1 を指定して下さい。

## point_load

point_save で登録した位置情報を呼び出し、  
戻り動作を行います。

## Configuration Change

Some operations can be changed by changing the CONST value in the .kl file.

## Update History

## License

Released under the Apache 2.0 License.
