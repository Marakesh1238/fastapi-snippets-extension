# FastAPI Snippets for VS Code

Complete collection of code snippets for FastAPI development.

## 🚀 All Available Snippets

### Project Structure
- `fastapi-structure` - Create complete project structure

### Basic Application  
- `fastapi-app` - Basic FastAPI application

### Database & Models
- `fastapi-base-model` - Base SQLAlchemy model
- `fastapi-user-model` - User SQLAlchemy model
- `fastapi-item-model` - Item SQLAlchemy model
- `fastapi-db-session` - Database session setup

### Schemas & Pydantic
- `fastapi-user-schemas` - User Pydantic schemas
- `fastapi-item-schemas` - Item Pydantic schemas
- `fastapi-model` - Pydantic model

### CRUD Operations
- `fastapi-crud-base` - Base CRUD class
- `fastapi-crud-user` - User CRUD operations  
- `fastapi-crud-item` - Item CRUD operations
- `fastapi-crud-init` - CRUD package initialization

### API Endpoints
- `fastapi-user-endpoints` - User API endpoints
- `fastapi-item-endpoints` - Item API endpoints
- `fastapi-get` - GET endpoint
- `fastapi-post` - POST endpoint
- `fastapi-put` - PUT endpoint
- `fastapi-delete` - DELETE endpoint

### HTTP Features
- `fastapi-query` - Query parameters
- `fastapi-path` - Path parameters  
- `fastapi-form` - Form data
- `fastapi-upload` - File uploads
- `fastapi-response` - Custom responses

### Security & Auth
- `fastapi-oauth2` - OAuth2 authentication
- `fastapi-cors` - CORS middleware

### Advanced Features
- `fastapi-bg` - Background tasks
- `fastapi-ws` - WebSocket endpoint
- `fastapi-rate` - Rate limiting
- `fastapi-cache` - Redis caching

### Testing & Utilities
- `fastapi-test` - Test cases
- `fastapi-dep` - Dependencies
- `fastapi-error` - Exception handlers
- `fastapi-middleware` - Custom middleware
- `fastapi-db` - Database setup

## 💡 Usage Example

```python
# Type: fastapi-app
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
async def root():
    return {"message": "Hello World"}



## 🚀 Installation

### From GitHub Releases:
1. Download the latest `.vsix` file from [Releases](https://github.com/Marakesh1238/fastapi-snippets-extension/releases)
2. In VS Code: `Ctrl+Shift+P` → **"Extensions: Install from VSIX"**
3. Select the downloaded file
4. Reload VS Code when prompted

### Manual Installation:
```bash
git clone https://github.com/Marakesh1238/fastapi-snippets-extension
cd fastapi-snippets-extension
vsce package
code --install-extension fastapi-snippets-*.vsix
```
