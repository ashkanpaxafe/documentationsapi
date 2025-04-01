# PAXAFE Live Risk API Documentation

This repository contains the OpenAPI specification and documentation for the PAXAFE Live Risk API v2.

## Documentation

The API documentation is available at: https://ashkanpaxafe.github.io/documentationsapi/

## Local Development

To run the documentation locally:

1. Install the Redocly CLI:
```bash
npm install -g @redocly/cli
```

2. Start the documentation server:
```bash
redocly preview-docs openapi.yaml
```

3. Open your browser and navigate to `http://localhost:8080`

## Repository Structure

- `openapi.yaml` - The OpenAPI specification file
- `redocly.yaml` - ReDocly configuration file
- `.github/workflows/deploy-docs.yaml` - GitHub Actions workflow for deploying documentation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Overview

The PAXAFE Live Risk API provides real-time risk assessment for shipments, including:
- Temperature monitoring and alerts
- Delivery time predictions
- External impact analysis (weather, traffic, geopolitical)
- Device and packaging status monitoring

## API Documentation

The API documentation is available in OpenAPI 3.1.0 format and can be viewed using any OpenAPI-compatible tool.

### Quick Links
- [OpenAPI Specification](openapi.yaml)
- [API Reference](https://stoplight.io/api/v1/projects/contxt/live-risk/nodes/live_risk_docs_v2.yaml)

## Getting Started

### Authentication
The API requires an API key for authentication. Include your API key in the request header:
```
x-api-key: your-api-key
```

### Base URLs
- Production: `https://api.paxafe.com/live-risk/v2`
- QA: `https://api-qa.paxafe.com/live-risk/v2`
- Development: `https://api-dev.paxafe.com/live-risk/v2`
- Pre-production: `https://api-preprod.paxafe.com/live-risk/v2`

## Features

### Live Risk Assessment
- Real-time shipment monitoring
- Temperature excursion alerts
- Delivery time predictions
- External risk factor analysis
- Device and packaging status monitoring

### Risk Levels
The API provides three risk levels:
- **Ignore**: No immediate action required
- **Watch**: Monitor the situation
- **Act**: Immediate action required

## Support

For support or questions, please contact:
- Email: help@paxafe.com
- Documentation: [PAXAFE Documentation](https://stoplight.io/api/v1/projects/contxt/live-risk/nodes/live_risk_docs_v2.yaml)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.