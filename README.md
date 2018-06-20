## Generating artistic string images 
This project aims to first implement the algorithm from [String Art: Towards Computational Fabrication of String Images](https://www.cg.tuwien.ac.at/research/publications/2018/Birsak2018-SA/Birsak2018-SA-preprint.pdf) which "takes an ordinary picture as input and converts it into a connected graph of strings that tries to reassemble the input image best possibly". 

Here is an example with the input image on the left, and the output image on the right:
![alt text](https://github.com/VanderpoelLiam/SingleThreadArt/blob/master/Images/Birsak2018-SA-image.png)

The paper provides [their code](https://github.com/Exception1984/StringArt), however it is written in Matlab and it is not immediately clear how to use the code to generate your own string images. I intend to convert the code into [Julia] (https://docs.julialang.org/en/stable/) as it is freely available and so that I understand the code well enough to modify it.

Once I have completed this first stage of the project, I want to modify the code to jointly optimize pin placement and string selection as this was a algorithmic limitation in the above paper. Hopefully this will allow the generation of artwork closer to the that of [Kumi Yamashita](http://www.kumiyamashita.com/constellation/):

|![alt text] (https://github.com/VanderpoelLiam/SingleThreadArt/blob/master/Images/1-CONSTELLATION-MANA-16.jpg) | ![alt text] (https://github.com/VanderpoelLiam/SingleThreadArt/blob/master/Images/2-CONSTELLATION-MANA-detail-26.jpg) |
