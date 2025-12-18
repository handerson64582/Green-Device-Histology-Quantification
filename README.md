# Green-Device-Histology-Quantification
The macros included in this repository was drafted with AI-generated assistance from Code Copilot (ChatGPT, OpenAI; model: GPT-5 Thinking) in December 2025, then reviewed and edited by Hannah Anderson, of whom responsibility for accuracy remains with. Semi-automated blinded analysis of images using the codes was conducted by Bhavana Talluri. 

The code was created to be run in ImageJ Version 1.54p 17 February 2025 with ImageJ macros plugin with language selection set to "ImageJ macros".

The objective was to analyze 3 sets of images for the following criteria:
1. H&E: Lamina propria thickness in 4 regions of interest, with proper normalization to scale bars. (Note that ideally these were chosen in evenly distributed quadrants in the images, but based on tissue distribution in the image measurements weren't perfectly taken one in each quadrant). 
2. Masson's Trichrome: Identify fibrosis (ImageJ colour deconvolution for Masson's Trichrome blue) pixel area in the implantation region vs. outside of the implantation region. (Note that implantation region is user-defined circular region).
3. CD45 % area implantation: Identify CD45 positive area (> 1 pixel) in the implantation region vs. outside of the implantation region based on thresholding from negative control tissue with no primary antibody.
4. CD45+ cells in non-implanted tissue: Identify average # CD45+ particles (>50 pixels) per DAPI cell (>50 pixels), as an estimate of expression on a cellular level in saline vs CYP groups. define non-implanted tissue region, then 4 random 1500x1500 pixel region roi's are chosen, can go through multiple iterations if the regions selected contain too much lumen space. Set thresholds based on negative control tissue. Ensure to blind file names due to semi-automated nature of the analysis.
