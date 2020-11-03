# Data_for_multi_laser_calibration
The calibration for a multi-sensor system needs to deal with accuracy and robustness while adjusting the parameters online. However, using low-cost 2D LiDARs with high uncertainty point clouds, which effect poorly to the calibrated estimation. In contrast, the line features extracted from the point cloud are robust and sufficient for high accuracy calibration. In this paper, we propose an automatic calibration framework adopting the line features-based optimization algorithm with fuzzy inference system-aware robust adaptive covariance for multiple low-cost 2D LiDARs on SE(2). We first develop efficient line based-factors for the graph optimization with two strategies using one line and multi-line corresponding. Then, we propose a self-executing strategy for the calibration schema online running in real-time. Furthermore, we propose a fuzzy inference system that mimics engineering rules to adapt the covariance of each line factor to be added to the graph. Besides, we develop a sensor system for the proposed calibration system, which is implemented and validated through our dataset. The results demonstrate that our system's accuracy and robustness have with the rotation and translation errors less than 2 degrees and 2 cm, respectively. It suggests that our algorithm can widely apply in industrial applications.

To summarize, our major contributions are following as:
1. We develop a multiple L2LD calibration framework based on the line features on SE(2) without any artificial board or prior measurements related to the environments. This framework can calibrate the parameters in both offline and online mode.
2. We propose the factor graph by using the one-line and multi-line feature corresponding for a Maximum A Posteriori (MAP) based-optimization with Type 2-Fuzzy adaptive covariance.
3. We build a sensor system consists of four L2LD and experimental in the collected datasets. Furthermore, we publish the dataset to the research social to do their experiments.
4. The algorithm can calibrate and self-refine online automatically. The experimental results verify the feasibility of this methodology, which can be widely used in the real world applications for AGV and moreover.

This is link to download datashet with gound-truth calibration, it should be adjust <added later>
  
  
  Video:
  [![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://youtu.be/j7XaZ1b32Zs)
