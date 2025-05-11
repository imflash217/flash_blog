Name: Vinay Kumar
GitHub: https://github.com/imflash217/

---------------

`Notable Repositories` with original implementation of AI systems:

### 1. Cybertron

- **GitHub link**: https://github.com/imflash217/cybertron/blob/main/cybertron/

- **Summary**: It implements various Transformer based algorithms from scratch in raw-python, for auto-regressive tasks, such as:

    - various embedding layers like: `Rotary_Embedding`, `Absolute_Positional`, `Fixed_Positional`, `Relative_PositionBias`, `Alibi_PositionBias`
    - Residual & GRU gates
    - various Normalization layers like `ReZero`, `ScaleNorm`, `RMSNorm` etc.
    - A unified attention layer class to support various configurations of transformer-based architectures.
    - Vision Transformer (ViT) Wrapper
    - Native implementation of Encoder & Decoder blocks.
    - Various utility methods like `top_k`, `top_p`, `top_a` etc to support the modular composition of various architectural components.

- **Navigation guide**: To navigate the repository, look at the `cybertron` folder. All implementation of various algorithms can be found inside `transformers.py` file and the autoregressive wrapper is written in `autoregressive_wrapper.py` file.


### 2. FlashGrid

- **GitHub link**: https://github.com/imflash217/flashGrid/tree/main
- **Summary & Navigation**: PyTorch implementation of GridCells and PlaceCells for Object Detection Task. This was my Master's Thesis Project.
  - It implements various algorithms for learning grid-cells pattern with different grid-initialization strategies. It implements MotionMatrix and various loss functions in learning grid-cells like patterns in `src/model.py`.
  - Generating proper data for training GridCells is written in `src/data_io.py`
