## Abbrevations

* Subject Alternative Name: SAN.

## Types of SSL certificates by amount of domain/s

* Single-domain SSL certificate
* Multi-domain SSL certificate
* Wildcard certificate

##  An SSL certificate should cover both 

All of the following domain variations should work without `Your website is not secured` errors.

* https://example.com (SAN 1)
* https://www.example.com (SAN 2)
* http://example.com (this CNAME redirect should redirect to https://example.com)
* http://www.example.com (this CNAME redirect should redirect to https://www.example.com)

## Installation

Paid certificates could be installed by an hosting company technical support team behind the scenes.

Gratis certificates such as Let's Encrypt certificates could be installed with acme.sh or with CertSage (some tools may require root access).

## Links

* https://community.letsencrypt.org/u/humbleasker/activity/topics
