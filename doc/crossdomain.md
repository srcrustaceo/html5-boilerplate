[HTML5 Boilerplate homepage](http://html5boilerplate.com) | [Documentation
table of contents](TOC.md)

# crossdomain.xml

The cross-domain policy file is an XML document that grants a web client — such
as Adobe Flash Player, Adobe Reader, etc. — permission to handle data across
multiple domains.

When a client hosts content from a particular source domain and that content
makes requests directed towards a domain other than its own, the remote domain
would need to host a cross-domain policy file that grants access to the source
domain, allowing the client to continue with the transaction. Policy files grant
read access to data, permit a client to include custom headers in cross-domain
requests, and are also used with sockets to grant permissions for socket-based
connections.

For complete details, please see the [cross-domain policy file
specification](http://www.adobe.com/devnet-docs/acrobatetk/tools/AppSec/CrossDomain_PolicyFile_Specification.pdf).

