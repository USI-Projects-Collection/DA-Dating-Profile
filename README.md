# DA-Dating-Profile Installation Guide
Data Analytics - Course Assignment N.16: Dating Profile


## 1. Using `conda` *(STRONGLY RECOMMENDED)*

If you are using `conda`, you can create an environment and install dependencies from `requirements.txt`.

### **Step 1: Create a Conda Environment with the right dependencies**
```sh
conda env create -f environment.yml
```

### **Step 2: Activate the Conda Environment**
```sh
conda activate DA_env
```

## 2. Using `pip` and `venv`

If you are using `pip`, it's recommended to create a virtual environment first.

### **Step 1: Create and Activate Virtual Environment**

```sh
python3 -m venv my_env  # For macOS/Linux
source my_env/bin/activate  # For macOS/Linux

python -m venv my_env  # For Windows
my_env\Scripts\activate  # For Windows
```

### **Step 2: Install Missing Dependencies**
```sh
pip install <package_name>
```