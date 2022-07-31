# rppico_tcpserver
* A minimalistic TCP server which accepts multiple connections and serves (but can be used for anything) a simple website.
* Pure C, no micropython
* It builds a simple http header. 
* A Python script converts html files to char* arrays, so it is simple to edit and store websites on the pico
  * Convert them with conv.py file1.html file2.html
  * binary data is stored in websites.h
* currently no handling of the received data, only printed to the console
![Screenshot](screenshot.jpg)
