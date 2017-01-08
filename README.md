# Parallel_Edge_Detection
Used the pthread library to drastically accelerate convolution for a large png image.

This project divides the input image into 64 separate threads and convolves over each of the smaller reigons in parallel

To build the project:
$ make

To run make sure there is an in.png in the same folder as the executable, then run the command:
$ ./pthreadtest
or
$ ./pthreadtest parallel
the "parallel" tag will specify parallel operation.
