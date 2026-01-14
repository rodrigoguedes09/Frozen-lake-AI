Reinforcement Learning Project on Frozen Lake



Project Description:

    This project presents a Reinforcement Learning agent that learns to navigate the Frozen Lake
    environment using the Q-Learning approach. Frozen Lake is a classic machine learning 
    environment where a character must find a safe path through a frozen lake to reach its
    destination while avoiding holes in the ice. The agent makes decisions to find the safest 
    route, trying to maximize its rewards along the way.


Prerequisites

  To run this project, you need to have Python installed in your development environment. Also, make sure you have the following libraries installed:

    OpenAI Gym: a reinforcement learning environment library.

    NumPy: a library for numerical calculations.

    Matplotlib: a library for creating plots.

    You can install the required libraries using the following command:

    pip install gym numpy matplotlib


Running the Project

    To run the project, simply copy and paste the above code into a Python 
    environment and run the script. Make sure to have the mentioned libraries
    installed correctly. The agent will perform 30 training episodes, learning 
    to navigate the Frozen Lake environment, and then make 5 attempts to reach 
    the destination based on what it has learned. The generated graph will show 
    the agent's performance over the training episodes.

![image](https://github.com/rodrigoguedes09/Frozen-lake-AI/assets/61996985/6b72e3fb-04ce-4ef6-8446-24394971581c)


Notes

    The Frozen Lake environment used in this project has slippery ice cells 
    disabled ("is_slippery=False"), making the environment deterministic. If you
    want to work with the original Frozen Lake environment, set "is_slippery=True". 
    The code can be improved by tuning hyperparameters, such as the number of training
    episodes, learning rate, and discount factor. For other functionalities and information
    about the OpenAI Gym library, refer to the official documentation: 
    https://gym.openai.com/docs/.


Conclusion

    This project demonstrates how to apply the Q-Learning algorithm to train an agent
    to navigate in a Frozen Lake environment. The agent learns to optimize its actions
    to reach the destination based on rewards and the Q-table updated after each training
    episode. Experiment with adjusting hyperparameters, trying different approaches, and 
    exploring other environments available in OpenAI Gym to further enhance the performance of 
    the reinforcement learning agent. Have fun exploring the world of machine learning and
    artificial intelligence!
