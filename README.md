**Digit-Classification-of-MNIST-Dataset-using-Tensorflow-Lite**
This is a handwritten character image (MNIST) classifier that can run on any android device. The app stores a set of images (0-9) that we can cycle through and classify in order. It uses a pre-trained model to perform inference on the device. This idea can be applied to any images, both by using the camera and by pulling from the Web. We're using preloaded images so we can run the app in a simulator (no need for the device since it doesn't require a camera).
<p><b> Installation Steps</b></p>
<p>Step 1</p>
<p>Download Android studio</p>
<p>https://developer.android.com/studio/index.html</p>
<p>Step 2</p>
<p><b>Download Android SDK</b></p>
<p>$ wget https://dl.google.com/android/android-sdk_r24.4.1-linux.tgz</p>
<p>$ tar xvzf android-sdk_r24.4.1-linux.tgz -C ~/tensorflow</p>
<p>Step 3</p>
<p><b>Download SDK Build Tools</b></p>
<p>$ cd ~/tensorflow/android-sdk-linux<br>
   $ tools/android update sdk --no-ui</p>  
<p>Step 4</p>
<p><b>Download Android NDK</b></p>
<p>$ wget https://dl.google.com/android/repository/android-ndk-r12b-linux-x86_64.zip<br>
   $ unzip android-ndk-r12b-linux-x86_64.zip -d ~/tensorflow
