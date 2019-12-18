# :trophy:Assignment2-Help John with Parallel Programming!:trophy::fire:

John is a data engineer who works at Lola Inc. He wants to download some pictures from internet, and resize them, however, his process takes a lot of time as the number of images increases. He wants my help, to speed up his process.

This is our second assigment for Big Data Analytics. We were asked to do programming for John using Multiprocessing and Multithreading.

First we were asked to change the name of the README.md file to instructions.md and create a new README.file ,this file will explain the work .

## Instruction for running the program

- Get an Imgur api key. Follow this [a link](https://apidocs.imgur.com/?version=latest#intro)

- Install requirements.txt in your environment. (pip install -r requirements.txt)

- Launch Jupyter Notebook.

- I have written the program for multithreading it took 1.21 but i was downloading the image without using multitheading it was taking 5.11 s for 1000 image.For multithreading, I used threading module and defined a function worker and ran the code Thread pool executer.

- Again, for resizing, John's code to resize 1004 images took 6.67  seconds as it is CPU bound process and it is suggested to use multiprocessing to reduce the time, so I used multiprocessing which took only 600 mili seconds on the same machine.
