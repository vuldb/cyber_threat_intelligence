# Zeus - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Zeus](https://vuldb.com/?actor.zeus). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.zeus](https://vuldb.com/?actor.zeus)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zeus:

* US
* CN
* GB
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Zeus.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 31.7.63.146 | game.bignamegamereviewz.com | High
2 | 31.28.27.17 | - | High
3 | 31.220.15.147 | offsite.swanseahost.co.uk | High
4 | 31.220.43.72 | - | High
5 | 37.123.99.188 | sv1.jojobulten.com | High
6 | 37.143.11.189 | hosted-by.ihc.ru | High
7 | 45.34.161.13 | zambusing.com | High
8 | 46.4.150.111 | static.111.150.4.46.clients.your-server.de | High
9 | 46.151.52.48 | - | High
10 | 46.151.52.61 | - | High
11 | 46.151.52.191 | - | High
12 | 46.151.54.46 | - | High
13 | 46.166.131.154 | svr508.redium.net | High
14 | 46.166.145.113 | . | High
15 | 46.183.221.240 | ip-221-240.dataclub.info | High
16 | 58.195.1.4 | - | High
17 | 59.157.4.2 | v-59-157-4-2.ub-freebit.net | High
18 | 60.13.186.5 | - | High
19 | 60.241.184.209 | 60-241-184-209.static.tpgi.com.au | High
20 | 62.14.215.109 | 109.215.14.62.static.jazztel.es | High
21 | 63.249.131.74 | - | High
22 | 63.249.133.74 | - | High
23 | 63.249.138.74 | - | High
24 | 63.249.141.74 | - | High
25 | 63.249.142.74 | - | High
26 | 63.249.143.70 | - | High
27 | 63.249.143.74 | - | High
28 | 63.249.146.74 | - | High
29 | 63.249.147.74 | - | High
30 | 63.249.148.74 | - | High
31 | 64.70.19.202 | mailrelay.202.website.ws | High
32 | 64.74.223.48 | - | High
33 | 64.85.233.8 | astound-64-85-233-8.ca.astound.net | High
34 | 64.90.187.131 | 64.90.187.131.static.nyinternet.net | High
35 | 64.127.71.73 | vcg2-4.slc1.tnltd.net | High
36 | 64.182.0.64 | - | High
37 | 64.182.1.64 | - | High
38 | 64.182.6.64 | - | High
39 | 64.182.10.64 | - | High
40 | 64.182.12.64 | hobart2.dal01.corespace.com | High
41 | 64.182.13.64 | - | High
42 | 64.182.16.64 | - | High
43 | ... | ... | ...

There are 167 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Zeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1110.001 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/admin/powerline` | High
3 | File | `/admin/syslog` | High
4 | File | `/api/upload` | Medium
5 | File | `/cgi-bin` | Medium
6 | File | `/cgi-bin/kerbynet` | High
7 | File | `/context/%2e/WEB-INF/web.xml` | High
8 | File | `/dcim/sites/add/` | High
9 | File | `/EXCU_SHELL` | Medium
10 | File | `/forum/away.php` | High
11 | File | `/fudforum/adm/hlplist.php` | High
12 | File | `/login` | Low
13 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
14 | File | `/monitoring` | Medium
15 | File | `/new` | Low
16 | File | `/proc/<pid>/status` | High
17 | File | `/public/plugins/` | High
18 | File | `/rom` | Low
19 | File | `/scripts/killpvhost` | High
20 | File | `/secure/QueryComponent!Default.jspa` | High
21 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
22 | File | `/tmp` | Low
23 | File | `/tmp/redis.ds` | High
24 | File | `/uncpath/` | Medium
25 | File | `/ViewUserHover.jspa` | High
26 | File | `/wp-admin` | Medium
27 | File | `/wp-json/wc/v3/webhooks` | High
28 | File | `actions/CompanyDetailsSave.php` | High
29 | File | `ActiveServices.java` | High
30 | File | `addlink.php` | Medium
31 | File | `addtocart.asp` | High
32 | File | `admin.php` | Medium
33 | File | `admin/?n=user&c=admin_user&a=doGetUserInfo` | High
34 | File | `admin/add-glossary.php` | High
35 | File | `admin/conf_users_edit.php` | High
36 | ... | ... | ...

There are 306 more IOA items available. Please use our online service to access the data.

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/iblocklist_abuse_zeus.netset

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
