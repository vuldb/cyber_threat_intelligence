# Sednit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sednit](https://vuldb.com/?actor.sednit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sednit](https://vuldb.com/?actor.sednit)

## Campaigns

The following _campaigns_ are known and can be associated with Sednit:

* Trump’s_Attack_on_Syria

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sednit:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sednit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | Trump&rsquo;s_Attack_on_Syria | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | Trump&rsquo;s_Attack_on_Syria | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | Trump&rsquo;s_Attack_on_Syria | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | Trump&rsquo;s_Attack_on_Syria | Medium
5 | [5.135.183.154](https://vuldb.com/?ip.5.135.183.154) | ns3290077.ip-5-135-183.eu | - | High
6 | [19.2.45.3](https://vuldb.com/?ip.19.2.45.3) | - | Trump&rsquo;s_Attack_on_Syria | High
7 | [21.15.46.55](https://vuldb.com/?ip.21.15.46.55) | - | Trump&rsquo;s_Attack_on_Syria | High
8 | [31.7.62.103](https://vuldb.com/?ip.31.7.62.103) | - | - | High
9 | [31.220.43.99](https://vuldb.com/?ip.31.220.43.99) | nl-2.sa-irc.com | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sednit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sednit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add_new_invoice.php` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/Admin/akun_edit.php` | High
6 | File | `/admin/apply.php` | High
7 | File | `/admin/article.php` | High
8 | File | `/admin/create-package.php` | High
9 | File | `/admin/doAdminAction.php?act=addCate` | High
10 | File | `/admin/edit-brand.php` | High
11 | File | `/admin/edit-card-detail.php` | High
12 | File | `/admin/edit-post.php` | High
13 | File | `/admin/edit.php` | High
14 | File | `/admin/edit_fuel.php` | High
15 | File | `/admin/home.php?con=add` | High
16 | File | `/admin/index2.html` | High
17 | File | `/Admin/Proses_Edit_Akun.php` | High
18 | File | `/admin/robot.php` | High
19 | File | `/admin/search-invoices.php` | High
20 | File | `/admin/search-vehicle.php` | High
21 | File | `/admin/students/view_details.php` | High
22 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
23 | File | `/admin/userprofile.php` | High
24 | File | `/admin/view-card-detail.php` | High
25 | File | `/api/baskets/{name}` | High
26 | File | `/app/index/controller/Common.php` | High
27 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
28 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
29 | File | `/applications/nexus/modules/front/store/store.php` | High
30 | File | `/backend/doc/his_doc_update-account.php` | High
31 | File | `/bitrix/admin/ldap_server_edit.php` | High
32 | File | `/cgi-bin/apkg_mgr.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/classes/Master.php` | High
37 | File | `/classes/master.php?f=delete_order` | High
38 | File | `/classes/Master.php?f=delete_record` | High
39 | File | `/classes/Master.php?f=save_category` | High
40 | File | `/classes/SystemSettings.php?f=update_settings` | High
41 | File | `/classes/Users.php?f=save` | High
42 | File | `/College/admin/teacher.php` | High
43 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
44 | File | `/customnode/install` | High
45 | File | `/dcim/rack-roles/` | High
46 | File | `/deal/{note_id}/note` | High
47 | File | `/deleteanimal.php` | High
48 | File | `/detailed.php` | High
49 | File | `/dtale/chart-data/1` | High
50 | File | `/etc/shadow.sample` | High
51 | File | `/fftools/ffmpeg_enc.c` | High
52 | File | `/file/accept.php` | High
53 | File | `/filter.php` | Medium
54 | File | `/forms/doLogin` | High
55 | File | `/formSysLog` | Medium
56 | File | `/forum/away.php` | High
57 | File | `/function/audit/newstatistics/mon_stat_hist_new.php` | High
58 | File | `/general/approve_center/query/list/input_form/delete_data_attach.php` | High
59 | ... | ... | ...

There are 514 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/eset-sednit-part-2.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/eset-sednit-part3.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/sednit-update-analysis-zebrocy_.pdf
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q3
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
