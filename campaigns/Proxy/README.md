# Proxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Proxy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Proxy:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [BR](https://vuldb.com/?country.br)
* ...

There are 29 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Proxy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Proxy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
2 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Proxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin/default.asp` | High
5 | File | `/ajax/networking/get_netcfg.php` | High
6 | File | `/app/options.py` | High
7 | File | `/assets/ctx` | Medium
8 | File | `/checkLogin.cgi` | High
9 | File | `/ci_spms/admin/category` | High
10 | File | `/ci_spms/admin/search/searching/` | High
11 | File | `/classes/Master.php?f=delete_train` | High
12 | File | `/cms/print.php` | High
13 | File | `/concat?/%2557EB-INF/web.xml` | High
14 | File | `/Content/Template/root/reverse-shell.aspx` | High
15 | File | `/dashboard/menu-list.php` | High
16 | File | `/data/remove` | Medium
17 | File | `/etc/passwd` | Medium
18 | File | `/ffos/classes/Master.php?f=save_category` | High
19 | File | `/filemanager/upload.php` | High
20 | File | `/goforms/rlminfo` | High
21 | File | `/index_amp.php` | High
22 | File | `/Items/*/RemoteImages/Download` | High
23 | File | `/login` | Low
24 | File | `/navigate/navigate_download.php` | High
25 | File | `/ocwbs/admin/?page=user/manage_user` | High
26 | File | `/ofrs/admin/?page=user/manage_user` | High
27 | File | `/owa/auth/logon.aspx` | High
28 | File | `/p` | Low
29 | File | `/password.html` | High
30 | File | `/proc/ioports` | High
31 | File | `/property-list/property_view.php` | High
32 | File | `/ptms/classes/Users.php` | High
33 | File | `/rest` | Low
34 | File | `/rest/api/2/search` | High
35 | File | `/s/` | Low
36 | File | `/scripts/cpan_config` | High
37 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
38 | File | `/services/system/setup.json` | High
39 | File | `/spip.php` | Medium
40 | File | `/uncpath/` | Medium
41 | File | `/vloggers_merch/?p=view_product` | High
42 | File | `/webconsole/APIController` | High
43 | File | `/websocket/exec` | High
44 | File | `/whbs/?page=my_bookings` | High
45 | File | `/wp-admin/admin-ajax.php` | High
46 | File | `/wp-json` | Medium
47 | File | `/wp-json/oembed/1.0/embed?url` | High
48 | File | `/_next` | Low
49 | File | `4.edu.php\conn\function.php` | High
50 | ... | ... | ...

There are 431 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/vishalyadav70/Proxy-Server/blob/main/proxy/blacklist.txt
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
