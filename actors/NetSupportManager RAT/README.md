# NetSupportManager RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [NetSupportManager RAT](https://vuldb.com/?actor.netsupportmanager_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.netsupportmanager_rat](https://vuldb.com/?actor.netsupportmanager_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NetSupportManager RAT:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NetSupportManager RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.72.55](https://vuldb.com/?ip.5.45.72.55) | - | - | High
2 | [5.45.74.233](https://vuldb.com/?ip.5.45.74.233) | zmta37.corpresponse.com | - | High
3 | [5.45.83.127](https://vuldb.com/?ip.5.45.83.127) | - | - | High
4 | [5.252.176.69](https://vuldb.com/?ip.5.252.176.69) | 5-252-176-69.mivocloud.com | - | High
5 | [5.252.179.13](https://vuldb.com/?ip.5.252.179.13) | 5-252-179-13.mivocloud.com | - | High
6 | [5.252.179.89](https://vuldb.com/?ip.5.252.179.89) | no-rdns.mivocloud.com | - | High
7 | [5.252.179.93](https://vuldb.com/?ip.5.252.179.93) | no-rdns.mivocloud.com | - | High
8 | [23.227.193.80](https://vuldb.com/?ip.23.227.193.80) | 23-227-193-80.static.hvvc.us | - | High
9 | [45.11.180.120](https://vuldb.com/?ip.45.11.180.120) | - | - | High
10 | [45.15.157.144](https://vuldb.com/?ip.45.15.157.144) | - | - | High
11 | [45.61.136.72](https://vuldb.com/?ip.45.61.136.72) | - | - | High
12 | [45.61.138.73](https://vuldb.com/?ip.45.61.138.73) | - | - | High
13 | [45.76.172.113](https://vuldb.com/?ip.45.76.172.113) | 45.76.172.113.vultrusercontent.com | - | High
14 | [45.77.31.210](https://vuldb.com/?ip.45.77.31.210) | 45.77.31.210.vultrusercontent.com | - | High
15 | [46.17.106.230](https://vuldb.com/?ip.46.17.106.230) | vds2364993.my-ihor.ru | - | High
16 | [46.21.159.165](https://vuldb.com/?ip.46.21.159.165) | 165.159.21.46.swiftway.net | - | High
17 | [46.161.40.59](https://vuldb.com/?ip.46.161.40.59) | - | - | High
18 | [51.195.53.204](https://vuldb.com/?ip.51.195.53.204) | ip204.ip-51-195-53.eu | - | High
19 | [62.173.140.156](https://vuldb.com/?ip.62.173.140.156) | spetstroymsk77.example.com | - | High
20 | [62.173.154.94](https://vuldb.com/?ip.62.173.154.94) | yurisleptsov.example.com | - | High
21 | ... | ... | ... | ...

There are 80 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _NetSupportManager RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by NetSupportManager RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\Teradici\PCoIP.exe` | High
2 | File | `/.vnc/sesman_${username}_passwd` | High
3 | File | `/addnews.html` | High
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/index.php` | High
6 | File | `/admin/maintenance/view_designation.php` | High
7 | File | `/api/RecordingList/DownloadRecord?file=` | High
8 | File | `/apply.cgi` | Medium
9 | File | `/cwc/login` | Medium
10 | File | `/etc/luminex/pkgmgr` | High
11 | File | `/etc/quantum/quantum.conf` | High
12 | File | `/forum/away.php` | High
13 | File | `/getcfg.php` | Medium
14 | File | `/iwguestbook/admin/badwords_edit.asp` | High
15 | File | `/iwguestbook/admin/messages_edit.asp` | High
16 | File | `/jeecg-boot/sys/common/upload` | High
17 | File | `/members/index.php` | High
18 | File | `/MIME/INBOX-MM-1/` | High
19 | File | `/mkshope/login.php` | High
20 | File | `/php_action/createUser.php` | High
21 | File | `/proc/self/environ` | High
22 | File | `/rom-0` | Low
23 | File | `/services/details.asp` | High
24 | File | `/spip.php` | Medium
25 | File | `/thruk/#cgi-bin/extinfo.cgi?type=2` | High
26 | File | `/uncpath/` | Medium
27 | File | `/user/updatePwd` | High
28 | File | `/usr/bin/at` | Medium
29 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
30 | File | `/var/log/nginx` | High
31 | File | `/way4acs/enroll` | High
32 | File | `/wp-admin/admin-ajax.php` | High
33 | File | `/wp-admin/admin.php?page=slickquiz-scores&id` | High
34 | File | `/wp-content/uploads/photo-gallery/` | High
35 | File | `7786/tcp` | Medium
36 | File | `12122006-djtest.doc` | High
37 | File | `abitwhizzy.php` | High
38 | File | `acc.php` | Low
39 | File | `AccessPoint.aspx` | High
40 | File | `activate.php` | Medium
41 | File | `activenews_search.asp` | High
42 | File | `addpost1.asp` | Medium
43 | File | `addshowsform.php` | High
44 | File | `add_quiz.php` | Medium
45 | File | `admin.loudmouth.php` | High
46 | File | `admin.php` | Medium
47 | File | `admin.pl` | Medium
48 | File | `admin/conf_users_edit.php` | High
49 | File | `admin/dashboard.php` | High
50 | File | `admin/haber_ekle.asp` | High
51 | File | `admin/index.php` | High
52 | File | `admin/modules_data.php` | High
53 | File | `admin/skins.php` | High
54 | File | `admin/specials.php` | High
55 | File | `admin_events.php` | High
56 | File | `agent_subaffiliates.pl` | High
57 | File | `ajax.php` | Medium
58 | File | `ajax_invoice.php` | High
59 | File | `app/topic/action/admin/topic.php` | High
60 | File | `appserv/main.php` | High
61 | File | `articulo.php` | Medium
62 | ... | ... | ...

There are 547 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/1a9b3968a2f3a4ae0c9c51e6fc41a48829ac4a0fa118a7530c36715638ef0209/
* https://bazaar.abuse.ch/sample/26cad4ec29bc07d7b2c32c94dbbef397391babf1c78cc533950b325aaf11bba8/
* https://bazaar.abuse.ch/sample/c9e6dc44db59f1883e850babac21890e5723d2627a623c47f709e3bb7d073e35/
* https://infosec.exchange/@malware_traffic/109762477310102114
* https://threatfox.abuse.ch
* https://twitter.com/BroadAnalysis/status/1544348111488929796
* https://twitter.com/Iamdeadlyz/status/1626286411879190528
* https://twitter.com/phage_nz/status/1562229369669828608
* https://twitter.com/pollo290987/status/1562087034948386817
* https://twitter.com/pollo290987/status/1654206717251530753
* https://twitter.com/StopMalvertisin/status/1648223628067237890

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
