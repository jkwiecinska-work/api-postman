# api-postman
Internal project for API tests in Postman

## Skills showcase
- API tests automation
- CI/CD integration with GitHub Actions
- Postman/Newman
- Secret variables 

### Run locally
```bash
npm install -g newman
newman run postman/collection.json -e postman/environment.json
