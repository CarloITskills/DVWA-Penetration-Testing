Vulnerability Report for DVWA
Medium Severity

    Browsable Web Directories
        Severity: Medium (5.3)
        Plugin ID: 40984
        Description: The web server has directories that can be browsed, potentially exposing sensitive files.

    Web Application Potentially Vulnerable to Clickjacking
        Severity: Medium (4.3)
        Plugin ID: 85582
        Description: The application lacks protection against clickjacking attacks, which can lead to malicious site interactions.

Informational Findings

    Apache HTTP Server Version
        Plugin ID: 48204
        Description: Information about the version of the Apache HTTP Server.

    CGI Generic Tests Load Estimation (all tests)
        Plugin ID: 33817
        Description: Estimates the load on the server from generic CGI tests.

    External URLs
        Plugin ID: 49704
        Description: Identifies external URLs that are referenced within the web application.

    HSTS Missing From HTTPS Server
        Plugin ID: 84502
        Description: The server does not enforce HTTP Strict Transport Security (HSTS), which protects against protocol downgrade attacks.

    HTTP Cookie 'secure' Property Transport Mismatch
        Plugin ID: 69826
        Description: Cookies marked as 'secure' are not transmitted over HTTPS, potentially exposing sensitive information.

    HTTP Methods Allowed (per directory)
        Plugin ID: 43111
        Description: Lists the HTTP methods that are allowed by the server for each directory.

    HTTP Server Type and Version
        Plugin ID: 10107
        Description: Information disclosure about the HTTP server type and version.

    HyperText Transfer Protocol (HTTP) Information
        Plugin ID: 24260
        Description: General information about the HTTP configuration.

    HyperText Transfer Protocol (HTTP) Redirect Information
        Plugin ID: 91634
        Description: Details about HTTP redirects configured on the server.

    Missing or Permissive Content-Security-Policy frame-ancestors HTTP Response Header
        Plugin ID: 50344
        Description: Lack of a strict Content Security Policy (CSP) to prevent content injection.

    Missing or Permissive X-Frame-Options HTTP Response Header
        Plugin ID: 50345
        Description: The server does not use the X-Frame-Options header to prevent framing, which is necessary to prevent clickjacking attacks.

    Nessus Scan Information
        Plugin ID: 19506
        Description: Information about the Nessus scan itself.

    Netstat Portscanner (SSH)
        Plugin ID: 14272
        Description: Information about the network services and ports detected.

    Web Application Cookies Not Marked HttpOnly
        Plugin ID: 85601
        Description: Cookies are not marked as HttpOnly, which increases the risk of client-side scripts accessing them.

    Web Application Cookies Not Marked Secure
        Plugin ID: 85602
        Description: Cookies are not marked as Secure, meaning they can be transmitted over unencrypted channels.

    Web Application Potentially Sensitive CGI Parameter Detection
        Plugin ID: 40773
        Description: Potentially sensitive CGI parameters that could be exploited.

    Web Application Sitemap
        Plugin ID: 91815
        Description: Details about the sitemap of the web application.

    Web Server Directory Enumeration
        Plugin ID: 11032
        Description: The server allows directory enumeration, which could expose sensitive directories.

    Web Server No 404 Error Code Check
        Plugin ID: 10386
        Description: The server does not return a 404 error code for non-existent pages, which can aid in information gathering by attackers.

    Web Server Office File Inventory
        Plugin ID: 11419
        Description: Identifies office files available on the web server.

    Web Server robots.txt Information Disclosure
        Plugin ID: 10302
        Description: The robots.txt file can disclose sensitive information about the site's structure.

    Web Mirroring
        Plugin ID: 10662
        Description: Details about the mirroring configuration of the web server.