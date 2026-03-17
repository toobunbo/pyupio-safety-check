# How to use Safety to check Security dependencies (example: pyproject.toml)
## Set up Safety
```
pip install safety
safety login 
```
## Check Security
```
### Load firewall Safety
safety firewall init
source ~/.safety/.safety_profile

### Check Security dependencies
safety uv add requests
```
