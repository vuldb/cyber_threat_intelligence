# Bulbature - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Bulbature_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bulbature:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Bulbature or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bulbature.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.34.176.150](https://vuldb.com/?ip.5.34.176.150) | vps.hostry.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [5.34.178.144](https://vuldb.com/?ip.5.34.178.144) | vps.hostry.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [38.54.50.120](https://vuldb.com/?ip.38.54.50.120) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [38.54.50.163](https://vuldb.com/?ip.38.54.50.163) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | [38.54.50.253](https://vuldb.com/?ip.38.54.50.253) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
6 | [38.54.56.45](https://vuldb.com/?ip.38.54.56.45) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
7 | [38.54.85.244](https://vuldb.com/?ip.38.54.85.244) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
8 | [38.54.88.248](https://vuldb.com/?ip.38.54.88.248) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
9 | [38.60.196.86](https://vuldb.com/?ip.38.60.196.86) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
10 | [38.60.203.61](https://vuldb.com/?ip.38.60.203.61) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
11 | [38.60.203.83](https://vuldb.com/?ip.38.60.203.83) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
12 | [38.60.206.78](https://vuldb.com/?ip.38.60.206.78) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
13 | [38.60.212.13](https://vuldb.com/?ip.38.60.212.13) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
14 | [38.60.212.167](https://vuldb.com/?ip.38.60.212.167) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
15 | [38.60.212.233](https://vuldb.com/?ip.38.60.212.233) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
16 | [38.60.223.208](https://vuldb.com/?ip.38.60.223.208) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
17 | [38.180.9.2](https://vuldb.com/?ip.38.180.9.2) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
18 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Bulbature. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Bulbature. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adm/setmain.php` | High
2 | File | `/admin-page.php` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin.php?page=album` | High
5 | File | `/admin/admin-profile.php` | High
6 | File | `/admin/ajax/avatar.php` | High
7 | File | `/admin/article/article-edit-run.php` | High
8 | File | `/admin/employee/index.php` | High
9 | File | `/admin/index.php` | High
10 | File | `/adminapi/system/file/openfile` | High
11 | File | `/admin_class.php` | High
12 | File | `/ajax` | Low
13 | File | `/api/admin/user/list` | High
14 | File | `/api/baskets/{name}` | High
15 | File | `/api/blade-system/menu/list?updatexml` | High
16 | File | `/api/upload` | Medium
17 | File | `/api2/html/` | Medium
18 | File | `/app/options.py` | High
19 | File | `/apply.cgi` | Medium
20 | File | `/auth_files/photo/` | High
21 | File | `/bin/goahead` | Medium
22 | File | `/bsms_ci/index.php/book` | High
23 | File | `/category.php` | High
24 | File | `/cgi-bin/cstecgi.cgi` | High
25 | File | `/cgi-bin/luci/api/auth` | High
26 | File | `/cgi-bin/luci;stok=/locale` | High
27 | File | `/cgi-bin/nas_sharing.cgi` | High
28 | File | `/cgi-bin/wapopen` | High
29 | File | `/cgi-bin/wlogin.cgi` | High
30 | File | `/CMD_ACCOUNT_ADMIN` | High
31 | File | `/cms/templates/templatesAssetsEditor` | High
32 | File | `/conf/app.conf` | High
33 | File | `/config/getuser` | High
34 | File | `/console/dashboard/executorCount?zkClusterKey` | High
35 | File | `/customnode/install` | High
36 | File | `/debug/pprof` | Medium
37 | File | `/debuginfo.htm` | High
38 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
39 | File | `/ecrire` | Low
40 | File | `/ecshop/admin/template.php` | High
41 | File | `/etc/init0.d/S80telnetd.sh` | High
42 | File | `/etc/passwd` | Medium
43 | File | `/export` | Low
44 | File | `/file/delete.php` | High
45 | File | `/forms/doLogin` | High
46 | File | `/forum/away.php` | High
47 | File | `/get.php` | Medium
48 | File | `/getcfg.php` | Medium
49 | File | `/goform/Diagnosis` | High
50 | File | `/goform/SetFirewallCfg` | High
51 | ... | ... | ...

There are 445 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.sekoia.io/bulbature-beneath-the-waves-of-gobrat/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
