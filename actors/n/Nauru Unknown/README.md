# Nauru Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nauru Unknown](https://vuldb.com/?actor.nauru_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nauru_unknown](https://vuldb.com/?actor.nauru_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nauru Unknown:

* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 27 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nauru Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.56.140](https://vuldb.com/?ip.5.62.56.140) | r-140-56-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.58.132](https://vuldb.com/?ip.5.62.58.132) | r-132-58-62-5.consumer-pool.prcdn.net | - | High
3 | [43.230.6.0](https://vuldb.com/?ip.43.230.6.0) | - | - | High
4 | [45.12.70.170](https://vuldb.com/?ip.45.12.70.170) | conscientiously.alltieinc.com | - | High
5 | [45.12.71.170](https://vuldb.com/?ip.45.12.71.170) | - | - | High
6 | [45.42.176.0](https://vuldb.com/?ip.45.42.176.0) | - | - | High
7 | [46.36.201.241](https://vuldb.com/?ip.46.36.201.241) | - | - | High
8 | [46.36.201.242](https://vuldb.com/?ip.46.36.201.242) | - | - | High
9 | ... | ... | ... | ...

There are 32 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nauru Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-25, CWE-29 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nauru Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\Steam` | High
2 | File | `/activation.php` | High
3 | File | `/Admin/changepassword.php` | High
4 | File | `/admin/create_product.php` | High
5 | File | `/admin/manage_academic.php` | High
6 | File | `/admin/upload.php` | High
7 | File | `/admin/user/user-move-run.php` | High
8 | File | `/ajax/get_patient_history.php` | High
9 | File | `/ajax_city.php` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/controllers/merchant/shop/PosterController.php` | High
12 | File | `/api/ping` | Medium
13 | File | `/blog` | Low
14 | File | `/boafrm/formSysCmd` | High
15 | File | `/car-rental-management-system/admin/view_car.php=` | High
16 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/hd_config.cgi` | High
19 | File | `/cgi-bin/mft/` | High
20 | File | `/cgi-bin/wlogin.cgi` | High
21 | File | `/cgi-mod/lookup.cgi` | High
22 | File | `/classes/Master.php?f=save_inquiry` | High
23 | File | `/component_server` | High
24 | File | `/config/config.json` | High
25 | File | `/core/config-revisions` | High
26 | File | `/debug/pprof` | Medium
27 | File | `/devinfo` | Medium
28 | File | `/diagnostics_doit` | High
29 | File | `/download` | Medium
30 | File | `/DXR.axd` | Medium
31 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
32 | File | `/etc/hosts.deny` | High
33 | File | `/flatpress/admin.php` | High
34 | File | `/goform/goform_get_cmd_process` | High
35 | File | `/goform/RP_checkCredentialsByBBS` | High
36 | File | `/ims/login.php` | High
37 | File | `/index.php?menu=asterisk_cli` | High
38 | File | `/index/ajax/lang` | High
39 | File | `/login.php?do=login` | High
40 | File | `/mee/login` | Medium
41 | File | `/metrics` | Medium
42 | File | `/php-opos/index.php` | High
43 | File | `/portal/search.htm` | High
44 | File | `/portal/user-register.php` | High
45 | ... | ... | ...

There are 388 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_nr.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_nr.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_nr.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
