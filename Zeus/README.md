# Zeus - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Zeus](https://vuldb.com/?actor.zeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.zeus](https://vuldb.com/?actor.zeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zeus:

* US
* CN
* GB
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zeus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 31.7.63.146 | game.bignamegamereviewz.com | - | High
2 | 31.28.27.17 | - | - | High
3 | 31.220.15.147 | offsite.swanseahost.co.uk | - | High
4 | 31.220.43.72 | - | - | High
5 | 37.123.99.188 | sv1.jojobulten.com | - | High
6 | 37.143.11.189 | hosted-by.ihc.ru | - | High
7 | 45.34.161.13 | zambusing.com | - | High
8 | 46.4.150.111 | static.111.150.4.46.clients.your-server.de | - | High
9 | 46.151.52.48 | - | - | High
10 | 46.151.52.61 | - | - | High
11 | 46.151.52.191 | - | - | High
12 | 46.151.54.46 | - | - | High
13 | 46.166.131.154 | svr508.redium.net | - | High
14 | 46.166.145.113 | . | - | High
15 | 46.183.221.240 | ip-221-240.dataclub.info | - | High
16 | 58.195.1.4 | - | - | High
17 | 59.157.4.2 | v-59-157-4-2.ub-freebit.net | - | High
18 | 60.13.186.5 | - | - | High
19 | 60.241.184.209 | 60-241-184-209.static.tpgi.com.au | - | High
20 | 62.14.215.109 | 109.215.14.62.static.jazztel.es | - | High
21 | 63.249.131.74 | - | - | High
22 | 63.249.133.74 | - | - | High
23 | 63.249.138.74 | - | - | High
24 | 63.249.141.74 | - | - | High
25 | 63.249.142.74 | - | - | High
26 | 63.249.143.70 | - | - | High
27 | 63.249.143.74 | - | - | High
28 | 63.249.146.74 | - | - | High
29 | 63.249.147.74 | - | - | High
30 | 63.249.148.74 | - | - | High
31 | 64.70.19.202 | mailrelay.202.website.ws | - | High
32 | 64.74.223.48 | - | - | High
33 | 64.85.233.8 | astound-64-85-233-8.ca.astound.net | - | High
34 | 64.90.187.131 | 64.90.187.131.static.nyinternet.net | - | High
35 | 64.127.71.73 | vcg2-4.slc1.tnltd.net | - | High
36 | 64.182.0.64 | - | - | High
37 | 64.182.1.64 | - | - | High
38 | 64.182.6.64 | - | - | High
39 | 64.182.10.64 | - | - | High
40 | 64.182.12.64 | hobart2.dal01.corespace.com | - | High
41 | 64.182.13.64 | - | - | High
42 | 64.182.16.64 | - | - | High
43 | ... | ... | ... | ...

There are 167 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Zeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zeus. This data is unique as it uses our predictive model for actor profiling.

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
16 | File | `/objects/getImageMP4.php` | High
17 | File | `/proc/<pid>/status` | High
18 | File | `/public/plugins/` | High
19 | File | `/rom` | Low
20 | File | `/scripts/killpvhost` | High
21 | File | `/secure/QueryComponent!Default.jspa` | High
22 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
23 | File | `/tmp` | Low
24 | File | `/tmp/redis.ds` | High
25 | File | `/uncpath/` | Medium
26 | File | `/ViewUserHover.jspa` | High
27 | File | `/wp-admin` | Medium
28 | File | `/wp-json/wc/v3/webhooks` | High
29 | File | `AccountManagerService.java` | High
30 | File | `actions/CompanyDetailsSave.php` | High
31 | File | `ActiveServices.java` | High
32 | File | `addlink.php` | Medium
33 | File | `addtocart.asp` | High
34 | File | `admin.php` | Medium
35 | File | `admin/?n=user&c=admin_user&a=doGetUserInfo` | High
36 | ... | ... | ...

There are 313 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/iblocklist_abuse_zeus.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
