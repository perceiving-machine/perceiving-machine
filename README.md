# Perceiving-Machine
A machine that attains awareness or understanding of ideas and meanings.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Perceive what is being said, machine." \
  | uvx perceiving-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install perceiving-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
perceiving-machine -a multilogue.txt
```
Or:
```bash
perceiving-machine multilogue.txt > response.txt
```
Or:
```bash
perceiving-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import perceiving_machine
```
