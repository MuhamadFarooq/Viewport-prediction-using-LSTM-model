Text file has data of user pitch and yaw angles. This data has beed taken from https://github.com/360VidStr/A-large-dataset-of-360-video-user-behaviour/blob/main/README.md
These angles are transformed into pixel coordinates.
Analyze pixel coordinates on video frame width and height.
Build viewport on pixel coordinates. 
Video : 8K, (width, height = 7680, 3840)
viewport size (width, height = 1920, 1080)
Data is being pre-processed and then made sequences that are required as input for LSTM model.
Using LSTM model, viewport prediction accuracy is calculated.
Different accuracy levels are introduced as how many frames have 100% accuracy, 75%, 50%, 25% and also 0% to check performance of model.
