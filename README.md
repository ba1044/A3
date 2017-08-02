Part 1

This is part is in preparation for the next assignment. There is no specific research question to be addressed, the goal is to build and verify functionality of a tool that will be used in a subsequent assignment. Write a simple program that measures the throughput of links between rb1 and rb2. It is up to you to decide the details of the implementation. The only requirements are:

The data transmission must use TCP in the transport layer (raw TCP or HTTP would satisfy this requirement)
The communication must have form of a request from client to what the server responds with a bulk data transfer for which you will measure throughput. HTTP GET is an example of such an exchange but you can come up with your own.
Your must be able to make the observation on both the client and the server side, i.e., how long it took for the client to get the data and how long it took the server to send it. For a large data transfer (1 MB is recommended), the two measurements will be very similar but you are still expected to measure and report both.
The deliverable for this part of the assignment is your code committed to the repository. Make sure that there are instructions on how to set it up and test it. It will be tested by cloning your repository on rb1/rb2, make sure that it runs there without modification. Besides added latency, there are no rate limits on the links so you should be observing rates close to the capacity of the gigabit interfaces.

Part 2

One of the goals of this class is to teach you how to present the results of your work. In the past two assignments you had the opportunities to give it a try. In this assignment, the burden of dealing with the research is taken away and you are given an opportunity to focus more on the formal presentation of the work that you did for the first two assignments. The task is to come up with significantly improved versions of the papers that you submitted for the first two assignments. You may have to redo some of the experimental work but the bulk of the effort should go into improving the papers. The overall goal is to come up with better but not necessarily longer papers.

Grading of this assignment is going to be significantly stricter than in the case of the previous two. The focus is going to be both on perfecting the experiment that you are performing as well as on cleaning up and improving the report. Specifically, you will be graded on the following items:

Does the paper clearly state the problem it is trying to solve?
Is the experiment setup fully and clearly described?
Do you give justification for why your findings are statistically valid?
Is all information included in the paper relevant to the problem you are solving?
Are your findings clearly stated?
Does you paper have a conclusion?
Is all of your code committed to the repository? Does the repository have the expected structure?
On the formal side of your paper presentation:

Are you following the IEEE Transaction format?
Do all included images and graphs use vector graphics (there must not be any bit-mapped images)
Are the formulas properly formatted?
Do all figures and tables have captions?
Are you citing all your sources and are your citations in proper format? This includes images.
