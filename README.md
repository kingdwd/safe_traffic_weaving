# safe_traffic_weaving

ROS package accompanying ["On Infusing Reachability-Based Safety Assurance within Probabilistic Planning Frameworks for Human-Robot Vehicle Interactions"](http://asl.stanford.edu/wp-content/papercite-data/pdf/Leung.Schmerling.Chen.ea.ISER18.pdf) by Karen Leung\*, Edward Schmerling\*, Mo Chen, John Talbot, J. Christian Gerdes, Marco Pavone) published in the [2018 International Symposium on Experimental Robotics](http://www.iser2018.org/). An extended [journal version](http://asl.stanford.edu/wp-content/papercite-data/pdf/Leung.Schmerling.ea.IJRR19.pdf) is to appear in the International Journal of Robotics Research. 

This ROS package performs the prediction and planning for a pairwise traffic-weaving interaction detailed in our ICRA2018 paper, [Multimodal Probabilistic Model-Based Planning for Human-Robot Interaction](http://asl.stanford.edu/wp-content/papercite-data/pdf/Schmerling.Leung.Vollprecht.Pavone.ICRA18.pdf) by Edward Schmerling, Karen Leung, Wolf Vollprecht, Marco Pavone. In a nutshell, it predictions are made about what the human-driven car will do in the future, and the robot selects an optimal action sequence to perform a traffic-weaving maneuver with the human-driven car. A desired trajectory (ROS msg) is produced. In our experiments, this trajectory is fed into a lower-level tracking controller. We use [`Pigeon.jl`](https://github.com/StanfordASL/Pigeon.jl).


# * Use the `packaging` branch*