This document keeps notes of all work starting on Dec 5, 2024

**A)** Starting with [Get Started with Atlas](https://www.mongodb.com/docs/atlas/getting-started/#get-started-with-atlas).
This section consists of 
- [Create an Atlas Account](https://www.mongodb.com/docs/atlas/tutorial/create-atlas-account/#create-an-service-account).
  This is done already. Login [here](https://account.mongodb.com/account/profile/overview) with password AnnArbor2024+ resulting with [this page](https://account.mongodb.com/account/profile/overview). Rather than visiting the proposed sections, we will continue with
  [Deploying a Free Cluster](https://www.mongodb.com/docs/atlas/tutorial/deploy-free-tier-cluster/#deploy-a-free-cluster):

  - [Create a cluster](https://www.mongodb.com/docs/atlas/tutorial/create-new-cluster/#create-a-cluster).
    - Start with [Install the Atlas CLI](https://www.mongodb.com/docs/atlas/cli/current/install-atlas-cli/); Installed **atlascli version: 1.33.0**
    - To use [Atlas Administration API](https://www.mongodb.com/docs/atlas/configure-api-access/#get-started-with-the-atlas-administration-api), use the Oauth 2.0 Authentication, which requires [Client Credentials](https://www.oauth.com/oauth2-servers/access-tokens/client-credentials/) flow
      - Start with [Grant Programmatic Access to Atlas](https://www.mongodb.com/docs/atlas/configure-api-access/#get-started-with-the-atlas-administration-api) - and continue to [Service Account Overview](https://www.mongodb.com/docs/atlas/api/service-accounts-overview/#service-accounts-overview). A service account comes with a client ID and secret, comparable to a username and password, that you use to generate access tokens for API requests. You can change the roles, name, description, or access list for a service account in an organization using the Atlas UI. You can also generate a new client secret.
        - [In Atlas, go to the Organization Access Manager page](https://www.mongodb.com/docs/atlas/configure-api-access-org/#in---go-to-the-organization-access-manager-page.-3)


---
  
**B)** Continuing with [Atlas Vector Search Overview](https://www.mongodb.com/docs/atlas/atlas-vector-search/vector-search-overview/#atlas-vector-search-overview)
- [Atlas Vector Search Quick Start](https://www.mongodb.com/docs/atlas/atlas-vector-search/tutorials/vector-search-quick-start/#atlas-vector-search-quick-start)
- [Integrate Vector Search with AI Technologies](https://www.mongodb.com/docs/atlas/atlas-vector-search/ai-integrations/#integrate-vector-search-with-ai-technologies)

**C)** use [Buildship](https://docs.buildship.com/) an AI-powered visual backend builder that enables you to automate any complex workflow. BuildShip integrates with any tools like Stripe, Sendgrid, Whatsapp or AI model from OpenAI, Replicate etc or database like Firebase, Supabase, Postgres, MongoDB.
