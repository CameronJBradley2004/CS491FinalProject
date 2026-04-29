# CS491FinalProject
## Setup
### All of this is taken care of py the .ipynb but are as follows
transformers and bitsandbytes need accelerated
torch, AutoProcessor - AutoModelImageTextToText - BitsAndBytesConfig from transformers, re, Image from PIL, requests, TextStreamer from imports
## Running
The 3 code cells at the end run in this order: normal, loose, strict. In the data there are different temperature cells which can be modified in those code cells. Each cell was run 5 times for each temperature, with 15 runs in total, the temperature being changed every 5. 
## Output
The output has to be manually tracked. I used an excel spreadsheet to keep track of the results of every cell, and then made data of those. The cells are broken up for adaptability, mostly because testing was volatile and led to many issues so it was used to mitigate time wasted.
