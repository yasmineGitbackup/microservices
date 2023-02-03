[![Python application test with Github Actions](https://github.com/phoebe20200523/microservices/actions/workflows/devops.yml/badge.svg)](https://github.com/phoebe20200523/microservices/actions/workflows/devops.yml)
[![aws code build passing](https://codebuild.us-east-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiNTBzTkRqd3FvL2dpQ3hsTHBvaE41N2c0TUN4UGt0dEFZR0dSK3B1RnBVU1N4OVRRWmRYV01ZRGVWSFMrdWlvbkhrSVB4c3k3ZzR0UmJCQ0UvalZ1dmI0PSIsIml2UGFyYW1ldGVyU3BlYyI6InZNVDc0dXdBSDAzUjVoeXQiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)
# microservices
## Design 
<img width="1022" alt="Screen Shot 2023-01-22 at 3 30 27 PM" src="https://user-images.githubusercontent.com/65870261/213938825-c9e9b9cb-818e-4398-b6b9-904914fd8e35.png">


## Steps

1. Create a Python Virtual Environment `python3 -m venv ~/.venv` or 'virtualenv ~/.venv`
2. Create empty files: `Makefile`, `requirements.txt`, `main.py`, `Dockerfile`, `mylib/__init__.py`
3. Populate `Makefile`
4. Setup Continuous Integeration, i.e. check code for issues like lint errors
<img width="1493" alt="lint-failure" src="https://user-images.githubusercontent.com/65870261/213890317-11c29a80-54b3-4703-8b03-15d0e1cd7bdf.png">

5. Build cli using Python Fire libraray ' ./cli-fire.py --help` to test logic


## Demo





https://user-images.githubusercontent.com/65870261/213940075-639d8904-1ae8-44b3-b690-e410cee2ceea.mp4

