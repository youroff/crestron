# Volume control for PAMP 4x100

PAMP 4x100 from Prodigy lineup has separate triggers to toggle mute state which is not convenient if you want to use only one button. The common solution based on Toggle symbol doesn't work cause mute state can be changed due to many internal or external reasons which are really difficult to track. So we rely on One Shot producing signal of 1 tick length.

![Volume Control symbol](http://i43.tinypic.com/vq70xe.png)

- `Mute_State` is a feedback output of the PAMP (RoomN_Mute_On_F) 
- `Reset_Volum` is an input for triggering volume initialization (Volume will be set to the level of initial_volume variable)
