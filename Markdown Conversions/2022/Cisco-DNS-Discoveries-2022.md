2022 DNS DiscoveriesUsing DNS to Uncover Trends and 
ProtectAgainst ThreatsSecurity ReportCisco PublicThe threat landscape is always changing. Billions of ever\-expandingconnections are made every day by organizations across the internet.Thereare more things to protect than ever before. Work patterns areconstantly shifting, which means businesses are more vulnerable againstincreasingly sophisticated attacks.Cisco Secure has a unique vantage point 
when it comes to cybersecurity. We know 
that you cant protect what you cant see. 
Because we resolve more than 620 billion 
daily DNS requests, we see more threats, 
more malware, and more attacks than any 
other security vendor in the world.We also power all Cisco Secure services with 
the threat intelligence of Cisco Talos. Talos isthe largest non\-governmental threat research 
organization in the world, made up of an elite 
group of security experts.These massive data sets and expert security 
researchers power our threat research and 
provide unmatched threat intelligence to stop 
attacks earlier. Its this foundation that lets us 
see and understand threats sooner and block 
them faster.DNS for Security: An Underrated Part of 
aModernSecurity PostureThe domain name system (DNS) was 
created to connect, not to protect. It was 
meant to connect users to websites or 
applications quickly and correctly, and it 
forms the foundation of internet. People 
use DNS thousands of times a day without 
knowing it every time a user connects to 
a website, opens an app on their phone, or 
updates software, their device queries DNS 
servers to find the IP address associated with 
thedomain.The Domain Name System (DNS) 
allows clients to connect to websites, 
perform software updates, and 
use many of the applications 
organizationsrely on.Since most organizations dont bother to 
secure the DNS layer, they might be missing 
opportunities to block cyberattacks.A recent report by Global Cyber Alliance 
explored the Value of DNS Security, and 
found that:1 in 3 breaches could have beencontained by DNSBillions of dollars in major losses could 
have been prevented by DNS\-layer 
securityMany of todays sophisticated attacks rely 
on DNS activity. This report looks at the top 
threats that exploited DNS for cyberattacks, 
as well as how DNS\-layer security provides 
better accuracy and detection of malicious 
activity and compromised systems2022 DNS Discoveries\|2Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved.Threat 1: MalwareDefinition: Malware is intrusive software that is designed to damage and destroy computers and 
computer systems. Malware is a contraction for malicious software. Examples of common 
malware include viruses, worms, Trojan viruses, spyware, adware, and ransomware.70% of organizations have users that wereserved malicious browser ads.48% of businesses foundinformation\-stealing malware activity.One type of malware, aptly called information 
stealers, is a shortcut to stealing credentials, 
passwords, and other sensitive or confidential 
information. It can compromise email 
programs, messaging apps, browsers, and 
more, stealing data and hijacking control of 
other programs and systems along the way.Real\-life threat: MassloggerThe malware campaign Masslogger focuses 
on business users and is delivered by email. 
The malicious email contains an RAR file with 
a compiled HTML (.chm)attachment.When the user opens the attachment, it 
launches the chain of exploitation, which 
results in MassLogger malware being installed 
on the workstation.This version of Masslogger retrieves 
credentials from applications such as Pidgin 
messenger client, FileZilla FTP client, Discord, 
NordVPN, Outlook, FoxMail, Thunderbird, 
FireFox, QQ Browser, and Chromium\-based 
browsers (Chrome, Chromium, Edge, 
Opera,Brave).Cisco UmbrellaMalspamWeaponized 
RAR fileFirst stage 
CHM file 
with JSSecond 
stage PS 
scriptDownloads 
MassLogerData 
extractionInformation stealer that arrives as an email with a RAR attachment containing
a malicious .chmfile.Potential damage:Can steal credentials from email clients, messaging applications, browsers, VPN, and 
FTPclients, which can be used to take over further systems.2022 DNS Discoveries\|3
2022 DNS Discoveries\|3Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved.Threat 2: PhishingDefinition: Phishing is the practice of sending fraudulent communications that appear to come 
from a reputable source. These attacks are usually performed through email. The goal is to steal 
sensitive data like credit card and login information or install malware on the victimsmachine.86% of organizations have had at least one user try to connect to a phishing sitePhishing attacks account for 90% of data breachesReal\-life threat: Conti ransomwareConti ransomware infection often begins with 
delivery of a malicious JavaScript file as an 
attachment in a phishing email.If run on a Windows system, a DLL of IcedID 
is installed and the system starts beaconing 
to C2 servers. The C2 connections are 
the only activity for a few days, then a 
CobaltStrike beacon is installed.Within hours, threat actors use the IcedID 
DLL and Cobalt Strike payloads to explore 
thesystem, escalate privileges, move 
laterally, exfiltrate data, and finally encrypt 
all systems with AES\-256 using the Conti 
ransomware. While encrypting files, Conti 
continues attempting to connect to other 
systems usingSMB.Cisco UmbrellaPhishingMalicious JSIcedID DDLCobalt Strike 
BeaconRDPData 
ExfiltrationData 
Encryption2022 DNS Discoveries\|4
2022 DNS Discoveries\|4Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved.Threat 3: Command \& ControlDefinition: A command\-and\-control \[C2] server is a computer controlled by an attacker which is 
used to send commands and remotely control compromised systems.Cisco Umbrella threat intelligence detected an increase in command\-and\-control traffic starting 
in April 2021, which increased to a 31% higher than average rate by July 2021\.Real\-life threat: BazarLoaderWhile BazarLoader has used a variety of 
tactics over the years, this particular malspam 
campaign sends emails that claim recipients 
need to unsubscribe from a trial service to 
avoid credit card charges. The attack leads to 
a legitimate\-looking website operated by the 
threat actors.When a user tries to unsubscribe, the page 
delivers a malicious Excel or Word document, 
which ultimately downloads BazarLoader. 
This malware strain uses C2 domains withthe .bazar and hosting that is designed to 
make it very difficult, if not impossible, for law 
enforcement to take over these domains.C2 activities include but are not limited 
to profiling, downloading additional 
payloads, executing PowerShell scripts, 
killing processes and services, and deleting 
itself.After that, follow\-up malware (such as 
commodity trojans like Trickbot, infostealers, 
and ransomware) is downloaded on the 
compromised systems.Cisco UmbrellaMalspamSocial 
EngineeringDownloads 
Weaponized 
DocumentsDownloads 
BazarLoaderC\&CLoader used to gain a foothold in compromised networks.Potential damage:Can deliver wide variety of secondary payloads, such as ransomeware, infostealers, or tools 
providing further control of network.2022 DNS Discoveries\|5
2022 DNS Discoveries\|5Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved. 
Threat 4: Malicious CryptominingDefinition: Malicious cryptomining malware is a browser or software\-based threat that enables 
bad actors to hijack system resources to generate cryptocurrencies.The technology sector sees far more cryptomining traffic than any other industryCryptomining generated the most DNS traffic out of any individual category. Its relativelynoisy on the DNS side, as it regularly pings mining servers for morework.Real\-life threat: The lifecycle of a malicious cryptomining attack chainMalicious cryptomining attacks often 
infiltrate networks by exploiting public\-facing 
infrastructure thats not fully protected. Once 
these unpatched systems are accessed, 
the threat actors use the processing power 
of business\-critical infrastructure to mine 
cryptocurrency, making money by using 
others resources for their own gains.Unauthorized cryptomining in your network 
can lead to performance degradation, 
increased energy consumption, or disruption 
of productivity. Plus, once an attacker has 
a foothold in your network, they can deploy 
other malware.Malicious Cryptomining Attack Chain1\. A vulnerability is discovered in software 
frequently found running on publicly 
accessibile company servers.2\. Malicious actors develop and shareexploits.3\. Attackers scan the internet to identifyvulnerable infrastructure.4\. When vulnerable infrastructure is found,attackers do the following:Use the exploit against companyservers.Deploy malicious scripts from C2servers5\. Automation takes over, and:Scripts download cryptocurrency minersCryptominers contact mining pools2022 DNS Discoveries\|6
2022 DNS Discoveries\|6Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved. 
Additional ways Cisco Umbrella leverages DNS to protect organizationsCybersecurity is about more than just 
protecting whats happening now, but 
also about whats happening next. 
Our DNS data sources are massive and 
diverse; it represents many markets, geos, 
and protocols. The research models are 
continuously run against this data so we can 
uncover malicious domains, IPs, and URLs 
before theyre even used in attacks. Our 
security researchers are always innovating 
and creating new models to provide better 
threat detection and classification.That means we can see more and use all the 
patterns, trends, and telemetry that we see 
every day to know what to pay attention to 
and protect going forward.Detect and block newly seen domainsNew domains are created and published 
every day, but they arent all used for 
legitimate purposes. Bad actors use new 
domains to host and deliver spam, malware, 
or botnets, often in the first minutes of the 
new domain being createdNewly seen domain category reduces risk of the unknownAttacker registers domain1\. Any user (free or paid) requests the domain
1\. Every minute, we sample from our streamine DNS logs
1\. Check if domain was seen before and if allowlisted
1\. If not, add to category, \& within minutes DNS resolvers update globallyDomain used in an attackBefore expiration if any user requests this 
domain, it's logged or blocked as newly seenLater, Talos intelligence 
models or reputation 
systems identify 
asmaliciousCisco 
UmbrellaReputation 
Systemsnot yet a threatpotentially unprotectedprotectednot yet a threatunprotectedprotectedDays to WeeksMinutes24 Hours2022 DNS Discoveries\|7
2022 DNS Discoveries\|7Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved.Newly seen domain example (mcorecari.com)Real\-life threat: DNS\-tunneling exampleHere, an attacker has incorporated 
aDNStunneling kit into an authoritative 
DNS nameserver and installed malware with 
aDNS tunneling client on a compromised 
system. DNS tunneling attacks are particularly 
difficult to block as they only occur at the 
DNS layer, so many other security tools dont 
blockthese.The attacker issues an encoded command(aop1\) that will tell the malware 
on the compromised computer to 
collectcredentials.The command is added to the domain(aop1\.18\-ququ.example.com) and sent 
over DNS.The malware receives the command andcollects the credentials.The malware encodes them and sendsthem back over DNS. (eui8\)A domain named mcorecari.com was 
discovered by Umbrella, categorized 
as Newly Seen Domain on Wednesday, 
September 22, 2021 6:14 AM. Newly 
Seen Domains (NSD) is a security category 
that identifies domains that have been 
queried for the first time within the past 24 
hours by any user of Cisco Umbrellas DNS 
service. Domains stay in the list for a period 
of24hours.Later that same day, at 10:44 PM, the 
mcorecari.com domain was used in a 
phishing attack, impersonating a large bank 
in Japan. It was subsequently categorized as 
Phishing and blocked by Cisco Umbrella.DNS tunnelingBecause DNS traffic is widely used, it is often 
blindly trusted.DNS tunneling allows malware 
authors to communicate in a covert channel. 
Threat actors use DNS tunneling techniques 
to exfiltrate sensitive data out of corporate 
networks or to send malicious commands to 
be executed as part of an attack chain. DNS 
tunneling can also be used to circumvent 
security controls and even obtain free WIFI by 
bypassing authentication steps.DNS\-Tunneling exampleMalware with 
Tunneling clientRecursive DNSAuthoritative DNSAttackereui8\.18\-ququ.example.comeui8\.18\-ququ.example.comaop1\.18\-ququ.example.comaop1\.18\-ququ.example.comeui8aop1Nameserver for 
example.comEncoded 
credentials: 
eui8aop1: collect 
credentialsusername
passwordEncoded information in DNS communications:{qname: vaaaakaw0i2\.iodine.umbrella\-
tunnel\-test.com qtype: 1}
{qname: vaaaakaw0ja.iodine.umbrella\-
tunnel\-test.com qtype: 1}
{qname: lafbgb04eecdkobxayfjgfpsugf3nusi.
iodine.umbrella\-tunnel\-test.com qtype: 1}
{qname: lafbgb04eecdkobxayfjgfpsugf3nusq.
iodine.umbrella\-tunnel\-test.com qtype: 1}
{qname: ytbwsl.iodine.umbrella\-tunnel\-
test.com qtype: 1}
{qname: ytbwsm.iodine.umbrella\-tunnel\-
test.com qtype: 1}Encoded command:
Collect credentials2022 DNS Discoveries\|8
2022 DNS Discoveries\|8Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved.DNS\-layer security benefitsSimplify security management: CiscoUmbrellas DNS\-layer protection reduces 
the number of infections and alerts 
you see from other security products 
by stopping threats at the earliest 
point. With no hardware to install or 
software tomanually update, ongoing 
management issimple.Improve internet performance: Umbrella 
has a highly resilient network that boasts 
100% business uptime since 2006\. Our 
carrier\-neutral data centers worldwide 
use Anycast routing so requests are 
transparently sent to the fastest available 
connection with automatic failover.Block malware: By enforcing security at 
the DNS layer, Umbrella blocks requests 
to malware, ransomware, phishing, 
and botnets before a connection is 
evenestablished.Increase visibility: Monitoring DNSrequests provides better accuracy and 
detection of compromised systems 
and improves security visibility and 
networkprotection.Proactively respond to threats: Umbrellalogs all DNS activity to simplify 
investigations. Umbrella Investigate 
provides context to prioritize incidents 
and speed up response. Cisco SecureX 
automates insights across Cisco products 
for quick answers.After deploying Umbrella, we were able to 
reduce malware infections by more than 
90% and the airline has not experienced 
any security incidents.Brett Stone, Network Operations Manager 
Cape Air2022 DNS Discoveries\|9
2022 DNS Discoveries\|9Security ReportCisco Public 2022 Cisco andor its affiliates. All rights reserved. 
Why Cisco UmbrellaCisco Umbrella analyzes internet activity to uncover known and emergent threats to protect 
users anywhere they go.Most predictive 
intelligenceOur unparalleled intelligence 
enables us to uncover 
malicious domains, IPs, and 
URLs before theyre even 
used in attacks.Easiest deploymentMost open platformTheres no hardware 
to install or software to 
manually update, and 
customers can leverage 
their existing Cisco footprint 
to provision thousands of 
network devices and laptops.Leveraging our bi\-directional 
API, customers can easily 
integrate Umbrella with 
existing tools to automatically 
add to our platform or 
enhance another system 
extending protection and 
enhancing information.Umbrella has given us visibility into our 
DNS traffic that weve never had before, 
enabling us to quickly respond to malware, 
command\-and\-control attacks, and more.Brandon Wood, Information Security Officer 
University of Alaska AnchorageSchedule a personalized demo to see our 
DNSdefense capabilities for yourself. 2022 Cisco andor its affiliates. All rights reserved. Cisco and the Cisco logo are trademarks or registered trademarks of Cisco andor its affiliates in the U.S. 
and other countries. To view a list of Cisco trademarks, go to this URL: www.cisco.comgotrademarks. Third\-party trademarks mentioned are the property of 
their respective owners. The use of the word partner does not imply a partnership relationship between Cisco and any other company.2022 DNS Discoveries\|100622Security ReportCisco Public