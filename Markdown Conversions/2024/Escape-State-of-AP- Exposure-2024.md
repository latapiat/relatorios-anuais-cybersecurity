Fortune 1
000 at Risk: How we discovered 30,000 exposed APIs \& 100,000 API issues in the worlds largest organizations
Fortune 1000 at Risk: How we discovered 30,000
exposed APIs \& 100,000 API issues in the worlds largest
organizations
included in the Fortune 1000 and CAC 40\. 
Heres what we found
30,784
Exposed APIs
included in the Fortune 1000 and CAC 40\. 
Development APIs exposed
secrets accessible in API services
secrets accessible in API services
Highly critical vulnerabilities
Highly critical vulnerabilities
Exposed APIs
Key Takeaways
Tristan Kalos, CEO of Escape
The State of API Exposure 2024 report provides an in\-depth analysis of the
 significant risks associated with exposed APIs, highlighting vulnerabilities across la
rge organizations, including Fortune 1000 companies and CAC 40 entities. Key finding
s reveal the pervasive nature of API security issues and the need for improved securit
y measures:
1,834 Highly Critical Vulnerabilities in Fortune 1000 Companies: Among the iden
tified vulnerabilities, 1834 were classified as highly critical, directly affect
ing Fortune 1000 companies. These critical vulnerabilities, often associated with broken authentication and configuration errors, place essential systems and sensitive data at significant risk of exposure and exploitation. Critical issues span various sectors, impacting tech platforms, financial companies, insurance, healthcare, tech, and others.
Development APIs: Nearly 4,000 development APIs were publicly accessible, often lac
king adequate security controls. Exposing these APIs can inadvertently reveal se
nsitive information and offer attackers potential entry points.
Exposed Secrets: The report found 1,816 highly sensitive secrets exposed within
 API environments, including access tokens, API keys, and authentication cred
entials. These exposed secrets significantly heighten the risk of unauthorized acc
ess and potential misuse of critical systems.
Call to action: We recommend to start auditing all APIsparticular
ly shadow and legacy APIsto identify and secure vulnera
bilities, and restricting access to development APIs with produc
tion\-level security standards. Implementing continuous monitoring
 and scanning tools is crucial to detect risks early, while ensuring that all secrets are encrypted and securely managed to prevent exposure.
