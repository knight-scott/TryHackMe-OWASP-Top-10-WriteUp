# Welcome

![Group photo](./img/misc/OWASP10.png)

## Introduction

This covers the questions for [TryHackMe's OWASP Top 10 Room](https://tryhackme.com/room/owasptop10). Only the tasks with challenges will be covered and I suggest you go through the room for a deeper understanding of the vulnerabilities covered here. You should also check out the [OWASP Top Ten](https://owasp.org/www-project-top-ten/). 

!!! note "OWASP"
    The Open Web Application Security Project is a nonprofit foundation focused on understanding web technologies and exploitations and provides resources and tools designed to improve the security of software applications.

!!! note "Template"
    This write up was created using the [Template](https://github.com/knight-scott/WriteUpTemplate) that I adapted from [crahan](https://github.com/crahan)'s [HolidayHackChallengeTemplate](https://github.com/crahan/HolidayHackChallengeTemplate/). While the original is holiday and CTF competition specific, the genral idea and formatting is applicable to any number of reporting scenarios. I hope to utilize this better for creating ongoing reports of CTF challenges I compete in. It's based on [MkDocs](https://www.mkdocs.org/) and the [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) theme.

## Answers

!!! success "Severity 1 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Use [command injection](./objectives/o1.md) with knowledge of Linux tools to exploit the vulnerability.

!!! success "Severity 2 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Use [broken authentication](./objectives/o2.md) to explore logic flaws within the authentication mechanism.

!!! success "Severity 3 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Using [sensitive data exposure](./objectives/o3.md) exploit the exposed technology to gain admin access.

!!! success "Severity 4 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Explore [XXE](./objectives/o4.md) vulnerability.

!!! success "Severity 5 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Learn how [broken access controll](./objectives/o5.md) can be exploited.

!!! success "Severity 6 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    View the [Security Misconfiguration](./objectives/o6.md) walkthrough here.

!!! success "Severity 7 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    This [XSS](./objectives/o7.md) challenge showcases DOM-Based, Reflected and Stored XSS exploitation.

!!! success "Severity 8 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Follow allong exploiting [insecure deserialization](./objectives/o8.md) here.

!!! success "Severity 9 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Follow in the steps of others when working with [components with known vulnerabilites](./objectives/o9.md).

!!! success "Severity 10 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Explore logs to emphsize the risk of [insufficient logging and monitoring](./objectives/o10.md) here.

## Conclusion

This was an informative, free room. It's surprising to me how many vulnerabilities are the result of human error and I am looking forward to refining detection and exploitation in the pursuit of further hardening systems.

![Group photo](./img/misc/owasptop10.svg)
