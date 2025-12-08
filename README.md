# Green-Device-Histology-Quantification
The macros included in this repository was drafted with AI-generated assistance from Code Copilot (ChatGPT, OpenAI; model: GPT-5 Thinking) in December 2025, then reviewed and edited by Hannah Anderson.

The code was created to be run in ImageJ Version 1.54p 17 February 2025 with ImageJ macros plugin with language selection set to "ImageJ macros".

The objective was to analyze 3 sets of images for the following criteria:
1. H&E: Urothelial denudation length in 4 regions of interest, with proper normalization to scale bars. (Note that ideally these were chosen in evenly distributed quadrants in the images, but based on tissue distribution in the image measurements weren't perfectly taken one in each quadrant)
2. Masson's Trichrome: Identify fibrosis (blue) pixel area in the implantation region vs. outside of the implantation region. (Note that implantation region is user-defined circular region)
3. CD45: Identify CD45 positive area (# red particles > 1 pixel) in the implantation region vs. outside of the implantation region based on thresholding from negative control tissue with no primary antibody.
