# Firewall and Network Security Lab

1. Project Overview

This project explores network security principles, firewall rules, authentication, authorisation, suspicious login attempts and network traffic monitoring.

The objective is to understand how organisations protect internal servers while maintaining access for legitimate users.

2. Scenario Description

A company has identified repeated login attempts and unusual network traffic targeting an internal server.

Some employees also require remote access from outside the office.

The IT team must reduce security risks without preventing authorised employees from accessing essential resources.

3. Identifying Security Risks

- Repeated login attempts.
- Possible brute-force attacks.
- Unusual network traffic.
- Potential unauthorised access.
- Security risks associated with remote connections.

4. Authentication and Authorisation

Authentication: Verifying the identity of a user.

Authorisation: Determining which systems and resources a user is permitted to access.

5. Firewall Rules and Access Control

A firewall helps protect an internal server by monitoring and filtering incoming and outgoing network traffic based on configured security rules.

Traffic to Allow

- Legitimate HTTPS traffic required for business operations.
- Approved VPN connections for authorised remote employees.
- Necessary network services and connections.

Traffic to Block

- Unauthorised connection attempts.
- Suspicious network traffic.
- Unnecessary access to open ports.
- Traffic that does not meet the organisation's security requirements.

Firewall Security Approach

- Apply a default-deny approach, allowing only necessary traffic.
- Restrict access to approved services and ports.
- Review firewall rules regularly.
- Ensure security controls do not unnecessarily disrupt legitimate users.

6. Network Traffic Monitoring

Network monitoring helps identify unusual activity and potential security threats.

Areas to investigate include:

- Source and destination IP addresses.
- Unusual connection attempts.
- Network ports and protocols.
- Firewall logs.
- Suspicious traffic patterns.

Monitoring Best Practices

- Review firewall logs regularly.
- Investigate repeated failed connection attempts.
- Identify unusual network activity.
- Review firewall rules when new risks are identified.

- Allow legitimate network traffic.
- Block unauthorised connections.
- Restrict unnecessary access to internal servers.
- Permit approved remote access.

7. Security Priorities and Recommendations

Priority: Strengthening Access Control

My first priority would be to strengthen access control by ensuring that only authorised users can access the internal server.

Recommended Security Measures

- Enforce Multi-Factor Authentication (MFA).
- Review repeated failed login attempts.
- Investigate suspicious account activity.
- Ensure remote employees use approved VPN connections.
- Apply appropriate access permissions based on employee roles.

Reasoning

Compromised user accounts could provide attackers with access to sensitive company systems and information.

Strengthening authentication and access control would reduce this risk while allowing legitimate employees to continue working securely.

8. Key Learning Outcomes

Through this project, I have developed my understanding of:

- Identifying network security risks.
- Recognising potential brute-force attacks.
- Authentication and authorisation.
- The principle of least privilege.
- Firewall rules and default-deny policies.
- Network traffic monitoring.
- Secure remote access using VPNs.
- Multi-Factor Authentication (MFA).

9. Further Improvements

Future development may include:

- Practical firewall configuration.
- Testing firewall rules in a lab environment.
- Analysing network traffic.
- Reviewing security logs.
- Exploring additional security monitoring tools.
