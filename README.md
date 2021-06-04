# Setup

### 1. Setup isolated Python environment for the project
```
 python -m venv env
 source env/bin/activate
```
### 2. Install SDK 
```
pip install google-cloud-storage
```

### 3. Restore global Python settings
```
deactivate
```

### 4. Set account credentials
```
export GOOGLE_APPLICATION_CREDENTIALS="${HOME}/.config/gcloud/application_default_credentials.json"
```

### Links
- https://cloud.google.com/python/docs/setup


