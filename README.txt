Allow me to state that in no way do I claim to be the sole inventor of this code.

I have sourced the code from a Github repository I don't quite remember now.

There are a few changes however that were required for accurate yawn detection. 

1) The distance between the subject's lips so as the movement to be called a yawn had to be corrected.

2) Furthermore, I introduced a time factor to co-relate the distance between lips the time for which they were x distance apart.

3) Additionally, anyone trying to run the following code will have to install the dlib library. Unfortunatel, Github isn't allowing any file above 50.0 mb. dlib library happens to be ust bove 94 Mb if I am not wrong. Hence it is required that you install the library and save it under in the same folder named " shape_predictor_68_face_landmarks.dat "

All these provided fair bit of accuracy to detect a yawn. 
