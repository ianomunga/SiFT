# SiFT
SiFT stands for 'Scientific Imaging Functional Transformer'
When complete, SiFT will be a full Deep Learning toolkit for analysing HEP event data in efficiently parallelised tensor operations that can then be used for prediction, simulation or visualization pipelines.  

I started this project in late 2022 to build newer, more efficient algorithms for the analysising the data from the High Energy Physics events that would happen at CERN's next iteration of the LHC, the High-Luminosity LHC. Since this new phase would be producing even more data (than the [30 Petabytes per year](https://home.cern/resources/faqs/facts-and-figures-about-lhc#:~:text=The%20CERN%20Data%20Centre%20stores,are%20permanently%20archived%2C%20on%20tape.) the last iteration used to produce), I'm hopeful that this work will be useful in aiding faster, and more efficient Particle Physics research. 


# Releasing The SET (Stress-Energy Tensor) Screen Algorithm 
I'm releasing the algorithm implementation steps for what I've worked on so far offline since I started, called setScreen. 

setScreen will use the Stress Energy Tensors of known hadrons and fields to isolate unknown ones based on their unique energy signatures. Screening for new particles and fields using energy signatures rather than through 3D particle track reconstruction from silicon screen hits is made necessary by the fact that hadrons inside the QGP (Quark Gluon Plasma) that ALICE gets from heavy-ion collisions aren't particulate. They're in a dense medium, almost akin to a soup. setScreen will help continue novel particle search from within QGPs efficiently. 

I'll release the algorthm's code implementation and the CERN Opendata/Simulation data used to build setScreen in the coming weeks after a few final reviews are done. setScreen is built in JAX.
If you have any questions about setScreen, email me: ianomunga@gmail.com

Thanks!
