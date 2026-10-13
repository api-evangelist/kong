<!-- fetched 2026-10-13 from https://developer.konghq.com/event-gateway/ by sweep-shape-compat.py; text extracted from the provider's own page -->

Event Gateway | Kong Docs 
 Ask AI 
 Platform 
 Explore the platform 
 Konnect 
 Build APIs 
 Kong Insomnia 
 API Design 
 API Testing and Debugging 
 Run APIs 
 API Gateway 
 AI Gateway 
 Event Gateway 
 Service Mesh 
 Kong Ingress Controller 
 Kubernetes Operator 
 Govern APIs 
 Observability 
 Metering & Billing 
 Kong Identity 
 Context Mesh 
 API Security & Access Control 
 Discover APIs 
 Developer Portal 
 Catalog 
 Tools 
 decK 
 kongctl 
 Inso CLI 
 Koh CLI 
 Terraform 
 Ingress controller 
 View all →
 Why Kong? 
 Kong's SaaS API management platform designed to simplify managing and securing APIs.
 Learn more → 
 Resources 
 Guides 
 API Gateway 
 AI Gateway 
 Event Gateway 
 Insomnia 
 Kong Ingress Controller 
 Kubernetes Operator 
 Kong Mesh 
 Dev Portal 
 Catalog 
 Kong Identity 
 View all → 
 Tools for AI 
 Konnect MCP 
 AI Cookbooks 
 Skills Hub 
 decK 
 kongctl 
 Inso CLI 
 Koh CLI 
 Plugins 
 API Gateway Plugins 
 AI 
 Authentication 
 Security 
 Traffic Control 
 Serverless 
 Analytics & Monitoring 
 Transformations 
 Logging 
 Monetization 
 View all → 
 Event Gateway Policies 
 Security 
 Traffic Control 
 Transformations 
 Data Quality 
 View all → 
 AI Gateway Policies 
 AI 
 Authentication 
 Security 
 Traffic Control 
 Serverless 
 Analytics & Monitoring 
 Transformations 
 Logging 
 Monetization 
 View all → 
 Service Mesh Policies 
 View all → 
 APIs 
 Support 
 Knowledge Base
 Community
 Github
 Community Forum
 Kong Pricing
 Demos
 User Calls
 Workshops
 Help & Support
 Theme 
 Get a Demo 
 Start Free Trial 
 Edit this Page 
 Edit 
 Report an Issue 
 Report 
 Kong Event Gateway
 A Kafka proxy for controlled, secure client access to your Kafka cluster—both internal and external. 
 Event Gateway Documentation
 Introducing Kong Event Gateway
 Kong Event Gateway is a lightweight, fast, and flexible cloud-native event streaming proxy. 
 It sits between Kafka clients and backend Kafka clusters.
 With its extensible policy engine, you can adapt Kafka to your requirements-transforming, encrypting, and monitoring 
 messages through a central proxy to add governance, enable multi-tenancy, and strengthen security.
 Kong Event Gateway runs in front of any Kafka cluster and can be extended through policies.
 Get started with Event Gateway → 
 Install Event Gateway 
 You can configure Event Gateway using Konnect.
 Before deploying Event Gateway, ensure that you have a Kafka cluster.
 Quickstart
 Konnect UI
 You can use the quickstart script to get a demo instance of Event Gateway running almost instantly.
 This command requires a Konnect Access Token .
 curl -Ls https://get.konghq.com/event-gateway | bash -s -- -k $KONNECT_TOKEN 
 Copied!
 The script creates an Event Gateway control plane in Konnect and deploys a local data plane using Docker.
 All licensing is handled automatically by Konnect.
 To set up Event Gateway using the Konnect UI, use the following steps:
 Sign in to your Konnect account at cloud.konghq.com .
 In the menu, navigate to Event Gateway .
 Click New Gateway .
 Fill in the fields:
 Name : A unique name for your control plane.
 Description : An optional description for your control plane.
 Minimum supported data plane version : The minimum allowed data plane version for this control plane. 
