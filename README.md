# Discrete Cosine Transform(DCT)
I have implemented DCT with OBC using verilog and matlab
1) In matlab converted RGB color image to gray color image
2) Store the image data in BRAMs modules in Xillinx
3) Segment image into 8x8 blocks since our DCT coefficient matrix is 8x8
4) Forward DCT Transform here matrix multiplications are performed using OBC.
5) Quantization
6) And again reconstructed the DCTQ image.

The DCT using OBC presentation gives you the idea on how I implement this new DCT computations on FPGA.
The DCT report have the code,results images.
I have upload my codes of OBC and DCT.
