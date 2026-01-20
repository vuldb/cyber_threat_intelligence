# Kinsing - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kinsing](https://vuldb.com/?actor.kinsing). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kinsing](https://vuldb.com/?actor.kinsing)

## Campaigns

The following _campaigns_ are known and can be associated with Kinsing:

* CVE-2022-36804
* CVE-2023-32315
* CVE-2023-46604
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kinsing:

* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kinsing.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.22.186.242](https://vuldb.com/?ip.3.22.186.242) | ec2-3-22-186-242.us-east-2.compute.amazonaws.com | - | Medium
2 | [3.215.110.66](https://vuldb.com/?ip.3.215.110.66) | ec2-3-215-110-66.compute-1.amazonaws.com | Log4Shell | Medium
3 | [5.34.183.14](https://vuldb.com/?ip.5.34.183.14) | vds-904894.hosted-by-itldc.com | - | High
4 | [5.34.183.145](https://vuldb.com/?ip.5.34.183.145) | a.sadeghi | - | High
5 | [5.35.101.62](https://vuldb.com/?ip.5.35.101.62) | hosted-by.ruweb.net | CVE-2023-32315 | High
6 | [31.184.240.34](https://vuldb.com/?ip.31.184.240.34) | 106863.web.hosting-russia.ru | CVE-2023-32315 | High
7 | [31.210.20.181](https://vuldb.com/?ip.31.210.20.181) | - | Log4Shell | High
8 | [34.81.218.76](https://vuldb.com/?ip.34.81.218.76) | 76.218.81.34.bc.googleusercontent.com | Log4Shell | Medium
9 | [42.112.28.216](https://vuldb.com/?ip.42.112.28.216) | midp.highlatrol.com | Log4Shell | High
10 | [45.10.88.102](https://vuldb.com/?ip.45.10.88.102) | 45.10.88.102.cl.darnytsia.net | - | High
11 | [45.10.88.124](https://vuldb.com/?ip.45.10.88.124) | - | - | High
12 | [45.15.158.124](https://vuldb.com/?ip.45.15.158.124) | - | - | High
13 | [45.67.230.68](https://vuldb.com/?ip.45.67.230.68) | vm330138.pq.hosting | - | High
14 | [45.95.169.118](https://vuldb.com/?ip.45.95.169.118) | zb64.antoniagavve.live | - | High
15 | [45.129.2.107](https://vuldb.com/?ip.45.129.2.107) | - | Log4Shell | High
16 | [45.137.151.106](https://vuldb.com/?ip.45.137.151.106) | - | Log4Shell | High
17 | [45.137.155.55](https://vuldb.com/?ip.45.137.155.55) | vm360194.pq.hosting | Log4Shell | High
18 | [45.142.214.48](https://vuldb.com/?ip.45.142.214.48) | server.com | Log4Shell | High
19 | [45.147.201.186](https://vuldb.com/?ip.45.147.201.186) | - | - | High
20 | [45.153.231.22](https://vuldb.com/?ip.45.153.231.22) | electacasper.example.com | - | High
21 | [45.156.23.210](https://vuldb.com/?ip.45.156.23.210) | - | Log4Shell | High
22 | [46.17.43.156](https://vuldb.com/?ip.46.17.43.156) | - | CVE-2023-46604 | High
23 | [51.222.154.100](https://vuldb.com/?ip.51.222.154.100) | ns577710.ip-51-222-154.net | CVE-2023-32315 | High
24 | [62.76.41.46](https://vuldb.com/?ip.62.76.41.46) | 392.mighost.ru | Log4Shell | High
25 | [62.113.113.60](https://vuldb.com/?ip.62.113.113.60) | v2065801.hosted-by-vdsina.ru | CVE-2022-36804 | High
26 | [62.113.115.166](https://vuldb.com/?ip.62.113.115.166) | v2296482.hosted-by-vdsina.ru | CVE-2022-36804 | High
27 | ... | ... | ... | ...

There are 103 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kinsing_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kinsing. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/add_librarian.php` | High
4 | File | `/admin/file_manager/export` | High
5 | File | `/admin/index2.html` | High
6 | File | `/admin/login.php` | High
7 | File | `/adminPage/conf/reload` | High
8 | File | `/admin_topic.php?action=delall` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/api/cron/settings/setJob/` | High
11 | File | `/api/wizard/setsyncpppoecfg` | High
12 | File | `/api2/html/` | Medium
13 | File | `/application/index/controller/Databasesource.php` | High
14 | File | `/bitrix/admin/ldap_server_edit.php` | High
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/koha/catalogue/search.pl` | High
17 | File | `/cgi-bin/nas_sharing.cgi` | High
18 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
19 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
20 | File | `/donor-wall` | Medium
21 | File | `/DXR.axd` | Medium
22 | File | `/etc/shadow` | Medium
23 | File | `/forum/away.php` | High
24 | File | `/forum1.php` | Medium
25 | File | `/h/rest` | Low
26 | File | `/inc/jquery/uploadify/uploadify.php` | High
27 | File | `/inc/parser/xhtml.php` | High
28 | File | `/index/ajax/lang` | High
29 | File | `/ipms/imageConvert/image` | High
30 | File | `/livesite/edit_designer_region.php` | High
31 | File | `/log/decodmail.php` | High
32 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
33 | File | `/log_proxy` | Medium
34 | ... | ... | ...

There are 292 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/315/kinsing-i-dark-iot-botnet-iocs/
* https://blog.aquasec.com/kinsing-malware-exploits-novel-openfire-vulnerability
* https://blog.aquasec.com/threat-alert-kinsing-malware-container-vulnerability
* https://blog.sekoia.io/activemq-cve-2023-46604-exploited-by-kinsing-and-overview-of-this-threat/
* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-campaign-briefs/log4j-indicators-of-compromise-to-date/
* https://gist.github.com/Iansus/050e121170a864c37b13f979c1883ad4
* https://threatfox.abuse.ch
* https://twitter.com/iansus/status/1472867647410819073
* https://urlhaus.abuse.ch/host/185.246.90.205/
* https://urlhaus.abuse.ch/url/2532766/
* https://urlhaus.abuse.ch/url/2532772/
* https://urlhaus.abuse.ch/url/3539650/
* https://urlhaus.abuse.ch/url/3709590/
* https://urlhaus.abuse.ch/url/3709592/
* https://urlhaus.abuse.ch/url/3715324/
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/l/patch-now-apache-log4j-vulnerability-called-log4shell-being-actively-exploited/IOCs-PatchNow-Log4Shell-Vulnerability.txt
* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/honeypot-recon-enterprise-applications-honeypot-unveiling-findings-from-six-worldwide-locations/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
