# Web Security

Notes and practical lab writeups covering web application vulnerabilities, their exploitation techniques, and security implications.

---

## Topics

| Topic                                                           | Description                                                                                                                                     |
| --------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [Access Control](access-control/)                               | Vulnerabilities that allow users to perform actions or access resources beyond their intended permissions.                                      |
| [Command Injection](command-injection/)                         | Injection vulnerability that allows attackers to execute arbitrary operating system commands through a vulnerable application.                  |
| [Local File Inclusion (LFI)](file-related/file-inclusion/lfi/)  | File inclusion vulnerability that allows an application to include local files, potentially exposing sensitive data or enabling code execution. |
| [Path Traversal](file-related/path-traversal/)                  | File path manipulation vulnerability that allows attackers to access files and directories outside the intended location.                       |
| [Remote File Inclusion (RFI)](file-related/file-inclusion/rfi/) | File inclusion vulnerability that allows an application to include remote resources, potentially leading to code execution.                     |
| [Server-Side Request Forgery (SSRF)](ssrf/)                     | Server-side vulnerability that allows attackers to manipulate server-side requests to access unintended internal or external resources.         |
