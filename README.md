# Dell Servers (dell-servers)

APIs for managing and monitoring Dell PowerEdge servers and infrastructure, including the iDRAC Redfish out-of-band management interface, OpenManage Enterprise centralized console and its modular, power, support, and VMware integrations, telemetry streaming, the Lifecycle Controller, RACADM, and the legacy WSMan interface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Hardware, Infrastructure, Management, Monitoring, Servers

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Dell iDRAC Redfish REST API

Integrated Dell Remote Access Controller REST API for server management, monitoring, and configuration. Builds on the DMTF Redfish standard for out-of-band server lifecycle management of Dell PowerEdge servers, including inventory, health, power control, BIOS configuration, virtual media, firmware updates, event subscriptions, and telemetry.

- **Base URL:** https://{idrac-ip}/redfish/v1
- **Human URL:** https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller

#### Properties

- [Documentation](https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller)
- [OpenAPI](openapi/dell-servers-idrac-redfish-openapi.yml)
- [Rules](rules/dell-servers-idrac-redfish-rules.yml)
- [Capabilities](capabilities/dell-servers-idrac-redfish-capabilities.yml)

### Dell OpenManage Enterprise API

REST API for centralized management of Dell EMC servers, chassis, and storage. Provides a comprehensive console for discovery, inventory, monitoring, alerting, jobs, configuration templates, firmware compliance baselines, and reporting across Dell PowerEdge infrastructure at scale.

- **Base URL:** https://{ome-server}/api
- **Human URL:** https://www.dell.com/support/kbdoc/en-us/000175879/support-for-openmanage-enterprise

#### Properties

- [Documentation](https://www.dell.com/support/manuals/en-us/dell-openmanage-enterprise/ome_p_api_guide/preface?guid=guid-82bcb773-392d-43a4-bdfa-431dd06a06f4&lang=en-us)
- [OpenAPI](openapi/dell-servers-openmanage-enterprise-openapi.yml)
- [Rules](rules/dell-servers-openmanage-enterprise-rules.yml)
- [Capabilities](capabilities/dell-servers-openmanage-enterprise-capabilities.yml)

### Dell OpenManage Enterprise Modular API

RESTful API for managing Dell PowerEdge MX7000 modular chassis and its components including compute sleds, network devices, IOMs, and storage. OME-Modular shares a common codebase with OpenManage Enterprise and supports multi-chassis management with up to 20 chassis per group.

- **Base URL:** https://{omem-server}/api
- **Human URL:** https://www.dell.com/support/manuals/en-us/openmanage-enterprise-modular/omem_2.00.00_api/openmanage-enterprise-modular-edition

### Dell OpenManage Enterprise Power Manager API

RESTful API for monitoring and managing power consumption, thermal conditions, and energy costs across Dell PowerEdge server infrastructure. Power Manager is a plug-in to the OpenManage Enterprise console that provides power policies, capping, and reporting capabilities.

- **Base URL:** https://{ome-server}/api
- **Human URL:** https://developer.dell.com/apis/5708/versions/3.0/docs/0.1%20Introduction-to-PMP-API.md

### Dell OpenManage Enterprise SupportAssist API

RESTful API for the OpenManage Enterprise SupportAssist plug-in that enables proactive and predictive monitoring of Dell PowerEdge servers. SupportAssist automates support case creation and parts dispatch for servers with ProSupport and ProSupport Plus entitlements.

- **Base URL:** https://{ome-server}/api
- **Human URL:** https://developer.dell.com/apis/2848/versions/1.2

### Dell OpenManage Integration for VMware vCenter API

RESTful API for the OpenManage Integration for VMware vCenter (OMIVV), enabling automation of Dell PowerEdge server management within VMware environments. The API is compliant with OpenAPI Specification 3.0.0 and supports firmware updates, inventory, and monitoring tasks.

- **Base URL:** https://{omivv-server}/api
- **Human URL:** https://www.dell.com/support/manuals/en-us/openmanage-integration-vmware-vcenter/omivv_5.4_api/overview

### Dell iDRAC Telemetry Streaming API

Server-Sent Events (SSE) streaming API for real-time telemetry data from Dell PowerEdge servers via iDRAC. Provides continuous metric reports including power statistics, CPU and memory metrics, thermal sensor data, NIC statistics, and PSU metrics using the Redfish TelemetryService.

- **Base URL:** https://{idrac-ip}/redfish/v1/SSE
- **Human URL:** https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/server-sent-events

### Dell Lifecycle Controller Remote Services API

Standards-based interface for remote deployment, configuration, and updates of Dell PowerEdge servers. Lifecycle Controller Remote Services supports WSMAN and Redfish management interfaces for bare-metal provisioning and one-to-many operating system deployments.

- **Base URL:** https://{idrac-ip}/wsman
- **Human URL:** https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.4-series/idrac_3.40.40.40_lc_re_qsg/about-lifecycle-controller-api

### Dell RACADM CLI

Command-line interface for Dell Remote Access Controller Administration. RACADM provides local and remote command-line access to iDRAC for scripting and automating server configuration, monitoring, and management tasks.

- **Human URL:** https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.x-series/idrac9_racadm_pub/

### Dell WSMan API

Web Services Management API for Dell server hardware management. WSMan provides a SOAP-based interface for managing server configuration, BIOS, RAID, NIC, and HBA settings on Dell PowerEdge servers through iDRAC.

- **Base URL:** https://{idrac-ip}/wsman
- **Human URL:** https://www.dell.com/support/kbdoc/en-us/000178046/how-to-use-the-wsman-interface-on-idrac

## Common Properties

- [Developer Portal](https://developer.dell.com/)
- [Getting Started](https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v6.x-series/smog_26.0/idrac-restful-apis-redfish-standards-based)
- [Documentation](https://www.dell.com/support/product-details/en-us/product/dell-openmanage-enterprise/resources/manuals)
- [Support](https://www.dell.com/support)
- [Community](https://www.dell.com/community/)
- [Blog](https://www.dell.com/community/en/topics/developer-blogs)
- [Terms of Service](https://i.dell.com/sites/csdocuments/Legal_Docs/en/us/api-terms-of-use_en.pdf)
- [Privacy Policy](https://www.dell.com/en-us/lp/legal/policies-privacy)
- [Website](https://www.dell.com/en-us/lp/dt/open-manage)
- [GitHub Organization](https://github.com/dell)
- [SDKs](https://developer.dell.com/apis/)
- [JSON-LD](json-ld/dell-servers-context.jsonld)
- [Vocabulary](vocabulary/dell-servers-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
