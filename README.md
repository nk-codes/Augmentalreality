# Augmental-Reality(19CSU199,19CSU202,19CSU207)
#GROUP :- 19CSU199,19CSU202,19CSU207
1. What is AR ?

    Augmented reality (AR) is an enhanced version of the real physical world that is achieved through the use of digital visual elements, sound, or other sensory stimuli     delivered via technology. 

2. What is difference between VR and AR?

   AR uses a real-world setting while VR is completely virtual. AR users can control their presence in the real world; VR users are controlled by the system. VR requires     a headset device, but AR can be accessed with a smartphone. AR enhances both the virtual and real world while VR only enhances a fictional reality.


Description :- We are going to implement API from scratch  using OpenCv and  python . At last we will be able to augment 2d Image(dl.jpg) on some another image(mask.jpg).

Activity Phase :- 
1) object detection and describing the features
2) object tracking 
3) Feature matching

Algo used :-ORB feature detector
{orientated fast (it detects features) rotated Brief(it describes features)}

Why ORB ? Ans shift and surf are not for commercial use as patented.
Opencv labs uses orb .so we r using this.



In code :-
Resize is used ...bcz to implement fast.
Orb is used in code.
After initialisation there is key points and descriptors
Detect ,compute(means describing) and here both detect-compute is there.
From gray image , it will detect

3. This project is on AR which is for :-
   1) feature detection :- In this , image detection is done in as "dl.png"
   2) feature matching :- now , we will find the match the " dl.png " with " dl_from_webcam.jpg " for feature matching .
   3) IMAGE augemtation :- and finally it will detect that image ("dl.png") and will match and mask that image with " mask.jpeg " .

Application of the Project :- 
Can be used in alert system for catching black listed people.

![image](https://user-images.githubusercontent.com/89216667/161902641-386d7599-7b60-4228-91a0-e2cf3a0116c8.png)
![image](https://user-images.githubusercontent.com/89216667/161902662-33cc97ff-9d6c-499d-ad72-65bc81b6b812.png)


run:-
just run according to the steps mentioned above.
