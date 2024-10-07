# UAC-0173 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0173](https://vuldb.com/?actor.uac-0173). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0173](https://vuldb.com/?actor.uac-0173)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0173:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0173.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [179.43.154.184](https://vuldb.com/?ip.179.43.154.184) | hostedby.privatelayer.com | - | High
2 | [195.123.225.51](https://vuldb.com/?ip.195.123.225.51) | vps.hostry.com | - | High
3 | [195.123.226.166](https://vuldb.com/?ip.195.123.226.166) | vjnl.cat | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0173_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0173. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/about-us.php` | High
3 | File | `/admin/action/delete-vaccine.php` | High
4 | File | `/admin/edit-post.php` | High
5 | File | `/admin/index2.html` | High
6 | File | `/admin/userprofile.php` | High
7 | File | `/api/baskets/{name}` | High
8 | File | `/app/index/controller/Common.php` | High
9 | File | `/app/options.py` | High
10 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
11 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
12 | File | `/applications/nexus/modules/front/store/store.php` | High
13 | File | `/apply.cgi` | Medium
14 | File | `/bitrix/admin/ldap_server_edit.php` | High
15 | File | `/cgi-bin/apkg_mgr.cgi` | High
16 | File | `/cgi-bin/cstecgi.cgi` | High
17 | File | `/cgi-bin/nas_sharing.cgi` | High
18 | File | `/cgi-bin/photocenter_mgr.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Master.php` | High
21 | File | `/classes/Master.php?f=delete_record` | High
22 | File | `/classes/Master.php?f=save_category` | High
23 | File | `/classes/SystemSettings.php?f=update_settings` | High
24 | File | `/classes/Users.php?f=save` | High
25 | File | `/College/admin/teacher.php` | High
26 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
27 | File | `/dcim/rack-roles/` | High
28 | File | `/debuginfo.htm` | High
29 | File | `/detailed.php` | High
30 | File | `/dtale/chart-data/1` | High
31 | File | `/etc/passwd` | Medium
32 | File | `/etc/shadow.sample` | High
33 | File | `/fftools/ffmpeg_enc.c` | High
34 | File | `/filter.php` | Medium
35 | File | `/forms/doLogin` | High
36 | File | `/formSysLog` | Medium
37 | File | `/forum/away.php` | High
38 | File | `/goform/aspForm` | High
39 | File | `/goform/SetOnlineDevName` | High
40 | File | `/h.php/page?ref=addtabs` | High
41 | File | `/h/autoSaveDraft` | High
42 | File | `/image.php` | Medium
43 | ... | ... | ...

There are 373 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/5628441

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
