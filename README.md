# ImageBundlerPy
A tool to bundle images together into a spritesheet with a .json

## Example
```sh
python3 image.py exm_input_dir exm_output_dir 512 512 .ignore notcompact
```

## Definitions
```py
[exm_input_dir] - Input folder containing the assets, must be .png
[exm_output_dir] - Output folder that the script will generate 0.png and 0.json in
[512] - Width of the spritesheet, increase or decrease to your liking
[512] - Height of the spritesheet, increase or decrease to your liking
[.ignore] - Files starting with .ignore will not be considered
[notcompact] - notcompact or compact, defines the look of 0.json
```