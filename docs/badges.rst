Badges
======

This file is intended to be a master list of badges
for the current iteration of the Fedora Badges project.
Please submit new badge ideas in the form of a pull request
or an email to oddshocks at riseup dot net.

The badges *as they are actually deployed in Fedora Infrastructure* can be
found `here <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/>`_
in our ansible repo.

A note on numbers
-----------------

The values given for certain badges (ex. "close 50 bugs") are tentative
and were picked based on inital brainstorms by various folks. These
numbers will almost certainly change before we get into production
with badges. For many things, I think the following ranking system
will work (numbers should be scaled based on difficulty of
task).

-   Badge level I: 10 or 20 things

-   Badge level II: 20 or 50 things

-   Badge level III: 50 or 150 things

-   Badge level IV: 100 or 300 things

-   Badge level V: 250, 500, or 1000 things

Distro
------

These badges are awarded by the Fedora Project. They should be
automatically awarded by a rules engine that responds to
events on the fedmsg bus.

Involvement
    Create a FAS account,
    `yaml <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/involvement.yml>`_,
    `art`.

First
    Submit 1 package review,
    `yaml`,
    `art`.

Reviewer
    Complete 1 package review submitted by another individual,
    `yaml`,
    `art`.

Is this thing on?
    Push 1 Bodhi update to testing,
    `yaml <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/is-this-thing-on.yml>`_,
    `art`.

Like a rock
    Push 1 Bodhi update to stable,
    `yaml <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/like-a-rock.yml>`_,
    `art`.

If you build it...
    Complete 1 successful Koji build,
    `yaml <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/if-you-build-it.yml>`_,
    `art`.

What goes up...
    Submitted a koji build that failed to build,
    `yaml <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/what-goes-up.yml>`_,
    `art`.

SCM
    Push to the Fedora Package Repository
    `yaml <http://infrastructure.fedoraproject.org/infra/ansible/roles/badges-backend/files/badges/scm.yml>`_,
    `art`.

Proven (Packager I)
    Become a member of the Provenpackager group,
    `yaml`,
    `art`.

Sponsor (Sponsor I)
    Become a member of the Packager sponsor group,
    `yaml`,
    `art`.

Skilled packager (Packager II)
    Approve 20 packages,
    `yaml`,
    `art`.

Skilled reviewer (Reviewer II)
    Complete 20 reviews,
    `yaml`,
    `art`.

Package guru (Packager III)
    Approve 50 packages,
    `yaml`,
    `art`.

Review guru (Reviewer III)
    Complete 50 reviews,
    `yaml`,
    `art`.

Secretary General
    Be noted as an IRC meeting chair by zodbot,
    `yaml`,
    `art`.

Generalissimo
    Become a member of the Fedora Board, FPC, or FESCo,
    `yaml`,
    `art`.

Commander in Chief
    Become the Fedora Project Leader,
    `yaml`,
    `art`.

Bug tracker
    Participate in 20 bugs that have been closed RAWHIDE, CURRENTRELEASE,
    or NEXTRELEASE,
    `yaml`,
    `art`.

Alpha tester
    Report 5 bugs against an alpha release,
    `yaml`,
    `art`.

Beta tester
    Report 5 bugs against a beta release,
    `yaml`,
    `art`.

Living on the edge
    Report 1 bug against a Rawhide critpath package,
    `yaml`,
    `art`.

Communicator
    Submit 1 translation to a Fedora package,
    `yaml`,
    `art`.

Polyglot
    Submit code in 2 or more languages to a single Fedora package,
    `yaml`,
    `art`.

SuperGuru
    Answer 20 questions on Ask Fedora that have been confirmed,
    `yaml`,
    `art`.

First Steps
    Complete an easyfix task,
    `yaml`,
    `art`.

Free Photographer
    Submit a supplemental wallaper to Fedora,
    `yaml`,
    `art`.

