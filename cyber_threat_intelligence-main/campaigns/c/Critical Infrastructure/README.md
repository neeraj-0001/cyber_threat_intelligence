# Critical Infrastructure - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Critical Infrastructure_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Critical Infrastructure:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Critical Infrastructure or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [GRU](https://vuldb.com/?actor.gru) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Critical Infrastructure.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [179.43.175.38](https://vuldb.com/?ip.179.43.175.38) | hostedby.privatelayer.com | [GRU](https://vuldb.com/?actor.gru) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Critical Infrastructure. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Critical Infrastructure. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin.php/Admin/adminadd.html` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/doAdminAction.php?act=addCate` | High
7 | File | `/admin/edit-post.php` | High
8 | File | `/admin/index2.html` | High
9 | File | `/admin/settings/save.php` | High
10 | File | `/admin/userprofile.php` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/app/index/controller/Common.php` | High
13 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
14 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
15 | File | `/applications/nexus/modules/front/store/store.php` | High
16 | File | `/apply.cgi` | Medium
17 | File | `/bitrix/admin/ldap_server_edit.php` | High
18 | File | `/cgi-bin/apkg_mgr.cgi` | High
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/nas_sharing.cgi` | High
21 | File | `/cgi-bin/photocenter_mgr.cgi` | High
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/classes/Master.php` | High
24 | File | `/classes/Master.php?f=delete_record` | High
25 | File | `/classes/Master.php?f=save_category` | High
26 | File | `/classes/SystemSettings.php?f=update_settings` | High
27 | File | `/classes/Users.php?f=save` | High
28 | File | `/College/admin/teacher.php` | High
29 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
30 | File | `/dcim/rack-roles/` | High
31 | File | `/detailed.php` | High
32 | File | `/dtale/chart-data/1` | High
33 | File | `/etc/shadow.sample` | High
34 | File | `/fftools/ffmpeg_enc.c` | High
35 | File | `/filter.php` | Medium
36 | File | `/forms/doLogin` | High
37 | File | `/formSysLog` | Medium
38 | File | `/forum/away.php` | High
39 | File | `/goform/addUserName` | High
40 | File | `/goform/aspForm` | High
41 | File | `/goform/delAd` | High
42 | File | `/goform/SetOnlineDevName` | High
43 | File | `/goform/wifiSSIDset` | High
44 | File | `/gpac/src/bifs/unquantize.c` | High
45 | File | `/h.php/page?ref=addtabs` | High
46 | File | `/image.php` | Medium
47 | File | `/inc/topBarNav.php` | High
48 | ... | ... | ...

There are 421 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.picussecurity.com/resource/blog/cisa-alert-aa24-249a-russian-military-cyber-actors-target-us-and-global-critical-infrastructure

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!