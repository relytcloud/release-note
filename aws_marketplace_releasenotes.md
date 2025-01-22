# Relyt Data Cloud on AWS Marketplace: Release Notes

## Overview
Relyt is a new-generation multimodal intelligent cloud-native data warehouse. Built on the latest cloud computing and AI technologies, Relyt features a groundbreaking data-centric multimodal storage, open heterogeneous computing, integrated real-time and batch processing, and adaptive hybrid workload architecture. It helps customers build an integrated, cost-effective, and versatile data platform service accessible to everyone. Relyt can be widely used for traditional ETL data processing, real-time analytics, and the latest GenAI (Generative AI) foundational data storage and computation scenarios.

Please visit the following link for more information:
https://aws.amazon.com/marketplace/pp/prodview-sj3gjqpgqdqq4

## Release Notes
### v1.50.0
- Added support for the `DISCARD ALL` syntax.

### v1.45.0
- Fixed an issue with JDBC parameters exceeding 9.
- Optimized Glue access to reduce multiple access attempts.

### v1.31.0
- Enhanced error handling by exposing configuration errors to users.

### v1.29.0
- Added support for user-defined external ID.

### v1.26.0
- Removed restrictions on constant folding.
- Support role mapping.

### v1.25.0
- Improved exception handling to provide better visibility for users.
- Introduced the LakeFormation access control module, including support for Delta Lake.
- Added Stage Connector functionality.

### v1.18.0
- Enhanced performance for the `SHOW TABLES` command.
- Introduced support for Delta Lake.
- Initial release on AWS Marketplace.

