# Updated Graph Neural Network to Identify Patient Zero(s)

## What is this package:
From a computational standpoint, the challenge of identifying a patient zero poses considerable difficulties. As the outbreak progresses, tracing the precise source or sources of the infection becomes computationally expensive and often impractical. This is primarily due to the stochastic and unpredictable nature of disease spread within a dynamic population and network. Consequently, the formidable challenge at hand revolves around not only determining the number of initial patient zeros but also accurately identifying their identities amidst the intricate web of transmission pathways. This multifaceted challenge underscores the need for innovative approaches, such as the one we are pursuing, which harness advanced technologies like graph neural networks (GNNs) to navigate the complexity of disease dynamics and patient zero identification.

Our method represents a significant advancement in modeling disease outbreaks by addressing several limitations present in current approaches. One key innovation lies in our recognition that the assumption of a single Patient Zero (P0) may not accurately reflect the complexity of real-world scenarios. In many instances, outbreaks may be initiated by multiple individuals simultaneously, and these multiple P0s could subsequently disperse to various locations before the disease begins to spread. Unlike existing models that focus on predicting a single P0, our approach extends the scope to accommodate the possibility of multiple initial cases, providing a more realistic representation of outbreak dynamics.

Furthermore, our model surpasses state-of-the-art techniques by incorporating snapshots of disease progression into its framework. Conventional approaches often rely on predicting the initial P0 based on the final state of the outbreak, a challenging task given the limited information available at the outset. In contrast, our model leverages snapshots captured at various stages of the outbreak, allowing it to track the disease's evolution over time. By considering the dynamic nature of the outbreak, our model gains insights into where and how the infection is spreading. This temporal information enables our model to refine its predictions and identify not only the location but potentially multiple P0s with higher accuracy.

## How to install:

You will need to install python and pip install the following packages

- torch

- networkx

- ndlib

- numpy

- plotly

# How to run the program:

To run the program, navigate to patient0.ipynb and hit the run all button in the python notebook.

This will set up the training/testing data, visualize an example of the graphs, create the model, and train/test the model under various set ups.

Any variable in capital can be modified and tested.