Bot Talk
    Talk to a Fedora bot,
    `yaml`,
    `art`.

Fedora Host
    Used a Fedora hostmask for the first time,
    `yaml`,
    `art`.

Social Butterfly
    Joined more than 10 #fedora-* IRC meetings,
    `yaml`,
    `art`.

In Demand
    Be pinged at least 20 times in #fedora-* meetings,
    `yaml`,
    `art`.

Role Player
    Used /me in #fedora-* meetings at least 20 times,
    `yaml`,
    `art`.

Nightowl
    Active in IRC past midnight local time at least 10 times,
    `yaml`,
    `art`.

Stylesheet Master
    Checked in at least 50 CSS changes to the fedora-web repo,
    `yaml`,
    `art`.

Junior Editor (Editor I)
    Edited at least 10 wiki pages,
    `yaml`,
    `art`.

Associate Editor (Editor II)
    Edited at least 20 wiki pages,
    `yaml`,
    `art`.

Senior Editor (Editor III)
    Edited at least 50 wiki pages,
    `yaml`,
    `art`.

Master Editor (Editor IV)
    Edited at least 100 wiki pages,
    `yaml`,
    `art`.

Tester I
    Tested and added karma to 10 updates-testing updates in Bodhi,
    `yaml`,
    `art`.

Tester II
    Tested and added karma to 50 updates-testing updates in Bodhi,
    `yaml`,
    `art`.

Tester III
    Tested and added karma to 150 updates-testing updates in Bodhi,
    `yaml`,
    `art`.

Master Tester (Tester IV)
    Tested and added karma to 300 updates-testing updates in Bodhi,
    `yaml`,
    `art`.

MegaTester (Tester V)
    Tested and added karma to 1000 updates-testing updates in Bodhi,
    `yaml`,
    `art`.

Testing is the Future
    Participated in a test day,
    `yaml`,
    `art`.

Junior Fixer (Fixer I)
    Closed 10 bugs,
    `yaml`,
    `art`.

Fixer (Fixer II)
    Closed 50 bugs,
    `yaml`,
    `art`.

Senior Fixer (Fixer III)
    Closed 150 bugs,
    `yaml`,
    `art`.

Master Fixer (Fixer IV)
    Closed 300 bugs,
    `yaml`,
    `art`.

Junior Comitter (Committer I)
    20 commits to pkgs git repo,
    `yaml`,
    `art`.

Commiter
    50 commits to pkgs git repo,
    `yaml`,
    `art`.

Senior Commiter
    150 commits to pkgs git repo,
    `yaml`,
    `art`.

Master Commiter
    300 commits to pkgs git repo,
    `yaml`,
    `art`.

Junior Updater (Updater I)
    Created 10 package updates in Bodhi,
    `yaml`,
    `art`.

Updater (Updater II)
    Created 50 package updates in Bodhi,
    `yaml`,
    `art`.

Senior Updater (Updater III)
    Created 150 package updates in Bodhir,
    `yaml`,
    `art`.

Master Updater (Updater IV)
    Created 300 package updates in Bodhi,
    `yaml`,
    `art`.

Questionable
************

Some badges ideas have been suggested that may require additional thought.

Bottom-poster
    Don't top-post in a mailing list response [will require some parsing
    of the mailing list thread]

Not a jerk
    Handle a situation well, as decided by steering committee

Community
---------

These badges are manually awarded by individuals.

Met $USER
    Users can award this badge to people who have met them

$USER's thanks
    Users can award this badge to people who have improved their day

Signed $USER's GPG key
    Users can award this badge to people who have signed their GPG key

Créme de la FEM
    Awarded by the Fedora Engineering Manager

The FPL's Blessing
    Awarded by the Feodra Project Leader

$EVENT $DATE
    Awarded by event organizers to attendees

Fedora <3 Python $YEAR
    Awarded by people running the Fedora booth at PyCon $YEAR
