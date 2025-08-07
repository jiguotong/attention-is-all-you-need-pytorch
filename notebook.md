conda create -n transformer python=3.8
pip install torch==1.13.0+cu116 torchvision==0.14.0+cu116 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu116
conda install -c conda-forge spacy
python -m spacy download en
python -m spacy download de
# 若服务器无法连接下载，参考https://blog.csdn.net/weixin_63577740/article/details/130133855

pip install dill
conda install torchtext==0.13.0     # 需要与torch对应