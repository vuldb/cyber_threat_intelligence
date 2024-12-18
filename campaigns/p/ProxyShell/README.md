# ProxyShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyShell:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
2 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/admin-update-employee.php` | High
6 | File | `/admin/login.php` | High
7 | File | `/ajax.php?action=read_msg` | High
8 | File | `/ajax/networking/get_netcfg.php` | High
9 | File | `/api/clusters/local/topics/{topic}/messages` | High
10 | File | `/api/gen/clients/{language}` | High
11 | File | `/API/info` | Medium
12 | File | `/app/options.py` | High
13 | File | `/bin/httpd` | Medium
14 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
15 | File | `/cgi-bin/tosei_kikai.php` | High
16 | File | `/cgi-bin/wapopen` | High
17 | File | `/ci_spms/admin/category` | High
18 | File | `/ci_spms/admin/search/searching/` | High
19 | File | `/classes/Master.php?f=delete_appointment` | High
20 | File | `/classes/Master.php?f=delete_train` | High
21 | File | `/concat?/%2557EB-INF/web.xml` | High
22 | File | `/Content/Template/root/reverse-shell.aspx` | High
23 | File | `/ctcprotocol/Protocol` | High
24 | File | `/dashboard/menu-list.php` | High
25 | File | `/data/remove` | Medium
26 | File | `/debug/pprof` | Medium
27 | File | `/detailed.php` | High
28 | File | `/dist/index.js` | High
29 | File | `/DXR.axd` | Medium
30 | File | `/ebics-server/ebics.aspx` | High
31 | File | `/EXCU_SHELL` | Medium
32 | File | `/ffos/classes/Master.php?f=save_category` | High
33 | File | `/forum/away.php` | High
34 | File | `/goform/form2systime.cgi` | High
35 | File | `/goform/modifyDhcpRule` | High
36 | File | `/goform/ModifyPppAuthWhiteMac` | High
37 | File | `/goform/net\_Web\_get_value` | High
38 | File | `/goform/setStaOffline` | High
39 | File | `/goform/WizardHandle` | High
40 | File | `/goforms/rlminfo` | High
41 | File | `/GponForm/usb_restore_Form?script/` | High
42 | File | `/group1/uploa` | High
43 | File | `/hedwig.cgi` | Medium
44 | File | `/HNAP1` | Low
45 | File | `/HNAP1/SetClientInfo` | High
46 | File | `/Items/*/RemoteImages/Download` | High
47 | ... | ... | ...

There are 412 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
