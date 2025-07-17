SC-900 - Microsoft Security, Compliance, and Identity Fundamentals Certification

**Skills at a glance**

- Describe the concepts of security, compliance, and identity (10–15%)
- Describe the capabilities of Microsoft Entra (25–30%)
- Describe the capabilities of Microsoft security solutions (35–40%)
- Describe the capabilities of Microsoft compliance solutions (20–25%)

**Material from Microsoft Learn:**

**Describe the concepts of security, compliance, and identity (10–15%):**

- _Shared responsibility model_

Identifies which security tasks are handled by the cloud provider and which are handled by the customer.

Customer is responsible for: Information and Data, Devices and Accounts and Identities.

- _Defence in depth_

Slows the advance of an attack.

Examples include physical, identity and access controls, network, and compute by closing certain ports.

CIA – Confidentiality, Integrity, and Availability

- _Zero Trust model_

Trust no one, verify everything.

Least privilege access.

Assume breach.

Identities, Devices, Applications, Data, Infrastructure and Networks.

- _Encryption and Hashing_

Symmetric encryption – Same key used to encrypt and decrypt.

Asymmetric encryption – Public key and private key pair.

Hashing – Algorithm to convert text to a unique fixed-length value called a hash.

- _Governance, risk, and compliance GRC concepts_

Framework for organisations to follow to ensure they are regulatory compliant. Includes, governance (set of rules, practises, processes), risk(identifying, assessing, responding) and compliance(countries laws or regulations).

- _Authentication and Authorisation_

Authentication – Proving someone is who they say they are.

Authorisation – Once authenticated, decide what the user can access.

- _Identity as the primary security perimeter_

Identity is considered a sole perimeter with work that is done remotely for example. It’s the first point of contact security wise.

- _Role of the identity provider_

The identity provider works as the Face ID for your iPhone for example. It ensures you are who you are and have access then lets the iPhone know to let you in.

Single-sign on(SSO) is when you sign in once and can access everything from then on.

- _Directory services and Active Directory_

Stores user information on who can access what essentially.

- _Concept of Federation_

A website trusting another website/linked. Signing into Facebook with your username and password then going to Microsoft Learn which has a trust relationship with Facebook so your password isn’t required again.

**Describe the capabilities of Microsoft Entra (25–30%):**

- _Describe Entra ID_

Microsoft’s cloud-based identity and access management service.

Allows employees to login and access the resources they need.

Tenant – Information about a single organisation resides.

Directory – Holds and organises resources for the tenant.

Multi-tenant – Organisations with multiple instances of Entra ID e.g. multiple subsidiaries.

- _Types of identities_

The different types of identities that can be assigned include user, workload identities, applications and service principals, managed identities, device, and groups.

- _Hybrid identities_

Syncing active directory identities into Entra ID

- _External identities_

Allows external users to access your applications and resources.

- _Authentication methods_

Passwords, SMS/Voice call, OATH(Open Authentication, one time passwords), biometrics.

- _Multifactor authentication_

Something you know, have, are.

- _Self-service password reset_

User resets their own password.

Cuts IT costs

- _Password protection and management capabilities_

Global banned password list – Constantly updated to stop known vulnerable passwords or phrases from being used.

Custom banned password list – Brand names, product names, locations

- _Conditional access_

After first sign on, conditional access determines whether the user can access what they’re trying to depending on location for example.

- _Global Secure Access in Microsoft Entra_

Microsoft Entra Internet Access – secures access to SaaS applications.

Microsoft Entra Private Access – provides users secure access to private corporate resources.

- _Microsoft Entra roles and role-based access control (RBAC)_

Role-based access controls only assign access to the user in which they can perform their job. For example, a finance employee does not need access to the work IT employee does or sees.

- _Microsoft Entra ID Governance_

Governs and automates who has access to what.

- _Access reviews_

Review who has access to what in case too many users are in privileged roles, business critical data access or confirm to group owners if they still need guests in their groups.

- _Entitlement engagement_

Enables organisations to manage the identity and access lifecycle at scale.

Automates request workflows, access assignments and reviews.

- _Privileged identity management_

Manage, control, and monitor access to important resources in your organisation.

- _Microsoft Entra ID protection_

Helps organisations detect, investigate, and remediate identity-based risks.

- _Microsoft Entra Permissions Management_

Cloud Infrastructure entitlement management (CIEM) product that provides comprehensive visibility and control over permissions for any identity and resource in Azure, AWS and Google cloud Platform.

