# Baldr - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Baldr](https://vuldb.com/?actor.baldr). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.baldr](https://vuldb.com/?actor.baldr)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Baldr:

* NL

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Baldr.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 5.8.88.198 | - | High
2 | 5.45.73.87 | - | High
3 | 5.188.60.7 | - | High
4 | 5.188.60.18 | - | High
5 | 5.188.60.24 | - | High
6 | 5.188.60.30 | - | High
7 | 5.188.60.54 | - | High
8 | 5.188.60.68 | - | High
9 | 5.188.60.74 | - | High
10 | 5.188.60.101 | - | High
11 | 5.188.60.115 | - | High
12 | 5.188.60.206 | - | High
13 | 5.188.231.96 | - | High
14 | 5.188.231.210 | - | High
15 | 18.207.217.146 | ec2-18-207-217-146.compute-1.amazonaws.com | Medium
16 | 18.221.49.166 | ec2-18-221-49-166.us-east-2.compute.amazonaws.com | Medium
17 | 23.19.58.101 | - | High
18 | 23.95.95.61 | 23-95-95-61-host.colocrossing.com | High
19 | 23.254.217.112 | hwsrv-930282.hostwindsdns.com | High
20 | 23.254.225.240 | sha29.phpautomailer.com | High
21 | 45.64.186.10 | 45-64-186-10.static.bangmod-idc.com | High
22 | 45.77.252.143 | 45.77.252.143.vultr.com | Medium
23 | 46.30.42.130 | assetshub.com | High
24 | 46.249.62.196 | - | High
25 | ... | ... | ...

There are 97 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Baldr. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1110.001 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Baldr. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/config.php?display=disa&view=form` | High
5 | File | `/BRS_netgear_success.html` | High
6 | File | `/category_view.php` | High
7 | File | `/dev/kmem` | Medium
8 | File | `/dev/shm` | Medium
9 | File | `/medical/inventories.php` | High
10 | File | `/monitoring` | Medium
11 | File | `/NAGErrors` | Medium
12 | File | `/plugins/servlet/audit/resource` | High
13 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
14 | File | `/proc/ioports` | High
15 | File | `/replication` | Medium
16 | File | `/rest/api/2/user/picker` | High
17 | File | `/RestAPI` | Medium
18 | File | `/rom-0` | Low
19 | File | `/tmp` | Low
20 | File | `/tmp/speedtest_urls.xml` | High
21 | File | `/uncpath/` | Medium
22 | File | `/var/log/nginx` | High
23 | File | `/wp-admin/admin.php` | High
24 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
25 | File | `abook_database.php` | High
26 | File | `account.asp` | Medium
27 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
28 | File | `admin/index.php` | High
29 | File | `admin/login.php` | High
30 | File | `admincp.php` | Medium
31 | File | `admincp.php?app=apps&do=save` | High
32 | File | `admincp.php?app=files` | High
33 | File | `admin\model\catalog\download.php` | High
34 | File | `ajax/render/widget_php` | High
35 | File | `apcupsd.pid` | Medium
36 | File | `api/sms/send-sms` | High
37 | File | `api/v1/alarms` | High
38 | ... | ... | ...

There are 323 more IOA items available. Please use our online service to access the data.

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Stealer-Baldr

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
