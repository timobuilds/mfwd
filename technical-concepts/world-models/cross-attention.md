# Cross attention

cross-attention mechanisms allow world models to maintain multiple aspects of the world simultaneously.



## The world model maintains multiple representations world\_state = { 'visual': image\_features, # What it looks like 'spatial': navmesh\_features, # Where you can walk 'semantic': text\_features, # What things mean 'geometric': depth\_features # 3D structure } # Cross-attention fuses these into coherent understanding output = cross\_attention(query=3d\_latents, keys=world\_state)
