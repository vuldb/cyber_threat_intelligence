# Campaign C - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign C_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign C:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Campaign C or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign C.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [9.72.55.135](https://vuldb.com/?ip.9.72.55.135) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [10.12.122.62](https://vuldb.com/?ip.10.12.122.62) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [15.50.42.142](https://vuldb.com/?ip.15.50.42.142) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [16.61.28.46](https://vuldb.com/?ip.16.61.28.46) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [17.129.132.89](https://vuldb.com/?ip.17.129.132.89) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [18.42.73.26](https://vuldb.com/?ip.18.42.73.26) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [20.93.133.52](https://vuldb.com/?ip.20.93.133.52) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [21.58.89.27](https://vuldb.com/?ip.21.58.89.27) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [21.88.128.66](https://vuldb.com/?ip.21.88.128.66) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | ... | ... | ... | ...

There are 37 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign C. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign C. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin/lab.php` | High
4 | File | `/ajax.php?action=read_msg` | High
5 | File | `/ajax/networking/get_netcfg.php` | High
6 | File | `/api/gen/clients/{language}` | High
7 | File | `/api/geojson` | Medium
8 | File | `/app/options.py` | High
9 | File | `/bin/httpd` | Medium
10 | File | `/cbs/system/ShowAdvanced.do` | High
11 | File | `/cgi-bin/wapopen` | High
12 | File | `/ci_spms/admin/category` | High
13 | File | `/ci_spms/admin/search/searching/` | High
14 | File | `/classes/Master.php?f=delete_appointment` | High
15 | File | `/classes/Master.php?f=delete_train` | High
16 | File | `/concat?/%2557EB-INF/web.xml` | High
17 | File | `/Content/Template/root/reverse-shell.aspx` | High
18 | File | `/ctcprotocol/Protocol` | High
19 | File | `/dashboard/menu-list.php` | High
20 | File | `/data/remove` | Medium
21 | File | `/debug` | Low
22 | File | `/ebics-server/ebics.aspx` | High
23 | File | `/env` | Low
24 | File | `/ffos/classes/Master.php?f=save_category` | High
25 | File | `/forum/away.php` | High
26 | File | `/goform/setmac` | High
27 | File | `/goforms/rlminfo` | High
28 | File | `/HNAP1` | Low
29 | File | `/HNAP1/SetClientInfo` | High
30 | File | `/Items/*/RemoteImages/Download` | High
31 | File | `/menu.html` | Medium
32 | File | `/modules/profile/index.php` | High
33 | File | `/navigate/navigate_download.php` | High
34 | File | `/ocwbs/admin/?page=user/manage_user` | High
35 | File | `/ofrs/admin/?page=user/manage_user` | High
36 | File | `/out.php` | Medium
37 | File | `/password.html` | High
38 | File | `/php_action/fetchSelectedUser.php` | High
39 | File | `/property-list/property_view.php` | High
40 | File | `/ptms/classes/Users.php` | High
41 | File | `/resources//../` | High
42 | File | `/rest/api/2/search` | High
43 | File | `/s/` | Low
44 | ... | ... | ...

There are 379 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_C_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