Tristan Kalos, CEO of Escape
OUR FINDINGS
5
METHODOLOGY
7
OUR FINDINGS
12
16
EXPOSED AND VULNERABLE DEVELOPMENT APIS
17
FORTUNE 1000 AT RISK
18
AMERICAN MULTINATIONAL TECH COMPANY: EXPOSED SPRING BOOT ACTUATOR
20
CVES FOUND
22
ESSENTIAL REMEDIATION 
STEPS
16
24
CONCLUSION
THE CONSEQUENCES OF UNSECURED
APIS EXPOSED IN THE WILD
API sprawl has emerged as a significant
challenge in recent years. As organizations
increasingly rely on APIs to fuel digital
transformation, connect services, and
deliver data\-driven experiences, the sheer
number of APIs in production has
skyrocketed.
As we move through 2024, the exponential
growth of APIs presents new challenges.
According to recent Gartners market
guide, APIs \- especially shadow and
dormant ones \- are causing data breaches
among organizations that, on average,
exceed the magnitude of other breaches.
Since 2022, at least 190M sensitive data
records have been breached. In our
previous research, we estimate that
enterprise companies lost $31B due to
breaches.
Many APIs are pushed to production too
soon, often bypassing critical security
testing stages or, in some cases, being
tested only after deployment rather than
within development environments. 
This rush to release frequently leads to gaps
in security coverage, allowing untested or
under\-tested endpoints to expose sensitive
information or become vulnerable to attack.
Another significant factor is the proliferation
of "shadow APIs"APIs that exist outside
the knowledge or management of security
teams. These undocumented, unmanaged,
or abandoned APIs often lack essential
security protocols, making them especially
prone to exploitation. Shadow APIs can
emerge from development shortcuts, legacy
applications, or third\-party integrations that
slip through regular security oversight,
creating hidden risks within the systems
architecture.
Given these trends, API security deserves
greater attention. It is now widely recognized
as a critical challenge requiring stringent
security management and thorough testing
before APIs are released into production
environments. By analyzing Fortune 1000
and CAC 40 exposed API services were here
to prove it.
ARE WE IGNORING HIDDEN DANGERS?
57%
of organizations suffered an
API\-related data breach in the
past two years
\*according to a 2023 report from Enterprise Management Associates (EMA)
\*according to a 2023 report from Enterprise Management Associates (EMA)
according to Escapes A
PI Threat Landscape Report
according to the 2025 Global State of API Security report
$31B
estimated losses due to 
API breaches
according to Escapes API Threat Landscape Report
A vulnerability in Trellos API configuration
led to a massive data leak in January 2024,
where over 15 million user records were
exposed on a dark web forum. Trello, a
popular project management platform, had
an API endpoint that inadvertently allowed
open access to sensitive user data, including
project details, personal information, and
task management records. Hackers were
able to scrape this data due to
misconfigurations in Trellos API permissions,
underscoring how quickly API flaws can
result in serious data leaks.
In July 2024, Twilios Authy service suffered a
IN 2024, DEUTSCHE TELEKOM REPORTED APPRO
XIMATELY 259M MOBILE CUSTOMERS WORLD
WIDE 
In July 2024, German security expert Lilith
Wittmann discovered an unprotected API
from Deutsche Telekom, that could be used,
to retrieve details about landline connections
via their internet access. While the exact
number of affected users was not disclosed,
it exposed sensitive user data such as names,
email addresses, and service usage details.
The open API lacked adequate access
controls, allowing unauthorized parties to
access this information. This incident
highlights the critical need for robust API
governance to prevent data exposure and
protect customer privacy.
2024'S CASES OF VULNERABLE
APIS EXPOSED IN THE WILD
In May 2024, Dell experienced a significant
data breach when a threat actor exploited an
unsecured API endpoint on a partner portal.
This 
vulnerability 
allowed 
unauthorized
access to approximately 49 million customer
records, 
including 
names, 
physical
addresses, 
and 
order 
information. 
The
breach highlighted the risks associated with
insufficient API security measures and the
potential for large\-scale data exposure.
IN 2024, DEUTSCHE TELEKOM
REPORTED APPROXIMATELY 259M
MOBILE CUSTOMERS WORLDWIDE 
While this approach provided a substantial data set, we recognize potential biases. Lar
ger domains with extensive resources may employ stronger security measures, potentially leading to fewer vulnerable APIs. However, our study focused on the largest American companies without specifically accounting for this bias.
Alternatively, with over 365 million domain names reported across the internet, our sample size becomes relatively small, potentially leading to greater volatility in the number of findings.The data collection was a one\-time process. During the collection, we enc
ountered several limitations. To respect legal and ethical boundaries, we deliberate
ly excluded certain types of 
domains. This included governmental, educational, and health\-related domains, as regular users are not typically authorized to explore these. This decision ensured that our study aligned with ethical norms for web crawling and data collection practices, prioritizing responsible research standards.capitalization\-weighted index of the 40 most significant stocks among the top
100 companies by market cap on Euronext Paris.
While this approach provided a substantial data set, we recognize potential biases. Larger
domains with extensive resources may employ stronger security measures, potentially
leading to fewer vulnerable APIs. However, our study focused on the largest American
companies without specifically accounting for this bias.
Alternatively, with over 365 million domain names reported across the internet, our sample
size becomes relatively small, potentially leading to greater volatility in the number of
findings.
Methodology
Data Gathering Strategy
The data collection was a one\-time process.
During the collection, we encountered several
limitations. To respect legal and ethical
boundaries, we deliberately excluded certain
types of domains. This included governmental,
educational, and health\-related domains, as
regular users are not typically authorized to
explore these. This decision ensured that our
study aligned with ethical norms for web crawling
and data collection practices, prioritizing
responsible research standards.
unique top\-level domains analyzed
In\-Depth API Discovery Process
Escape uses a sophisticated combination of techniques to identify and inventory APIs by
scanning exposed source code:
Subdomain enumeration
Escape begins by performing subdomain enumeration. This process involves scanning for all
subdomains associated with the main domain you previously entered into the platform.
Subdomains often host APIs or services that may not be immediately apparent. By identifying
these subdomains, Escape can uncover additional endpoints that might otherwise be missed.
This initial step lays the foundation for a comprehensive discovery process.
AI\-powered fingerprinting
Once subdomains are identified, Escape employs AI\-powered fingerprinting to recognize and
classify the APIs. Fingerprinting involves analyzing various characteristics of the APIs, such
as their structure, endpoints, and response patterns. The AI algorithms used by Escape can
detect and categorize different API types (REST, GraphQL, gRPC) with high accuracy. This
machine learning\-based approach ensures that APIs are identified and classified correctly,
even if they have unique or non\-standard configurations.
OSINT techniques
Escape also leverages Open Source Intelligence (OSINT) techniques. OSINT involves
gathering and analyzing publicly available information to enhance the discovery process. By
examining code repositories, documentation, and other public resources, Escape can identify
additional API endpoints and services. This technique helps in discovering APIs that are not
directly exposed but can still be found through public information.
Through this multi\-layered process, we discovered 158,079 subdomains, allowing for
extensive coverage and a highly detailed analysis. This broad scope provided a deep view
into the exposure and security practices around APIs across various industries, offering
critical insights into the current landscape of API security and vulnerability.
Methodology
1K
unique top\-level domains
analyzed

