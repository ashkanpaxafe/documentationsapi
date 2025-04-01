# PAXAFE Live Risk API Documentation

This repository contains the OpenAPI specification for the PAXAFE Live Risk API v2.

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

This API is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.