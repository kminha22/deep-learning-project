## Title: A Unified Framework for Graph Integration in Transformers

Student(s) name: 22000034 Minha kwon

Youtube link : https://youtu.be/r__FlccfZ4s

[ View The Report ](Report.pdf) 

--- 
Summary : 

Graph transformers aim to combine the strengths of graph structures and transformer models. However, existing approaches vary widely, making them difficult to compare or understand. Each method uses different techniques to build graphs, represent them, encode structural information, and integrate it into the model. Because of this, it is hard to see the overall design space clearly.

In this project, I reorganize graph-transformer methods into five key dimensions: graph type, graph representation strategy, positional encoding, integration strategy, and model architecture. For positional encoding and model architecture, I just re-organize the existing methods. But for representation strategy and integration strategy I define some new dimension addressing underlying concept across papers. Each dimension represents one step in how graph information is introduced and used in the model.

Graph type defines what relationships exist in the data. Representation strategy explains how the graph is used. Positional encoding converts structure into vectors. Integration strategy decides where the information is injected. Model architecture defines how attention uses this information.

I analyze representative models and show that most approaches are combinations of these design choices. This structured categorization provides a simple and systematic way to understand, compare, and design graph-transformer models for different tasks.

