# Unknown RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Unknown RAT](https://vuldb.com/?actor.unknown_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.unknown_rat](https://vuldb.com/?actor.unknown_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Unknown RAT:

* [IO](https://vuldb.com/?country.io)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Unknown RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.221.64.34](https://vuldb.com/?ip.37.221.64.34) | new43 | - | High
2 | [37.221.64.37](https://vuldb.com/?ip.37.221.64.37) | new13 | - | High
3 | [37.221.64.39](https://vuldb.com/?ip.37.221.64.39) | new05 | - | High
4 | [37.221.64.40](https://vuldb.com/?ip.37.221.64.40) | new31 | - | High
5 | [37.221.64.42](https://vuldb.com/?ip.37.221.64.42) | new47 | - | High
6 | [37.221.64.43](https://vuldb.com/?ip.37.221.64.43) | new48 | - | High
7 | [37.221.64.44](https://vuldb.com/?ip.37.221.64.44) | new29 | - | High
8 | [37.221.64.47](https://vuldb.com/?ip.37.221.64.47) | new46 | - | High
9 | [37.221.64.56](https://vuldb.com/?ip.37.221.64.56) | new08 | - | High
10 | [37.221.64.57](https://vuldb.com/?ip.37.221.64.57) | new27 | - | High
11 | [37.221.64.58](https://vuldb.com/?ip.37.221.64.58) | new26 | - | High
12 | [37.221.64.60](https://vuldb.com/?ip.37.221.64.60) | new11 | - | High
13 | [37.221.64.76](https://vuldb.com/?ip.37.221.64.76) | new24 | - | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Unknown RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Unknown RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/;/admin/role/edit` | High
2 | File | `/admin/admin.php` | High
3 | File | `/admin/ajax.php?action=add_to_cart` | High
4 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
5 | File | `/admin/CloudAccounts` | High
6 | File | `/admin/cmsTemplate/savePlace` | High
7 | File | `/admin/cmsWebFile/doUpload` | High
8 | File | `/admin/config/uploadicon.php` | High
9 | File | `/admin/config_time_sync.php` | High
10 | File | `/admin/course.php` | High
11 | File | `/admin/edit-customer-detailed.php` | High
12 | File | `/admin/edit_area.php` | High
13 | File | `/admin/faculty_action.php` | High
14 | File | `/admin/File/fileUpload` | High
15 | File | `/admin/index.php` | High
16 | File | `/admin/infoSys_deal.php?mudi=deal` | High
17 | File | `/admin/list_crl_conf` | High
18 | File | `/admin/list_resource_icon.php?action=delete` | High
19 | File | `/admin/overtime_row.php` | High
20 | File | `/admin/pages/list` | High
21 | File | `/admin/plugin.php` | High
22 | File | `/admin/search-maid.php` | High
23 | File | `/admin/search.php` | High
24 | File | `/admin/twitter.php` | High
25 | File | `/admin/update_user.php` | High
26 | File | `/adminPage/main/upload` | High
27 | File | `/adminPage/www/addOver` | High
28 | File | `/admin_class.php` | High
29 | File | `/adv_resource` | High
30 | File | `/animalsadd.php` | High
31 | File | `/api/authentication/login` | High
32 | File | `/api/stl/actions/search` | High
33 | File | `/api/user` | Medium
34 | File | `/api/v1/terminal/sessions/?limit=1` | High
35 | File | `/api/v2/maps` | Medium
36 | File | `/api/v4/opengraph` | High
37 | File | `/api/{org_id}/users/{email_id}` | High
38 | File | `/app/admin/controller/api/Plugs.php` | High
39 | File | `/app/api/controller/default/Sqlite.php` | High
40 | File | `/app/zentao/module/repo/model.php` | High
41 | File | `/application/controller/Pelanggan.php` | High
42 | File | `/apply/index.php` | High
43 | File | `/blog-details.php` | High
44 | File | `/cgi-bin/cstecgi.cgi` | High
45 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
46 | File | `/cgi-bin/hd_config.cgi` | High
47 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
48 | File | `/cgi-bin/nas_sharing.cgi` | High
49 | File | `/cgi-bin/vitogate.cgi` | High
50 | ... | ... | ...

There are 438 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/b7efe4d1-72b1-4eb8-8735-c246ea98638f
* https://bazaar.abuse.ch/sample/47eac657dd8ba8d47851dc1e5270ce314e104ba32b1c01056902e72a9d78c126/
* https://bazaar.abuse.ch/sample/e60f5ea6362b16c2ed0a7872e1265baf419602f386ff05945acbb6b5d55be6d3/
* https://threatfox.abuse.ch
* https://www.shodan.io/host/45.77.110.173#4443
* https://www.shodan.io/host/49.232.224.106#8100
* https://www.shodan.io/host/107.173.214.76#80
* https://www.shodan.io/host/124.156.152.46#80
* https://x.com/s1dhy/status/1900298352664678907
* https://x.com/s1dhy/status/1900681864345764169

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
