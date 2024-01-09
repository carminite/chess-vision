# chess-vision
 Reads an image of a chessboard using YOLOv8 and outputs it in FEN, by Bernie Chen and Harry Xiang.
 
 Some concepts and code were adapted from Shai Nisan's blog post on Roboflow [here](https://blog.roboflow.com/chess-boards/). This project was mainly a way to learn and apply AI image processing tools, specifically the Roboflow platform and YOLOv8 models.

 `pieces.pt`, our chess piece recognition model, isn't perfect (cut-off white kings are sometimes mistaken as white rooks), and we'll probably try retraining or use a heftier model than Nano, but this is a nice proof-of-concept of what we learned while developing this app.