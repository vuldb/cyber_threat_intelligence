# Phishing Korea - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Phishing Korea_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Phishing Korea:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Phishing Korea or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Agent Tesla](https://vuldb.com/?actor.agent_tesla) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Phishing Korea.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [69.174.99.181](https://vuldb.com/?ip.69.174.99.181) | unassigned.quadranet.com | [Agent Tesla](https://vuldb.com/?actor.agent_tesla) | High
2 | [149.56.200.165](https://vuldb.com/?ip.149.56.200.165) | ip165.ip-149-56-200.net | [Agent Tesla](https://vuldb.com/?actor.agent_tesla) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Phishing Korea. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Phishing Korea. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/addProduct.php` | High
3 | File | `/admin/add-module.php` | High
4 | File | `/admin/add_expenses.php` | High
5 | File | `/admin/archives_add.php` | High
6 | File | `/admin/categories/save` | High
7 | File | `/admin/contact-us.php` | High
8 | File | `/admin/delete_user.php` | High
9 | File | `/admin/index.php` | High
10 | File | `/admin/newsletterdel.php` | High
11 | File | `/admin/pages/` | High
12 | File | `/admin/positions.php` | High
13 | File | `/admin/receipt.php` | High
14 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
15 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
16 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
17 | File | `/Administrator/PHP/AdminEditUser.php` | High
18 | File | `/Administrator/PHP/AdminReply.php` | High
19 | File | `/admins` | Low
20 | File | `/adv_mac_filter.php` | High
21 | File | `/ajax.php?action=login` | High
22 | File | `/ajax/getBasicInfo.php` | High
23 | File | `/api/admin/system/store/order/list` | High
24 | File | `/api/files/recipepictures/` | High
25 | File | `/app/register.php?action=reg` | High
26 | File | `/authentication.cgi` | High
27 | File | `/boaform/formSamba` | High
28 | File | `/boafrm/formDdns` | High
29 | File | `/boafrm/formTracerouteDiagnosticRun` | High
30 | File | `/boafrm/formVpnConfigSetup` | High
31 | File | `/cgi-bin/cstecgi.cgi` | High
32 | File | `/cgi-bin/wapopen` | High
33 | File | `/cgi-bin/wlogin.cgi` | High
34 | File | `/clientdetails/admin/regester.php` | High
35 | File | `/csms/?page=contact_us` | High
36 | File | `/detailtransac.php` | High
37 | File | `/dev/ptpX` | Medium
38 | File | `/editeddonor.php` | High
39 | File | `/editprofile.php` | High
40 | File | `/etc/ajenti/config.yml` | High
41 | File | `/farm/product.php` | High
42 | File | `/foreigner-search.php` | High
43 | File | `/forum/away.php` | High
44 | File | `/FrontEnd/Albums.php` | High
45 | File | `/function.php` | High
46 | File | `/gallery/api/status/` | High
47 | File | `/goform/AdvSetLanip` | High
48 | File | `/goform/AdvSetMacMtuWa` | High
49 | File | `/goform/AdvSetMacMtuWan` | High
50 | File | `/goform/aspForm` | High
51 | File | `/goform/ConfigExceptAli` | High
52 | File | `/goform/ConfigExceptMSN` | High
53 | File | `/goform/DhcpListClient` | High
54 | File | `/goform/exeCommand` | High
55 | File | `/goform/formConfigFastDirectionW` | High
56 | File | `/goform/formFireWall` | High
57 | File | `/goform/formNatStaticMap` | High
58 | ... | ... | ...

There are 509 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.fortinet.com/blog/threat-research/phishing-campaign-targeting-korean-to-deliver-agent-tesla-new-variant

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
