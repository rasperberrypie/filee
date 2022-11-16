//compile and execute in Linux

1) upload the file cpp to linux
2) g++ B11015010.cpp -o stateMin
3) ./stateMin input.kiss output.kiss output.dot
4) dot -T png output.dot > output.png
5) dot -T png OriginSTG.dot > OriginSTG.png