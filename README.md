# Install uv Package Manager
```bash
# On macOS and Linux.
curl -LsSf https://astral.sh/uv/install.sh | sh
```
```bash
# On Windows.
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
# Or, With pip.
```bash
pip install uv
```
```bash
# Or pipx.
pipx install uv
```
# Create Project
```bash
uv init
```
# Make virtual Environment and then Install 
```bash
uv add langgraph python-dotenv notebook
uv add langchain langchain-google-genai
```