We recommend setting this to the latest version.
 For example, if you select 1.1, you will be able to use features introduced in 1.1, but
 you won’t be able to run 1.0 data planes with this control plane.
 Click Create to save.
 Select a platform for your data plane.
 Click Generate Certificate .
 Copy the generated command.
 Run the command on your data plane host to start the data plane.
 After the data plane is connected and the control plane recognizes it, click Done .
 You can adjust data plane node settings using bootstrap configuration parameters at start time.
 Get started with Kong Event Gateway 
 Deploy Event Gateway in Konnect
 Configure a control plane and launch a Kong Event Gateway data plane through Konnect in minutes
Set up Event Gateway in Konnect →
 Try the Getting Started guide
 Set up a data plane, configure backend cluster, create virtual cluster, set up a listener, and apply policies
Get started →
 Understand core concepts
 Learn about how Event Gateway works, including its architecture and key entities
Learn about Event Gateway →
 Event Gateway policy hub
 See all available virtual cluster and listener policies for Kong Event Gateway
See all policies →
 Kong Event Gateway in the Konnect UI
 Konnect lets you manage, connect to, and monitor 
the status of all Kong Event Gateway control planes (CPs) and data plane nodes (DPs) in one place.
 Key features include:
 Manage control planes and their configurations
 Deploy and monitor data plane nodes
 Find backend clusters, virtual clusters, listeners, and resources directly in a control plane’s sidebar
 Create and manage policies through the Virtual Clusters and Listeners sections
 Kong Event Gateway entities 
 Backend clusters
 Physical Kafka clusters that are proxied by Event Gateway
Learn about backend clusters →
 Virtual clusters
 Core abstraction for client isolation when connecting to the same backend cluster
Learn about virtual clusters →
 Listeners
 Network interfaces for Kafka client connections
Learn about listeners →
 Policies
 Control how Kafka protocol traffic is modified between the client and the backend cluster
Learn about policies →
 Use cases for Kong Event Gateway 
 Use case 
 (You’re trying to…) 
 Outcome 
 (…so that you can…) 
 Feature 
 (…using these solutions…) 
 How-to guide or example 
 (…implemented like this) 
 Govern Kafka to enforce security and guidelines in an automated fashion
 Centrally manage and instantly update access control policies without touching individual brokers
 ACL policy 
 Get started with Event Gateway and ACLs 
 Replace legacy auth methods with modern enterprise identity standards your team already uses
 OAuth 
 Set up Event Gateway with Kong Identity OAuth 
 Automatically apply policies based on the metadata of connected clients, with no per-user rule changes needed
 Modify Headers policy 
 Enrich SASL PLAIN connections with principal metadata 
 Enrich OAuth connections with principal metadata 
 Know exactly which teams and topics are driving cluster load, in real time, via in-platform dashboards or exported to your preferred tooling
 Observability 
 Configure observability with OpenTelemetry 
 Demonstrate compliance with data privacy regulations through auditable, enforceable controls
 Encryption policy , Decryption policy ,
 Encrypt Fields policy , Decrypt Fields policy 
 Encrypt and decrypt Kafka messages ,
 encrypt and decrypt Kafka message fields 
