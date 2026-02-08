\# How to deploy FastAPI on Azure App Service (Linux)



\## Problem

FastAPI deployments on Azure App Service often fail due to an incorrect startup command, wrong module path, missing environment configuration, or binding to the wrong host and port.



\## When you’d need this

When you want a working production deployment on Azure App Service (Linux) and need a reproducible setup with clear validation steps.



\## Prerequisites

\- Azure subscription

\- A FastAPI app with an entrypoint like `main.py` containing `app = FastAPI()`

\- Python 3.9+ locally

\- Azure CLI installed and logged in

\- A `requirements.txt` that includes: `fastapi`, `gunicorn`, `uvicorn`





