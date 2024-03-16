# MooBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MooBot](https://vuldb.com/?actor.moobot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.moobot](https://vuldb.com/?actor.moobot)

## Campaigns

The following _campaigns_ are known and can be associated with MooBot:

* DDoS Ukraine
* UNIX CCTV DVR

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MooBot:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MooBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.80.126](https://vuldb.com/?ip.5.181.80.126) | ip-80-126-bullethost.net | - | High
2 | [14.225.213.142](https://vuldb.com/?ip.14.225.213.142) | static.vnpt.vn | - | High
3 | [31.13.195.56](https://vuldb.com/?ip.31.13.195.56) | - | - | High
4 | [34.18.78.72](https://vuldb.com/?ip.34.18.78.72) | 72.78.18.34.bc.googleusercontent.com | - | Medium
5 | [37.49.226.216](https://vuldb.com/?ip.37.49.226.216) | - | - | High
6 | [42.96.2.220](https://vuldb.com/?ip.42.96.2.220) | - | - | High
7 | [42.119.113.85](https://vuldb.com/?ip.42.119.113.85) | - | - | High
8 | [45.11.93.150](https://vuldb.com/?ip.45.11.93.150) | - | - | High
9 | [45.13.227.12](https://vuldb.com/?ip.45.13.227.12) | tube-hosting.com | - | High
10 | [45.77.240.70](https://vuldb.com/?ip.45.77.240.70) | 45.77.240.70.vultrusercontent.com | - | High
11 | [45.95.168.90](https://vuldb.com/?ip.45.95.168.90) | - | - | High
12 | [45.95.169.14](https://vuldb.com/?ip.45.95.169.14) | - | - | High
13 | [45.95.169.135](https://vuldb.com/?ip.45.95.169.135) | - | - | High
14 | [45.118.146.123](https://vuldb.com/?ip.45.118.146.123) | - | - | High
15 | [45.128.232.4](https://vuldb.com/?ip.45.128.232.4) | - | - | High
16 | [45.139.104.69](https://vuldb.com/?ip.45.139.104.69) | - | - | High
17 | [51.250.71.111](https://vuldb.com/?ip.51.250.71.111) | - | - | High
18 | [79.137.207.38](https://vuldb.com/?ip.79.137.207.38) | workable-moon.aeza.network | - | High
19 | [84.54.51.103](https://vuldb.com/?ip.84.54.51.103) | nekololis.ovh | - | High
20 | [85.204.116.119](https://vuldb.com/?ip.85.204.116.119) | - | - | High
21 | [87.121.58.103](https://vuldb.com/?ip.87.121.58.103) | nekololis.ovh | - | High
22 | [89.190.156.176](https://vuldb.com/?ip.89.190.156.176) | hosted-by.alsycon.net | - | High
23 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | UNIX CCTV DVR | High
24 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | UNIX CCTV DVR | High
25 | ... | ... | ... | ...

There are 97 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MooBot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MooBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin/action/new-father.php` | High
3 | File | `/admin/edit_teacher.php` | High
4 | File | `/admin/fields/manage_field.php` | High
5 | File | `/admin/orders/view_order.php` | High
6 | File | `/admin_ping.htm` | High
7 | File | `/admin_route/dec_service_credits.php` | High
8 | File | `/admin_route/inc_service_credits.php` | High
9 | File | `/api/sys/set_passwd` | High
10 | File | `/app/api/controller/default/Sqlite.php` | High
11 | File | `/application/index/controller/Databasesource.php` | High
12 | File | `/application/index/controller/Icon.php` | High
13 | File | `/application/index/controller/Screen.php` | High
14 | File | `/application/plugins/controller/Upload.php` | High
15 | File | `/arch/x86/mm/cpu_entry_area.c` | High
16 | File | `/b2b-supermarket/shopping-cart` | High
17 | File | `/bin/boa` | Medium
18 | File | `/boafrm/formMapDelDevice` | High
19 | File | `/calendar/minimizer/index.php` | High
20 | File | `/cgi-bin/cstecgi.cgi` | High
21 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
22 | File | `/cgi-bin/koha/catalogue/search.pl` | High
23 | File | `/cgi-bin/mainfunction.cgi` | High
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/core/conditions/AbstractWrapper.java` | High
26 | File | `/core/redirect` | High
27 | File | `/core/tools/update_menu.php` | High
28 | File | `/dashboard/snapshot/*?orgId=0` | High
29 | File | `/dayrui/My/Config/Install.txt` | High
30 | File | `/DXR.axd` | Medium
31 | File | `/ECT_Provider/` | High
32 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
33 | File | `/Employer/EditProfile.php` | High
34 | File | `/endpoint/add-user.php` | High
35 | File | `/fax/fax_send.php` | High
36 | File | `/forum/away.php` | High
37 | File | `/forums/editforum.php` | High
38 | File | `/general/attendance/manage/ask_duty/delete.php` | High
39 | File | `/goform/` | Medium
40 | File | `/goform/WifiMacFilterGet` | High
41 | File | `/goform/wifiSSIDset` | High
42 | ... | ... | ...

There are 365 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/44b44c4def50c86469bb2fa08da19dfe0439d6461d84eb612ac2e2c8ec2cff43/
* https://bazaar.abuse.ch/sample/71d1ed5fba5b97dd00bc8d7c5c155cb45822c5b63f5162e3fddaa177d7fa76d7/
* https://bazaar.abuse.ch/sample/90ee907f4847013a3c42e7f9292b27b0957e531556f2d610e81864beb6b7c663/
* https://bazaar.abuse.ch/sample/907cc83a60ad4dce687274f158cf52e1f5f65f5ffc2916e391ec8f36982986dd/
* https://bazaar.abuse.ch/sample/b3d25c49483da2433b6dd0888f2bef0d4a7528d5a30b3366e6be9d956815ff31/
* https://bazaar.abuse.ch/sample/e09dfc1ba1052e4b5c2c3ff2d9985f6f5024b526aeb8ae4a1d28d8cd81bb0c1e/
* https://blog.netlab.360.com/ddos-botnet-moobot-en/
* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://blog.netlab.360.com/the-botnet-cluster-on-185-244-25-0-24-en/
* https://isc.sans.edu/diary/rss/30694
* https://search.censys.io/hosts/42.96.2.220
* https://search.censys.io/hosts/42.119.113.85
* https://search.censys.io/hosts/45.77.240.70
* https://search.censys.io/hosts/45.95.169.14
* https://search.censys.io/hosts/45.95.169.135
* https://search.censys.io/hosts/45.118.146.123
* https://search.censys.io/hosts/45.128.232.4
* https://search.censys.io/hosts/45.139.104.69
* https://search.censys.io/hosts/51.250.71.111
* https://search.censys.io/hosts/79.137.207.38
* https://search.censys.io/hosts/91.92.252.23
* https://search.censys.io/hosts/91.92.252.33
* https://search.censys.io/hosts/93.123.39.165
* https://search.censys.io/hosts/93.123.85.14
* https://search.censys.io/hosts/93.123.85.43
* https://search.censys.io/hosts/93.123.85.60
* https://search.censys.io/hosts/93.123.85.79
* https://search.censys.io/hosts/93.123.85.90
* https://search.censys.io/hosts/93.123.85.116
* https://search.censys.io/hosts/93.123.85.122
* https://search.censys.io/hosts/93.123.85.206
* https://search.censys.io/hosts/103.65.235.21
* https://search.censys.io/hosts/103.74.100.192
* https://search.censys.io/hosts/103.77.240.62
* https://search.censys.io/hosts/103.78.0.159
* https://search.censys.io/hosts/103.116.52.207
* https://search.censys.io/hosts/103.172.79.74
* https://search.censys.io/hosts/103.180.149.224
* https://search.censys.io/hosts/103.189.203.36
* https://search.censys.io/hosts/108.174.198.206
* https://search.censys.io/hosts/109.107.181.93
* https://search.censys.io/hosts/116.118.49.164
* https://search.censys.io/hosts/137.175.17.80
* https://search.censys.io/hosts/137.175.17.137
* https://search.censys.io/hosts/146.19.191.178
* https://search.censys.io/hosts/147.78.103.103
* https://search.censys.io/hosts/179.61.251.93
* https://search.censys.io/hosts/185.36.81.46
* https://search.censys.io/hosts/194.48.250.11
* https://search.censys.io/hosts/194.116.216.83
* https://search.censys.io/hosts/210.211.117.205
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
