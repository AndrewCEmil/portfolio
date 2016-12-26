+++
date = "2015-05-05T19:41:01+05:30"
title = "Music Visualizer"
draft = false
image = "img/portfolio/plane.png"
showonlyimage = true
weight = 1
+++

3d Music Visualizer.  C++/OpenFrameworks
<!--more-->

[Terrible Source](https://github.com/AndrewCEmil/visualizer-one)

I created a 3d music vizualizer.  Using OpenFrameworks, it takes the FFT of sound input and then places points in 3d space corrosponding the the frequence and magnitude of the sound.

Writing the music visualizer was a lot of fun.  I enjoyed playing with open frameworks and learning a (tiny) bit about FFTs and how audio works generally.  In creating it, I also played with passing the audio information into a pixel shader [using uniform buffer objects](https://www.opengl.org/wiki/Uniform_Buffer_Object).  The code for this application is some of the worst I have ever written, but I am not ashamed!

I attempted to write a "4d" visualizer, where you would specify a 4 dimensional objects by its planes and move the the fourth dimension using the mouse scroll wheel.  I was able to get something working for a sphere (lol), but was never able to figure out how to do this for more complicated shapes like a 4d "cube".  If you know how to do this, let me know as I am still extremely curious.

<img src="/img/portfolio/plane_large.png" alt="plane" width="100%">

<img src="/img/portfolio/visualizer_sphere.png" alt="sphere" width="100%">

<img src="/img/portfolio/visualizer_sphere2.png" alt="sphere2" width="100%">

<img src="/img/portfolio/numerical_sphere_outer.png" alt="numerical" width="100%">
