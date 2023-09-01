# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-36 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/ajax.php?action=read_msg` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/upload.php` | High
5 | File | `/api?path=profile` | High
6 | File | `/authenticationendpoint/login.do` | High
7 | File | `/cgi-bin/luci` | High
8 | File | `/cgi-bin/wlogin.cgi` | High
9 | File | `/ci_spms/admin/search/searching/` | High
10 | File | `/classes/Master.php?f=save_brand` | High
11 | File | `/contact/store` | High
12 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
13 | File | `/ecommerce/support_ticket` | High
14 | File | `/etc/pki/pesign` | High
15 | File | `/forum/away.php` | High
16 | File | `/FuguHub/cmsdocs/` | High
17 | File | `/goform/set_LimitClient_cfg` | High
18 | File | `/graphql` | Medium
19 | File | `/h/autoSaveDraft` | High
20 | File | `/HNAP1` | Low
21 | File | `/index.php` | Medium
22 | File | `/Log/Query?appid=0B736354-9473-4D66-B9C0-15CAC149EB05&tabid=tab_0B73635494734D66B9C015CAC149EB05` | High
23 | File | `/mc` | Low
24 | File | `/modules/projects/vw_files.php` | High
25 | File | `/php-inventory-management-system/product.php` | High
26 | File | `/plain` | Low
27 | File | `/plugins/playbooks/api/v0/runs` | High
28 | File | `/registration.php` | High
29 | File | `/release-x64/otfccdump+0x61731f` | High
30 | File | `/search.php` | Medium
31 | File | `/settings/account` | High
32 | File | `/sitecore/shell/Invoke.aspx` | High
33 | File | `/staff/edit_book_details.php` | High
34 | File | `/student/bookdetails.php` | High
35 | File | `/uncpath/` | Medium
36 | File | `/userfs/bin/tcapi` | High
37 | File | `/var/log/nginx` | High
38 | ... | ... | ...

There are 327 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