- _Microsoft Entra Verified ID_

Managed verifiable credentials services based on open standards. Verified ID automates verification of identity credentials and enables privacy-protected interactions between organisations and users.

- _Microsoft Entra integration with Microsoft Security Copilot_

With Entra plug-in enabled within the browser, security analysts can get instant summary of occurrences, steps to remediate and mitigate for next time.

**Describe the capabilities of Microsoft security solutions (35–40%):**

- _Microsoft Security Copilot_

AI-powered, cloud-based security analysis tool that enables analysts to respond to threats quickly.

Assesses risk exposure almost instantly.

Stand-alone and embedded experience

Natural language processing (NLP) – Integration with other tools is used to allow for the machine to learn what is needed and how to interpret it.

- _Microsoft Security Copilot terminology_

Session – A particular conversation within Copilot

Prompt – Statement or question within a session

Capability – What Copilot does to solve part of a problem.

Plugin – Collection of capabilities by a resource.

Orchestrator – Coplots system to collate capabilities together to answer the user.

- _Microsoft Security Copilot enable_

Admins need to have either an Azure subscription, Azure owner or Azure contributor as a resource group level as a minimum.

You can provision capacity within Copilot which is recommended or through Azure portal.

To setup the default environment to perform admin tasks such as user usage monitoring you need to be either a Global Admin or Security Admins.

- _Azure DDoS protection_

Distributed Denial of Service (DDoS) – Overwhelms the resources on your applications and servers, making them unresponsive or slow for genuine users.

Volumetric – Flood the network layer with seemingly legit traffic, overwhelms bandwidth.

Protocol – Render a target inaccessible by exhausting serve resources.

Resource (Application) layer attacks – Target web application packets to disrupt the transmission of data between hosts.

DDoS protection – Helps protect applications and servers by analysing network traffic and discarding anything that looks like a DDoS attack.

- _Azure Firewall_

Managed cloud-based network security service that provides threat protection for cloud workloads and resources running in Azure.

Hardware or Software or a combination of both.

Basically, a barrier between a trusted and untrusted network.

- _Web Application Firewall_

Provides centralised protection of your web applications from common exploits and vulnerabilities.

- _Network Segmentation in Azure_

Dividing something into smaller pieces so easier to isolate when attacked and disallows the spread of malware.

Azure Virtual Network (VNet) allows organisations to segment their networks.

- _Azure Network Security Groups_

Network Security Groups (NSGs) – Let you filter network traffic to and from Azure resources in an Azure virtual network.

- _Azure Bastion_

Let’s you connect to a virtual machine using your browser and Azure portal.

PaaS that you provision in your virtual network.

Seamless connectivity to RDP and SSH connectivity.

- _Azure Key Vault_

Cloud service for securely storing and accessing secrets.

Secrets include API keys, passwords, and certificates.

- _Microsoft Defender_

Application with a set of security measures and practises designed to protect cloud-based applications from various cyber threats and vulnerabilities.

Unifies security management at the code level, prevents breaches, and offers specific protections for servers, containers, storage, and databases.

- _Security policies and initiatives improve cloud security posture_

Defender contains policies which applies security initiatives to your subscriptions.

Microsoft cloud security benchmark is a default guideline initiative that Defender applies although this can be custom-made by an admin.

- _Cloud security posture management_

Provides hardening guidance.

Offers a secure score within Defender.

Integrates with Microsoft Security Copilot.

- _Enhanced security of Microsoft Defender for cloud_

Defender can defend against threats and vulnerabilities by offering plans for specific resources such as servers, Key Vault, and SQL.

- _DevOps Security management_

Empowers security teams to manage DevOps security across multi-pipeline environments.

- _SIEM and SOAR_

Security Information Event Management (SIEM) – Tool that collects data from across the whole estate, including infrastructure, software, and resources. Looks for correlations and anomalies and generates incidents.

Security Orchestration Automated Response (SOAR) – Takes alerts from many sources, such as SIEM. Then triggers action-driven automated workflows and processes to run security tasks that mitigate the issue.

- _Threat detection and mitigation capabilities in Microsoft Sentinel_

Scalable

Collects data at scale

Detects threats by analytics, MITRE ATT&CK coverage, threat intelligence, and watchlists.

Investigates threats.

Responds to incidents rapidly through automation and playbooks.

- _Microsoft Sentinel integration with Microsoft Security Copilot_

Integrates through plugins.

Both Sentinel and natural language to KQL for Microsoft Sentinel (Preview) are accessible plugins within Copilot.

