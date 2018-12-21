# YOLO-Annotation-Tool
## This is for creating the training set of images for YOLO

###### Commands on terminal:
```
cd YOLO-Annotation-Tool
./darknet detector train cfg/obj.data cfg/yolo-obj.cfg darknet19_448.conv.23
```
### Make sure to have the input image folder ( 003 and 004 for the code in this repo )

### Convert to .JPEG from any type of images. Use this command(Ubuntu)

```mogrify -format jpg *.JPEG```
or
```mogrify -format jpg *.jpeg```
or
```mogrify -format jpg *.png```

