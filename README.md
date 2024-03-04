## Idea/Approach
MGFN (Magnitude-Contrastive Glance-and-Focus Network: State-of-the-Art (SOTA) model for detection of anomalies in videos.
Consists of 2 modules, 
Glance Module that extracts long term context information,      
Focus Module that generates local features from regions of anomalies.
Usage of Magnitude-Contrastive loss function that encourages the model to learn the discriminating features between normal and anomalous videos.
Top-k features are taken instead of full videos for classification as anomalous or not.
MGFN gives the frames of videos with the probability of it being anomalous.
An initial ping is sent to the police station and nearby officers about an anomaly occurring with the clip of anomaly, location and time details.
The cropped video of the anomaly is sent to a battery of Classification Models that finds the intricate details about the anomaly that has occurred (type of anomaly: assault, robbery, etc., instruments used: knife, gun, etc.) and finds the severity on a scale of 1-10.

![image](https://github.com/KeerthanaG23/IVP_Scene_Understanding/assets/116378322/db075a7e-32fa-41f9-9d7b-41c94ca778e3)
## Workflow
![image](https://github.com/KeerthanaG23/IVP_Scene_Understanding/assets/116378322/cc254d85-a1a4-4344-a053-2079fd0450ae)

