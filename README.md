# Setup-Guides
The setup manuals for the Pi, and Jands StageCL

##Patching the Jands StageCL
Manually add a generic dimmer fixture on the same dmx channel as the Pi is defaulted to listen to in the python script!

<img src="data:image/jpeg;base64,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" alt="A collection of our favorite lighting memes"/>![image](https://user-images.githubusercontent.com/119905567/232915914-7957c7aa-ae2a-4ec2-9c82-9fb6762a31a1.png)
