# saml-jumpcloud-elasticcloud

## Requirements

1. Create a free (trial) account on https://jumpcloud.com/
1. Create a free trial account on https://cloud.elastic.co with a deployment on Google Cloud
1. Follow elastic cloud instructions to enable SAML integration: https://www.elastic.co/guide/en/cloud/current/ec-securing-clusters-SAML.html
1. Follow jump cloud instructions to configure a generic saml provider: https://support.jumpcloud.com/customer/portal/articles/2551066
1. IMPORTANT: when looking for generic saml provider on jumpcloud search for `saml`
1. Demonstrate authentication flow where when accessing elastic cloud kibana end-point browser is redirected to jumpcloud login page
1. End-user can login using non-administrative jumpcloud directory account
1. End-user can access kibana user interface with full permissions after successful authentication with jump-cloud account
1. Document the setup using markdown format and/or setup scripts that will be tested to reproduce

## Deliverables

* Markdown step-by-step instructions and/or scripts that can be executed from Mac/Linux desktop
* No unknown/undocumented pre-requisites

## Acceptance criteria

* The documented setup instructions will be followed by a third party to create a new jump-cloud account and new elastic cloud deployment
* At the end of a documented setup an end-user will be able to authenticate to elastic cloud kibana end-point using non-admin jump-cloud account

## How to submit work

* Fork this repository
* Commit documentation/scripts to your own repository
* Upon completion submit a pull request to this repository
