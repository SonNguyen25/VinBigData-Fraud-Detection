
# IEEE-CIS Fraud Detection

- Information about the competition, dataset and the related issues can be found on: [IEEE-CIS Fraud Detection](https://www.kaggle.com/competitions/ieee-fraud-detection/overview).
- Quick link to download dataset: https://drive.google.com/drive/folders/1stPchCtWg9WY5okkPiTRmdvcK0yKcibK?usp=sharing

---
### Setup

- First, you need install python enviroment
- Install Python (over 3.6): https://www.python.org/downloads/
- Or install Conda
##### You can use these scripts to install anaconda
```
sudo apt update
apt-get install wget
wget https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh
bash Anaconda3-2020.07-Linux-x86_64.sh
export PATH=~/anaconda3/bin:$PATH
```
##### Create a conda environment with python > 3.6
```
conda create -n py38 python=3.8 -y
source ~/anaconda3/etc/profile.d/conda.sh
```

##### After that, install the required packages
```
pip install -r requirements.txt
```
  
---
### Compile & Run
- Run Jupyter Notebook from the root of the directory of source code - Reference: [Running the Jupyter Notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
- Open the notebooks you want to rerun and run the desired cells
- Some cells will require the other cells to be run first so my suggestion is to run cells sequentailly. Also, if there is something that does not follow the normal sequential run, it is always noted in the head comments of each cell or through text cell with prefix "Caution".

---
### Contributors

- Nguyễn Bảo Sơn
- Nguyễn Trung Kiên
- Đặng Xuân Lộc
- Phạm Hoàng Tùng
- Nguyễn Nhật Quang
