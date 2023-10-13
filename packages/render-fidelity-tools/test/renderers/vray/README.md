## Requirements

- [V-Ray App SDK](https://www.chaos.com/vray/application-sdk)
- A V-Ray license
- Python 3

To run this with a specific version of python, install the required python version and then create
a virtual environment from the root render-fidelity-tools directory with:

```bash
# Setup virtual environment for Python 3.10 or which ever one you want
python3.10 -m venv venv_vray
# Enter the virtual environment
source venv_vray/bin/activate
# Install the required packages
pip install numpy pyquaternion numba pillow

# Then run the tests
npm run update-screenshots vray
```
