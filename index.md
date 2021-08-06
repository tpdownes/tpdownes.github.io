# About Me

I'm a high performance computing consultant for [Univa][univa] based in Chicago.
I lead our Professional Services team where we help customers in wide-ranging
domains (life sciences, oil/gas, EDA) adopt [Navops Launch][launch]. Launch
automates the scaling and tagging of Univa Grid Engine and Slurm clusters in the
cloud (dedicated and hybrid!) to minimize and track cloud spend. I have led
engagements with major life sciences customers to help them migrate many
production clusters in the cloud to Launch.

I work with the sales team closely to understand use cases, develop statements
of work and to translate customer requirements to the engineering team when the
product doesn't quite fit but could be made to. I've experienced the
difficulties of making HPC work at extreme scales within a corporate IT
environment more attuned to other priorities. Along the way, I've picked up
Terraform, Chef, and a taste for solving problems in varying environments.

[univa]: https://www.univa.com/
[launch]: https://www.univa.com/products/navops.php

In a former life, I managed a team of DevOps engineers at the [Center for
Gravitation, Cosmology, and Astrophysics](https://cgca.uwm.edu) supporting the
[LIGO experiment](https://www.ligo.org). LIGO observes objects like black holes
and neutron stars through their impact on gravity rather than by light. We were
responsible for delivering computing services critical to the collaboration's
scientific objectives. Examples include:

* 6000 core computing cluster running [HTCondor][htcondor]
* [LIGO GitLab](https://git.ligo.org): managing our analysis libraries through
  proper continuous integration techniques. Over 1000 users migrated to this
  service, replacing a long list of duplicative (and older) services such as
  CVS, SVN, Jenkins.
* [GraceDB](https://gracedb.ligo.org). GraceDB is a web portal (on AWS) that
  coordinates near-real-time observations by partner observatories when the
  LIGO/Virgo network detects a gravitational wave event. In 2017, the LIGO/Virgo
  detection of a binary neutron star meger -- and follow-up by 50 observatories!
  -- was [Science Magazine's Breakthrough of the Year][sciencemag].

[htcondor]: https://research.cs.wisc.edu/htcondor/
[sciencemag]: https://vis.sciencemag.org/breakthrough2017/

## Professional Information

* [Resume](resume.pdf)
* [Academic CV](cv.pdf)

## Talks

* [Open Mic Night at Milwaukee Big Data Meetup](open-mic-night.pptx)
* [LIGO Containers in diverse computing environments](https://agenda.hep.wisc.edu/event/1201/session/13/contribution/34/material/slides/1.pdf)
* [Effective use of cgroups in HTCondor](https://research.cs.wisc.edu/htcondor/HTCondorWeek2017/presentations/WedDownes_cgroups.pdf)

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-169259371-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-169259371-1');
</script>