MethodologyAPI specifications found in the wild
Automated API Specification Generation
API specifications programmatically generated
Having an OpenAPI Specification (OAS) is particularly beneficial as it provides a
standardized, machine\-readable format for documenting RESTful APIs, promoting clarity and
consistency across services.Through our initial scan, we located 4,547 exposed API specifications, so we had to generate
most of the specifications ourselves. This process involved parsing the Abstract Syntax Tree
(AST) from the code to create dynamically detailed and accurate API specifications.
Luckily, Large Language Models (LLMs) have recently become extremely good at analyzing
and generating code. Moreover, they show great performance across a wide variety of code
languages, frameworks, and coding styles, which is exactly what we want for framework and
language\-agnostic OAS generation software. Finally, LLMs can also leverage information in
code comments, which the traditional static analysis approach cannot do.
In our current approach, integrated into Escapes platform, we focused on two key areas:
Semantic Analysis: We identify essential code fragments using custom rules (e.g
Semantic Analysis: We identify essential code fragments using custom rules (e.g sp
ecific S
emgrep patterns), optimizing the data sent to the LLM and enhancing prompt quality.
Specification Generation: The LLM processes each identified fragment to ge
nerate precise OAS methods, with contextuali
zation ensuring accuracy by resolving dependencies and references within the 
code.
time.
4\.5K
API specifications
found in the wild
29\.7K
API specifications
programmatically generated
MethodologyAPI services scanned for vulnerabilities
Final step \- API Security Scanning
After the comprehensive specification generation process, the final step is API security
scanning. Using Escapes Dynamic Application Security Testing (DAST) solution, we conducted
in\-depth analysis of each identified API endpoint to detect potential vulnerabilities and risks.
Escapes DAST approach is specifically designed for API security. Unlike traditional web
application DAST tools, which are often limited in scope and primarily test web applications at
the surface level, Escapes DAST is purpose\-built to handle the unique requirements and
complexities of APIs. This makes it exceptionally effective at identifying security flaws in API
configurations, authentication, authorization, and more.
At the core of Escape's DAST is a proprietary algorithm that combines static and dynamic
analysis to deliver precise, high\-confidence results. The algorithm operates in multiple stages:
Contextual Analysis: The algorithm first conducts a contextual analysis of each endpoint,
 identifying the APIs structure, parameters, and dependencies. This allows it to adapt it
s scanning approach to each specific API, ensuring relevance and reducing false positives.
1\. Fuzzing and Payload Injection: In the next stage, the algorithm uses fuzzing techniques to
 test each endpoint by sending random, unexpected, or malformed inputs. This help
s identify weaknesses like input validation flaws, injection vulnerabilities, a
nd misconfigurations. The algorithm adapts these payloads based on real\-time feedba
ck, simulating complex attacks more effectively than conventional static methods.
1\. Behavioral Monitoring: As it interacts with each endpoint, the algorithm monitors response
 patterns and behaviors to detect anomalies. By observing responses over multipl
e interactions, it can identify issues such as data exposure, error leakage, and misconfigur
ed permissions, providing insights into the APIs security posture.
1\. Risk Prioritization: Escapes DAST concludes with an analysis that ranks detected
 vulnerabilities based on risk and classifies them based on the metric named Escape severity.Escape
severity.
1\. You can find an in\-depth technical explanation of the algorithm here.
30,784
API services scanned
for vulnerabilities
The complete event\-based architecture of the Escape Security Scanner, with the reinforcement loop in the center
Final step \- API Security Scanning
The complete event\-based architecture of the Escape Security Scanner, with the
reinforcement loop in the center
Findings \- API Exposure
30,784
API services exposed
3,945
development APIs exposed, 
including 6 organizations with more than
100 development APIs exposed per domain 
\* 5 from Fortune 1000 and 1 from CAC40
1,189
maximum exposed APIs per one domain
Findings \- API Exposure
3,001
REST APIs
91%
APIs exposed, including 
more than 166 exposed staging APIs
by one Fortune 1000 organization
0\-10
11\-50
51\-100
101\-200
200\+
0,000
50,000
100,000
150,000
200,000
250,000
300,000
227,000
259,000
156,000
156,000
230,000
Number of Domains Exposing a Given
Range of API Services
AWS
51\.1%
AZURE
16%
CLOUDFLARE
10\.7%
AKAMAI
8\.2%
GCP
7\.5%
FASTLY
4\.9%
IBM
0\.6%
maximum exposed APIs per on
e domain
28\.5K
among Fortune 1000
8\.1K
Total vulnerabilities fou
nd
240 highly critical 
Highly critical
107,368
vulnerabilities found among Fortune 1000 organizations (large tech orgs. like Amazon, Google or Meta excluded)
2,038
Highly critical
Distribution of highly critical vulnerabilities
98\.8K
API vulnerabilities found among CAC40 or
ganizations, including 240 highly critical 
1\.8K
highly critical
high risk CVEs found
11
API services vulnerable to SQL injection
10
API services vulnerable to BOLA
API services vulnerable to
BOLA
API8:2023 API2:2023 API9:2023 API7:2023 API1:2023
0
200
400
600
800
746
381
30
32
10
Alignment of high\-risk Fortune 1000 vulnerabilities
with OWASP Top 10 2023 classification
Findings42
average vulnerabilities per domain
domains are above the
average
domains are above the average
average vulnerabilities per
domain
the biggest number of medium\-risk vulnerabilities per
exposed domain
the biggest number of medium\-risk vulnerabilities per exposed domain
(an insurance company based in the US)
the biggest number of high\-risk vulnerabilities
 per exposed domain
Insurance
Technology
Healthcare
Automotive
Retail
Financial Services
Real Estate
Manufacturing
Aerospace
(same insurance company)
(same insurance company)
205
Findings \- API Secrets
Total secrets found
29
29
AWS Access Token
Bearer Token
Generic API Keys
geocodio
Github App Token
Github OAuth
graphcms
hashicorp\_tf\_password
jdbc
Jira Token
JWT
md5
Password
Phone number
Plaid Secret Key
SSH URL
YouTube apikey
0,000
10,000
20,000
30,000
40,000
6,000
6,000
2,000
4,000
8,000
2,000
3,000
7,000
7,000
5,000
3,000
17,000
3,000
38,000
5,000
1,000
6,000
6,000
2,000
4,000
1,000
8,000
2,000
3,000
7,000
7,000
5,000
3,000
17,000
3,000
38,000
5,000
Highly critical
This time, we did not scan for secrets exposed in front\-end
applications, as we have already covered that topic in our previous
report. Instead, we focused on secrets accessible through vulnerable
APIs identified by our DAST scans.
High impact secrets found
exposed development
 APIs
highly critical vulnerabilities
Among the exposed APIs, we identified at least 198 critical vulnerabilities, including various
CVEs and OWASP Top 10 risks, such as API2:2023: Broken Authentication and API8:2023:
Security Misconfiguration. These vulnerabilities include risks that could allow unauthorized
access to sensitive data, privilege escalation, and potential unauthorized control over critical
applications. The nature and distribution of these vulnerabilities indicate a systemic gap in
security practices across development environments, as many of these APIs lack proper
access control, authentication, and monitoring.
More than that, our analysis highlighted that six organizations were particularly impacted, each
with over 100 exposed development APIs within their domains. Of these:
Five organizations are listed within the Fortune 1000 companies, representing some of
the largest and most influential corporations globally.
One organization is part of the CAC40 index, underscoring that even prominent
European enterprises are not immune to these security oversights.
Five organizations are listed within the Fortune 1000 companies, representing some of the largest and most influential corporations globally.
One organization is part of the CAC40 index, underscoring that even prominent European ente
rprises are not immune to these security oversights.
3,945
exposed development APIs
198
highly critical vulnerabilities
highly critical vul
nerabilities found (very large tech orgs. like Amazon, Google or Meta etc. were excluded)
companies impacted, some in highly r
egulated industries like financial 
services
We dug into the specifics and found
some troubling patterns. According to
the OWASP API Security Top 10 for
2023, vulnerabilities like Broken
Authentication (API2:2023\) and
Security Misconfiguration (API8:2023\)
were rampant, with 381 and 746
instances respectively. 
1\.8K
highly critical vulnerabilities found (very
large tech orgs. like Amazon, Google or
Meta etc. were excluded)
316
companies impacted, some in highly
regulated industries like financial
services
API8:2023
62\.2%
API2:2023
31\.8%
API7:2023
2\.7%
API9:2023
2\.5%
Alignment of high\-risk Fortune 1000 vulnerabilities
with OWASP Top 10 2023 classification
Many of these APIs lacked even the most basic access controls, allowing for unauthorized data
access or manipulation. A staggering 19 NoSQL injection vulnerabilities and 11 SQL injection flaws
were scattered across APIs, with 10 instances of Broken Object Level Authorization (BOLA)all
creating a perfect storm for potential exploitation.
It is clear that API security practices hadnt kept up with the growing reliance on APIs across
industries, revealing a systemic gap in both development and deployment practices. To tackle this,
companies need to close the gap with immediate action: strengthen access controls, enforce secure
configurations, and regularly test APIs to catch issues before they become threats.
By design, Actuator exposes diagnosti
c and monitoring data, such as environment variables, configuration properties, and detailed mappings of application routes. However, if not properly secured, these endpoints can inadvertently expose sensitive information about an applications internal state, providing attackers with critical insights that can be leveraged to exploit vulnerabilities.
During a security assessment of one of the exposed API endpoints o
wned by a major American technology company, we gained unrestricted access to several Spring Boot Actuator endpoints, specifically:
https:\[redactedcompanydomain.com]adminactuatorenv
https:\[redactedcompanydomain.com]adminactuatormappings
https:\[redactedcompanydomain.com]adminactuatorhttptrace.
Each of these endpoints revealed sensitive details about the applications environment, structure, and operations, collectively presenting a substantial security risk.
The first significant finding was with the env endpoint, which revealed critical environment variables in plain text. Upon loading the endpoints response, it became clear that sensitive informationsuch as database credentials, API keys, and service tokenswas accessible without any obfuscation. Exposure of these variables presents a substantial risk, as they can provide unauthorized actors with the means to gain elevated access, move laterally through systems, and potentially launch further targeted attacks on backend services.
Further investigation led to the mappings endpoint, which disclosed a comprehensive ma
p of the APIs routing structure. This included not only public endpoints but also private routes intended for restricted internal use. By detailing the APIs route mappings and configuration, the endpoint unintentionally provided a roadmap of the systems structure, revealing potential entry points and avenues for exploitation. In the hands of an attacker, this visibility into the applications internal architecture could simplify the task of identifying weak spots and exploiting vulnerabilities in a targeted manner.
The third exposed endpoint, httptrace, offered a detailed log of recent HTTP requests, compl
ete with request headers, response statuses, and metadata. This level of trace data, includin
g potential session cookies and internal IP addresses, can significantly aid an attac
ker in reconstructing user behavior, mimicking legitimate requests, or even hijacking active 
sessions. Such logs can facilitate a range of attacks, from session replay to broader reco
nnaissance efforts, making the exposure of this endpoint particularly sensitive.
 as database credentials and API keys, to prevent accidental exposure.
The third exposed endpoint, httptrace, offered a detailed log of recent HTTP requests,
complete with request headers, response statuses, and metadata. This level of trace data,
including potential session cookies and internal IP addresses, can significantly aid an
attacker in reconstructing user behavior, mimicking legitimate requests, or even hijacking
active sessions. Such logs can facilitate a range of attacks, from session replay to broader
reconnaissance efforts, making the exposure of this endpoint particularly sensitive.
 as database credentials and API keys, to prevent accidental exposure.
American multinational tech company: 
Exposed Spring Boot Actuator
Restrict Access to Actuator Endpoints:
Implement access control to ensure that sensitive Actuator endpoints, such as env, mappings, and httptrace, are accessible only to authorized users on the internal network or authenticated users with administrative privileges.
Disable Sensitive Actuator Endpoints in Production:
1\. Configure the Spring Boot Actuator settings to disable endpoints like env, mappin
gs, and httptrace in the production environment, or at least restrict them to aut
horized, internal users only.
Obfuscate Sensitive Data in env:
1\. In cases where env must be used, consider redacting or obfuscating sensitive environm
ent variables, such as database credentials and API keys, to prevent accidental exposu
re.
Monitor and Log Access Attempts to Actuator Endpoints:
1\. Implement logging and monitoring of all access attempts to these endpoints, e
nabling detection of any unauthorized access and facilitating incident respo
nse.
Overall, this assessment underscores how easily operational details can become visible without proper restrictions, turning what might otherwise be routine endpoints into critical vulnerabilities. Addressing these exposures is essential to uphold the security and integrity of the companys infrastructure.
1\. Implement logging and monitoring of all access attempts to these endpoints, enabling
detection of any unauthorized access and facilitating incident response.
Overall, this assessment underscores how easily operational details can become visible
without proper restrictions, turning what might otherwise be routine endpoints into critical
vulnerabilities. Addressing these exposures is essential to uphold the security and integrity
of the companys infrastructure.
Standout Scenarios: 
High\-Impact CVEs in the WildTotal High Impact CVEs Found
This section highlights critical cases where APIs, compromised by known CVEs (Common Vulnerabilities
and Exposures), are openly accessible on the internet. These vulnerabilities, if unaddressed, can serve
as entry points for malicious actors to exploit vulnerable API services.
Distinct High Impact CVEs Types
98
High Impact CVEs in 2024, with CVE\-2024\-5535 as a clear leader
Top 5 CVE occurencies 
0
20
40
60
80
100
CVE\-2024\-5535
CVE\-2022\-2274
CVE\-2022\-2068
CVE\-2022\-1292
CVE\-2021\-3711
95
70
70
57
57
98
Distinct High Impact CVEs
Types
Prevalence of OpenSSL Vulnerabilities: A lot of found CVEs are associated with OpenSSL, a widely used library for secure communications. APIs leveraging OpenSSL must ensure they are using updated versions to mitigate these vulnerabilities.
Risk of Remote Code Execution:
 Several vulnerabilities, notably CVE\-2022\-2274 and CVE\-2021\-3711, can lead to remote code execution if exploited, posing severe risks to API integrity and security.
Importance of Input Validation: Vulnerabilities
 like CVE\-2022\-2068 and CVE\-2022\-1292 highlight 
the critical need for proper input validatio
n to prevent command injection attacks.
Legacy Vulnerabilities: A significant 
number of older CVEs, frequently appearing from
 2020 through 2023, continue to impact APIs. Th
is trend suggests that many organizations struggle 
to patch legacy vulnerabilities. These unpatched older CVEs are often well\-documented, making them attractive targets for attackers who can easily exploit known weaknesses.
Organizational Impact of Unaddressed CVEs: The prese
nce of these CVEs in production may affect co
mpliance with security standards and lead to potenti
al regulatory issues. Furthermore, should these CVEs be exploited, the resultant damage could impact not only security but also customer trust and business continuity.
Legacy Vulnerabilities: A significant number of older
CVEs, frequently appearing from 2020 through 2023,
continue to impact APIs. This trend suggests that
many organizations struggle to patch legacy
vulnerabilities. These unpatched older CVEs are often
well\-documented, making them attractive targets for
attackers who can easily exploit known weaknesses.
Organizational Impact of Unaddressed CVEs: The
presence of these CVEs in production may affect
compliance with security standards and lead to
potential regulatory issues. Furthermore, should these
CVEs be exploited, the resultant damage could
impact not only security but also customer trust and
business continuity.
CVE\-2021\-3711 (57 instances) 
As an older CVE, if it pertains to
cryptographic weaknesses or data
exposure, it would directly impact APIs by
potentially making data\-in\-transit
vulnerable
Diiscovered CVEs map
 to several key CWEs associated with common API weaknesses. Here are the main categories of weaknesses found in the list and their implications for API security:
Diiscovered CVEs map to several key CWEs associated with common API weaknesses. Here
are the main categories of weaknesses found in the list and their implications for API security:
Relevance: Improper input validation is one of the most common vulnerabilities in API systems, where unvalidated or poorly sanitized inputs can lead to injection attacks, unauthorized access, or unintended behavior.
Implications: APIs with CWE\-20 vulnerabilities are susceptible to attacks that bypass
 intended restrictions, exploit business logic flaws, or cause unexpected outcomes.
Implications: APIs with CWE\-20 vulnerabilities are susceptible to attacks that bypass
intended restrictions, exploit business logic flaws, or cause unexpected outcomes.
Relevance: Command injection can lead to unauthorized command execution on the server
, enabling attackers to gain deeper access to systems.
Implications: CWE\-78 vulnerabilities in APIs are especially dangerous as they can prov
ide attackers with access to server operations, potentially allowing unauthorized data access, privilege escalation, or remote code execution.
Implications: CWE\-78 vulnerabilities in APIs are especially dangerous as they can provide
attackers with access to server operations, potentially allowing unauthorized data access,
privilege escalation, or remote code execution.
Relevance: Integer overflows occur when calculations exceed the allocated storage for integers, leading to unexpected or unsafe values. In APIs, such vulnerabilities can be used to bypass restrictions or overflow buffers.
Implications: Vulnerabilities in this category make APIs susceptible to buffer overfl
ows or logic manipulation, often leading to crashes or arbitrary code execution.
Implications: Vulnerabilities in this category make APIs susceptible to buffer overflows or
logic manipulation, often leading to crashes or arbitrary code execution.
Relevance: API communications rely heavily on encryption for data protection, especially when handling sensitive information. Poorly implemented cryptographic measures expose APIs to data interception or decryption attacks.
Implications: Weak cryptographic implementations in APIs can lead to data leakage, man\-i
n\-the\-middle (MitM) attacks, or unauthorized data access.
Implications: Weak cryptographic implementations in APIs can lead to data leakage, man\-
in\-the\-middle (MitM) attacks, or unauthorized data access.
Relevance: A null pointer dereference occurs when a program attempts to access or modify data at a null (nonexistent) memory location. In APIs, these vulnerabilities often lead to application crashes or denial of service.
Implications: API systems with CWE\-476 vulnerabilities may be exploited to cause applica
tion disruptions, affecting service availability and reliability.
Addressing these CWEs through consistent validation, secure cryptographic practi
ces, and boundary checks is essential to reduce attack surfaces in API environments.
Addressing these CWEs through consistent validation, secure cryptographic practices, and
boundary checks is essential to reduce attack surfaces in API environments.
Essential remediation steps
This extensive exposure of vulnerable APIs underscores a critical security issue.
If you have publicly accessible APIs or are uncertain about whether your developers
 adhere to best practices to prevent unsecured staging or development APIs from bein
g exposed, we recommend taking the following actions immediately:
Conduct a Comprehensive API Audit: Review all public\-facing APIs to identify any
 endpoints that are exposed unintentionally. This includes testing for staging
, development, and unused APIs that may have been left accessible. Categorize AP
Is based on sensitivity, usage, and the type of data they handle. This helps priorit
ize which APIs require immediate attention and remediation.
Deactivate Unused or Duplicate APIs: Regularly review and disable APIs that are no
 longer in use or required. This practice helps reduce the attack surface of you
r application and minimizes potential security risks associated with outdated 
or redundant APIs.
Recheck for Exposed API Secrets: Conduct a thorough check to ensure that API keys,
 tokens, and other secrets are not exposed in public repositories, documentation, o
r within API endpoints. Implement automated secret scanning tools to prevent su
ch exposures continuously.
Implement an API Governance Strategy: Establish a robust API governance strategy to
 manage the growing number of APIs across your organization. This strategy shoul
d include standardized processes for API development, documentation, versioning, a
nd security, ensuring consistency and reducing the risk of unsecured APIs.
Enforce Authentication and Authorization: Ensure all APIs are protected with strong
 authentication and authorization mechanisms. Use industry\-standard methods lik
e OAuth 2\.0, JWT tokens, and role\-based access controls to restrict access and preve
nt unauthorized use.
Implement Automated API Discovery: Deploy automated API discovery tools to
 continuously scan and catalog all APIs, including shadow, unused, and potentiall
y exposed APIs. This proactive approach ensures full visibility of your API environment.
Implement an Automated Security Solution that Can Start Scanning in Minutes:
 Utilize a security solution that enables immediate scanning of your API ecosystem fo
r vulnerabilities and misconfigurations. A solution that provides quick setup and fa
st scanning capabilities can help identify and mitigate risks efficiently without disrupt
ing workflows.
Educate Your Internal Teams: Ensure that all team members understand the
 importance of token security and adhere to best practices. Consider enhancing th
e security experience through gamification or implementing a Security Champi
on Program, following The Security Champion Program Success Guide.
These measures are crucial for 
protecting your APIs and maintaining secure and compliant applications. For more detailed information, you can use our API Security Checklist or refer to the resources provided on the Escape blog.Escape blog.
ANY API
ARE THEY OPEN TO 
THE INTERNET?
YES
Immediate steps to take
NO
IS IT BY DESIGN?
HARDEN YOUR 
API ENVIRONMENT 
We also prepared a handy diagram to help you understand your environment and
mitigate the risks with confidence:
AUTOMATE API CATALOG 
(ENSURE ALL APIS AND THEIR VERSIONS ARE DOCUMENTED)
DEACTIVATE UNUSED OR DUPLI
CATE APIS
REGULARLY SCAN FOR
 APIVULNERABILITIES
SCAN FOR EXPOSED 
API SECRETS
ENFORCE STRONG AUTHENTICATION AND AUTHORIZATION
API SECRETS
TAKE IMMEDIATE 
ACTION
NO
YES
NO
YES
AM I ALLOWING TO ACCESS 
API WITHOUT
AUTHENTICATION
PATCH IMMEDIATELY
YES
NO
SCAN TO VERIFY THAT THERE
ARE NO API SECRETS
ACCESSIBLE
HARDEN YOUR SECURITY
POSTURE
Securing all your APIs is hard. Its even harder when you dont know what you have to secure, want to ship (insecure) APIs too fast in the wild and have to monitor them at large scale. Your organization is now not only prone to data breach risks but also to severe financial implications.Our study reveals that over 100,000 vulnerabilities are present across Fortune 1000 and CAC 40 companies, with 1,800 classified as highly critical, directly impacting some of the largest organizations globally.
One of the most striking findings was the extensive exposure of vulnerable developmen
t APIs and the high level of overall vulnerability criticality. This highlights the real an
d present dangers for each organization and the necessity of thoroughly testing applic
ations both before and after deployment.
Moreover, we identified that organizations continue to expose sensitive secrets, includ
ing access tokens and API keys, within their API environments, amplifying security risks a
nd potential misuse.
Organizations must respond fast, adopting best practices for risk mitigation and integ
rating continuous, automated testing of their applications. 
Are you looking to automate discovery and security of your APIs at scale, improve your org
anization's security posture and need to ensure compliance with standards like HIPAA, GD
PR, and PCI DSS?
Our team is here for you. We'll help identify your online exposures and provide strategic ad
vice on implementing effective security practices. Feel free to reach out! 
Are you looking to automate discovery and security of your APIs at scale, improve your
organization's security posture and need to ensure compliance with standards like HIPAA,
GDPR, and PCI DSS?
Our team is here for you. We'll help identify your online exposures and provide strategic
advice on implementing effective security practices. Feel free to reach out! 
escape.tech
ping@escape.tech
\+1 (707\) 615 6448
Automate the discovery of all APIs at scale
Automate API documentation generation
Ensure comprehensive security coverage with 130\+ API security tests,
including OWASP Top 10, business logic, and access control
Automated security scanning by plugging Escapes modern DAST into
your CICD systems 
Learn more
Learn more
Do you need help in assessing whether your APIs are exposed and at risk?
Were here for you. With Escape you can: