# My-Projects
All Samples done in VisualStudio


Dear all,

We have setup the account for CUSTOMER_NAME in our productive environment.

Attached are the following files:

CN_NAME.pem -  Signed certificate for access. This can be renamed to certificate.cer so it will match the examples in the implementation guide
[SpecificationFileName with API_VERSION] - OpenAPI Specification for the REST API
DigiCert_Global_Root_CA.pem - Root CA for MQTT connections, required for CES notifications and Live Position Indicator.
Below are the API  details:

              Rest API URL: https://p-dxc.azure-api.net/v1/

              Subscription Keys: (used for the REST API)

                            Primary: PRIMARY_SUB_KEY

                            Secondary: SECONDARY_SUB_KEY

              MQTT Broker: mr-d8f4yze1pn9.messaging.solace.cloud (port 443)

              CN Name: CN_NAME (used when subscribing to CES notifications or Live Position Indicator)



Please feel free to reach out to us if you have any issues, we would be happy to help.

Best Regards,

Siva
