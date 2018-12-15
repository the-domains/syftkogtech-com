---
inFeed: true
description: |-

  Would
  SeLinux have stopped Equifax Breach ?
dateModified: '2018-12-15T03:39:57.500Z'
datePublished: '2018-12-15T03:40:00.995Z'
title: |-
  News in brief: Linux advice for Equifax; fired
  over phish; Security.txt standard proposed 
author:
  - name: The Naked Security
publisher: {}
via: {}
sourcePath: _posts/2017-09-23-news-in-brief-linux-advice-for-equifax-fired-over-phish-s.md
hasPage: true
starred: false
datePublishedOriginal: '2017-09-23T03:06:37.837Z'
url: news-in-brief-linux-advice-for-equifax-fired-over-phish-s/index.html
_type: Article

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/c2583c74-97a8-4483-93d1-39e9dc32878e.png)

# News in brief: Linux advice for Equifax; fired
over phish; Security.txt standard proposed 

Would
SeLinux have stopped Equifax Breach ?

Writing
on the Double Pulsar site, infosec practitioner Kevin Beaumont
suggests Security
Enhanced Linux (SELinux) would have saved Equifax from
the disastrous
breach it
disclosed earlier this month.

If you're going to have Apache Struts facing the internet, SELinux is
the way to go, he wrote, referring to the Apache
Struts vulnerability the thieves exploited:

" _This is the \#1 thing almost every organisation seems to miss. Security
Enhanced Linux is__very
simple to deploy --- usually just one command --- and it
beefs up security on processes. Correctly deployed, it stops Tomcat
accessing the system --- so stops unknown exploits."_

_~_by__Bill Brenner

The
article goes on to describe how the absence of SELinux makes things
easy for the bad guys, and how IT/infosec practitioners can get the
best bang from it.

## BBC: Finance director phished, then fired

The BBC has a cautionary tale for pretty much everyone who uses
email. It's the story of a finance director who was sacked after
falling for a phishing scam disguised as a message from the boss. The
name of the company and the players are anonymous in the story, but
the BBC describes the sequence of events this way:

The email from
the boss looked kosher. He said a new supplier needed paying urgently
-- £50,000 to secure an important contract. He wanted it done as
soon as possible because he was on holiday and didn't want to worry
anymore about work. This rang true to the finance director because
his boss had already posted a photo of his Greek island getaway on
Instagram. His email address looked genuine too. But, of course, it
wasn't the boss.

It was a fraudster who'd done his research and was
skilled at psychological manipulation. The small manufacturing firm --
that wishes to remain anonymous -- ended up losing £150,000 to the
fraudster in the mistaken belief that he was a legitimate supplier.
When the boss found out the bad news, he fired the finance director.

The article says to beware of three words in any email subject
field: "urgent", "payment" and "request".

## Proposed
Security.txt standard resembles Robots.txt

Security researcher and web developer Ed Foudil has an idea he
hopes the Internet Engineering Task Force (IETF) will go for:
[turning security.txt
into a standard][0]. security.txt is a file webmasters can
host on their domain root and use to describe the site's security
policies. It's a lot like robots.txt, a standard websites use
to communicate and define policies for web and search engine
crawlers.

The difference is that security.txt would be specific to security
policies.

In his paper, Foudil says the following:

When security risks in web services are discovered by
independent security researchers who understand the severity of the
risk, they often lack the channels to properly disclose them. As a
result, security issues may be left unreported. Security.txt defines
a standard to help organizations define the process for security
researchers to securely disclose security vulnerabilities.

According to Bleepingcomputer, it would [work
this way][1]:

* A security researcher finds a
security vulnerability on a website 
* He/she accesses the site's security.txt file for
information on how to contact the company and securely report the
issue. 

Security.txt is currently labelled as an "Internet Draft", the
first IETF regulatory step in a three-stage process that also
includes [RFC
(Request For Comment)][2] and official [Internet
Standards][3].

_[Catch
up with all of today's stories on Naked Security][4]_

[0]: https://www.ietf.org/id/draft-foudil-securitytxt-00.txt
[1]: https://www.bleepingcomputer.com/news/security/security-txt-standard-proposed-similar-to-robots-txt/
[2]: https://en.wikipedia.org/wiki/Request_for_Comments
[3]: https://en.wikipedia.org/wiki/Internet_Standard
[4]: https://nakedsecurity.sophos.com/2017/09/19/