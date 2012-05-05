---
layout: default
title: Autotest 0.14.0 released!
description: See what's on the newest autotest stable release
categories: news
---

<p>
We are proud to announce a new release of autotest, 0.14.0. It is a new release,
that tracks the latest development efforts on the code base, and brings a number
of changes, the most visible ones are API changes and some entry point names
updated. Breaking this down a little further:
</p>

<ul>
 <li> Autotest underwent several changes that make it installable on a system
 wide location, allowing for autotest packages in major linux distributions,
 first being Fedora 18. </li>
 <li> Overhauled test API: We've got rid of names ending in _lib on our API, and
 now things are much easier to navigate and figure out where they came from.</li>
 <li> The old perl based boottool was replaced by a python implementation that
 uses a mature C program, called grubby, to handle boot entries. This was a
 major effort, considering the large amount of scenarios handled by this tool.</li>
 <li> The git repo history was rewritten to properly follow git authorship
 conventions. This effort reveals over 200 unique authors that did contribute
 to autotest during the last 6 years. May we have many years more with an active
 and healthy development community!</li>
</ul>

A more complete comparison can be seen on a compare view between the 0.13.1 tag
and 0.14.0:

<ul>
<li><a href="https://github.com/autotest/autotest/compare/0.13.1...0.14.0-rc1">https://github.com/autotest/autotest/compare/0.13.1...0.14.0-rc1</a></li>
</ul>

Please download, use and give your feedback!

<h1>What is autotest?</h1>

<p>
Autotest is a framework for fully automated testing. It is designed
primarily to test the Linux kernel, though it is useful for many other
purposes such as qualifying new hardware, virtualization testing and
general user space program testing under linux platforms. It's an
open-source project under the GPL and is used and developed by a number
of organizations, including Google, IBM, Red Hat, and many others.
</p>

Release repository:

<ul>
<li><a href="https://github.com/autotest/autotest/downloads">https://github.com/autotest/autotest/downloads</a></li>
</ul>
