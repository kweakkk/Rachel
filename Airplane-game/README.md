<h1 align="left">Airplane Game</h1> 
<h2 align="left">Introduction</h2>

**Airplane Game:** Actually I just try to create a game that user can control the airplane by microphone. But now I just set the initial thing include the airplane model and write the script that connect the airplane and microphone. The script tutorial comes from <a href="https://www.youtube.com/watch?v=dzD0qP8viLw&list=PLkmEDZ0E8yk5x4hV5hUS4tGfuNurF54Ql">youtube link</a>. <br>

The airplane model comes from the <a href="https://assetstore.unity.com/packages/3d/vehicles/air/planes-choppers-polypack-194946">Unity Asset Store</a>.
The project now has the relevant scripts which can let loudness of voice to control the scale of airplane, and I also upload a finger snap audio to test it.But according to our GDD, the loudness should control the action/position of airplane, I think maybe the logic of script is the same and we can change the scale to position.

<h2 id="guide">Project Installation and Set Up Guide</h2>

**Step 1**: Download <a href="https://unity.com/download">Unity Hub </a>.

**Step 2**: Download ZIP of this project in Github then extract the file on your computer.

**Step 3**: Open your Unity Hub Projects section. Click ‘add’ then choose ‘add project from disk’.

**Step 4**: Click the project name to access it.

**Step 5**: Open the Scene through Project → Assets → Scenes → SampleScene.

**Step 6**: Click the complaneV1 of the hierarchy window to see the details. 

**Step 7**: Drag fiinger snap audio to the AudioClip of the Audio Source of the inspector window.

**Step 8**: Click open to see the chage of scale of the airplane with voice.


**The code of voice control mainly from the components of 'scale from audio' of comPlaneV1 and AudioLoudnessDetection,you can double click it to see the script details.**
![image](https://github.com/kweakkk/Rachel/blob/main/Airplane-game/image.png)



