# Mira Documentation

This repository contains the official documentation for Mira's API. Our documentation covers:

- Quick Start Guide
- API Reference
- Advanced Capabilities
- Patient Management
- Task Management

### Local Development

To preview the documentation locally, you'll need the [Mintlify CLI](https://www.npmjs.com/package/mintlify). Install it using:

```bash
npm i -g mintlify
```

Then run the following command at the root of the documentation:

```bash
mintlify dev
```

### Making Changes

1. **Content Updates**
   - Documentation files are in MDX format
   - API specifications are in OpenAPI/Swagger format
   - Images should be placed in the `/public` directory

2. **Configuration**
   - Main configuration is in `docs.json`
   - Theme and styling can be customized in the `colors` section
   - Navigation structure is defined in the `navigation` section

### Troubleshooting

- If Mintlify dev isn't running, try `mintlify install` to reinstall dependencies
- If a page loads as 404, ensure you're in the correct directory with `docs.json`
- For logo/image issues, verify files exist in the `/public` directory

### Need Help?

Contact the development team at [support@miramace.com](mailto:support@miramace.com) for assistance.
