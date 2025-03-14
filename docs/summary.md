# Table of contents

* [🍁 Home](README.md)
* [🔍 Overview](overview/README.md)
  * [Architecture](overview/architecture.md)
* [🆔 ID Lifecycle Management](id-lifecycle-management.md)
  * [ID Schema](id-schema.md)
  * [Identifiers](identifiers.md)
  * [Anonymous Profiling Support](anonymous-profiling-support.md)
* [✅ ID Authentication](id-authentication.md)
* [🔐 Privacy and Security](privacy-and-security.md)
  * [Data Protection](data-protection.md)
  * [Privacy](privacy.md)
* [🤳 Biometrics](biometrics.md)
  * [ABIS](abis.md)
  * [ABIS API](abis-api.md)
  * [Biometric SDK](biometric-sdk.md)
  * [Biometric Devices](biometric-devices.md)
  * [FTM](ftm.md)
  * [MDS Specificiation](https://docs.mosip.io/1.1.5/biometrics/mosip-device-service-specification)
  * [Biometric Specification](https://docs.mosip.io/1.1.5/biometrics/biometric-specification)
  * [CBEFF](cbeff-xml.md)
  * [Compliance Tool Kit](https://docs.mosip.io/compliance-tool-kit/)
* [👨‍💼 Partners](partners.md)
* [⚒️ Modules](modules/README.md)
  * [Administration](administration.md)
    * [Admin Portal User Guide](admin-portal-user-guide.md)
    * [Admin Services Developers Guide](admin-services-developers-guide.md)
    * [Masterdata Guide](masterdata-guide.md)
  * [Android Registration Client](android-registration-client.md)
    * [Configuration Guide](android-registration-client-configuration.md)
    * [Developer Guide](android-registration-client-developer-guide.md)
    * [User Guide](android-registration-client-user-guide.md)
  * [Automation Testing](automation-testing.md)
  * [Artifactory](artifactory.md)
  * [Commons](commons.md)
    * [Commons Developers Guide](commons-developer-guide.md)
    * [Audit Manager Developers Guide](audit-manager-developer-guide.md)
    * [OpenID-Bridge Developers Guide](openid-bridge-developer-guide.md)
  * [Datashare](datashare.md)
  * [ID Authentication Services](id-authentication-services.md)
    * [ID Authentication Demographic Data Normalization](normalization-reference-impl.md)
    * [ID Authentication Service Developers Guide](id-authentication-service-developer-guide.md)
    * [ID Authentication OTP Service Developer Guide](id-authentication-otp-service-developer-guide.md)
    * [ID Authentication Internal Service Developers Guide](id-authentication-internal-service-developer-guide.md)
  * [ID Repository](id-repository.md)
    * [Credential Request Generator Service Developers Guide](id-repository-credential-request-generator-service-developer-guide.md)
    * [Identity Service Developers Guide](id-repository-identity-service-developer-guide.md)
    * [VID Service Developers Guide](id-repository-vid-service-developer-guide.md)
    * [.well-known](well-known.md)
    * [Custom Handle Implementation Guide](modules/id-repository/custom-handle.md)
  * [Inji](https://docs.mosip.io/inji)
  * [Inji User Guide](inji-user-guide.md)
  * [Keycloak](keycloak.md)
  * [Key Manager](keymanager.md)
    * [Keys](keys.md)
    * [Hadware Security Module (HSM)](hsm.md)
    * [Key Manager Developers Guide](keymanager-developer-guide.md)
  * [Mock Services](mock-services.md)
  * [Module Configurations](module-configuration.md)
  * [Packet Manager](packet-manager.md)
    * [Registration Packet Structure](registration-packet-structure.md)
  * [Partner Management](partner-management-services.md)
    * [Partner Policies](partner-policies.md)
    * [Partner Management Portal](partner-management-portal.md)
    * [Auth Partner](auth-credential-partner.md)
    * [Device Provider](device-provider-partner.md)
    * [Foundational Trust Provider](ftm-partner.md)
    * [Partner Management Services Developers Guide](partner-management-services-developer-setup.md)
  * [Pre-registration](pre-registration.md)
    * [Pre-registration User Guide](pre-registration-user-guide.md)
    * [Pre-registration UI Specifications](pre-registration-ui-specifications.md)
    * [Pre-registration Developers Guide](pre-registration-developer-setup.md)
  * [Reference Implementations](reference-implementations.md)
  * [Registration Client](registration-client.md)
    * [Operator Onboarding](operator-onboarding.md)
    * [Registration Client Installation Guide](registration-client-installation-guide.md)
    * [Registration Client User Guide](registration-client-user-guide.md)
    * [Registration Client Configuration Guide](registration-client-configuration.md)
    * [Registration Client UI Specifications](registration-client-ui-specifications.md)
    * [Registration Client Settings page](registration-client-settings-page.md)
    * [Registration Client Developers Guide](registration-client-developers-guide.md)
    * [Telemetry from Registration Client](registration-client-tus-protocol.md)
  * [Registration Processor](registration-processor.md)
    * [Manual Adjudication and Verification](manual-adjudication-and-verification.md)
    * [Registration Processor Developers Guide](registration-processor-developers-guide.md)
  * [Reporting](reporting.md)
  * [Resident Portal](resident-services.md)
    * [Resident Services Developers Guide](resident-services-developer-guide.md)
    * [Resident Services UI Developers Guide](resident-services-ui-developer-guide.md)
    * [Resident Portal Configuration Guide](resident-portal-configuration-guide.md)
    * [Resident Services Deployment Guide](resident-services-deployment-guide.md)
    * [Configuring Resident OIDC Client](resident-services-configure-resident-OIDC-client.md)
    * [Resident Portal User Guide](resident-portal-user-guide.md)
  * [Persistence](persistence.md)
    * [Postgres DB](postgres-db.md)
    * [Object Store](object-store.md)
  * [WebSub](websub.md)
    * [WebSub Developers Guide](websub-developer-guide.md)
* [👨‍💻 Technology Stack](technology-stack.md)
* [🛃 Deployment](deploymentnew/README.md)
  * [Getting Started](deploymentnew/getting-started.md)
  * [V2 installation](deploymentnew/v2-installer.md)
  * [V3 installation](deploymentnew/v3-installation.md)
    * [On-Prem Installation Guidelines](deploymentnew/on-prem-installation-guidelines.md)
    * [On-Prem without DNS Installation Guidelines](deploymentnew/on-prem-without-dns.md)
    * [AWS Installation Guidelines](aws-installation-guidelines-new.md)
    * [Testrig](deploymentnew/testrig.md)
    * [MOSIP External Dependencies](deploymentnew/mosip-external-dependencies.md)
    * [MOSIP Modules Deployment](deploymentnew/mosip-modules-deployment.md)
  * [Helm Charts](helm-charts.md)
  * [Versioning](deployment/versioning.md)
  * [Wireguard](deployment/wireguard/README.md)
    * [Wireguard Bastion Host](deployment/wireguard/wireguard-bastion.md)
    * [Wireguard Administrator's Guide](https://github.com/mosip/k8s-infra/blob/main/docs/wireguard-administrators-guide.md)
    * [Wireguard Client Installation Guide](https://github.com/mosip/documentation/blob/1.2.0/docs/wireguard-client-installation-guide.md)
  * [Production](deployment/production/README.md)
    * [Server Hardware Requirements](deployment/production/server-hardware-requirements.md)
    * [Production Hardening Guide](deployment/production/production-hardening-guide.md)
    * [Administration Using Rancher](deployment/production/rancher.md)
* [🌍 Country Implementation](country-implementation.md)
* [🔄 Integrations](integrations/README.md)
  * [MOSIP OpenCRVS](mosip-opencrvs-integration.md)
  * [MOSIP e-Manas](mosip-emanas-integration.md)
  * [Digital Signature](integrations/digital-signature.md)
  * [MOSIP Token Seeder](mosip-token-seeder.md)
    * [MTS Versions](mts-versions.md)
      * [Version 1.0.0](mts1.0-release-notes.md)
      * [Version 1.0.1](mts-version-1.0.1.md)
      * [Version 1.1.0 (WIP)](integrations/mosip-token-seeder/mts-versions/mts1.1.0-release-notes.md)
    * [MTS Developer Guides](integrations/mosip-token-seeder/mts-developer-guides/README.md)
      * [Developer Guide 1.0](integrations/mosip-token-seeder/mts-developer-guides/mosip-token-seeder-api.md)
      * [Developer Guide 1.1](integrations/mosip-token-seeder/mts-developer-guides/mosip-token-seeder-api-1.md)
    * [MTS Connector](mts-odk-importer.md)
    * [OpenG2P-registry MTS Connector](integrations/mosip-token-seeder/openg2p-registry-mts-connector.md)
  * [MOSIP eSignet](e-signet.md)
    * [ID Authentication](integrations/e-signet/ida.md)
    * [Partner Management](integrations/e-signet/partner-management.md)
    * [Configuring eSignet](integrations/esignet/configuring-esignet.md)
  * [Print Service Integration](print-service.md)
    * [Verified Credentials](verified-credentials.md)
* [🛗 Community](community/README.md)
  * [Contributions](contributions.md)
  * [Code Contributions](code-contributions.md)
  * [Code of Conduct](code-of-conduct.md)
  * [MOSIP Release Process](release-process.md)
    * [Go/No Go Release Checklist](go-nogo.md)
  * [MOSIP Branching Strategy](mosip-branching-strategy.md)
  * [Community Calendars](community/community-calendar.md)
* [📖 Releases](releases.md)
  * [Android Registration Client 0.9.0](release-notes-android-reg-client-0.9.0.md)
    * [Test Report](arc-0.9.0-test-report.md)
  * [1.2.0.1](release/1.2.0.1/release-notes-1.2.0.1.md)
    * [Test Report](release/1.2.0.1/test-report-1.2.0.1.md)
  * [1.2.0.1-B4 (Beta)](release/1.2.0.1/release-notes-1.2.0.1-b4.md)
    * [Test Report](release/1.2.0.1/test-report-1.2.0.1-b4.md)
  * [Android Registration Client DP1](release-notes-android-reg-client-dp1.md)
  * [Resident Services DP1](release-notes-resident-portal-dp1.md)
  * [1.2.0.1-B3 (Beta)](release/1.2.0.1/release-notes-1.2.0.1-b3.md)
    * [Test Report](release/1.2.0.1/test-report-1.2.0.1-b3.md)
  * [1.2.0.1-B2 (Beta)](release/1.2.0.1/release-notes-1.2.0.1-b2.md)
  * [1.2.0.1-B1 (Beta)](release/1.2.0.1/release-notes-1.2.0.1-beta.md)
    * [Functional Test Report](release/1.2.0.1/functional-test-report-B1.md)
    * [Sonar Report](release/1.2.0.1/sonar-report-B1.md)
  * [1.2.0](release/1.2.0/release-notes.md)
    * [Enhancements](release/1.2.0/enhancements.md)
    * [Functional Test Report](release/1.2.0/functional-test-report.md)
    * [Sonar Scan Report](release/1.2.0/sonar-scan-report.md)
    * [Performance Test Report](release/1.2.0/performance-report/performance-test-report.md)
    * [Security Test Report](release/1.2.0/security-test-report.md)
    * [Feature Health Report](release/1.2.0/feature-health-report.md)
* [📋 Adopting LTS 1.2.0](adopting-lts-1.2.0.md)
* [🈴 Upgrade Runbook](upgrade-runbook.md)
  * [Deployment Architecture Upgrade](upgrade-deployment-architecture.md)
  * [Platform Upgrade](upgrade-platform.md)
  * [Additional Information](upgrade-runbook/mock-services/README.md)
    * [Handling Duplicate Entries](upgrade-runbook/mock-services/upgrade-db-script-error.md)
    * [Adapting Changes in Administration Roles](upgrade-runbook/mock-services/upgrade-admin-services-roles-guide.md)
    * [Identifying Applicant Type](upgrade-runbook/mock-services/upgrade-applicant-typemvel-scriptmigration.md)
    * [Changes in Camel Route](upgrade-runbook/mock-services/upgrade-camel-route-changes.md)
    * [Changes in Role Management based on Client IDs](upgrade-runbook/mock-services/upgrade-changes-in-role-management.md)
    * [Handling Case Insensitive Duplicated User Details](upgrade-runbook/mock-services/upgrade-handling-case-insensitive-duplicates.md)
    * [Managing Unequal Certificates](upgrade-runbook/mock-services/upgrade-handling-unequal-certificates.md)
    * [Update Identity Mapping file in Configuration](upgrade-runbook/mock-services/upgrade-identity-json-file.md)
    * [New Datashare Properties](upgrade-runbook/mock-services/upgrade-new-datashare-properties.md)
    * [Handling Non-Recoverable Packets](upgrade-runbook/mock-services/upgrade-non-recoverable-packets.md)
    * [Partners' Certificate Expired](upgrade-runbook/mock-services/upgrade-partner-certificate-expired.md)
    * [Handling Partner Organization Name Mismatch Issue](upgrade-runbook/mock-services/upgrade-partner-organization-name.md)
    * [Pre-Registration UI Upgrade](upgrade-runbook/mock-services/upgrade-prereg-ui-specifications.md)
    * [Registration Client Upgrade](upgrade-runbook/mock-services/upgrade-registration-client.md)
    * [Guide to Reprocess Packets Manually](upgrade-runbook/mock-services/upgrade-regproc-reprocessing.md)
* [👾 Test Automation](test-automation/README.md)
  * [DSL Test Rig Automation](test-automation/dsl-test-rig-automation.md)
  * [UI Test Rig Automation](test-automation/ui-test-rig-automation.md)
  * [API Test Rig Automation](test-automation/api-test-rig-automation.md)
* [📚 MOSIP Support Policy](support-policy.md)
* [📫 Sandbox Details](sandbox-details.md)
* [🗳️ Collab Environment Setup Guides](collab-getting-started-guide.md)
  * [Inji](collab-inji-setup-guide.md)
  * [eSignet](collab-esignet-setup-guide.md)
  * [Pre-registration](collab-pre-registration-guide.md)
  * [Registration Client](collab-reg-client-setup-guide.md)
  * [Resident Portal](collab-resident-portal-guide.md)
  * [Partner Management Portal](collab-pmp-guide.md)
  * [Android Registration Client](collab-android-reg-client.md)
* [🛣️ Roadmap](roadmap.md)
  * [Roadmap 2023-2024](roadmap-2023-2024.md)
  * [Roadmap 2024-2025](roadmap-2024-2025.md)
* [❗ MOSIP Documentation Style Guide](mosip-documentation-style-guide.md)
* [📩 License](license.md)
* [API](https://mosip.github.io/documentation/1.2.0/1.2.0.html)
* [Documentation for 1.1.5](https://docs.mosip.io/1.1.5)
