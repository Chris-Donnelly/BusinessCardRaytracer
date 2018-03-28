# BusinessCardRaytracer
Business card Raytracer

*(based on Fabbiensanglard.net article, found [here](http://fabiensanglard.net/rayTracing_back_of_business_card/index.php))*

Simply made a few changes to tailor the program to my name, changed the floor colours and image dimensions, and re-compacted the code back to its original layout.

Compiled using C++ (Bash on Ubuntu for Windows 10 / Windows subsystem for Linux):

```bash
c++ -O3 -o card card.cpp
```

The software is then executed by directing the output to a PPM file using:

```bash
./card > card.ppm
```

*The output may take up to a minute or more based on image dimensions and sampling amounts*
