# Managing different environments for AWS CDK Dev Test Prod

Published: 2024-09-30
Medium: [https://medium.com/@kyle-t-jones/managing-different-environments-for-aws-cdk-dev-test-prod-3ce6336bb7c0](https://medium.com/@kyle-t-jones/managing-different-environments-for-aws-cdk-dev-test-prod-3ce6336bb7c0)

## Business context

When developing applications with AWS CDK, managing multiple environments, such as development, testing, and production, is essential. Each environment typically has its own configuration and infrastructure needs. For instance, your development environment might use smaller, cost-effective resources, while production requires more reliable, scalable infrastructure.

One common approach to managing multiple environments is through environment variables. This allows you to configure different settings for development, testing, and production environments without changing the underlying code. You can set environment-specific variables in your cdk.json or in your operating system's environment settings.

This code checks the environment variable ENV and provisions different S3 buckets based on whether the environment is production or development.

## About

Place the code for this article in this repository.
The original article export is saved as `article.md`.

## Files

Add your `.ipynb`, `.py`, `.yaml`, `.js`, `.ts`, or other project files here.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).