# Bike sharing Analysing
 An opportunity to demonstrate Data Scientist skills  from various angles - processing data, analyzing and vizalizing it, finding insights, applying predictive techniques and explaining my reasoning about it



This repository contains the code and resources for analyzing the bike sharing dataset from the UCI Machine Learning Repository.

## Setup Instructions

Follow the steps below to set up the Python environment for this project.

### 1. Install `virtualenv`

If you don't have `virtualenv` installed, you can install it using `pip`:

```bash
pip install virtualenv
```

### 2. Create a Virtual Environment

Create a virtual environment named `bike_sharing_env`:

```bash
virtualenv bike_sharing_env
```

### 3. Activate the Virtual Environment

- **On Windows:**

  ```bash
  bike_sharing_env\Scripts\activate
  ```

- **On macOS/Linux:**

  ```bash
  source bike_sharing_env/bin/activate
  ```

### 4. Install Required Packages

Once the virtual environment is activated, install the necessary packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 5. Generate `requirements.txt`

To capture the installed packages in a `requirements.txt` file, run:

```bash
pip freeze > requirements.txt
```

### 6. Deactivate the Virtual Environment

When you're done, deactivate the virtual environment with:

```bash
deactivate
```

---

Copy and paste this into your `README.md` file in the root directory of your GitHub repository. This will guide users through the process of setting up their environment to work with your code.