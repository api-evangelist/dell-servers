# Dell Servers (dell-servers)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for managing and monitoring Dell PowerEdge servers and infrastructure, including the iDRAC Redfish out-of-band management interface, OpenManage Enterprise centralized console and its modular, power, support, and VMware integrations, telemetry streaming, the Lifecycle Controller, RACADM, and the legacy WSMan interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Hardware
- Infrastructure
- Management
- Monitoring
- Servers

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Dell iDRAC Redfish REST API

Integrated Dell Remote Access Controller REST API for server management, monitoring, and configuration. The iDRAC RESTful API builds upon the DMTF Redfish standard to provide a comprehensive interface for out-of-band server lifecycle management of Dell PowerEdge servers, including inventory, health monitoring, power control, BIOS configuration, virtual media, firmware updates, event subscriptions, and telemetry.

- **Human URL:** [https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller](https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller)
- **Base URL:** `https://{idrac-ip}/redfish/v1`

#### Tags

- BMC
- Hardware Monitoring
- Redfish
- Server Management

#### Properties

- [Documentation](https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller)
- [OpenAPI](openapi/dell-servers-idrac-redfish-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/dell-servers-idrac-redfish-rules.yml)
- [Capabilities](capabilities/dell-servers-idrac-redfish-capabilities.yml)
- [Authentication](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/redfish-authentication-and-authorization?guid=guid-d572792f-afd2-499a-bf12-38a6778b9bbc&lang=en-us)
- [Getting Started](https://developer.dell.com/apis/2978/versions/5.xx/docs/1.0Intro.md)
- [GitHub Repository](https://github.com/dell/iDRAC-Redfish-Scripting)

### Dell OpenManage Enterprise API

REST API for centralized management of Dell EMC servers, chassis, and storage. OpenManage Enterprise provides a comprehensive console for discovery, inventory, monitoring, alerting, jobs, configuration templates, firmware compliance baselines, and reporting across Dell PowerEdge infrastructure at scale.

- **Human URL:** [https://www.dell.com/support/kbdoc/en-us/000175879/support-for-openmanage-enterprise](https://www.dell.com/support/kbdoc/en-us/000175879/support-for-openmanage-enterprise)
- **Base URL:** `https://{ome-server}/api`

#### Tags

- Automation
- Enterprise Management
- Monitoring
- Orchestration

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/dell-openmanage-enterprise/ome_p_api_guide/preface?guid=guid-82bcb773-392d-43a4-bdfa-431dd06a06f4&lang=en-us)
- [OpenAPI](openapi/dell-servers-openmanage-enterprise-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/dell-servers-openmanage-enterprise-rules.yml)
- [Capabilities](capabilities/dell-servers-openmanage-enterprise-capabilities.yml)
- [GitHub Repository](https://github.com/dell/OpenManage-Enterprise)

### Dell OpenManage Enterprise Modular API

RESTful API for managing Dell PowerEdge MX7000 modular chassis and its components including compute sleds, network devices, IOMs, and storage. OME-Modular shares a common codebase with OpenManage Enterprise and supports multi-chassis management with up to 20 chassis per group.

- **Human URL:** [https://www.dell.com/support/manuals/en-us/openmanage-enterprise-modular/omem_2.00.00_api/openmanage-enterprise-modular-edition?guid=guid-fe459ff7-030b-4375-a6d5-9f0ab2278946&lang=en-us](https://www.dell.com/support/manuals/en-us/openmanage-enterprise-modular/omem_2.00.00_api/openmanage-enterprise-modular-edition?guid=guid-fe459ff7-030b-4375-a6d5-9f0ab2278946&lang=en-us)
- **Base URL:** `https://{omem-server}/api`

#### Tags

- Chassis Management
- Modular Infrastructure
- Multi-Chassis
- PowerEdge MX

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/openmanage-enterprise-modular/omem_2.00.00_api/openmanage-enterprise-modular-edition?guid=guid-fe459ff7-030b-4375-a6d5-9f0ab2278946&lang=en-us)
- [GitHub Repository](https://github.com/dell/OpenManage-Enterprise)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell OpenManage Enterprise Power Manager API

RESTful API for monitoring and managing power consumption, thermal conditions, and energy costs across Dell PowerEdge server infrastructure. Power Manager is a plug-in to the OpenManage Enterprise console that provides power policies, capping, and reporting capabilities.

- **Human URL:** [https://developer.dell.com/apis/5708/versions/3.0/docs/0.1%20Introduction-to-PMP-API.md](https://developer.dell.com/apis/5708/versions/3.0/docs/0.1%20Introduction-to-PMP-API.md)
- **Base URL:** `https://{ome-server}/api`

#### Tags

- Data Center
- Energy Efficiency
- Power Management
- Thermal Monitoring

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/openmanage-enterprise-power-manager/pmp_3.1_apiguide/about-this-document)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell OpenManage Enterprise SupportAssist API

RESTful API for the OpenManage Enterprise SupportAssist plug-in that enables proactive and predictive monitoring of Dell PowerEdge servers. SupportAssist automates support case creation and parts dispatch for servers with ProSupport and ProSupport Plus entitlements.

- **Human URL:** [https://developer.dell.com/apis/2848/versions/1.2](https://developer.dell.com/apis/2848/versions/1.2)
- **Base URL:** `https://{ome-server}/api`

#### Tags

- Alerting
- Predictive Analytics
- Proactive Monitoring
- Support

#### Properties

- [Documentation](https://developer.dell.com/apis/2848/versions/1.2)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell OpenManage Integration for VMware vCenter API

RESTful API for the OpenManage Integration for VMware vCenter (OMIVV), enabling automation of Dell PowerEdge server management within VMware environments. The API is compliant with OpenAPI Specification 3.0.0 and supports firmware updates, inventory, and monitoring tasks.

- **Human URL:** [https://www.dell.com/support/manuals/en-us/openmanage-integration-vmware-vcenter/omivv_5.4_api/overview](https://www.dell.com/support/manuals/en-us/openmanage-integration-vmware-vcenter/omivv_5.4_api/overview)
- **Base URL:** `https://{omivv-server}/api`

#### Tags

- Server Management
- vCenter Integration
- Virtualization
- VMware

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/openmanage-integration-vmware-vcenter/omivv_5.4_api/overview)
- [GitHub Repository](https://github.com/dell/omivv)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell iDRAC Telemetry Streaming API

Server-Sent Events (SSE) streaming API for real-time telemetry data from Dell PowerEdge servers via iDRAC. Provides continuous metric reports including power statistics, CPU and memory metrics, thermal sensor data, NIC statistics, and PSU metrics using the Redfish TelemetryService.

- **Human URL:** [https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/server-sent-events?guid=guid-fc87fd01-2cff-4ae0-9714-1bd712bb5ce3&lang=en-us](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/server-sent-events?guid=guid-fc87fd01-2cff-4ae0-9714-1bd712bb5ce3&lang=en-us)
- **Base URL:** `https://{idrac-ip}/redfish/v1/SSE`

#### Tags

- Monitoring
- Server-Sent Events
- Streaming
- Telemetry

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/server-sent-events?guid=guid-fc87fd01-2cff-4ae0-9714-1bd712bb5ce3&lang=en-us)
- [GitHub Repository](https://github.com/dell/iDRAC-Telemetry-Reference-Tools)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell Lifecycle Controller Remote Services API

Standards-based interface for remote deployment, configuration, and updates of Dell PowerEdge servers. Lifecycle Controller Remote Services supports WSMAN and Redfish management interfaces for bare-metal provisioning and one-to-many operating system deployments.

- **Human URL:** [https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.4-series/idrac_3.40.40.40_lc_re_qsg/about-lifecycle-controller-api?guid=guid-f7bcc1d3-46c1-4ec3-9a45-0f33d734585c&lang=en-us](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.4-series/idrac_3.40.40.40_lc_re_qsg/about-lifecycle-controller-api?guid=guid-f7bcc1d3-46c1-4ec3-9a45-0f33d734585c&lang=en-us)
- **Base URL:** `https://{idrac-ip}/wsman`

#### Tags

- Deployment
- Lifecycle Management
- Provisioning
- Remote Services

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.4-series/idrac_3.40.40.40_lc_re_qsg/about-lifecycle-controller-api?guid=guid-f7bcc1d3-46c1-4ec3-9a45-0f33d734585c&lang=en-us)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell RACADM CLI

Command-line interface for Dell Remote Access Controller Administration. RACADM provides local and remote command-line access to iDRAC for scripting and automating server configuration, monitoring, and management tasks.

- **Human URL:** [https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.x-series/idrac9_racadm_pub/](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.x-series/idrac9_racadm_pub/)

#### Tags

- Automation
- CLI
- Remote Management
- Scripting

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.x-series/idrac9_racadm_pub/)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dell WSMan API

Web Services Management API for Dell server hardware management. WSMan provides a SOAP-based interface for managing server configuration, BIOS, RAID, NIC, and HBA settings on Dell PowerEdge servers through iDRAC.

- **Human URL:** [https://www.dell.com/support/kbdoc/en-us/000178046/how-to-use-the-wsman-interface-on-idrac](https://www.dell.com/support/kbdoc/en-us/000178046/how-to-use-the-wsman-interface-on-idrac)
- **Base URL:** `https://{idrac-ip}/wsman`

#### Tags

- Hardware Management
- Legacy
- Web Services
- WSMan

#### Properties

- [Documentation](https://www.dell.com/support/kbdoc/en-us/000178046/how-to-use-the-wsman-interface-on-idrac)
- [Profile  Catalog](https://downloads.dell.com/solutions/dell-management-solution-resources/)
- [GitHub Repository](https://github.com/dell/DellPEWSMANTools)
- [Postman Collection](collections/dell-servers-idrac-redfish.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-idrac-redfish.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dell-servers-openmanage-enterprise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dell-servers-openmanage-enterprise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.dell.com/)
- [Getting Started](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v6.x-series/smog_26.0/idrac-restful-apis-redfish-standards-based?guid=guid-476c6603-818e-4e2e-82f0-699bde0c3a3c&lang=en-us)
- [Documentation](https://www.dell.com/support/product-details/en-us/product/dell-openmanage-enterprise/resources/manuals)
- [Support](https://www.dell.com/support)
- [Community](https://www.dell.com/community/)
- [Blog](https://www.dell.com/community/en/topics/developer-blogs)
- [Terms of Service](https://i.dell.com/sites/csdocuments/Legal_Docs/en/us/api-terms-of-use_en.pdf)
- [Privacy Policy](https://www.dell.com/en-us/lp/legal/policies-privacy)
- [Website](https://www.dell.com/en-us/lp/dt/open-manage)
- [Git Hub](https://github.com/dell)
- [S D Ks](https://developer.dell.com/apis/)
- [Sign Up](https://developer.dell.com/)
- [Login](https://developer.dell.com/)
- [JSON-LD](json-ld/dell-servers-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/dell-servers-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
