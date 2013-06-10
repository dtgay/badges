A Guide to the FEDerated BADGES Stack
#####################################

The purpose of this guide is to provide a clear understanding of the Fedbadges
stack's operation and goals to anyone -- not just developers. This guide will
help you understand the project, and install the software, if you so choose. It
will also explain why the Fedora Project is interested, and what they hope to
do with this awesome new technology.

What are Federated Badges?
==========================

In recent times, the Mozilla group -- the same folks responsible for the
Firefox web browser -- defined some basic guidelines for creating what they
call "Open Badges". Their goal was to create a broad specification for groups
and individuals to award folks virtual badges for participating in their
project, whatever it may be.  They purposely made the specification open --
anyone can define their own Open Badges and award them to whomever they please.
Much like other awards in life, the value stems from the issuer. Mozilla hopes
that websites everywhere will begin to create badges to award to their users.

A badge is simple -- just a few lines of data: the issuer of the badge, a badge
name, a badge description, an image of the badge, and the email address of the
recipient. Users who are awarded a badge can choose to accept or decline it. If
they accept, it is added to their virtual "backpack", from where they can
display, export, and import their badges from all over the Internet.

The Fedbadges stack is all of the Fedora software built around the Open Badges
specification. Our goal at Fedora is to start awarding badges to Fedora Project
contributors, and eventually to regular users, as well. Imagine being able to
display your Bug Masher badge for crushing 50 Fedora bugs. But this isn't just
for coders.  Badges will be available for all walks of freedom, including
designers, artists, community members, writers, event attendees, package
reviewers, and systems administrators. Maybe you will be the first to earn the
Picky Browser badge, for installing an alternative to Firefox, Fedora's default
web browser.

Get on the Bus: Endless data delivered to you by Fedmsg
=======================================================

As the saying goes, you're either on the bus, or you're off the bus. Well,
with the FEDora MeSsaGing infrastructure, *everything* is on the bus. Thanks
to the efforts of RJ Bean and other Fedora hackers, (almost) everything
that happens in Fedora land emits a message to a public logging system.
That means new code, wiki edits, team meetings, announcements, blog posts,
package updates, system logs, Ask Fedora questions and answers, package
builds, and so much more. This "Fedmsg" system is a central piece
of how Fedora plans to leverage Open Badges, because badges can be
awarded based on the events that Fedmsg captures.

Om Nom Nom: Consuming Fedmsg data with Datanommer
=================================================


