# Python script to convert LabelMe JSON files to Darknet's txt file format

I saw a lot of code on the web which claimed to do this but for some reason none worked. So here's a small and simple script for the task.

### Does this work?

Well it worke-

![alt text](https://memegenerator.net/img/instances/67381149.jpg)

Tried it with the [Yolo_Label] tool. Here's an example - 

![alt text](https://github.com/pulkitvyas08/LabelMeToDarknet/blob/master/res/works.jpg?raw=true)

So it probably does

A bit more work is needed to correctly setup the directory structure of the dataset. Refer to the [training custom data] section in YOLOv5 repository for information about the Darknet dataset structure

Follow a detailed version of doing this from this [tutorial]







[tutorial]: https://www.youtube.com/watch?v=NsxDrEJTgRw
[training custom data]: https://github.com/ultralytics/yolov5/wiki/Train-Custom-Data
[Yolo_Label]: https://github.com/developer0hye/Yolo_Label
