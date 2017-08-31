# Computational physics
## General
Contains some projects from a "computational physics"-course. The Repo will contain for example a simulation of a double pendulum, am molecular dynmaics simulation (for simple Lennard-Jones-potential), maybe some random-number- and some de-solving stuff and probably an metropolis-monte-carlo simulation of the two-dimensional Ising-model.

## Language
The main code is written in C++ while the evaluation (plotting and movies) is done with Python and Matplotlib.

## Resources

Check http://t1.physik.tu-dortmund.de/files/kierfeld/teaching/LectureNotes/kierfeld_CompPhys.pdf for the lecture notes. They contain some great recommendations for useful literature on the topic. 

## Build and run

If you hava *make* installed just type *make install* and it will do everything for you. You can fiddle around with the parameters and observe the outcome in the plots. If you don't have *make* you first have to compile the code using *g++*, then run it and then use the python script to plot the generated data (which will only work if you have Matplotlib installed). Some projects might require the C++ library *Eigen* (see: http://eigen.tuxfamily.org/index.php?title=Main_Page) to work.
