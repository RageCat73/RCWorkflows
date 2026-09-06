
Here you will find the original Files for a "severed arm regeneration" workflow including a prompt, 1st frame, last frame
I think pretty much any minimax model will work. I'm using an FL2V LightX Lora with shift video = 12 and shift audio = 3 node included in the workflow.

There is an OPTIONAL memory optimization and sparse attention group for increased speed. The H3 optimizations are at this github:

https://github.com/Zironic/H3-Optimizations

If you have trouble installing or using that optimizations repo, then just disable that group and substitute whatever H3 speed ups like Plaguekind Sparse attention, h3 spectrum, Sage attention or Comfy Kitchen attention - whatever you like in place of it.
