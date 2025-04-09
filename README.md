# HyPyP-template
Example of how to start a project HyPyP

**Linux example to start the project**

```
# Create a virtual environment
python -m venv venv-hypyp

# Enter the virtual environment
source venv-hypyp/bin/activate

# Install HyPyP using pip
git clone -b feature/fnirs https://github.com/patricefortin/HyPyP.git
cd HyPyP
pip install -r requirements.txt
pip install -e .

```