- _Microsoft Defender XDR services_

Enterprise defence suite of solutions that protects against cyber-attacks.

Includes the following: Defender for Endpoint, Vulnerability management, Defender for Office 365, Defender for Identity, Defender for Cloud Apps.

Integrates with Copilot.

- _Microsoft Defender for Office 365_

Seamless integration

Helps to prevent and detect cyber-attacks within the M365 suite.

Investigates potential vulnerabilities within the apps and can respond.

- _Microsoft Defender for Endpoint_

Platform designed to help enterprise networks protect endpoints including laptops, phones, tablets, and PCs. It does this by preventing, detecting, investigating, and responding to advanced threats.

- _Microsoft Defender for Clod Apps_

Delivers full protecting for SaaS applications, helping you monitor and protect your cloud app data.

- _Microsoft Defender for Identity_

Cloud-based security solution that uses signals from your on-premises identity infrastructure servers to detect threats, like privilege escalation or high-risk later movement, and reports on easily exploited identity issues.

- _Microsoft Defender Vulnerability Management_

Asset visibility, intelligent assessments, and built-in remediation tools for Windows, MacPS, Linux, Android, and iOS devices.

- _Microsoft Defender Threat Intelligence_

Aggregates and enriches critical data sources and displays them in an easy-to-use interface.

Threat reports allow analysts to track reported threats, and the steps needed to mitigate them.

- _Microsoft Defender portal_

Portal allows you to view the health of your organisation as well as lookover apps including XDR, SIEM, poster management and threat intelligence.

**Describe the capabilities of Microsoft compliance solutions (20–25%):**

- _Service Trust portal_

Provides a variety of content, tools, and other resources about how Microsoft cloud services protect your data, and how you can manage cloud security for your own organisation.

It includes legislation such as GDPR and ISO27001

- _Microsoft’s privacy principles_

Control, transparency, security, strong legal protection, no content-based targeting.

- _Microsoft Priva_

Comprehensive set of privacy solutions that support privacy operations across your organisation’s entire digital estate and enable your org to consolidate privacy protection across your digital data landscape, streamline compliance to regulations, and mitigate privacy risk.

- _Data classification capabilities of Microsoft Purview Information Protection_

Microsoft Purview is a comprehensive set of integrated data security, data governance, and data compliance solutions that can help organisations secure and govern their entire data estate.

Helps sensitise sensitive organisation data such as employee IDs and project numbers (custom-made by org – classifiers).

- _Sensitivity labels and policies in Microsoft Purview Information protection_

Sensitivity labels include Customisable – Admins can choose. Clear text – Third parties can read it and apply their own protective actions. Persistent – Policy applied remains the same even when moved around.

- _Data loss prevention in Microsoft Purview_

Implementation of data loss prevention (DLP) by defining and applying DLP policies.

- Insider risk management in Microsoft Purview

A solution that helps minimise internal risks by enabling an organisation to detect, investigate, and act on risky and malicious activities.

- _Adaptive protection in Microsoft Purview_

Uses machine learning (ML) to identify the most critical risks and proactively and dynamically apply protection controls from: DLP, Purview Data Lifecycle Management, Entra Conditional Access.

- _Audit in Microsoft Purview_

Auditing can allow security teams to understand where they may be vulnerable to an attack, have a weak secure score or accommodating for new infrastructure and how secure it may be for example.

Purview offers a standard and a premium edition.

- _eDiscovery_

Electronic discovery (eDiscovery) is the process of identifying and delivering electronic information that can be used as evidence in legal cases.

- _Compliance manager_

Compliance manager helps you automatically assess and manage compliance across your multi-cloud environment.

Provides an overview of your compliance through a pie chart and a compliance score across your estate.

- _Communication Compliance_

Insider risk solution that helps you detect, capture, and act on inappropriate messages that can lead to potential data security or compliance incidents within your organisation.

- _Data Lifecycle Management_

Provides you with tools and capabilities to retain the content that you need to keep and delete the content that you don’t.

Retention policies and labels help organisations to manage and govern information by ensuring content is kept only for a required time, and then permanently deleted. This helps to comply with industry regulations and reduce risk when there’s litigation or a security breach.

- _Records Management_

Helps an organisation look after their legal obligations. It also helps demonstrate compliance with regulations and increases efficiency with regular disposition of items that are no longer required to be kept, no longer of value, or no longer required for business purposes.

- _Concepts and benefits of data governance_

