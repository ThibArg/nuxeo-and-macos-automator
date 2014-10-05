nuxeo-and-macos-automator
=========================

### What's in this Repository

It's **_amazing_** what you can do with **_Automator_** on Mac OS.

For example, say you have [Nuxeo Drive](http://doc.nuxeo.com/x/04HQ) installed and want to send files/folders to Nuxeo _via_ Nuxeo Drive, without navigating to the Nuxeo Drive folder: Just copy the two Automator workflows, `Nuxeo Drive/ Move to the "Nuxeo Drive" folder.workflow` and `Nuxeo Drive/ Copy to the "Nuxeo Drive" folder.workflow` (which are in the `Services` folder of this repository) to your Library/Services folder<sup>(1)</sup>. They are immediately available when you right-click on items, file(s)/folder(s), in the Finder.


Also, please have a look at their content with Automator (just open them with Automator) to see how easy it is to create a Service with Automator. You will see that 80% of the script is about checking all is good (we do have a `Nuxeo Drive` folder, the destination is in this folder, etc.)

(1) To open this `Services` folder: In the Finder select the "Go" menu, "Go to Folder..." item (or hit the command-shift-G keyboard shortcut) and enter the following address: `/Users/here-your-username/Library/Services`, or just `~/Library/Services`

### License
(C) Copyright 2014 Nuxeo SA (http://nuxeo.com/) and others.
 
All rights reserved. This program and the accompanying materials
are made available under the terms of the GNU Lesser General Public License
(LGPL) version 2.1 which accompanies this distribution, and is available at
http://www.gnu.org/licenses/lgpl-2.1.html

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
Lesser General Public License for more details.

Contributors:
    Thibaud Arguillere (https://github.com/ThibArg)

### About Nuxeo

Nuxeo provides a modular, extensible Java-based open source software platform for enterprise content management and packaged applications for Document Management, Digital Asset Management and Case Management. Designed by developers for developers, the Nuxeo platform offers a modern architecture, a powerful plug-in model and extensive packaging capabilities for building content applications.

More information on: <http://www.nuxeo.com/>