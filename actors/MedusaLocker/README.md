# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)
* [DE](https://vuldb.com/?country.de)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
2 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
3 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
4 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
5 | [87.251.75.71](https://vuldb.com/?ip.87.251.75.71) | - | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-29 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.authlie` | Medium
2 | File | `/admin/ajax.php?action=delete_user` | High
3 | File | `/admin/ajax.php?action=save_queue` | High
4 | File | `/app/dao/CustomerDAO.php` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/apps/app_user/sys_user.php` | High
7 | File | `/bsms_ci/index.php/book` | High
8 | File | `/classes/Master.php?f=delete_category` | High
9 | File | `/config/api/v1/reboot` | High
10 | File | `/etc/shadow` | Medium
11 | File | `/food` | Low
12 | File | `/forum/away.php` | High
13 | File | `/forums.php?action=post` | High
14 | File | `/index.php` | Medium
15 | File | `/index/user/user_edit.html` | High
16 | File | `/inxedu/demo_inxedu_open/src/main/resources/mybatis/inxedu/website/WebsiteImagesMapper.xml` | High
17 | File | `/login/index.php` | High
18 | File | `/opt/Citrix/ICAClient/util/ctxwebhelper` | High
19 | File | `/rest/api/2/user/picker` | High
20 | File | `/setNTP.cgi` | Medium
21 | File | `/system/site.php` | High
22 | File | `/tpts/manage_user.php` | High
23 | File | `/uncpath/` | Medium
24 | ... | ... | ...

There are 198 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