or encrypt and decrypt Kafka message fields dynamically 
 Simplify your Kafka deployment because it’s too complicated and expensive
 Isolate teams or environments on a shared cluster without complex infrastructure duplication
 Virtual clusters 
 Set up virtual clusters 
 Automatically enforce access rules based on identity metadata with no manual ACL management
 OAuth 
 Set up Event Gateway with Kong Identity OAuth 
 Improve the developer experience to increase adoption and achieve faster time-to-value
 Prevent malformed messages from ever reaching consumers
 Schema validation - produce phase and 
 Schema validation - consume phase 
 Ensure data quality with schema validation 
 Onboard apps using OAuth flows developers already know, with no Kafka expertise required
 OAuth 
 Set up Event Gateway with Kong Identity OAuth 
 Let any developer produce and consume Kafka events using standard REST - no Kafka client needed
 Protocol mediation 
 –
 Productize Kafka data into “data products” with self-service access that you can monetize
 Package raw topic data into clean, audience-specific products without duplicating data
 Namespaces 
 Set up namespaces and enforce access control with ACLs 
 Ensure each consumer only sees the records they’re entitled to, enforced automatically
 Modify Headers policy and Skip Records policy 
 Filter Kafka records by classification headers 
 Tools to manage Kong Event Gateway 
 Konnect UI : Manage Event Gateway control planes, data planes, and configurations using a UI.
 Control Plane API : Manage Event Gateway entities within Konnect control planes via an API.
 Terraform : Manage infrastructure as code and automated deployments to streamline setup and configuration of Konnect and Kong Event Gateway.
 kongctl : Manage Event Gateway control planes and the entities within them declaratively via a CLI.
 Key references 
 Authentication
 Flexible authentication for both virtual cluster client connections and backend cluster access
 Authentication for backend clusters → 
 Authentication for virtual clusters → 
 Hostname mapping
 Map gateway servers to upstream Kafka brokers using port mapping or SNI routing
 Understand hostname mapping → 
 Expressions language reference
 Learn about the expressions language used in Kong Event Gateway for conditional fields
 Expressions language reference → 
 API reference
 Explore the reference documentation for all Kong Event Gateway APIs
 Event Gateway API reference → 
 Data plane configuration reference
 Explore the reference documentation for all Kong Event Gateway data plane configuration parameters
 Data plane configuration reference → 
 Entities and resources
 See all the entities that make up Kong Event Gateway and its ecosystem
 See reference → 
 Metrics and headers
 Reference for the metrics and headers added or exposed by Kong Event Gateway
 Metrics reference → 
 Headers reference → 
 Kong Event Gateway changelog
 Changelog for supported Kong Event Gateway versions.
 See changelog → 
 Frequently asked questions about Kong Event Gateway 
 How is Kong Event Gateway deployed?
 The Kong Event Gateway data planes are self-managed and deployed by you, the user. 
The Kong Event Gateway control plane is part of the Kong Konnect platform.
 Does Kong Event Gateway run on-prem?
 No, Kong Event Gateway is only available through the Kong Konnect platform.
 Can I proxy multiple Kafka clusters?
 Yes, the gateway can proxy multiple backend clusters, though only one can currently be proxied in a single client connection.
 I’m getting connection errors between the control plane and data plane. What should I check?
 You may need to add specific hostnames or IP addresses to an allowlist so that communication can reach Konnect uninterrupted.
See Networking in Konnect for the required ports and hostnames.
 How-to Guides 
 Authenticate Kong Event Gateway connections to Kafka using mTLS
 View → 
 Configure mTLS client authentication with Kong Event Gateway
 View → 
 Set up observability for Kong Event Gateway
 View → 
 Authenticate Kong Event Gateway connections to Kafka using SASL/PLAIN
 View → 
 Configure SNI routing with Kong Event Gateway
 View → 
 Configure topic aliases with Kong Event Gateway
 View → 
 Encrypt and decrypt Kafka fields dynamically in message values with Kong Event Gateway
 View → 
 Encrypt and decrypt Kafka fields in message values with Kong Event Gateway
 View → 
 View More → 
 Looking for HTTP over Kafka? Check out the Kong Gateway protocol mediation plugins . 
 Something wrong? 
 Report an Issue 
 | 
 Edit this Page 
 View all Kong documentation 
 Help us make these docs great!
 Kong Developer docs are open source. If you find these useful and want to make them better,
 contribute today!
 Contribute 
 Still need help?
 Ask in our Slack Community
 Contact Support
 The AI Connectivity Company
 Kong enables the connectivity layer for the agentic era – securely connecting, governing, and monetizing APIs and AI tokens across any model or cloud.
 Ready to get started with Kong?
 Start free trial 
 Get a Demo 
 Platform
 API Platform 
 API Gateway 
 AI Gateway 
 Service Mesh 
 Dev Portal 
 Pricing 
 Platform Docs
 Kong Gateway 
 Kong AI Gateway 
 Kong Mesh 
 Insomnia 
 OpenAPI Specs 
 Ingress Controller 
 Plugins
 AI Plugins 
 Analytics Plugins 
 Authentication Plugins 
 Security Plugins 
 Traffic Control Plugins 
 View all → 
 How-to Guides
 Kong Gateway 
 Insomnia 
 Kong Mesh 
 Terraform 
 View all → 
 Support
 Community 
 Community Forum 
 GitHub 
 Demos 
 User Calls 
 Workshops 
 Help & Support 
 Contact Us 
 Terms 
 | 
 Privacy 
 | 
 Trust and Compliance 
 © Kong Inc. 2026
