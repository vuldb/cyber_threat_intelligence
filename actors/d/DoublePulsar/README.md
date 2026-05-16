# DoublePulsar - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [DoublePulsar](https://vuldb.com/?actor.doublepulsar). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.doublepulsar](https://vuldb.com/?actor.doublepulsar)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DoublePulsar:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DoublePulsar.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.94.31.178](https://vuldb.com/?ip.45.94.31.178) | NSA.GOV | - | High
2 | [45.154.98.190](https://vuldb.com/?ip.45.154.98.190) | 45.154.98.190.powered.by.rdp.sh | - | High
3 | [66.59.196.107](https://vuldb.com/?ip.66.59.196.107) | - | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _DoublePulsar_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by DoublePulsar. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/aboutedit.php` | High
3 | File | `/admin` | Low
4 | File | `/admin/admin_running.php` | High
5 | File | `/admin/ajax.php?action=delete_window` | High
6 | File | `/admin/api/theme-edit/` | High
7 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
8 | File | `/admin/del_feedback.php` | High
9 | File | `/admin/edit-services.php` | High
10 | File | `/admin/edit_query_account.php` | High
11 | File | `/admin/maintenance/brand.php` | High
12 | File | `/admin/manage_movie.php` | High
13 | File | `/admin/positions_add.php` | High
14 | File | `/admin/sales/manage_sale.php` | High
15 | File | `/admin/user/manage_user.php` | High
16 | File | `/admin/user/user-move-run.php` | High
17 | File | `/admin/view-patient.php` | High
18 | File | `/Administrator/PHP/AdminReply.php` | High
19 | File | `/agc/vicidial.php` | High
20 | File | `/ajax.php?action=save_user` | High
21 | File | `/ajax/myshop` | Medium
22 | File | `/api/admin/user` | High
23 | File | `/api/gen/clients/{language}` | High
24 | File | `/api/v1/admin/restart` | High
25 | File | `/api/v2/maps` | Medium
26 | File | `/app/action/add_staff.php` | High
27 | File | `/application/index/controller/File.php` | High
28 | File | `/apply.cgi` | Medium
29 | File | `/auth/AzureRedirect.php` | High
30 | File | `/auth/userkey/logout.php` | High
31 | File | `/backup.pl` | Medium
32 | File | `/build/reproducible-path/linux-6.17.8/sound/pci/ctxfi/ctamixer.c` | High
33 | File | `/cgAutoListController.do?datagrid` | High
34 | File | `/cgi-bin/cstecgi.cgi` | High
35 | File | `/cgi-bin/nas_sharing.cgi` | High
36 | File | `/cgi-bin/photocenter_mgr.cgi` | High
37 | File | `/cgi-bin/touchlist_sync.cgi` | High
38 | File | `/check_user.php` | High
39 | File | `/contactform/contactform.php` | High
40 | File | `/controllers/updatesettings.php` | High
41 | File | `/data/src/benchmarks/unqlite/unqlite.c` | High
42 | File | `/deleteTicket.php` | High
43 | File | `/dev/mem` | Medium
44 | File | `/dodelete.php` | High
45 | File | `/ecrire/exec/puce_statut.php` | High
46 | File | `/employeeview.php` | High
47 | File | `/etc/config/product.ini` | High
48 | File | `/etc/crash` | Medium
49 | File | `/etc/passwd` | Medium
50 | File | `/forum/away.php` | High
51 | File | `/goform/aspForm` | High
52 | File | `/goform/DDNS` | Medium
53 | File | `/goform/formEasySetupWWConfig` | High
54 | File | `/goform/goform_get_cmd_process` | High
55 | ... | ... | ...

There are 476 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.threat.rip/file/1d9e48cb4318fd11574963c3235f75419b08678f5cb02d05ca945409f4f8e7a2/config
* https://www.threat.rip/file/90d5dca5a7c377d98eb2e739ec1309304432827633ca25b2fa8e031c2f271429/config
* https://www.threat.rip/file/1451d0b716ad3398b469c0208660d73a51a7d575dc5746876c1404fffd8e230d/config
* https://www.threat.rip/file/2369befdd2e05f4f5b79e3f2370fa18463e2dcdba5bd86da83092edad923434f/config
* https://www.threat.rip/file/da7d4b3c8f7e0faad821dced83ec1d12dca704e28d6fce6d7c26bcfdc4914e62/config
* https://www.threat.rip/file/f835e92eb109331beb56cd269bd2f6cc7998cee93511c3fe2976fe29005dc2c2/config

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
