Text file has data of user pitch and yaw angles. This data has been taken from https://github.com/360VidStr/A-large-dataset-of-360-video-user-behaviour/blob/main/README.md

These angles are transformed into pixel coordinates.

Analyze pixel coordinates on video frame width and height.

Build viewport on pixel coordinates.

Video : 8K, (width, height = 7680, 3840)

Viewport size (width, height = 1920, 1080)

Data is being pre-processed and then made sequences that are required as input for LSTM model.

Using LSTM model, viewport prediction accuracy is calculated.

Different accuracy levels are introduced as how many frames have 100% accuracy, 75%, 50%, 25% and also 0% to check performance of model.

This model is then trained for real time 360-degree video streaming (calculating inference time, latency, throughput and feasibility for 30 fps)
