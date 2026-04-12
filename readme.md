# Acoustic Modem

Simple acoustic modem to transmit and receive digital data over audible spectrum (sound).
UC Berkeley EE123 Final Project

---

## Initial Environment Setup


### 1. Clone the Repository
```bash
git clone [https://github.com/ncarpenedo26/acoustic-modem](https://github.com/ncarpenedo26/acoustic-modem)
cd acoustic-modem
```

### 2. Create Python Virtual Environment
```bash
python -m venv .venv

# Linux/Mac
source .venv/bin/activate

# Windows
.venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Launch Jupyter
```bash
jupyter notebook
```
Or open in VSCode. Make sure to set the kernel to the correct virtual environment.


## Dependency Management

After adding packages to the virtual environment, run
```bash
pip freeze > requirements.txt
```