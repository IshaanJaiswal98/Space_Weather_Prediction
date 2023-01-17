# Space_Weather_Prediction
A software built using MATLAB that uses DST INDEX dataset, trains on NARX Neural network, using Levenberg Marquardt, Baysian Regularization and Scaled conjugate gradient algorithms, to predict the future DST values predicting the occurrence of solar flares or other solar storms.

Solar storms are harmful for various communication systems like radio communications, satellite communications, radars and navigation systems. When the frequencies are below 30MHz, the ionosphere generally acts as a good reflector, allowing communications to distance effectively. Solar extreme ultraviolet and soft xray emissions from solar flares and other solar activities change the density of electrons and causes variations in the functioning of ionosphere responsible for effective communication. An abrupt increase of x-ray radiation from a solar flare causes an increase in ionization of the lower region of the ionosphere producing disturbances of radio signals, sudden phase changes, unnoticed enhancement of signals and fading of short waves. Polar cap absorption (PCA), aurora absorption etc are the effects that are associated with coronal mass ejections (CMEs), can also disrupt radio communications. The prediction will help us take active measures and save the various satellites from damage.

The nonlinear autoregressive network with exogenous inputs (NARX) is a recurrent dynamic network, with feedback connections enclosing several layers of the network. The NARX model is based on the linear ARX model, which is commonly used in time-series modeling.
The defining equation for the NARX model is
y(t)=f(y(t−1), y(t−2),…,y(t−ny),u(t−1),u(t−2),…,u(t−nu))
Scrutinizing Space Weather Prediction System
CSE Department SRMCEM, Lucknow Page 5
where the next value of the dependent output signal y(t) is regressed on previous values of the output signal and previous values of an independent (exogenous) input signal. You can implement the NARX model by using a feedforward neural network to approximate the function f. 

DST (Diturbance Storm Time Index) -The equatorial ring currents or electrojet causes variation in magnetic field. This variation is measured by this index. The four near-equatorial observatories record these variations and help in calculation of dst.
