# 3D.Cloud
- Here are two methods to convert bin file to pcd file.
## bin to pcd in Python
- This is for converting bin files that scanned by LIDAR of autonomous vihicles into pcd files which is using for further processing like 3d.cloud annotation.
## Requirements
- open3d
- struct
## Example data
- source data: ./bin/test.bin
- result: ./pcd/test.pcd


## pcd format
```
# .PCD v0.7 - Point Cloud Data file format
VERSION 0.7
FIELDS x y z intensity
SIZE 4 4 4 4
TYPE F F F F
COUNT 1 1 1 1
WIDTH 18929
HEIGHT 1
VIEWPOINT 0 0 0 1 0 0 0
POINTS 18929
DATA ascii
11.546668 9.0313597 0.30003649 57
11.507449 9.0317659 0.30279371 56
11.460706 9.0278406 0.306564 53
11.416166 9.0320606 0.30922675 47
11.368566 9.023489 0.3135519 47
11.350843 9.0567999 0.31095392 51
11.299603 9.0457211 0.31578568 17
11.254622 9.0397186 0.3195802 8
11.202293 9.0291519 0.32439047 8
11.16323 9.0332756 0.32656816 8
```
