# SmokeLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SmokeLoader](https://vuldb.com/?actor.smokeloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.smokeloader](https://vuldb.com/?actor.smokeloader)

## Campaigns

The following _campaigns_ are known and can be associated with SmokeLoader:

* Tsunami
* Whiffy Recon

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmokeLoader:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SmokeLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.16.165.19](https://vuldb.com/?ip.2.16.165.19) | a2-16-165-19.deploy.static.akamaitechnologies.com | - | High
2 | [5.9.224.217](https://vuldb.com/?ip.5.9.224.217) | static.217.224.9.5.clients.your-server.de | - | High
3 | [5.42.92.190](https://vuldb.com/?ip.5.42.92.190) | hosted-by.yeezyhost.net | - | High
4 | [5.101.0.32](https://vuldb.com/?ip.5.101.0.32) | - | - | High
5 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | Tsunami | High
6 | [5.196.8.173](https://vuldb.com/?ip.5.196.8.173) | vps-b5645e9a.vps.ovh.net | - | High
7 | [8.209.65.68](https://vuldb.com/?ip.8.209.65.68) | - | - | High
8 | [10.1.105.117](https://vuldb.com/?ip.10.1.105.117) | - | - | High
9 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
10 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | - | High
11 | [23.0.48.75](https://vuldb.com/?ip.23.0.48.75) | a23-0-48-75.deploy.static.akamaitechnologies.com | - | High
12 | [23.0.209.167](https://vuldb.com/?ip.23.0.209.167) | a23-0-209-167.deploy.static.akamaitechnologies.com | - | High
13 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
14 | [23.6.69.99](https://vuldb.com/?ip.23.6.69.99) | a23-6-69-99.deploy.static.akamaitechnologies.com | - | High
15 | [23.13.211.142](https://vuldb.com/?ip.23.13.211.142) | a23-13-211-142.deploy.static.akamaitechnologies.com | - | High
16 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | - | Medium
17 | [23.48.95.144](https://vuldb.com/?ip.23.48.95.144) | a23-48-95-144.deploy.static.akamaitechnologies.com | - | High
18 | [23.66.61.153](https://vuldb.com/?ip.23.66.61.153) | a23-66-61-153.deploy.static.akamaitechnologies.com | - | High
19 | [23.193.177.127](https://vuldb.com/?ip.23.193.177.127) | a23-193-177-127.deploy.static.akamaitechnologies.com | - | High
20 | [23.218.40.161](https://vuldb.com/?ip.23.218.40.161) | a23-218-40-161.deploy.static.akamaitechnologies.com | - | High
21 | [23.221.48.201](https://vuldb.com/?ip.23.221.48.201) | a23-221-48-201.deploy.static.akamaitechnologies.com | - | High
22 | [23.227.203.30](https://vuldb.com/?ip.23.227.203.30) | 23-227-203-30.static.hvvc.us | - | High
23 | [27.102.67.144](https://vuldb.com/?ip.27.102.67.144) | - | - | High
24 | [31.13.65.36](https://vuldb.com/?ip.31.13.65.36) | edge-star-mini-shv-01-atl3.facebook.com | - | High
25 | [31.44.6.123](https://vuldb.com/?ip.31.44.6.123) | - | - | High
26 | [31.44.185.182](https://vuldb.com/?ip.31.44.185.182) | - | - | High
27 | ... | ... | ... | ...

There are 102 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SmokeLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/edit-doc.php` | High
2 | File | `/api/admin/store/product/list` | High
3 | File | `/cgi-bin/qcmap_auth` | High
4 | File | `/conf/` | Low
5 | File | `/debug/pprof` | Medium
6 | File | `/film-rating.php` | High
7 | File | `/group1/uploa` | High
8 | File | `/index.php` | Medium
9 | File | `/js/app.js` | Medium
10 | File | `/librarian/bookdetails.php` | High
11 | File | `/pix_projetos/servlet?act=login&submit=1&evento=0&pixrnd=0125021816444195731041` | High
12 | File | `/soplanning/www/process/xajax_server.php` | High
13 | File | `/student/bookdetails.php` | High
14 | File | `/test/cookie/` | High
15 | File | `/ureport/designer/saveReportFile` | High
16 | File | `/users` | Low
17 | File | `account.asp` | Medium
18 | File | `admin.php` | Medium
19 | File | `admin/establishment/manage.php` | High
20 | File | `admin/inquiries/view_details.php` | High
21 | ... | ... | ...

There are 176 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/0cbee59f9e035659029cc87768c25903a603582a0d247460dcbbf6bf497311c4/
* https://bazaar.abuse.ch/sample/1ce005163f0931b60a2340dae83894ab89a710d930c7e0c28da75b41518a6ef3/
* https://bazaar.abuse.ch/sample/3ab01b2ae713f3f64d98e50cc72e066329b78751621d91b01f4b1736b69163fa/
* https://bazaar.abuse.ch/sample/5bbe4ff9dc3e2fb44d356785216d39faa2ea386b1a5227798aea9c2d18b8b3fa/
* https://bazaar.abuse.ch/sample/5e30a88fb1c9a45bd6697990493098ca05e87b2560172ae89e9811ea887ff8b4/#intel
* https://bazaar.abuse.ch/sample/83b5b5e0e33939cd18fbb34cb15e39647d93aeeb878df52a324f73f357749811/
* https://bazaar.abuse.ch/sample/217098c45eed16334b9d30551cc45b8a7b5e028163ee2bbc0d0906c2b381a1c4/
* https://bazaar.abuse.ch/sample/871884457a26252704be8ed779adb8420580f0d879ce40fca002de154770eaeb/
* https://bazaar.abuse.ch/sample/c7d04743911aa4264b47d44df511d4c1f72dc789293b2457bf995ca2a592add3/#intel
* https://bazaar.abuse.ch/sample/ea0a7467efc74d7a947774d83d440426510243bd4b443391f753902bf275c86c/
* https://bazaar.abuse.ch/sample/ea8ecda6aaf0a6560b614a46a33112caf8ab6404be64ced23fa202737ddbacbf/
* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://community.blueliv.com/#!/s/6333fa0182df417ed0331a1d
* https://ddanchev.blogspot.com/2022/11/smokeloader-themed-malware-serving.html
* https://de.darktrace.com/blog/how-darktrace-extinguished-the-threat-of-smokeloader-malware
* https://de.darktrace.com/blog/how-darktraces-ai-detects-metamorphic-malware
* https://detect.fyi/demystification-8base-threat-hunting-and-detection-opportunities-44c55c4c5667
* https://farghlymal.github.io/SmokeLoader-Analysis/
* https://github.com/threatlabz/iocs/blob/main/smokeloader_tradingview_campaign/c2s.txt
* https://isc.sans.edu/forums/diary/Resumethemed+malspam+pushing+Smoke+Loader/23054/
* https://research.checkpoint.com/2019/2019-resurgence-of-smokeloader/
* https://threatfox.abuse.ch
* https://tria.ge/220511-fxrezafgg2
* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/
* https://urlhaus.abuse.ch/url/3533501/
* https://www.secureworks.com/blog/smoke-loader-drops-whiffy-recon-wi-fi-scanning-and-geolocation-malware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
