# ERMAC - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ERMAC](https://vuldb.com/?actor.ermac). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ermac](https://vuldb.com/?actor.ermac)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ERMAC:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ERMAC.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.199.3](https://vuldb.com/?ip.5.42.199.3) | - | - | High
2 | [5.42.199.22](https://vuldb.com/?ip.5.42.199.22) | - | - | High
3 | [5.42.199.91](https://vuldb.com/?ip.5.42.199.91) | - | - | High
4 | [20.108.0.165](https://vuldb.com/?ip.20.108.0.165) | - | - | High
5 | [20.210.252.118](https://vuldb.com/?ip.20.210.252.118) | - | - | High
6 | [20.249.63.72](https://vuldb.com/?ip.20.249.63.72) | - | - | High
7 | [31.41.244.187](https://vuldb.com/?ip.31.41.244.187) | - | - | High
8 | [35.90.154.240](https://vuldb.com/?ip.35.90.154.240) | ec2-35-90-154-240.us-west-2.compute.amazonaws.com | - | Medium
9 | [35.91.53.224](https://vuldb.com/?ip.35.91.53.224) | ec2-35-91-53-224.us-west-2.compute.amazonaws.com | - | Medium
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ERMAC_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ERMAC. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/api/theme-edit/` | High
2 | File | `/admin/index/index.html#listarticle` | High
3 | File | `/app/options.py` | High
4 | File | `/card_scan.php` | High
5 | File | `/cgi-bin/viewcert` | High
6 | File | `/cgi-bin/wlogin.cgi` | High
7 | File | `/cwc/login` | Medium
8 | File | `/download` | Medium
9 | File | `/etc/quagga` | Medium
10 | File | `/etc/shadow` | Medium
11 | File | `/face-recognition-php/facepay-master/camera.php` | High
12 | File | `/forms/doLogin` | High
13 | File | `/forum/PostPrivateMessage` | High
14 | File | `/h/calendar` | Medium
15 | File | `/home/masterConsole` | High
16 | File | `/hrm/employeeadd.php` | High
17 | File | `/hrm/employeeview.php` | High
18 | File | `/inc/extensions.php` | High
19 | File | `/iwguestbook/admin/badwords_edit.asp` | High
20 | File | `/iwguestbook/admin/messages_edit.asp` | High
21 | File | `/nova/bin/console` | High
22 | File | `/nova/bin/detnet` | High
23 | File | `/out.php` | Medium
24 | File | `/req_password_user.php` | High
25 | File | `/rom-0` | Low
26 | File | `/secure/QueryComponent!Default.jspa` | High
27 | File | `/ServletAPI/accounts/login` | High
28 | File | `/SysInfo.htm` | Medium
29 | File | `/TemplateManager/indexExternalLocation.jsp` | High
30 | File | `/uncpath/` | Medium
31 | File | `/user/updatePwd` | High
32 | File | `/usr/syno/etc/mount.conf` | High
33 | File | `/v2/quantum/save-data-upload-big-file` | High
34 | File | `/WEB-INF/web.xml` | High
35 | File | `/wp-content/plugins/woocommerce/templates/emails/plain/` | High
36 | File | `/wp-json` | Medium
37 | File | `action.php` | Medium
38 | File | `adm.cgi` | Low
39 | File | `admin.php` | Medium
40 | File | `admin.php&r=article/AdminContent/edit` | High
41 | File | `admin/?page=admin` | High
42 | File | `admin/batch_manager_unit.php` | High
43 | File | `admin/dashboard.php` | High
44 | File | `admin/general.php` | High
45 | File | `admin/reply-ticket.php` | High
46 | ... | ... | ...

There are 396 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/6290743382df41552632f5fe
* https://research.nccgroup.com/2023/09/11/from-ermac-to-hook-investigating-the-technical-differences-between-two-android-malware-variants/
* https://search.censys.io/hosts/82.147.85.136
* https://search.censys.io/hosts/91.92.246.222
* https://search.censys.io/hosts/94.131.111.119
* https://threatfox.abuse.ch
* https://twitter.com/0xrb/status/1564222855830597632
* https://twitter.com/ReBensk/status/1695321207766127094
* https://www.threatfabric.com/blogs/ermac-another-cerberus-reborn.html
* https://www.trendmicro.com/de_de/research/22/g/examining-new-dawdropper-banking-dropper-and-daas-on-the-dark-we.html
* https://www.virustotal.com/gui/file/f642d2c6a70828028e0f3f7e9b9a87537c6556870cdf4602ee992091040a1850/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
