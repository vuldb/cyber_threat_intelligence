# CoinMiner - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CoinMiner](https://vuldb.com/?actor.coinminer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.coinminer](https://vuldb.com/?actor.coinminer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CoinMiner:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [IM](https://vuldb.com/?country.im)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CoinMiner.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [4.4.0.0](https://vuldb.com/?ip.4.4.0.0) | - | - | High
2 | [5.196.13.29](https://vuldb.com/?ip.5.196.13.29) | 29.ip-5-196-13.eu | - | High
3 | [5.196.23.240](https://vuldb.com/?ip.5.196.23.240) | 240.ip-5-196-23.eu | - | High
4 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
5 | [18.210.126.40](https://vuldb.com/?ip.18.210.126.40) | ec2-18-210-126-40.compute-1.amazonaws.com | - | Medium
6 | [23.21.48.44](https://vuldb.com/?ip.23.21.48.44) | ec2-23-21-48-44.compute-1.amazonaws.com | - | Medium
7 | [23.21.76.253](https://vuldb.com/?ip.23.21.76.253) | ec2-23-21-76-253.compute-1.amazonaws.com | - | Medium
8 | [23.21.126.66](https://vuldb.com/?ip.23.21.126.66) | ec2-23-21-126-66.compute-1.amazonaws.com | - | Medium
9 | [23.21.140.41](https://vuldb.com/?ip.23.21.140.41) | ec2-23-21-140-41.compute-1.amazonaws.com | - | Medium
10 | [23.21.252.4](https://vuldb.com/?ip.23.21.252.4) | ec2-23-21-252-4.compute-1.amazonaws.com | - | Medium
11 | [49.12.80.38](https://vuldb.com/?ip.49.12.80.38) | static.38.80.12.49.clients.your-server.de | - | High
12 | [49.12.80.40](https://vuldb.com/?ip.49.12.80.40) | static.40.80.12.49.clients.your-server.de | - | High
13 | [50.19.48.59](https://vuldb.com/?ip.50.19.48.59) | ec2-50-19-48-59.compute-1.amazonaws.com | - | Medium
14 | [50.19.96.218](https://vuldb.com/?ip.50.19.96.218) | ec2-50-19-96-218.compute-1.amazonaws.com | - | Medium
15 | [50.19.252.36](https://vuldb.com/?ip.50.19.252.36) | ec2-50-19-252-36.compute-1.amazonaws.com | - | Medium
16 | [51.15.54.102](https://vuldb.com/?ip.51.15.54.102) | 102-54-15-51.instances.scw.cloud | - | High
17 | ... | ... | ... | ...

There are 63 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CoinMiner_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CoinMiner. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.plan` | Low
2 | File | `.tin` | Low
3 | File | `/admin/read.php?mudi=announContent` | High
4 | File | `/advanced-tools/nova/bin/netwatch` | High
5 | File | `/ajaxGetFileByPath.php` | High
6 | File | `/app/sys1.php` | High
7 | File | `/cgi-bin/editBookmark` | High
8 | File | `/cgi-bin/luci;stok=/locale` | High
9 | File | `/classes/Login.php` | High
10 | File | `/config/list` | Medium
11 | File | `/configs/application.ini` | High
12 | File | `/home/cavesConsole` | High
13 | File | `/home/httpd/cgi-bin/cgi.cgi` | High
14 | File | `/home/kickPlayer` | High
15 | File | `/home/masterConsole` | High
16 | File | `/home/sendBroadcast` | High
17 | File | `/rapi/read_url` | High
18 | File | `/services/Card/findUser` | High
19 | File | `/spacecom/login.php` | High
20 | File | `/student/bookdetails.php` | High
21 | File | `/sys/dict/queryTableData` | High
22 | File | `/Taier/API/tenant/listTenant` | High
23 | File | `/ucenter/active.php` | High
24 | File | `/uncpath/` | Medium
25 | File | `/user/updatePwd` | High
26 | File | `/userRpm/PingIframeRpm` | High
27 | File | `/vm/admin/doctors.php` | High
28 | File | `/xampp/guestbook-en.pl` | High
29 | File | `/zm/index.php` | High
30 | File | `abook_database.php` | High
31 | File | `action.php` | Medium
32 | File | `admin.php` | Medium
33 | File | `admin/admin_process.php` | High
34 | File | `admin/user.php` | High
35 | File | `admin/vqmods.app/vqmods.inc.php` | High
36 | File | `ad_manage.php` | High
37 | File | `afd.sys` | Low
38 | File | `akocomment.php` | High
39 | File | `app/routes/research.js` | High
40 | ... | ... | ...

There are 345 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/60440/
* https://blog.talosintelligence.com/2018/09/threat-roundup-0914-0921.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0212-0219.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0219-0226.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0416-0423.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0507-0514.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0604-0611.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0611-0617.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0617-0624.html
* https://blog.talosintelligence.com/2022/04/threat-roundup-0408-0415.html
* https://blog.talosintelligence.com/threat-roundup-1013-1020/
* https://blog.trendmicro.com/trendlabs-security-intelligence/zoomed-in-a-look-into-a-coinminer-bundled-with-zoom-installer/
* https://isc.sans.edu/forums/diary/CoinMiners+searching+for+hosts/24364/
* https://isc.sans.edu/forums/diary/From+Microtik+with+Love/23762/ https://isc.sans.edu/forums/diary/More+malspam+pushing+Lokibot/23754/
* https://isc.sans.edu/forums/diary/Pornographic+malspam+pushes+coin+miner+malware/23119/
* https://threatfox.abuse.ch
* https://tria.ge/220416-dv7casgchn
* https://urlhaus.abuse.ch/url/2739139/
* https://www.trendmicro.com/en_us/research/22/i/a-post-exploitation-look-at-coinminers-abusing-weblogic-vulnerab.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
