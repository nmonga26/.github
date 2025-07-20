# ONDC Repository Topics Guide

## Overview

This guide defines the standardized topics system for all repositories in the ONDC-Official organization. Consistent topic usage enables better discovery, categorization, and management of repositories.

## Repository Topics System

GitHub Topics provide a powerful way to categorize and enhance repository discoverability. Topics act as tags that help organize repositories by technology, purpose, or business domain.

## Common Topic Categories

### Technology Stack

- `react` - React.js framework
- `vue` - Vue.js framework
- `angular` - Angular framework
- `nodejs` - Node.js runtime
- `python` - Python language
- `java` - Java language
- `javascript` - JavaScript language
- `typescript` - TypeScript language
- `golang` - Go language
- `rust` - Rust language
- `kotlin` - Kotlin language
- `swift` - Swift language

### Application Type

- `frontend` - Frontend applications
- `backend` - Backend services
- `api` - API services
- `microservice` - Microservice architecture
- `mobile-app` - Mobile applications
- `web-application` - Web applications
- `desktop-app` - Desktop applications
- `cli-tool` - Command line tools
- `library` - Reusable libraries
- `sdk` - Software Development Kit
- `plugin` - Plugin/Extension
- `widget` - UI Widget/Component

### Business Domain

- `buyer-app` - Buyer-side applications
- `seller-app` - Seller-side applications
- `admin-portal` - Administrative interfaces
- `analytics` - Analytics and reporting
- `gateway` - Gateway services
- `registry` - Registry services
- `payment` - Payment processing
- `logistics` - Logistics management
- `inventory` - Inventory management
- `catalog` - Product catalog
- `search` - Search functionality
- `order-management` - Order processing

### Environment/Status

- `production` - Production-ready
- `staging` - Staging environment
- `development` - Under development
- `archived` - No longer maintained
- `deprecated` - Deprecated, use alternative
- `experimental` - Experimental features
- `beta` - Beta version
- `alpha` - Alpha version
- `stable` - Stable release
- `legacy` - Legacy system

### Purpose/Classification

- `reference-app` - Reference implementation
- `library` - Reusable library
- `tool` - Development/operational tool
- `documentation` - Documentation repository
- `template` - Project template
- `example` - Example implementation
- `tutorial` - Tutorial/learning resource
- `specification` - Specification document
- `test-suite` - Testing framework
- `benchmark` - Performance benchmark

## Complete Topics Taxonomy

### Categories (Primary)

**Core Categories:**
- `specifications` - Protocol and API specifications
- `reference-apps` - Reference implementations
- `automation-testing` - Testing automation tools
- `mock-sandbox` - Mock servers and sandboxes
- `adaptors` - Platform adaptors and connectors
- `sdks` - Software Development Kits
- `infrastructure` - Infrastructure and DevOps
- `documentation` - Documentation and guides
- `logs` - Logging and monitoring

**Additional Categories:**
- `tools` - Development and operational tools
- `templates` - Project templates
- `examples` - Example implementations
- `utilities` - Utility libraries
- `security` - Security tools and policies

### Subcategories

**Application Subcategories:**
- `buyer-apps` - Buyer applications
- `seller-apps` - Seller applications
- `logistics-apps` - Logistics applications
- `payment-apps` - Payment applications
- `gateway-apps` - Gateway applications

**Service Subcategories:**
- `ecommerce` - E-commerce services
- `core-framework` - Core framework components
- `services` - Microservices
- `mock-servers` - Mock server implementations
- `validation` - Validation services
- `scoring` - Scoring and rating services

### Domain Tags

**Primary Domains:**
- `retail` - Retail and e-commerce
- `logistics` - Logistics and delivery
- `agriculture` - Agriculture sector
- `healthcare` - Healthcare services
- `financial` - Financial services
- `mobility` - Transportation and mobility
- `education` - Education sector

**Extended Domains:**
- `hospitality` - Hotels and hospitality
- `travel` - Travel and tourism
- `energy` - Energy sector
- `manufacturing` - Manufacturing
- `services` - General services
- `government` - Government services

### Type Tags

**Application Types:**
- `frontend` - Frontend application
- `backend` - Backend service
- `mobile` - Mobile application
- `api` - API service
- `library` - Software library
- `tool` - Development tool
- `documentation` - Documentation

**Technical Types:**
- `microservice` - Microservice
- `monolith` - Monolithic application
- `serverless` - Serverless function
- `container` - Containerized application
- `database` - Database-related
- `messaging` - Messaging service
- `cache` - Caching solution

### Status Tags

- `production` - Production-ready
- `beta` - Beta testing
- `alpha` - Alpha testing
- `experimental` - Experimental
- `deprecated` - Deprecated
- `archived` - Archived
- `maintenance` - Maintenance mode
- `active` - Actively developed
- `stable` - Stable release
- `preview` - Preview release

