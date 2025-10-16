# Behind RoPE: How Does Causal Mask Encode Positional Information?
- An official implementation of the paper [Behind RoPE: How Does Causal Mask Encode Positional Information?](https://arxiv.org/abs/2509.21042)

![image](main.png)


## Requirements
- `$pip install -r requirements.txt`
- FYI: tested with `transformers==4.52.4`

## Usage
- Each Jupyter notebook in the `concept` directory corresponds to a subsection of the paper:
  - `concept/math.ipynb`: Figure 1
  - `concept/simulation.ipynb`: Section 4.1
  - `concept/with_params.ipynb`: Section 4.2
  - `concept/simulation_rope.ipynb`: Section 5.1
  - `concept/rope_llms.ipynb`: Section 5.2
- The outputs of each notebook are saved in the `figures` directory.
- The model checkpoint is provided on [huggingface](https://huggingface.co/starmpcc/NoPE_1.5B_FW_EDU_15T).


## Citation
```
@misc{kim2025ropedoescausalmask,
      title={Behind RoPE: How Does Causal Mask Encode Positional Information?}, 
      author={Junu Kim and Xiao Liu and Zhenghao Lin and Lei Ji and Yeyun Gong and Edward Choi},
      year={2025},
      eprint={2509.21042},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2509.21042}, 
}
```
