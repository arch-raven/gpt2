# gpt2

```
# Requirements
torch >= 2.1
tiktoken
``` 


Uses nanoGPT repo as base structure.  `CasualSelfAttention` has been modified to use RoPE embeddings instead of Learned Position Embeddings. Adds support for Multi Head Attention, Group Query Attention & Multi Query Attention.

```
# Run following command to test model
python generate.py
```


Only tested for Single GPU run, Adding support/testing of DDP / FSDP requires access to multi-GPU / multi - Node systems which I do not. 
