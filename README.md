# Virtual Reality Museum of Renaissance Musical Instruments
This award-winning project focuses on making an immersive Virtual Reality (VR) experience for an exhibit of a Museum of Musical Instruments from the Renaissance era. It includes the capability of being able to interact with 30 various instruments of various ages throughout history, their evolution, and their classification and role in today’s musical world. It also includes small audio clips of the instruments attached to their 3D Models so that the users can tap/click on them and listen to how the instrument sounded like. Alongside this, the project also features some interactive videos which can be accessed in browser mode to understand better about some of the most groundbreaking instruments of the Renaissance period. 

## For a quick insight of this project, here is the link to a short video of the museum: https://youtu.be/RLCYF9-hMKg

**Tools Used**

1. AWS Sumerian
2. Adobe Photoshop
3. Rhinoceros 3D

**Award**

This project won the Best Project (Audience Choice) Award under the Virtual Reality Projects category at the Festival of Animation - Fall 2020 at The George Washington University, Washington D.C., USA.

**Sister Project** 

This project has a sister project which is an Interactive Multimedia Interface of the same museum, developed using Adobe XD. Learn more: https://github.com/ivedants/Interactive-Multimedia-Interface-for-a-Museum-Exhibit-of-Renaissance-Musical-Instruments

## Table of Contents

