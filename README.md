# cloud-config-server

- Store & Serve distributed config across multiple application.
- Central place to keep common configs.

e.g. - Order, Payment & Gateway Services used the common Eureka configurations
     - for Payment Service UL inside Order Service - if someone changes in Payment Service, then whole build, deploy & packaging needed for Order Service to make          the correction.
