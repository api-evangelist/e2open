# E2open (e2open)

E2open (https://www.e2open.com/) provides supply chain software with a connected network and SaaS platform that help businesses seize opportunities, predict disruptions, and drive efficiency and sustainability across global supply chains. The platform connects more than 400,000 manufacturing, logistics, channel, and distribution partners and tracks billions of transactions annually.

This repository tracks the APIs, OpenAPI specifications, JSON Schemas, JSON-LD contexts, and other developer resources associated with E2open and its INTTRA ocean shipping platform.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/apis.yml

## APIs

### E2open Supply Chain Platform API

E2open's supply chain platform APIs enable supply chain event management, transportation management, customs compliance, and end-to-end shipment visibility. The platform supports REST/JSON, XML, and EDI protocols.

- **Human URL:** https://www.e2open.com/
- **Base URL:** https://api.e2open.com
- **Tags:** Supply Chain, Logistics, Visibility, Trade Management, REST, JSON
- **Documentation:** https://www.e2open.com/

### INTTRA Ocean Execution API

INTTRA (now part of E2open) provides ocean execution APIs for the world's largest multi-carrier e-commerce platform for global shipping. The RESTful API uses HTTPS with JSON for booking, ocean schedules, rates, and visibility/track and trace products. Authentication requires a token obtained from the identity service before making API requests.

- **Human URL:** https://apidocs.inttra.com/
- **Base URL:** https://api.inttra.com
- **Tags:** Booking, JSON, Logistics, Ocean Shipping, REST, Supply Chain, Track and Trace
- **Documentation:** https://apidocs.inttra.com/
- **Getting Started:** https://www.inttra.com/services/integration/
- **OpenAPI:** [inttra-ocean-execution-openapi.yml](./openapi/inttra-ocean-execution-openapi.yml)

### E2open Transportation Management API

E2open Transportation Management API provides appointment scheduling, carrier integration, and real-time rating capabilities. REST endpoints allow carriers to POST documents, retrieve current rates, manage load stop details, and communicate appointment status updates with supply chain stakeholders.

- **Human URL:** https://marketplace.e2open.com/
- **Base URL:** https://api.e2open.com
- **Tags:** Appointment Scheduling, Carrier Integration, Logistics, Supply Chain, Transportation
- **Documentation:** https://marketplace.e2open.com/product/api-implementation/

## Machine-Readable Artifacts

- **OpenAPI:** [openapi/inttra-ocean-execution-openapi.yml](./openapi/inttra-ocean-execution-openapi.yml)
- **JSON Schema:** [json-schema/e2open-shipment-schema.json](./json-schema/e2open-shipment-schema.json)
- **JSON-LD Context:** [json-ld/e2open-context.jsonld](./json-ld/e2open-context.jsonld)

## Common Properties

- [Website](https://www.e2open.com/)
- [Portal (INTTRA)](https://apidocs.inttra.com/)
- [Documentation](https://www.e2open.com/e2open-network-connectivity/)
- [Getting Started](https://marketplace.e2open.com/)
- [Support](https://knowledge.e2open.com/knowledgecenter/inttra-resources/)
- [Privacy Policy](https://www.e2open.com/privacy-policy/)
- [Terms of Service](https://www.inttra.com/legal/)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