Federated governance – Provides a centralised place to develop data safety, and standards, but provides tools to create self-service access control, discoverability, and maintenance.

Benefits include secure access, understanding of the data, management of the data and responsible data use.

- _Microsoft Purview Data catalogue_

Governance domains, data products, glossary terms, critical data elements, objectives and key results (OKRs), data access policies, search and browse, health management, and data quality.

**Material from John Savill’s SC-900 Study Cram V2:**

Shared Responsibility:

- On-Prem – All customer
- IaaS – Customer OS. Underlying infrastructure is Microsoft
- PaaS – Customer responsible for data, identities. Underlying infrastructure is Microsoft. Shared responsibility with applications.
- SaaS – Customer responsible for data, identities. Microsoft manages everything else.

As you move from on-prem to SaaS Microsoft takes more responsibility.

Defence in depth:

- Multiple layers of security
- Physical security, Identity (Primary), perimeter, network (segmentation), compute (firewalls), application, data

All the above are layers. Each are seen as a security perimeter of defence.

CIA:

- Confidentiality, Integrity, Availability.

Zero trust:

- Don’t trust anything, verify everything. Authenticate everything.
- Focus on least privilege. Minimum set of permissions needed to perform a role. Only applied when needed (JIT).
- Assume breaches.

Encryption basics:

- Symmetric – Same key used to encrypt and decrypt data.
- Asymmetric – Public and private key used to encrypt and decrypt data.
- Hashing – Takes data and runs algorithm to convert it into unreadable code/numbers.

Hashing algorithms can also be used on passwords. The hash can be stored in the database. When typing in the password, if the hash matches, you’ll securely logon. Can add a SALT for extra security.

GRC:

- Governance, risk, compliance
- Governance – Adhering to regulations, country and industry specific.
- Risk – Identifying, assessing and responding to threats or events that impact business (Internal, External).
- Compliance – Country, region, federal, industry. What do I need to comply to?
- Data residency – Where does my data have to live?
- Data Sovereignty – Which countries laws apply to the data I am storing?
- Data privacy – What am I storing? How am I protecting it?

Identity:

- Administration (Setup)
- Authentication
- Authorisation
- Audit

Authentication:

- Single sign-on – Authenticate once and have access to all resources.
- OAuth2 – Open standard for access delegation used as a way for users to grant websites or applications access to their information.

Active Directory Domain Services:

- Used on-prem.
- Speaks Kerberos (Authentication protocol) and NTLM.
- Hybrid identity – Synchronises objects up. Flows from ADDS services. Synchronisations to SSO.

Federation:

- Multiple identity providers in play.
- Trusting the first identity provider that it has authenticated the user so the user can access resources on the second identity provider.
- User just needs a single account for a federation and can access multiple resources from multiple identity providers.

Types of accounts:

- Internal user – Account created in own tenant – Employee
- External user – Collaborated companies’ client – Client
- Applications – Workload identities – Service Principle, identifies via password or if it’s an Azure resource then you can use a managed identity (tied to a resource).
- Devices – Entra ID joined – Authenticate to device as a user of Azure (Corporate owned device). Entra ID Registered – BYOD, known to Entra, not authenticating directly with Entra.
- Entra Free – Basic features
- Entra P1 – Conditional access, MFA
- Entra P2 – Advanced risk analysis, PIM

MFA:

- Worst is password only. Better option is MFA.
- MFA – Phone, SMS, software/hardware token
- MFA – Something I know, have, am.
- Password list – No password needed. Microsoft Authenticator.
- Passkeys – Phishing resistant. Need to be close to device authenticating.
- Windows Hello for business – passkey
- FIDO2 (Open standard for user authentication that uses passkeys).
- Custom banned password lists allow admins to ban commonly exploited passwords.

Authorisation:

- Conditional access – Authorises depending on location, device health, risk of user, risk of sign-in, what you’re trying to access. These needs to be met before a token can be given for access.
- Terms of use – Rules put in and need to be met for access to be allowed.
- RBAC – Have a role which has a set of permissions. Can only give permissions to certain identities if they meet the requirements (depending on the role).

Audit and governance:

- Entra ID governance – JML. Dynamic groups add and remove users based on the properties of them.
- Access reviews – Check access of users, roles, devices etc. to check if you still need those things.
- PIM – Get access only when you need it for a specific time. Then the access is removed when not needed (JIT).
- ID Protection – Risk level of user, specific sign-ins.
- Permissions management – Discover what permissions an identity has and which ones they’re using. Then go and remediate (shrink) and monitor ongoing and see what you use.