- [Getting Started (Find Project Link and Preview Video Link here)](#getting-started)
- [VR Application Design](#VR-application-design)
- [Integration](#integration)
- [User Experience](#user-experience)
- [User Guidelines](#user-guidelines)
- [Suggestions for Further Improvements](#suggestions-for-further-improvements)
- [Efforts taken for Additional Complexity and Creativity](#efforts-taken-for-additional-complexity-and-creativity)
- [Appendix: Lessons Learned](#appendix-lessons-learned)
- [References](#references)

## Getting Started [FIND PROJECT LINK AND PREVIEW VIDEO LINK HERE]

There are two ways to access this project. One is to simply access it through a web browser (Google Chrome, recommended for best performance) or through your VR Headset browser. The project link is:  https://c54237d0af0b40a2ac35b70846537582.us-east-2.sumerian.aws/?

**NOTE:** Feel free to reach out to ivedantshrivastava@gmail.com for any doubts or suggestions regarding this project.

## VR Application Design

**Navigation via teleportation:** The app features three different areas - the welcome room which acts as the first room the visitors visit upon their entry, the gallery which features 9 instruments on either of its two sides, and the central room which features 6 instruments each on both its sides. Navigation via teleportation would be a handy option for users who are not willing to walk every step physically to the other rooms.

**Guiding audio/sound effects:** The visitors can interact with all the instruments and listen to their sounds. They can also click on the videos in Browser Mode and enjoy learning more from them about music during the Renaissance Period.

**Text instructions:** The museum is acquainted with various floating text instructions at multiple places to instruct the visitors about how to interact with all the featured instruments. The museum also features text besides all the instruments so that the users can read them and learn more about each and every instrument in the exhibit.

**Instructional signs/wayfinders:** The app has floating text at various places pointing to different rooms and instruments just like a real world museum.
Activities involving Six Degrees of Freedom (6DOF): Users would be able to walk around in the museum and look at the objects from all angles. This would make them feel as if they are actually in a real world museum.

## Integration

**Data Collection:** One of the first and biggest challenges in this project was to gather enough data from trustworthy sources. All the information about the instruments featured in this project has been collected from various sources such as websites of various museums around the world, various music schools, sources like wikipedia, and more.

## User Guidelines

In order to access the application in VR, all that the user needs to do is visit the URL link through their VR HMD Browser and enter VR Mode. In order to access all the interactive videos alongside the instruments, the user has to visit the URL without the HMD through a regular web browser on a computer. This is a limitation of Amazon Sumerian where it renders HTML 3D videos into 2D images when accessed in VR Mode. More information about this limitation can be found on Amazon Sumerian’s official website at https://docs.sumerian.amazonaws.com/articles/html3d/

**Processing audio files:** The audio files collected had to be edited and cleaned for better experience in the VR. The editing and cleaning was done using Apple Garageband.

**Making 3D Models of the instruments:** All the 3D Models of all the musical instruments in this project have been **custom designed** by me using **Adobe Photoshop and Rhinoceros 3D**. The objects have been used in .OBJ file format while their textures are in JPEG file format.

![alt text](https://github.com/ivedants/Virtual-Reality-Museum-of-Renaissance-Musical-Instruments/blob/main/Image%201.png)

**Designing the Museum Layout:** The museum layout features three different areas - the welcome room which acts as the first room the visitors visit upon their entry, the gallery which features 9 instruments on either of its two sides, and the central room which features 6 instruments each on both its sides. This was made and turned into a VR experience using **Amazon Sumerian**.

![alt text](https://github.com/ivedants/Virtual-Reality-Museum-of-Renaissance-Musical-Instruments/blob/main/Image%202.png)

![alt text](https://github.com/ivedants/Virtual-Reality-Museum-of-Renaissance-Musical-Instruments/blob/main/Image%203.png)

![alt text](https://github.com/ivedants/Virtual-Reality-Museum-of-Renaissance-Musical-Instruments/blob/main/Image%204.png)

![alt text](https://github.com/ivedants/Virtual-Reality-Museum-of-Renaissance-Musical-Instruments/blob/main/Image%205.png)

## User Experience

For delivering the best experience, the first and foremost thing has been to design a very user-friendly layout of the museum with appropriate text instructions and way finders at appropriate places so that the users have a real-world like museum experience. The simplicity and elegance of the layout combined with the amazing 3D models of the musical instruments are all significantly conducive in delivering this experience. The users can also interact with various videos throughout the museum in Browser Mode in order to learn more about the music during the Renaissance era.

## Suggestions for Further Improvements

The first and foremost suggestion is out of a current limitation of Amazon Sumerian which is that the HTML 3D videos should be accessible in VR Mode too along with the Browser Mode. This will help every developer on Sumerian get more done in the VR experience and make it even better. The second suggestion would be the addition of a Sumerian Host using Amazon Lex for backing it up with a chatbot. This would make the Sumerian Host pretty much like a museum curator to answer any questions that the visitor may have.

## Efforts taken for Additional Complexity and Creativity

In order to deliver beyond the required project deliverables, I custom designed all the musical instruments from scratch so that they look like they actually did in real life to the visitors and give them a better insight of how it might have been for the musicians of the Renaissance period to experience them and make music. Besides this, I processed and cleaned all the audio files of these instruments so that their individual sounds can be experienced by the user. This required me to download various orchestral pieces and cut out all the other instruments from the files apart from the subject instruments. The layout of the whole museum has been created in such a user-friendly manner that the user can easily remember the way to navigate around in the VR space and have the feel of visiting a museum in real life. Besides this, I added interactive video capability to the project so that users can learn better about how the evolution of music took place over time since Renaissance to centuries later to today. On top of this, I also custom designed the welcome room of the museum which the users visit first upon their entry so that they feel just like at home and learn about the Renaissance first through the interactive video on the TV screen in that room before they visit the exhibit in the gallery and the central room.

## Appendix: Lessons Learned

One of the biggest challenges in this development experience has been to collect data from trustworthy sources to use. This took some time but was achieved successfully. I learned a great deal about how VR content developers render and process all the multimedia content, design 3D Models, and integrate them all into one immersive VR experience. I also learned about the capabilities of Amazon Sumerian and how it can help shape the future of VR in the coming times. I discovered new ways of developing 3D objects using photo-editing tools like Adobe Photoshop. I also learned a great deal about VR headsets of today’s time and finally got to experience my first project in VR on my Oculus Quest 2 HMD.

## References

1. https://www.metmuseum.org/about-the-met/curatorial-departments/musical-instruments
2. https://mim.org/galleries/special-exhibitions/
3. http://www.accademia.org/esplora-il-museo/le-sale/museo-degli-strumenti-musicali/
4. https://www.khm.at/en/visit/collections/collection-of-historic-musical-instruments/selected-masterpieces/
5. https://artsandculture.google.com/usergallery/pgKiYHawYnw9JA
6. http://www.vam.ac.uk/content/articles/m/music-for-the-lute/
7. https://www.recorderhomepage.net/history/the-renaissance-period/
8. https://www.music.iastate.edu/antiqua/ 
9. Music 121-Renaissance Instruments: https://www.youtube.com/watch?v=jPJNJr6iBrs&list=PLFZEKHKLkiB1aMGmKlA05Hs2R4Qzj1zD1
10. https://www.youtube.com/watch?v=I8tW06fv8sg 
11. Google Images
12. Wikipedia

# Author

Vedant "Vito" Shrivastava (GitHub: https://github.com/ivedants ; Email: ivedantshrivastava@gmail.com)
