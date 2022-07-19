What Is SSRF?
A Server-Side Request Forgery (SSRF) attack involves an attacker abusing server functionality to access or modify resources. 
The attacker targets an application that supports data imports from URLs or allows them to read data from URLs. URLs can be manipulated, 
either by replacing them with new ones or by tampering with URL path traversal.

Typically, attackers supply a URL (or modify an existing one) and the code running on the server reads or submits data to it. 
Attackers can leverage URLs to gain access to internal data and services that were not meant to be exposed – including HTTP-enabled 
databases and server configuration data.

Once an attacker has tampered with the request, the server receives it and attempts to read data to the altered URL. 
Even for services that aren’t exposed directly on the public internet, attackers can select a target URL, which enables them to read the data.

SSRF Risks Explained
What damage SSRF might do depends entirely on the configuration of systems and the attacker’s inventiveness. 
Here are some common risks of SSRF.

RESOURCES TO LEARN :- https://www.imperva.com/learn/application-security/server-side-request-forgery-ssrf/
