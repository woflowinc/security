## Overview

Keeping our customers' data protected at all times is our highest priority. This security overview provides a high-level overview of the security practices put in place to achieve that objective.
Have questions or feedback? Feel free to reach out to us at [tech@woflow.com](mailto:tech@woflow.com)

## Infrastructure

### Cloud infrastructure

All of our services run in the cloud. We don’t host or run our own routers, load balancers, DNS servers, or physical servers.
Our service is built on Amazon Web Services, Google Cloud Platform, and Heroku. They provide strong security measures to protect our infrastructure and are compliant with most certifications. You can read more about their practices here:
- [AWS](https://aws.amazon.com/security/)
- [Google Cloud Platform](https://cloud.google.com/security/)
- [Heroku](https://www.heroku.com/policy/security)

## Data encryption

Encryption in transit: All data sent to or from our infrastructure is encrypted in transit via industry best-practices using Transport Layer Security (TLS). You can see our SSLLabs report [here](https://www.ssllabs.com/ssltest/analyze.html?d=https://app.woflow.com)
Encryption at rest: All our user data (including passwords) is encrypted using battled-proofed encryption algorithms in the database.

## Business continuity and disaster recovery

We back up all our critical assets and regularly attempt to restore the backup to guarantee a fast recovery in case of disaster.

## Application security monitoring

- We use a security monitoring solution to get visibility into our application security, identify attacks and respond quickly to a data breach.
- We use technologies to monitor exceptions, logs and detect anomalies in our applications.
- We collect and store logs to provide an audit trail of our applications activity.

## Application security protection

- We use a runtime protection system that identifies and blocks OWASP Top 10 and business logic attacks in real-time.
- We use security headers to protect our users from attacks. You can check our grade on [this security scanner](https://www.sqreen.io/scan?url=https://app.woflow.com).
- We use security automation capabilities that automatically detect and respond to threats targeting our apps.

## Secure development

We develop following security best practices and frameworks (OWASP Top 10, SANS Top 25). We use the following best practices to ensure the highest level of security in our software:
- Developers participate in regular security training to learn about common vulnerabilities and threats
- We review our code for security vulnerabilities
- We regularly update our dependencies and make sure none of them has known vulnerabilities
- We use Static Application Security Testing (SAST) to detect basic security vulnerabilities in our codebase
- We use Dynamic Application Security Testing (DAST) to scan our applications
- We rely on bi-annually third-party security experts to perform penetration tests of our applications.

## User protection

We protect our users against data breaches by monitoring and blocking brute force attacks.

**Role-based access control**

Role-based access control (RBAC) is offered on all our accounts and allows our users to define roles and permissions.

## Employee access

- All our employees sign a Non-Disclosure and Confidentiality Agreement when joining the company to protect our customers' sensitive information.
