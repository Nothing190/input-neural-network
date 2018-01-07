# input-neural-network -> your own photos
## Prepare your own images to feed them in a neural network. All images get the same size

This code will help you to create .jpg photos which all have the same size to feed them in a neural network. Therefore you can use your own photos and converte them in the size you need for your network.

1. you need a special folder structure to process the images the same way as mayself (of course you can change my code to use a your own folder structure). My folder structure is the following.
 * _Projectfolder_ (in the code you will see that this is the root folder for my operations)
   * _originalphotos_ (here you can save your original .jpg photos)
   * _originalphotosnetwork_ (here the code will save the .jpg photos with the new size for the neural network)
2. The Code will find the biggest width/ height auf all photos in originalphotos
3. Every photo will be squared (e.g. 500x500 pixel if the biggest width/ height was 500 pixel of your originalphotos)
4. Every photo which is smaller than the biggest width/ height will keep the old size but gets a black border to reach consistent size for every photo
5. Every photo will get the size which you want as input for your network
