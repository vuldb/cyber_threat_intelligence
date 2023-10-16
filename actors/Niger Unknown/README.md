# Niger Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Niger Unknown](https://vuldb.com/?actor.niger_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.niger_unknown](https://vuldb.com/?actor.niger_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Niger Unknown:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [ES](https://vuldb.com/?country.es)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Niger Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.61.56](https://vuldb.com/?ip.5.62.61.56) | r-56-61-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.63.48](https://vuldb.com/?ip.5.62.63.48) | r-48-63-62-5.consumer-pool.prcdn.net | - | High
3 | [41.78.116.0](https://vuldb.com/?ip.41.78.116.0) | - | - | High
4 | [41.138.32.0](https://vuldb.com/?ip.41.138.32.0) | - | - | High
5 | [41.190.228.0](https://vuldb.com/?ip.41.190.228.0) | - | - | High
6 | [41.203.128.0](https://vuldb.com/?ip.41.203.128.0) | - | - | High
7 | [41.221.217.0](https://vuldb.com/?ip.41.221.217.0) | - | - | High
8 | ... | ... | ... | ...

There are 28 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Niger Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Niger Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/acms/admin/cargo_types/view_cargo_type.php` | High
4 | File | `/addNotifyServlet` | High
5 | File | `/admin.php/pic/admin/pic/hy` | High
6 | File | `/admin/?page=reports/stockin` | High
7 | File | `/admin/addemployee.php` | High
8 | File | `/admin/inbox.php&action=read` | High
9 | File | `/admin/index.php` | High
10 | File | `/admin/operations/packages.php` | High
11 | File | `/admin/orders/update_status.php` | High
12 | File | `/admin/pages/sections_save.php` | High
13 | File | `/admin/settings/save.php` | High
14 | File | `/admin/uesrs.php&action=display&value=Show` | High
15 | File | `/admin/vote_edit.php` | High
16 | File | `/apilog.php` | Medium
17 | File | `/appliance/users?action=edit` | High
18 | File | `/apply.cgi` | Medium
19 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
20 | File | `/classes/Master.php?f=save_inquiry` | High
21 | File | `/collection/all` | High
22 | File | `/config/list` | Medium
23 | File | `/coreframe/app/guestbook/myissue.php` | High
24 | File | `/dede/co_do.php` | High
25 | File | `/DXR.axd` | Medium
26 | File | `/etc/init.d/sshd_service` | High
27 | File | `/filemanager/upload.php` | High
28 | File | `/forum/away.php` | High
29 | File | `/fuel/sitevariables/delete/4` | High
30 | File | `/goform/saveParentControlInfo` | High
31 | File | `/goform/setSnmpInfo` | High
32 | File | `/if.cgi` | Low
33 | File | `/include/make.php` | High
34 | File | `/index.php` | Medium
35 | File | `/index.php/admins/Fields/get_fields.html` | High
36 | File | `/login` | Low
37 | File | `/mgm_dev_reset.asp` | High
38 | File | `/mifs/c/i/reg/reg.html` | High
39 | File | `/modules/profile/index.php` | High
40 | File | `/news.dtl.php` | High
41 | File | `/odlms/classes/Master.php?f=delete_message` | High
42 | File | `/php-sms/classes/SystemSettings.php` | High
43 | File | `/php_action/createUser.php` | High
44 | File | `/release-x64/otfccdump+0x6e7e3d` | High
45 | File | `/reps/admin/?page=agents/manage_agent` | High
46 | File | `/see_more_details.php` | High
47 | File | `/services/Card/findUser` | High
48 | File | `/services/details.asp` | High
49 | File | `/setup` | Low
50 | File | `/spip.php` | Medium
51 | ... | ... | ...

There are 446 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_ne.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_ne.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_ne.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
