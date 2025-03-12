# structure-carving
A structure carved building mesh simplification


Three-dimensional building models are extensively utilized in domains such as smart cities and virtual reality. However, the complex geometric structures and topological relationships of building models present significant challenges for applications such as rendering and spatial analysis. This paper first proposes a novel approach to simplify man-made building meshes through structure carving. Initially, the spatial relationships of planar primitives are analyzed to construct an attribute-connected graph. The graph is then decomposed, and structures are extracted based on various connected relationships. Finally, the Visual Hull algorithm is employed to generate the visual mesh, which is subsequently simplified into a low-poly mesh through structure carving and mesh simplification.
![image](https://github.com/user-attachments/assets/4ebcf400-4614-4a63-829e-ce4c89004acb)

 Structure carving introduces a novel framework comprising structures selection, structure primitives generation, and iterative carving based on depth loss. Experiments on various building models show that our method generates lightweight meshes that are watertight, accurate, and exhibit high geometric similarity, outperforming other state-of-the-art methods.
![image](https://github.com/user-attachments/assets/729950d5-898a-47e7-bb8f-3ebf960535b7)


![image](https://github.com/user-attachments/assets/251c02bb-feee-46c8-847a-59e396613a71)
                   Input city model
 
![image](https://github.com/user-attachments/assets/06e974df-dd36-463a-ace2-86f47225f88e)
                    Simplified model
                    
![image](https://github.com/user-attachments/assets/5e6994d8-9863-4710-b74b-b0735386b5bd)
                    Lod model
