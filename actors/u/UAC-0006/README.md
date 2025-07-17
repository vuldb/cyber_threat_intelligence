# UAC-0006 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0006](https://vuldb.com/?actor.uac-0006). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0006](https://vuldb.com/?actor.uac-0006)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0006:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0006.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.230.13.93](https://vuldb.com/?ip.23.230.13.93) | - | - | High
2 | [31.44.4.9](https://vuldb.com/?ip.31.44.4.9) | - | - | High
3 | [31.44.4.97](https://vuldb.com/?ip.31.44.4.97) | acmenaturaltu.com | - | High
4 | [31.44.5.6](https://vuldb.com/?ip.31.44.5.6) | - | - | High
5 | [31.44.5.98](https://vuldb.com/?ip.31.44.5.98) | - | - | High
6 | [31.44.5.128](https://vuldb.com/?ip.31.44.5.128) | - | - | High
7 | [31.44.6.30](https://vuldb.com/?ip.31.44.6.30) | - | - | High
8 | [31.44.6.84](https://vuldb.com/?ip.31.44.6.84) | - | - | High
9 | [31.44.6.114](https://vuldb.com/?ip.31.44.6.114) | - | - | High
10 | [31.44.7.29](https://vuldb.com/?ip.31.44.7.29) | - | - | High
11 | [31.44.7.87](https://vuldb.com/?ip.31.44.7.87) | - | - | High
12 | [45.84.0.173](https://vuldb.com/?ip.45.84.0.173) | vps.hostry.com | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0006_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0006. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adfs/ls` | Medium
2 | File | `/admin/admin.php` | High
3 | File | `/admin/comn/service/update.json` | High
4 | File | `/api/0/api-tokens/` | High
5 | File | `/api/template/renderSprig` | High
6 | File | `/app/options.py` | High
7 | File | `/auth_files/photo/` | High
8 | File | `/card_scan.php` | High
9 | File | `/cgi-bin/wlogin.cgi` | High
10 | File | `/cwc/login` | Medium
11 | File | `/debuginfo.htm` | High
12 | File | `/download` | Medium
13 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
14 | File | `/DXR.axd` | Medium
15 | File | `/etc/passwd` | Medium
16 | File | `/etc/quagga` | Medium
17 | File | `/forms/doLogin` | High
18 | File | `/forum/away.php` | High
19 | File | `/goform/setmac` | High
20 | File | `/h/autoSaveDraft` | High
21 | File | `/h/calendar` | Medium
22 | File | `/inc/extensions.php` | High
23 | File | `/include/chart_generator.php` | High
24 | File | `/manager?action=getlogcat` | High
25 | File | `/members/profiles.php` | High
26 | File | `/nova/bin/console` | High
27 | File | `/nova/bin/detnet` | High
28 | File | `/out.php` | Medium
29 | File | `/php/ping.php` | High
30 | File | `/products/view_product.php` | High
31 | File | `/req_password_user.php` | High
32 | File | `/rom-0` | Low
33 | File | `/secure/QueryComponent!Default.jspa` | High
34 | File | `/ServletAPI/accounts/login` | High
35 | File | `/show_news.php` | High
36 | File | `/src/helper.c` | High
37 | File | `/tmp` | Low
38 | File | `/tools_command.php` | High
39 | File | `/uncpath/` | Medium
40 | ... | ... | ...

There are 340 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/4555802
* https://cert.gov.ua/article/4755642
* https://cert.gov.ua/article/5158006
* https://cert.gov.ua/article/5269451
* https://cert.gov.ua/article/6032734
* https://cert.gov.ua/article/6276584
* https://cert.gov.ua/article/6279366
* https://github.com/blackorbird/APT_REPORT/blob/master/cybercrime/SmokeLoader/UAC0006_FC.pdf.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
