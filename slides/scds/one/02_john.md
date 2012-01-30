!SLIDE
# John Fink #
# Digital Scholarship Librarian #

.notes Relax and breathe.

!SLIDE bullets incremental
# Computing Infrastructure #
* Heavy reliance on VMs
* Keep administration agile

.notes Could not do this with standard admin. Note that some work scenarios
demand that outside parties have access (even root!) with inside machines:
using VM insures that we can provide that if needed. Also, ~10-15 minutes to
spin up a completely new machine ready to go, can't beat that.

!SLIDE bullets incremental
# Right now this means #
* KVM for VMs
* .deb based Linux distributions
* sysadmin through cherry-pick or clusterssh

.notes KVM is a particular kind of Linux virtualization technology that requireshypervisor support in hardware. .deb is because I am a Debian fascist. Explain clusterssh.

!SLIDE bullets incremental
# This is not terribly scalable #
* Puppet/Chef for VM admin
* Maybe other OSs

.notes I am one guy and am not undergoing cellular mitosis. So at this point we are sort of OK, but scaling beyond is going to get hard. What's stopping me? laziness. Puppet/Chef are new. Laziness will always be a driver, so at the point where it's more lazy to use Puppet or Chef than do things clusterssh, I will switch.

!SLIDE bullets incremental
# grad and faculty relationship #
* (initially) Concentrate on underserved populations
* At Mac this means humanities grad students, humanities in general

.notes At McMaster sadly enough historically most of the attention has been on STEM. However this is also AWESOME really because underserver population = a market that will think you are wonderful for helping them out. Grad students especially.

!SLIDE bullets incremental
# sla writing #
* Necessary for a framework

!SLIDE bullets incremental
# services #
* Physical services
* Virtual services

!SLIDE
# where do we stop or start with a project? #

!SLIDE bullets incremental
# Theory Vs. Practice #
* aka hack v. yak

!SLIDE bullets incremental
# github #
* Already a site for a lot of DH development
* Scholarslab, CHNM
* Visibility!

!SLIDE
# version control evangelism #

!SLIDE
# project management and culture #

