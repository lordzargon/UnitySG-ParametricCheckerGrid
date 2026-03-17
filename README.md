Just create a material using this shader.

Defaults to an Unlit material, but you can change the lighting model in the Shader Graph file as you wish (i.e. Lit)

Checker Scale and Grid Line scale will round to keep it fixed to world units. You can override by removing the Round nodes in the Shader Graph.

Designed really to be cheap (its all simple math with no trig and no texture samples)
