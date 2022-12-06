[![GitHub Repo stars](https://img.shields.io/github/stars/ruankie/m1-tensorflow)](https://github.com/ruankie/m1-tensorflow)

# m1-tensorflow
Template setup of GPU-enabled Tensorflow development environment on the Apple M1 chip with Apple GPU
This template development environment includes the following common data science packages:

    - Tensorflow
    - Pandas
    - Numpy
    - Seaborn
    - Jupyter Lab

## Usage
1. Start a new repo using this template
2. Update your `LICENSE` file.
3. Update your `README.md` file.
   1. Update description
   2. Update usage
   3. Update shields
4. Set up and activate conda environment
   1. Add/change any dependencies and their versions in the `./conda.yml` file.
   2. Set up your conda environment and activate it by running:
        ```bash
        conda env create -f conda.yml
        conda activate tf-metal
        ```
5. Add your own scripts in `./src/`
6. Add your own notebooks in `./notebooks/`
7. Add your own data in `./data/`

This template creates the following folder structure:

```
<your-repo-name>
├── LICENSE
├── README.md
├── conda.yml
├── data
├── notebooks
│   └── example.ipynb
├── setup.py
└── src
    ├── __init__.py
    └── utils.py
```
## References
- https://developer.apple.com/metal/tensorflow-plugin/
- https://stackoverflow.com/questions/72964800/what-is-the-proper-way-to-install-tensorflow-on-apple-m1-in-2022