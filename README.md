SVN_Additions
=============

Addional utils for SVN 1.7


<b>post-commit_slack</b>

The snippet enables the post-commit SVN operation and notification through Slack service (https://slack.com). Information of commit is drived by payload JSON and POST operation. Tested on Centos 6.4 with SVN 1.7. Lib perl-JSON is required. File must be copied into /myrepo/hooks directory and named "post-commit".
<br>
<b>post-commit_mail</b>

The snippet enables the post-commit SVN operation and notification through Mail Server. Informations of commit are writed into mail body and sent to address setted. Tested on Centos 6.4 with SVN 1.7. File must be copied into /myrepo/hooks directory and named "post-commit".
