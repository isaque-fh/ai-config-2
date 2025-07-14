# AI Agent Configuration for Roo VSCode

## 1. Download Roo VSCode
Install the Roo VSCode extension from the Visual Studio Marketplace.

## 2. Configuration Settings

### API Provider Selection
- Provider Type: `OpenAI Compatible`

### Connection Settings
```yaml
api:
  url: API_URL
  key: API_KEY
```

### Model Configuration
```yaml
model: DeepSeek
parameters:
  enable_r1: true
```

### Custom Headers
```yaml
headers:
  Organization: ORGANIZATION_KEY
  Project: PROJECT_KEY
```

### Approval Settings
```yaml
approvals:
  all: true
