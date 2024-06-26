# Behavioral-Cloning
This assignment will give you a tutorial on behavioral cloning, a very important tool for robotlearning. Behvioral cloning allows us to learn policies from datasets of previously collecteddemonstrations. This is very powerful for a number of reasons. First, these offline approaches donot require environment interactions (we do not need to query the environment for rewards asyou need to do with Reinforcement Learning). For robotics this is particularly helpful asenvironment interaction can be expensive or dangerous. Even more importantly, offlineapproaches are necessary for robot learning as they allow for much greater scalability andportability (which is exactly what we are looking for in this era of deep learning). Datasets ofdemonstrations can be shared across institutions and grown over time (think RT-X dataset).These large scale datasets can help bring robotics closer to the successes of computer visionand NLP. If you work in robotics you may realize that this is not exactly how things currentlywork, datasets are often not reused and it is very common to collect new data for everyexperiment. This is exactly why we need better methods for behavioral cloning. Learningeffictive policies from diverse demonstration datasets is a very active area of research.

Robomimic:
Robomimic is an open source platform for imitation learning algorithms anddatasets. The platform's foundational study paper investigates a variety of offline learningalgorithms across a suite of demonstrated tasks (provided by real humans of differing skilllevels). The authors draw insights about algorithm design and dataset characterists from theresults in this paper. You will be using the robomimic codebase and datasets for this project. Atthe end of the assignment you will conduct your own experiments and draw your own lessonsabout three key behavioral cloning algorithms. You will read the robomimic paper(
https://arxiv.org/abs/2108.03298
) for the class on 2/14.

Robosuite:
"Rososuite is a simulation framework powered by the MuJoCo physics engine forrobot learning. It also offers a suite of benchmark environments for reproducible research." Thisis the simulation environment upon which robomimic is build. Here is the robosuite paper(
https://arxiv.org/abs/2009.12293
).
