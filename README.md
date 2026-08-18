# c3gb

**c3gb**, Gradient Boosting models for predicting the CO2 uptake of Coal ashes in Carbon mineralization, were developed in the research article: [AI-guided prediction and control of CO2 mineralization in coal ashes as carbon-efficient supplementary cementitious materials](). They are tree-based ensemble models. 

The models take the physicochemical properties of coal ashes, along with the process parameters related to reactant proportions and carbonation conditions as input features, while the output is CO2 uptake. The models can be used as a objective function to optimize the carbonation process for CO2 mineralization in coal ashes.

Kangyi Cai 2026 @ Missouri S&T

## Environment setup

The code requires `python>=3.9.23`. You can install **c3gb** using `conda`:

```bash
# Create and activate conda environment
conda create -n c3gb python=3.9.23
conda activate c3gb

# Clone the repository
git clone https://github.com/kycai/c3gb.git
cd /path/to/c3gb

# Install dependencies
## using requirements.txt, for windows OS
pip install -r requirements.txt

## specific package versions for windows or other OSes
pip install deep-forest==0.1.7 numpy==1.26.4 pandas==2.3.3 scikit-learn==1.6.1 matplotlib==3.9.4 ipykernel==6.31.0
```

## Getting started

The `reg_pred.ipynb` notebook provides an example of how to use the **c3gb** model to make predictions. You can modify the input data in the `data` folder to test new data.

## License

The **c3gb** checkpoints and demo code are licensed under [MIT](./LICENSE).

## Citing

If you use **c3gb** in your research, please consider citing our paper:

```markdown
K. Cai, X. Cheng, Y. Huang, F. Zhang, H. Ma. AI-guided prediction and control of CO2 mineralization in coal ashes as carbon-efficient supplementary cementitious materials (2026).
```

Or use the following BibTeX entry:

```bibtex
@article{cai2026c3gb,
  title={AI-guided prediction and control of CO2 mineralization in coal ashes as carbon-efficient supplementary cementitious materials},
  author={Cai, Kangyi and Cheng, Xing and Huang, Yuyang and Zhang, Fan and Ma, Hongyan},
  journal={},
  volume={},
  pages={},
  year={2026},
  issn={},
  doi={https://doi.org/}
}
```
