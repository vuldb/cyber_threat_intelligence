# Kimsuky - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kimsuky](https://vuldb.com/?actor.kimsuky). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kimsuky](https://vuldb.com/?actor.kimsuky)

## Campaigns

The following _campaigns_ are known and can be associated with Kimsuky:

* AppleSeed
* PebbleDash
* RftRAT/Amadey

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kimsuky:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kimsuky.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.243.200.130](https://vuldb.com/?ip.1.243.200.130) | - | - | High
2 | [2.57.90.16](https://vuldb.com/?ip.2.57.90.16) | - | - | High
3 | [5.61.59.53](https://vuldb.com/?ip.5.61.59.53) | - | - | High
4 | [15.197.130.221](https://vuldb.com/?ip.15.197.130.221) | aeaff23b87fbce26d.awsglobalaccelerator.com | - | High
5 | [23.106.122.16](https://vuldb.com/?ip.23.106.122.16) | - | - | High
6 | [23.106.122.239](https://vuldb.com/?ip.23.106.122.239) | - | - | High
7 | [23.236.181.108](https://vuldb.com/?ip.23.236.181.108) | 108.181.236.23.in-addr.arpa | RftRAT/Amadey | High
8 | [27.102.102.70](https://vuldb.com/?ip.27.102.102.70) | - | - | High
9 | [27.102.107.63](https://vuldb.com/?ip.27.102.107.63) | - | AppleSeed | High
10 | [27.102.112.44](https://vuldb.com/?ip.27.102.112.44) | - | - | High
11 | [27.102.112.58](https://vuldb.com/?ip.27.102.112.58) | - | - | High
12 | [27.102.114.63](https://vuldb.com/?ip.27.102.114.63) | - | - | High
13 | [27.102.114.79](https://vuldb.com/?ip.27.102.114.79) | - | - | High
14 | [27.102.114.89](https://vuldb.com/?ip.27.102.114.89) | - | AppleSeed | High
15 | [27.102.127.240](https://vuldb.com/?ip.27.102.127.240) | - | - | High
16 | [27.102.128.169](https://vuldb.com/?ip.27.102.128.169) | - | - | High
17 | [27.255.75.137](https://vuldb.com/?ip.27.255.75.137) | - | - | High
18 | [27.255.79.204](https://vuldb.com/?ip.27.255.79.204) | - | - | High
19 | [27.255.80.170](https://vuldb.com/?ip.27.255.80.170) | - | - | High
20 | [27.255.81.71](https://vuldb.com/?ip.27.255.81.71) | - | - | High
21 | [27.255.81.80](https://vuldb.com/?ip.27.255.81.80) | - | - | High
22 | [27.255.81.109](https://vuldb.com/?ip.27.255.81.109) | - | - | High
23 | [31.172.80.100](https://vuldb.com/?ip.31.172.80.100) | - | - | High
24 | ... | ... | ... | ...

There are 90 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kimsuky_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-29 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kimsuky. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/` | Low
2 | File | `/admin/admin_user.php` | High
3 | File | `/admin/category/save` | High
4 | File | `/admin/list_ipAddressPolicy.php` | High
5 | File | `/admin/subject.php` | High
6 | File | `/api/runscript` | High
7 | File | `/api/snapshots/` | High
8 | File | `/api/v1/snapshots` | High
9 | File | `/api/v2/maps` | Medium
10 | File | `/auth/auth.php?user=1` | High
11 | File | `/boaform/device_reset.cgi` | High
12 | File | `/cgi-bin/cstecgi.cgi` | High
13 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
14 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
15 | File | `/cgi-bin/nas_sharing.cgi` | High
16 | File | `/cgi-bin/system_mgr.cgi` | High
17 | File | `/cgi-bin/wlogin.cgi` | High
18 | File | `/cgi/cpaddons_report.pl` | High
19 | File | `/common/dict/list` | High
20 | File | `/debug/pprof` | Medium
21 | File | `/DXR.axd` | Medium
22 | File | `/forum/away.php` | High
23 | File | `/goform/DhcpListClient` | High
24 | File | `/goform/goform_get_cmd_process` | High
25 | File | `/HNAP1/` | Low
26 | File | `/hrm/leaverequest.php` | High
27 | File | `/importexport.php` | High
28 | File | `/install/` | Medium
29 | File | `/Interface/DevManage/VM.php` | High
30 | File | `/main/doctype.php` | High
31 | File | `/main/webservices/additional_webservices.php` | High
32 | File | `/mc` | Low
33 | File | `/ndmComponents.js` | High
34 | File | `/net/bluetooth/rfcomm/core.C` | High
35 | File | `/oauth/idp/.well-known/openid-configuration` | High
36 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
37 | File | `/pdf` | Low
38 | File | `/register.php` | High
39 | File | `/registrar/` | Medium
40 | File | `/remote/put_file` | High
41 | File | `/setting/NTPSyncWithHost` | High
42 | File | `/spip.php` | Medium
43 | ... | ... | ...

There are 373 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/30532/
* https://asec.ahnlab.com/en/53046/
* https://asec.ahnlab.com/en/57873/
* https://asec.ahnlab.com/en/59590/
* https://asec.ahnlab.com/en/60054/
* https://asec.ahnlab.com/en/63396/
* https://blog.alyac.co.kr/2234
* https://blog.alyac.co.kr/4892
* https://blog.malwarebytes.com/threat-analysis/2021/06/kimsuky-apt-continues-to-target-south-korean-government-using-appleseed-backdoor/
* https://community.blueliv.com/#!/s/5fa1234a82df413ea9349a07
* https://github.com/blackorbird/APT_REPORT/blob/master/kimsuky/20231016_threat_inteligence_report_DarkHorse.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/kimsuky/20231101_Kimsuky_OP.-Covert-Stalker-EN.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/kimsuky/ATIP_2023_Feb_Threat-Trend-Report-on-Kimsuky-Group.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/kimsuky/Kimsuky%20APT%20Group%20targeted%20on%20South%20Korean%20defense%20and%20security%20departments.pdf
* https://github.com/blackorbird/APT_REPORT/tree/master/kimsuky
* https://github.com/eset/malware-ioc/tree/master/kimsuky/hotdoge_donutcat_case
* https://threatfox.abuse.ch
* https://twitter.com/shadowchasing1/status/1500778382966939653
* https://twitter.com/souiten/status/1473862308132651011
* https://www.sentinelone.com/labs/kimsuky-new-social-engineering-campaign-aims-to-steal-credentials-and-gather-strategic-intelligence/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
