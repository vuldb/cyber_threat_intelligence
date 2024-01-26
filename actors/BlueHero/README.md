# BlueHero - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlueHero](https://vuldb.com/?actor.bluehero). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bluehero](https://vuldb.com/?actor.bluehero)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlueHero:

* [IN](https://vuldb.com/?country.in)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlueHero.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.5.10.1](https://vuldb.com/?ip.2.5.10.1) | - | - | High
2 | [10.3.6.0](https://vuldb.com/?ip.10.3.6.0) | - | - | High
3 | [12.1.3.0](https://vuldb.com/?ip.12.1.3.0) | - | - | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlueHero_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlueHero. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/` | Low
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/add_exercises.php` | High
6 | File | `/admin/add_trainers.php` | High
7 | File | `/admin/admin_user.php` | High
8 | File | `/admin/api/admin/articles/` | High
9 | File | `/admin/api/theme-edit/` | High
10 | File | `/Admin/createClass.php` | High
11 | File | `/admin/edit.php` | High
12 | File | `/admin/edit_product.php` | High
13 | File | `/admin/settings.php` | High
14 | File | `/admin/students/manage.php` | High
15 | File | `/api/baskets/{name}` | High
16 | File | `/api/public/signup` | High
17 | File | `/api/v1/attack` | High
18 | File | `/api/v1/bait/set` | High
19 | File | `/api/v2/open/tablesInfo` | High
20 | File | `/blog` | Low
21 | File | `/boaform/device_reset.cgi` | High
22 | File | `/boaform/wlan_basic_set.cgi` | High
23 | File | `/category.php` | High
24 | File | `/cgi-bin/koha/catalogue/search.pl` | High
25 | File | `/cgi-bin/upload_vpntar` | High
26 | File | `/core/tools/customblock.php` | High
27 | File | `/course/filterRecords/` | High
28 | File | `/CPE` | Low
29 | File | `/csms/?page=contact_us` | High
30 | File | `/csms/admin/?page=user/list` | High
31 | File | `/cwms/classes/Master.php?f=save_contact` | High
32 | File | `/debug/pprof` | Medium
33 | File | `/ebics-server/ebics.aspx` | High
34 | File | `/edituser.php` | High
35 | File | `/employeeview.php` | High
36 | File | `/forum/away.php` | High
37 | File | `/FuguHub/cmsdocs/` | High
38 | File | `/goform/Diagnosis` | High
39 | File | `/home/search` | Medium
40 | File | `/inc/jquery/uploadify/uploadify.php` | High
41 | File | `/leaves/validate` | High
42 | File | `/login.php` | Medium
43 | File | `/loginVaLidation.php` | High
44 | File | `/mail.php` | Medium
45 | File | `/MicroStrategyWS/happyaxis.jsp` | High
46 | File | `/mims/app/addcustomerHandler.php` | High
47 | File | `/mkshope/login.php` | High
48 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
49 | File | `/oauth/idp/.well-known/openid-configuration` | High
50 | File | `/obs/bookPerPub.php` | High
51 | File | `/omos/admin/?page=user/list` | High
52 | File | `/one_church/churchprofile.php` | High
53 | File | `/one_church/userregister.php` | High
54 | File | `/out.php` | Medium
55 | ... | ... | ...

There are 475 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://s.tencent.com/research/report/675
* https://www.zscaler.com/blogs/research/recent-bulehero-botnet-payload

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
