# Python Virtual Environment
## Pratham Bhise

### 1. Check version

```bash
python --version
```

### 2. Install virtual environment

```bash
pip install virtualenv
```

### 3. Create virtual environment

```bash
virtualenv myenv
```

> Here `myenv` is name of the virtual environment, you can change it to your preference.


### 4. Activate virtual environment

```bash
myenv\scripts\activate
```

### 5. Deactivate virtual environment

```bash
myenv\scripts\deactivate
```

### 6. Create requirements file

- to display installed packages

```bash
pip freeze
```

- to write list of installed packages to `requirements.txt`

```bash
pip freeze > requirements.txt
```

### 7. Install requirements

```bash
pip install -r requirements.txt
```
