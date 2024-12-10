# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | - | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | - | High
3 | [24.88.87.29](https://vuldb.com/?ip.24.88.87.29) | syn-024-088-087-029.res.spectrum.com | - | High
4 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | - | High
5 | [32.143.50.222](https://vuldb.com/?ip.32.143.50.222) | - | - | High
6 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | - | High
7 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | - | High
8 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | - | High
9 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | - | High
10 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | - | High
11 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | - | High
12 | [68.76.150.97](https://vuldb.com/?ip.68.76.150.97) | 68-76-150-97.lightspeed.hstntx.sbcglobal.net | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pawn Storm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29, CWE-35, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/?Page=Node/OBJ=/System/DeviceFolder/DeviceFolder/DateTime/Action=Submit` | High
3 | File | `/abcd/opac/php/otros_sitios.php` | High
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/aboutus.php` | High
6 | File | `/admin/admin-profile.php` | High
7 | File | `/admin/admin_cl.php?mudi=revPwd` | High
8 | File | `/admin/admin_log.php?clear=1` | High
9 | File | `/admin/admin_widgets.php?action=install/widget=akismet` | High
10 | File | `/admin/contacts/organizations/edit/2` | High
11 | File | `/admin/dialog/select_images_post.php` | High
12 | File | `/admin/emp-profile-avatar.php` | High
13 | File | `/admin/login.php` | High
14 | File | `/admin/order.php` | High
15 | File | `/admin/robot.php` | High
16 | File | `/admin/system.php` | High
17 | File | `/admin/SystemUsers` | High
18 | File | `/admin/template/edit` | High
19 | File | `/admins/{adminId}` | High
20 | File | `/api/authentication/login` | High
21 | File | `/api/swaggerui/static` | High
22 | File | `/api/sys/set_passwd` | High
23 | File | `/articles/welcome-to-your-site#comments-head` | High
24 | File | `/bin/login` | Medium
25 | File | `/bloodrequest.php` | High
26 | File | `/boafrm/formSystemCheck` | High
27 | File | `/buscar_integrada.php` | High
28 | File | `/cgi-bin/alexserv` | High
29 | File | `/cgi-bin/cstecgi.cgi` | High
30 | File | `/cgi-bin/hd_config.cgi` | High
31 | File | `/cgi-bin/photocenter_mgr.cgi` | High
32 | File | `/cgi-bin/tosei_kikai.php` | High
33 | File | `/cgi-bin/webfile_mgr.cgi` | High
34 | File | `/cgi-bin/wlogin.cgi` | High
35 | File | `/classes/Master.php?f=save_inquiry` | High
36 | File | `/classes/Master.php?f=save_package` | High
37 | File | `/contact.php` | Medium
38 | File | `/controllers/add_user.php` | High
39 | File | `/core/config-revisions` | High
40 | File | `/core/tools/delete_place.php` | High
41 | File | `/dcim/power-ports/add/` | High
42 | File | `/DXR.axd` | Medium
43 | File | `/ecommerce/admin/login.php` | High
44 | File | `/ejbca/ra/cert` | High
45 | File | `/endpoint/add-calorie.php` | High
46 | File | `/endpoint/delete-account.php` | High
47 | File | `/endpoint/update.php` | High
48 | File | `/etc/passwd` | Medium
49 | File | `/files/` | Low
50 | File | `/film-rating.php` | High
51 | File | `/formLoginAuth.htm` | High
52 | File | `/forms/doLogin` | High
53 | ... | ... | ...

There are 458 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
