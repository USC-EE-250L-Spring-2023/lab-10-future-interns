# Lab 10
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Kobe Kodachi
- Jacob Damasco

## Lab Question Answers

Question 1: It would be worthwhile to offload the processing tasks to your PC if they are resource-intensive, as in things like simulations, or if there's some private information that you don't want to be exposed to a cloud-based server. It would not be worthwhile to offload in instances where you need the processes to be done quicker because the speed of other servers may be faster than that of your own PC.

Question 2: We need to join the thread here because we just offloaded process1 and need to rejoin the multiple threads.

Question 3: Concurrent execution is when tasks are executed at the same time. However, this does not mean that they happen simutaneously. Parallel execution means that both tasks are executing simultaneously, usually through multiple cores or processors in a system. Used ChatGPT for this question.

Question 4: The best offloading mode according to our makespan.png is offloading process1. Offloading process1 onto the PC instead of our server takes longer than process2 because process2 processes only one data element, while process1 must process a list of data instead of just one item.

Question 5: The worst offloading mode according to our makespan.png is offloading None. This could most likely be because our laptops are not as efficient in terms of time when trying to handle both processes.

Question 6: A processing function like signal processing or data processing might be more likely to be used in a real-world application. You would want to offload signal processing data once you detect a waveform, most likely in the form of sound. For data processing, you would want to offload data processing when you get a dataset that exceeds a threshold that would be hard for your computer to handle. 