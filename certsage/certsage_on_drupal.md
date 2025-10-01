[Initial details](https://github.com/GriffinSoftware/CertSage).

## Let's start

### 1)

Downlad certsage.php and put it at:

> example.com/web/certsage.php

### 2)

Navigate to the above address from a new web browser, which is cacheless (all caches from all times flushed).

### 3)

For simple websites, RSA is more common and widely supported, especially on shared hosting environments like Namecheap.

Choose RSA unless you are certain your host and all clients (browsers/devices) support EC (Elliptic Curve). RSA offers maximum compatibility.

### 4)

Enter your password into the Password box from your `password.txt` file found in your CertSage data directory, which is located in the parent directory of the directory where you uploaded certsage.php.

### 5 )

Click to test and if the test is successful then **refill all data** and click *Acquire Certificate and Install into cPanel*.

## Notes

* CertSage communicates with Cpanel API. Cpanel is a shared-hosting standard and should be available. If there is no Cpanel, probably there is root access and it's best to use Certbot or equivalent.
