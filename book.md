## Types of SSL certificates by amount of domain/s

* Single-domain SSL certificate
* Multi-domain SSL certificate

## Installing an SSL Certificate

Often times installing an SSL certificate requires a root access but with CertSage, it doesn't.

SSL certificates should be installed with their CNAME redirects.

##  An SSL certificate should cover all URL patters

All of the following domain variations should work without `Your website is not secured` errors.

* https://example.com
* https://www.example.com
* http://example.com (this CNAME redirect should redirect to https://example.com)
* http://www.example.com (this CNAME redirect should redirect to https://www.example.com)

## Links

* https://community.letsencrypt.org/u/humbleasker/activity/topics