### Technology Tags

**Languages:**
- `javascript` - JavaScript
- `typescript` - TypeScript
- `python` - Python
- `java` - Java
- `go` - Go
- `rust` - Rust
- `kotlin` - Kotlin
- `swift` - Swift
- `csharp` - C#
- `php` - PHP

**Frameworks:**
- `react` - React
- `vue` - Vue.js
- `angular` - Angular
- `nextjs` - Next.js
- `express` - Express.js
- `spring` - Spring Framework
- `django` - Django
- `flask` - Flask
- `fastapi` - FastAPI

**Databases:**
- `postgresql` - PostgreSQL
- `mysql` - MySQL
- `mongodb` - MongoDB
- `redis` - Redis
- `elasticsearch` - Elasticsearch

**Infrastructure:**
- `docker` - Docker
- `kubernetes` - Kubernetes
- `aws` - AWS
- `gcp` - Google Cloud
- `azure` - Azure

## Example Implementations

### Example 1: Reference Buyer Frontend App

**Repository:** `ref-app-buyer-frontend`

**Topics:**
- `reference-apps`
- `buyer-apps`
- `frontend`
- `react`
- `javascript`
- `production`
- `retail`
- `reference-app`
- `buyer-app`
- `frontend`
- `react`
- `web-application`

### Example 2: Seller Backend API

**Repository:** `biap-app-ui-front`

**Topics:**
- `reference-apps`
- `buyer-apps`
- `frontend`
- `react`
- `production`
- `retail`

### Example 3: Logistics Adaptor

**Repository:** `logistics-adaptor-api`

**Topics:**
- `adaptors`
- `logistics-apps`
- `api`
- `nodejs`
- `beta`
- `logistics`

### Example 4: Python SDK

**Repository:** `ondc-sdk-python`

**Topics:**
- `sdks`
- `library`
- `python`
- `stable`
- `sdk`
- `python`
- `library`

## Repository Description Format

### Template

```
[CATEGORY/SUBCATEGORY] Brief description |  {Status} |  {Domain}
```

### Examples

- **biap-app-ui-front**: `[REFERENCE-APPS/BUYER] React-based buyer application frontend |  Production |  Retail`
- **shopify-adaptor**: `[ADAPTORS/ECOMMERCE] Shopify platform integration for ONDC |  Production | Platform: Shopify`
- **ondc-sdk-python**: `[SDKS/CORE] Python SDK for ONDC protocol implementation |  Stable | Language: Python`
- **log-validation-utility**: `[TOOLS/VALIDATION] Log validation and verification tool |  Beta |  CLI`

## Repository Search URLs

### By Category

**All reference apps:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:reference-apps
```

**All SDKs:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:sdks
```

**All specifications:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:specifications
```

### By Subcategory

**Buyer apps only:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:buyer-apps
```

**Seller apps only:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:seller-apps
```

### By Status

**Production-ready repositories:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:production
```

**Beta repositories:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:beta
```

### By Domain

**Retail domain repos:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:retail
```

**Logistics domain repos:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:logistics
```

### Combined Searches

**Production-ready SDKs:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:sdks+topic:production
```

**React-based buyer apps:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:buyer-apps+topic:react
```

**Frontend reference apps in production:**
```
https://github.com/orgs/ONDC-Official/repositories?q=topic:reference-apps+topic:frontend+topic:production
```

## Best Practices

1. **Use Multiple Topics**: Apply 5-10 relevant topics to maximize discoverability
2. **Be Consistent**: Use standardized topics across all repositories
3. **Update Regularly**: Keep topics current with repository changes
4. **Include All Levels**: Use category, subcategory, type, tech, and status tags
5. **Domain Specificity**: Always include relevant domain tags
6. **Technology Stack**: Include all major technologies used
7. **Status Accuracy**: Keep status tags updated to reflect current state

## Topic Management Guidelines

### Adding Topics

1. Navigate to repository settings
2. Add topics in the "Topics" section
3. Use lowercase, hyphenated format
4. Apply relevant topics from each category

### Topic Limits

- Maximum 20 topics per repository
- Prioritize most relevant topics
- Balance between categories

### Regular Review

- Review topics quarterly
- Update status tags as needed
- Add new technology tags when stack changes
- Archive repositories with `archived` tag

## Compliance Checklist

For each repository, ensure:

- [ ] At least one category tag
- [ ] Appropriate subcategory tag(s)
- [ ] Type classification tag
- [ ] Current status tag
- [ ] Relevant domain tag(s)
- [ ] Technology/framework tags
- [ ] Purpose classification tag
- [ ] Updated repository description
- [ ] Consistent naming convention
- [ ] Regular topic review schedule
