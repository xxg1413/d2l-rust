# d2l-rust
《动手学深度学习》Rust版本

## 环境安装

[jupyter rust install](https://datacrayon.com/posts/programming/rust-notebooks/setup-anaconda-jupyter-and-rust/)


conda create -n xxx python=3
conda activate xxx 

conda install -c conda-forge jupyterlab=2.2.9
conda install -c anaconda cmake -y

conda install -c conda-forge nodejs=15 -y
jupyter labextension install jupyterlab-plotly

安装rust


cargo install evcxr_jupyter --version 0.5.3
evcxr_jupyter --install


