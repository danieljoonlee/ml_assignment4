# CS-7641 Machine Learning Project 4 - Markov Decision Processes

Following repos influenced by:
https://github.gatech.edu/mmallo3/CS7641_Project4 
https://github.com/cmaron/CS-7641-assignments 
https://github.com/JonathanTay/CS-7641-assignment-4

**Execution**

    1. If using virtualenv, run:

        source bin/activate

    2. Use the run_experiment.py script, which dumps all results in the output directory defined for each dataset:

        python run_experiment.py --all --plot --verbose

    3. When completed, if using virtualenv, run:

        deactivate

    NOTE: run_experiments.py arguments:

        --threads     Number of threads (defaults to -1 for auto)
        --seed        A random seed to set, if desired
        --policy      Run the Policy Iteration (PI) experiment
        --value       Run the Value Iteration (VI) experiment
        --ql          Run the Q-Learner (QL) experiment
        --all         Run all experiments (policy, value, ql)
        --plot        Plot data results
        --verbose     If true, provide verbose output (defaults to false)
        --help        Display the help message and exit

