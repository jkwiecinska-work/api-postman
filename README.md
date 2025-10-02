# api-postman
![API Tests](https://github.com/jkwiecinska-work/api-postman/actions/workflows/api-tests.yml/badge.svg)


Internal project for REST API automated tests in Postman, using [GoRest](https://gorest.co.in) API

## Skills showcase
- API tests automation
- CI/CD integration with GitHub Actions
- Postman/Newman
- Secret and variables management
- Enviromnent management
- Integration with GitHub issues

### Run locally from CLI
```bash
npm install -g newman
newman run postman/postman/GoRest_API_tests.postman_collection.json -e postman/postman/GoRest_CI.postman_environment.json
