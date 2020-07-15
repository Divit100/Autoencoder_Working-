# Autoencoder_Working-

In this project,using the make_blobs method of sklearn library,a dataset was created to which a third feature of random noise was added.


![Autoencoder _work](https://user-images.githubusercontent.com/58786895/87521379-f0310480-c6a1-11ea-97fa-822daffa8610.png)

Representing in 3-,The third added feature (Noise) does not affect the clustering in anyway  :

![Autoencoder_work2](https://user-images.githubusercontent.com/58786895/87521499-18206800-c6a2-11ea-8671-84e6e74ee019.png)


After feeding it to the Autoencoder and training it,the encoder part was extracted as predicted on,despite the third feature(random noise) ,the model predicted showing that the encoder had extracted only the useful features(removing noise) from the data as the third feature (noise which is an extra dimension) does not determine the clustered outputs.

![autoencoder 3](https://user-images.githubusercontent.com/58786895/87521896-941ab000-c6a2-11ea-972a-dba7958cf0dd.png)
