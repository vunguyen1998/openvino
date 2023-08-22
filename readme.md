# Cách khởi động openvino_notebooks trên Window (sau khi đã cài đặt thành công)
Bước 1: Activate the Environment
```
openvino_env\Scripts\activate
```

Bước 2: Launch the Notebooks!
```
cd openvino_notebooks
jupyter lab notebooks
```

-------------------------------------------------------------------------------
# Hướng dẫn cài đặt openvino_notebooks trên Window
Bước 1: Create a Virtual Environment
```
python -m venv openvino_env
```
Bước 2: Activate the Environment
```
openvino_env\Scripts\activate
```
Bước 3: Clone the Repository
```
git clone --depth=1 https://github.com/openvinotoolkit/openvino_notebooks.git
cd openvino_notebooks
```
Bước 4: Install the Packages
```
python -m pip install --upgrade pip wheel setuptools
pip install -r requirements.txt
```
Bước 5: Launch the Notebooks
```
jupyter lab notebooks
```

