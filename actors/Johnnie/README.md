# Johnnie - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Johnnie](https://vuldb.com/?actor.johnnie). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.johnnie](https://vuldb.com/?actor.johnnie)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Johnnie:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Johnnie.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
2 | [23.1.236.9](https://vuldb.com/?ip.23.1.236.9) | a23-1-236-9.deploy.static.akamaitechnologies.com | - | High
3 | [23.6.69.99](https://vuldb.com/?ip.23.6.69.99) | a23-6-69-99.deploy.static.akamaitechnologies.com | - | High
4 | [23.46.150.48](https://vuldb.com/?ip.23.46.150.48) | a23-46-150-48.deploy.static.akamaitechnologies.com | - | High
5 | [23.46.150.72](https://vuldb.com/?ip.23.46.150.72) | a23-46-150-72.deploy.static.akamaitechnologies.com | - | High
6 | [23.105.131.235](https://vuldb.com/?ip.23.105.131.235) | - | - | High
7 | [23.218.140.208](https://vuldb.com/?ip.23.218.140.208) | a23-218-140-208.deploy.static.akamaitechnologies.com | - | High
8 | [23.221.72.10](https://vuldb.com/?ip.23.221.72.10) | a23-221-72-10.deploy.static.akamaitechnologies.com | - | High
9 | [23.221.72.16](https://vuldb.com/?ip.23.221.72.16) | a23-221-72-16.deploy.static.akamaitechnologies.com | - | High
10 | [23.221.72.27](https://vuldb.com/?ip.23.221.72.27) | a23-221-72-27.deploy.static.akamaitechnologies.com | - | High
11 | [23.221.73.32](https://vuldb.com/?ip.23.221.73.32) | a23-221-73-32.deploy.static.akamaitechnologies.com | - | High
12 | [34.107.221.82](https://vuldb.com/?ip.34.107.221.82) | 82.221.107.34.bc.googleusercontent.com | - | Medium
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Johnnie_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Johnnie. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/../conf/config.properties` | High
3 | File | `/ajax.php?action=read_msg` | High
4 | File | `/ajax/networking/get_netcfg.php` | High
5 | File | `/api/gen/clients/{language}` | High
6 | File | `/app/options.py` | High
7 | File | `/bin/httpd` | Medium
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/ci_spms/admin/category` | High
10 | File | `/ci_spms/admin/search/searching/` | High
11 | File | `/classes/Master.php?f=delete_appointment` | High
12 | File | `/classes/Master.php?f=delete_train` | High
13 | File | `/cms/print.php` | High
14 | File | `/concat?/%2557EB-INF/web.xml` | High
15 | File | `/configs/application.ini` | High
16 | File | `/Content/Template/root/reverse-shell.aspx` | High
17 | File | `/ctcprotocol/Protocol` | High
18 | File | `/dashboard/menu-list.php` | High
19 | File | `/data/remove` | Medium
20 | File | `/ebics-server/ebics.aspx` | High
21 | File | `/ffos/classes/Master.php?f=save_category` | High
22 | File | `/forum/away.php` | High
23 | File | `/goforms/rlminfo` | High
24 | File | `/HNAP1` | Low
25 | File | `/HNAP1/SetClientInfo` | High
26 | File | `/Items/*/RemoteImages/Download` | High
27 | File | `/menu.html` | Medium
28 | File | `/MIME/INBOX-MM-1/` | High
29 | File | `/modules/profile/index.php` | High
30 | File | `/navigate/navigate_download.php` | High
31 | File | `/ocwbs/admin/?page=user/manage_user` | High
32 | File | `/ofrs/admin/?page=user/manage_user` | High
33 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
34 | File | `/out.php` | Medium
35 | File | `/password.html` | High
36 | File | `/php_action/fetchSelectedUser.php` | High
37 | File | `/property-list/property_view.php` | High
38 | File | `/ptms/classes/Users.php` | High
39 | File | `/resources//../` | High
40 | File | `/rest/api/2/search` | High
41 | File | `/s/` | Low
42 | File | `/scripts/cpan_config` | High
43 | ... | ... | ...

There are 369 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/06/threat-roundup-0601-0615.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0226-0305.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0311-0318.html
* https://blog.talosintelligence.com/2022/06/threat-roundup-0610-0617.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
