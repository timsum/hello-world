# hello-world
A hello world project to start things off.

I'm working on a project to develop a notation for harmony, in binary, similar to figured bass and jazz charts. The system can analyze a chord *and* its function, and thus extrapolate (improvise) based on any input -- especially gesture input and situation-tension input.

The kernel of the system is built, and at present working in C as a Puredata external. 

I'd like to see if it can become a kind of ASCII standard for musical harmony. 

Mathematically, it is complete: it can find root position easily for any input and should serve as a good basis for tonal analysis, music generation, and education.

It can be visualized as a parallelepiped with two internal dimensions.  Songs are given by paths in this space.

I am working to develop machine-learning interfaces so it can be intuitively and flexibly driven.

Current projects are centered around the machine learning course at Kadenze, and non-synthesized sounds are being run out to Native Instruments sounds in Kontakt.
