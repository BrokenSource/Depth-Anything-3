Fork of https://github.com/ByteDance-Seed/Depth-Anything-3 with:
- Minimal dependencies for monocular estimation only
- No default torch dependency, that should be decided at runtime
- Python 3.13+ works, as open3d is missing wheels
- No numpy<2 restriction

This repository shall be deprecated in favor of an official transformers release, likely through the currently missing https://huggingface.co/depth-anything/DA3-SMALL-hf repository.