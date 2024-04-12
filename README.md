# Graph-Coloring-MATLAB-

This code is a MATLAB script for solving the Graph Coloring Problem (GCP) using a genetic algorithm (GA). Here's an overview of what each section of the code does:

    Input Section:
        The user is prompted to input the number of nodes (N_nodes) and the number of colors (N_Colors).
        The user also selects whether to generate a custom graph or a random graph.

    Graph Generation Section:
        If the user selects a custom graph, they are prompted to specify the connectivity between nodes.
        If the user selects a random graph, edges between nodes are randomly generated.

    Drawing Graph Section:
        The generated graph is plotted using random positions for the nodes.
        Edges between connected nodes are drawn.

    Genetic Algorithm Section:
        A population of solutions (chromosomes) is initialized.
        The genetic algorithm iteratively optimizes the solutions to minimize the cost function.
        The cost function evaluates the number of conflicts (uncolored adjacent nodes) for each solution.
        Crossover and mutation operations are applied to create new solutions.
        The process continues until convergence or reaching the maximum number of generations.

    Drawing Colored Graph Section:
        Once the optimal solution is found, the graph is redrawn with nodes colored according to the solution.
        Each color is represented by an RGB triplet.
        The colored nodes and their corresponding color indices are displayed.

Overall, this code implements a genetic algorithm to solve the Graph Coloring Problem and visualize the solution. If you have any specific questions about any part of the code or need further explanation, feel free to ask!
