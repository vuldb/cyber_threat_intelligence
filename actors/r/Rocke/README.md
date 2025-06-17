# Rocke - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rocke](https://vuldb.com/?actor.rocke). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rocke](https://vuldb.com/?actor.rocke)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rocke:

* [CN](https://vuldb.com/?country.cn)
* [CH](https://vuldb.com/?country.ch)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rocke.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.4.151](https://vuldb.com/?ip.23.234.4.151) | - | - | High
2 | [23.234.4.153](https://vuldb.com/?ip.23.234.4.153) | - | - | High
3 | [27.193.180.224](https://vuldb.com/?ip.27.193.180.224) | - | - | High
4 | [27.210.170.197](https://vuldb.com/?ip.27.210.170.197) | - | - | High
5 | [27.221.28.231](https://vuldb.com/?ip.27.221.28.231) | - | - | High
6 | [27.221.54.252](https://vuldb.com/?ip.27.221.54.252) | - | - | High
7 | [36.103.236.221](https://vuldb.com/?ip.36.103.236.221) | - | - | High
8 | [36.103.247.121](https://vuldb.com/?ip.36.103.247.121) | - | - | High
9 | [36.248.26.205](https://vuldb.com/?ip.36.248.26.205) | - | - | High
10 | [42.56.76.104](https://vuldb.com/?ip.42.56.76.104) | - | - | High
11 | [42.202.141.230](https://vuldb.com/?ip.42.202.141.230) | - | - | High
12 | [42.236.125.84](https://vuldb.com/?ip.42.236.125.84) | hn.kd.ny.adsl | - | High
13 | [43.224.225.220](https://vuldb.com/?ip.43.224.225.220) | - | - | High
14 | [43.242.166.88](https://vuldb.com/?ip.43.242.166.88) | - | - | High
15 | [52.167.219.168](https://vuldb.com/?ip.52.167.219.168) | - | - | High
16 | [58.215.145.137](https://vuldb.com/?ip.58.215.145.137) | - | - | High
17 | [58.216.107.77](https://vuldb.com/?ip.58.216.107.77) | - | - | High
18 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rocke_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rocke. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.cpr/` | Low
2 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
3 | File | `/aboutadd.php` | High
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/?setting-base.htm` | High
6 | File | `/Admin/add-admin.php` | High
7 | File | `/admin/budget/manage_budget.php` | High
8 | File | `/admin/bwdates-reports-ds.php` | High
9 | File | `/admin/index.php` | High
10 | File | `/admin/index2.html` | High
11 | File | `/admin/sql` | Medium
12 | File | `/admin/students.php` | High
13 | File | `/admin/students/manage.php` | High
14 | File | `/admin/system.html` | High
15 | File | `/admin/system.php` | High
16 | File | `/admin/twitter.php` | High
17 | File | `/admin/update_users.php` | High
18 | File | `/adminapi/system/crud` | High
19 | File | `/adminPage/conf/reload` | High
20 | File | `/amssplus/index.php` | High
21 | File | `/api/admin/store/product/save` | High
22 | File | `/api/admin/system/store/order/list` | High
23 | File | `/api/snapshots/` | High
24 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
25 | File | `/api /v3/auth` | High
26 | File | `/api/wechat/app_auth` | High
27 | File | `/api/wizard/getDualbandSync` | High
28 | File | `/api/wizard/getWifiNeighbour` | High
29 | File | `/app-api/infra/file/upload` | High
30 | File | `/app/api/controller/Store.php` | High
31 | File | `/application/index/controller/Icon.php` | High
32 | File | `/application/index/controller/Screen.php` | High
33 | File | `/apps/api/views/deploy_api.py` | High
34 | File | `/backend/admin/his_admin_register_patient.php` | High
35 | File | `/backend/register.php` | High
36 | File | `/bin/ate` | Medium
37 | File | `/boaform/device_reset.cgi` | High
38 | File | `/book_list.php` | High
39 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
40 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
41 | File | `/cgi-bin/cstecgi.cgi` | High
42 | File | `/cgi-bin/nas_sharing.cgi` | High
43 | File | `/classes/Users.php?f=save` | High
44 | File | `/com/esafenet/servlet/system/ProtocolService.java` | High
45 | File | `/control/edit_client.php` | High
46 | ... | ... | ...

There are 403 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/rocke-champion-of-monero-miners.html
* https://blog.talosintelligence.com/2018/12/cryptomining-campaigns-2018.html
* https://unit42.paloaltonetworks.com/malware-used-by-rocke-group-evolves-to-evade-detection-by-cloud-security-products/
* https://unit42.paloaltonetworks.com/rockein-the-netflow/
* https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
