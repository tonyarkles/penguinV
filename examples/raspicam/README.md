# How to compile    
- g++    
In this directory you need to type/paste this text in terminal:    
	```bash
	g++ -std=c++11 -Wall main.cpp ../../src/blob_detection.cpp ../../src/image_function_helper.cpp ../../src/image_function.cpp -o main -I/usr/local/include -L/opt/vc/lib -lraspicam -lmmal -lmmal_core -lmmal_util
	```