DDoS:

- DDoS (Distributed Denial of Service attack). Azure offers traditional DDoS protection
- Free DDoS only covers large scale attacks whereas the paid version offers specific attack volume thresholds per application used. Paid version uses ML to check what’s normal traffic within the organisation.

Firewalls:

- Azure Firewall – Works in the application (HTTP) and network (TCP/IP) policies.
- Azure Web-Application Firewall – Protects against SQL injections. Protects from web-exploits.

Virtual networks and Network Security Groups:

- VNET – Lives within a specific subscription. VNETs can’t talk to each other.
- NSG – List of rules assigned to subnets. Segments network, allows flow in and out of network.
- Azure Virtual Network Manager – Allows you to create a security admin rule. Very similar to NSGs. Works before the NSG, flows to NSG once allowed or can be always allowed or denied.

Azure Bastion:

- Enables you to connect to a VM via RDP/SSH from the web.
- Website -> Azure Bastion -> VM

Azure Key Vault:

- Cloud service for securely storing secrets such as passwords.
- Let’s you store and access cryptographic keys.
- Private key can sign/decrypt, but it can’t leave the key vault (can’t be exported).
- Standard – Software based encryption.
- Premium – Hardware based protection.

Microsoft Defender for cloud:

- Cloud security posture management – What’s the state of my cloud? Azure policy – Create an initiative (whole set of policies). Microsoft Security Benchmark (recommendations from Microsoft).
- Cloud workshop protection platform – Features for different workloads. Adds JIT, add key capabilities from Microsoft Defender to things like Azure Key vault, storage, containers.
- DevSecOps – Adding unified security management.

Microsoft Sentinel:

- SIEM – Security Incident and Event management
- SOAR – Security Orchestration Automated Response
- Both provide signals to collect.
- Collects, detects, investigates (SOAR, helps develop a response).
- AI helps a lot with investigation and responding.

Security Copilot:

- Adding AI – Interacts with modern language.
- Sentinel, Entra, Intune, Defender can get integrated in an embedded way. Icons for Copilot will pop up depending on the Microsoft appliances layout.

Defender XDR:

- Merged with Sentinel for the portal experience.
- SIEM, SOAR + XDR.
- Solutions for M365 – Works for email (collaboration) QR codes sent, Endpoint (malware protection).
- Extended detection and Response (XDR).
- Defender for Identity – Looks at signals from on-prem identity infrastructure to look for signals showing compromises.
- Vulnerability management – Continuous asset vulnerability scanning. Checks environment for vulnerabilities.
- Threat intelligence – Look at reports and information for things I need to be considering in my environment.

Compliance:

- Prove you are adhering to whatever you need to be in your industry.
- 6 key principles: Control, Transparency, Security, Legal Protections, No Content Based Targeting, Benefits.
- Service Trust Portal – Different certification details that exists, standards used (ISO/IEC, GDPR). Can create a library to things that are relevant to you.

Priva:

- Private, personal data.
- Helps you understand what private data you have as an organisation.
- Privacy risk management – What private data I have, limit its transfer.
- Subject Rights request – Handles workflow for requests about personal data (Reporting, requests, removal).

Purview:

- Three key pillars – Governance, Compliance, Data Security.

Compliance manager:

- Helps to understand your compliance against other things. You can get a compliance score to view your compliance posture.

Data security:

- Find data, classify it – built-ins or custom classifications, protect, prevent and govern the data.
- Data Lifecycle Management – Retention labels, sensitive info types, different policy types can be enforced. Data, content, and activity explorer.
- Digital loss protection (DLP).
- Govern – retention and deletion – Labels
- Records management – Meet different types of legal requirements. Blocks activity logged and proof of disposition to show it has been disposed of.

Insider risk management:

- Define a policy for what I’m looking for, creates alerts when it sees a specific behaviour, triaged (can I dismiss or create a case for further investigation).

eDiscovery:

- Finding data in mailboxes, Teams, Skype.
- Content search.
- eDiscovery (Standard) – search and export, case management, legal hold.
- eDiscovery (Premium) – Custodian management, Legal hold notifications, Advanced indexing, Review set filtering, Tagging, Analytics, Predictive coding models, and more.

Audit:

- Keeping the data so I can respond to requests.
- Compliance.
- M365 (thousands of operations occurring). For all of these operations, they get captured and logged so we can search against it.
- Standard – 90 days retention.
- Premium – 1 year retention, higher bandwidth (more records).
