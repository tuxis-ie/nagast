nagast
======

A lot of people use SMS (text-messages to cellphones) to be notified about
issues that Nagios notices. These are usually mission-critical services, at
least for someone on the planet.

Text-messages do not have any kind of mechanism to check if the message
actually arrived, and if the person receiving it had read it. That's where
phonecalls come in.

Nagast is a SSL-secured, IPv6-enabled layer between Nagios and Asterisk and
will place calls in the queue if nagios finds an issue. It will ask for
confimation before playing the message, and will ask for confirmation to know
that you actually heard the message.

license
=======

This software is distributed under the GNU General Public License v2. See COPYING for details.

Some code is taken from Lefteris Zafiris <zaf.000@gmail.com>
"asterisk-googletts"-project at http://zaf.github.com/asterisk-googletts/. This
code produces the soundsamples with Google TTS.
