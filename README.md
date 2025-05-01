Our planning model consists of a CNN to extract hierarchical spatial features of the camera image, whose ouput volume goes through a ViT which returns a learned special token. We then concatenate this learned token and the history, and finally they go through a final MLP decoder to ouput
the future/predicted waypoints.
