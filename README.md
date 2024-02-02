Base PR: https://github.com/ggerganov/llama.cpp/pull/5267   
Note: integration in llama.cpp is partial at this point - it uses llava-1.5 preprocessing  

The mmproj files are the embedded ViT's that came with llava-1.6, I've not compared them but given the previous releases from the team I'd be surprised if the ViT has not been fine tuned this time.
If that's the case, using another ViT can cause issues.  

