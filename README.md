# FIREQ
Finite Impulse Response / Linear Phase EQ
This is based on the Haar wavelet, an orthogonal filter bank.  
The frequencies are fixed for a certian decomposition level (number of bands) and there is some overlap.

The purpose of using linear phase filters is to not cause phase distortion. 
When a solo channel in a mix is listened to with an IIR (nonlinear phase) EQ, phase differences will not be heard. 
Mixing will typically be easier with an IIR EQ because of the finer control over resonance and frequency.

One possible application of this EQ is in cabinet simulation. Many cabinets (and speakers) have transfer functions with gain curves that look very similar to the type of curves that are generated with a linear phase EQ. 

Just demo pictures...for now! Come back soon or message me if you would like to collaborate. 
The first picture demonstrates the orthogonality. The sum of the bands is represented in black for phase and white for gain (overlappting in the first picture). The gain is 0 dB when all bands have a gain of 1. Changing the gains for each band will change the curves, shown in the second picture. 
![Alt text](fireq.png?raw=true "Title")
![Alt text](fireq2.png?raw=true "Title")
