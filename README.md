# chess-vision
 Reads an image of a chessboard using YOLOv8 and outputs it in FEN, by Bernie Chen and [Harry Xiang](https://github.com/CQMian).
 
 Some concepts and code were adapted from Shai Nisan's blog post on Roboflow [here](https://blog.roboflow.com/chess-boards/) with permission (you can find our Linkedin messages [here](https://cdn.discordapp.com/attachments/667344478532796436/1194168327694725130/image.png)). This project was mainly a way to learn and apply AI image processing tools, specifically the Roboflow platform and YOLOv8 models.

 `pieces.pt`, our chess piece recognition model, isn't perfect (cut-off white kings are sometimes mistaken as white rooks), and we'll probably try retraining or use a heftier model than Nano, but this is a nice proof-of-concept of what we learned while developing this app.

 Stay tuned for this script with Xiangqi instead!