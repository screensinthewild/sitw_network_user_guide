v3\_after\_Lei\_additions\_March2014 – ANONYMISED BY STEVE 2016

Authors:

Holger Schnädelbach

Holger.Schnadelbach@nottingham.ac.uk

Lei Ye

L.Ye@nottingham.ac.uk

Steve North

Steve.North@nottingham.ac.uk

Mixed Reality Laboratory (MRL), Department of Computer Science,
University of Nottingham

> [*Basic System Description (natural language and*
> *diagram)*](#basic-system-description-natural-language-and-diagram)
>
> [*Day-to-day operation of the screens
> network*](#day-to-day-operation-of-the-screens-network)
>
> [*How do I schedule web-based content to run on the screens
> network?*](#how-do-i-schedule-web-based-content-to-run-on-the-screens-network)
>
> [*Schedule file location*](#schedule-file-location)
>
> [*Backing up and editing the schedule
> file*](#backing-up-and-editing-the-schedule-file)
>
> [*Schedule file syntax guide*](#schedule-file-syntax-guide)
>
> [*How do I host web-based content to run on the screens
> network?*](#how-do-i-host-web-based-content-to-run-on-the-screens-network)
>
> [*How can I override the schedule file and manually control
> content?*](#how-can-i-override-the-schedule-file-and-manually-control-content)
>
> [*Manual Content Selection with the SitW Client Scheduler Remote
> Control web
> app.*](#manual-content-selection-with-the-sitw-client-scheduler-remote-control-web-app.)
>
> [*Keyboard switching to a local copy of the schedule
> file*](#keyboard-switching-to-a-local-copy-of-the-schedule-file)
>
> [*How do I remotely monitor/administer the screens
> network?*](#how-do-i-remotely-monitoradminister-the-screens-network)
>
> [*Maintenance via TeamViewer*](#maintenance-via-teamviewer)
>
> [*How to enable remote keyboard
> shortcuts*](#how-to-enable-remote-keyboard-shortcuts)
>
> [*How to transfer files to a node
> PC*](#how-to-transfer-files-to-a-node-pc)
>
> [*How to use text chat with a colleague
> on-site*](#how-to-use-text-chat-with-a-colleague-on-site)
>
> [*Screen Remote Control via NEC PC Control Utility PD1
> tool*](#screen-remote-control-via-nec-pc-control-utility-pd1-tool)
>
> [*UNION Server remote administration via the
> Web*](#union-server-remote-administration-via-the-web)
>
> [*UNION Server - the ‘interaction
> server’*](#union-server---the-interaction-server)
>
> [*How to quickly check if our UNION Server is running, without
> credentials*](#how-to-quickly-check-if-our-union-server-is-running-without-credentials)
>
> [*How to remotely administer UNION
> server*](#how-to-remotely-administer-union-server)
>
> [*Stopping and restarting UNION Server when installed as a Windows
> Service using Remote
> Desktop*](#stopping-and-restarting-union-server-when-installed-as-a-windows-service-using-remote-desktop)
>
> [*Regular maintenance tasks*](#regular-maintenance-tasks)
>
> [*Regular screens check via Team
> Viewer*](#regular-screens-check-via-team-viewer)
>
> [*Reviewing user added content for suitability (Moment Machine
> etc)*](#reviewing-user-added-content-for-suitability-moment-machine-etc)
>
> [*On-site screen checks*](#on-site-screen-checks)
>
> [*Video Server maintenance*](#video-server-maintenance)
>
> [*A suggested timetable for
> checks*](#a-suggested-timetable-for-checks)
>
> [*Troubleshooting and problem
> solving*](#troubleshooting-and-problem-solving)
>
> [*How do I disable security features to fault find on a node
> PC?*](#how-do-i-disable-security-features-to-fault-find-on-a-node-pc)
>
> [*Secure Lockdown*](#secure-lockdown)
>
> [*Firefox Kiosk Mode plugin*](#firefox-kiosk-mode-plugin)
>
> [*Where do I find the log files?*](#where-do-i-find-the-log-files)
>
> [*UNION Server logging*](#union-server-logging)
>
> [*SitW Client logging*](#sitw-client-logging)
>
> [*Known issues and solutions*](#known-issues-and-solutions)
>
> [*Windows User account corruption at The Mill and how to
> recover*](#windows-user-account-corruption-at-the-mill-and-how-to-recover)
>
> [*How to manually close the iSpy video panel (grey
> frame)*](#how-to-manually-close-the-ispy-video-panel-grey-frame)
>
> [*How fix iSpy when the stream from the local USB camera (via YawCam)
> has
> frozen*](#how-fix-ispy-when-the-stream-from-the-local-usb-camera-via-yawcam-has-frozen)
>
> [*Keyboard shortcuts for closing crashed Firefox kiosk mode browser
> windows.*](#keyboard-shortcuts-for-closing-crashed-firefox-kiosk-mode-browser-windows.)
>
> [*What can I do if a screen node is unreachable via
> TeamViewer?*](#what-can-i-do-if-a-screen-node-is-unreachable-via-teamviewer)
>
> [*Node PC recovery via Windows Remote
> Desktop*](#node-pc-recovery-via-windows-remote-desktop)
>
> [*Contacting a venue to request manual reboot of a node
> PC*](#contacting-a-venue-to-request-manual-reboot-of-a-node-pc)
>
> [*Where do I find important configuration
> settings?*](#where-do-i-find-important-configuration-settings)
>
> [*SitW Client*](#sitw-client)
>
> [*SitwScheduler.ini*](#sitwscheduler.ini)
>
> [*iSpy video panel*](#ispy-video-panel)
>
> [*iSpy video stream configuration*](#ispy-video-stream-configuration)
>
> [*UNION Server*](#union-server)
>
> [*Touch Foil configuration and
> calibration*](#touch-foil-configuration-and-calibration)
>
> [*Phidgets Interface configuration and
> calibration*](#phidgets-interface-configuration-and-calibration)
>
> [*LAN and WAN configuration for nodes (router, IP addresses, port
> forwarding)*](#lan-and-wan-configuration-for-nodes-router-ip-addresses-port-forwarding)
>
> [*Port Forwarding summary for a
> node*](#port-forwarding-summary-for-a-node)
>
> [*Testing Correct Port Forwarding with the NetCat
> tool*](#testing-correct-port-forwarding-with-the-netcat-tool)
>
> [*Node PC configuration*](#node-pc-configuration)
>
> [*List of software to install on a new node
> PC*](#list-of-software-to-install-on-a-new-node-pc)
>
> [*Firefox configuration (plugin updates disabled
> etc)*](#firefox-configuration-plugin-updates-disabled-etc)
>
> [*Windows configuration (resolution, update disabled, pop-ups
> etc)*](#windows-configuration-resolution-update-disabled-pop-ups-etc)
>
> [*Yawcam configuration*](#yawcam-configuration)
>
> [*Node hardware configuration*](#node-hardware-configuration)
>
> [*Enable/disable audio system*](#enabledisable-audio-system)
>
> [*Schedule audio mute and unmute in Windows
> 7*](#schedule-audio-mute-and-unmute-in-windows-7)
>
> [*Maintenance of Foscam IP
> cameras*](#maintenance-of-foscam-ip-cameras)
>
> [*UNION Server configuration*](#union-server-configuration)
>
> [*How to setup UNION Server as a Windows Service - will run without a
> user logged
> in*](#how-to-setup-union-server-as-a-windows-service---will-run-without-a-user-logged-in)
>
> [*Important Configuration Summary (IP addresses, video stream URLs,
> Windows accounts, port forwarding etc) - NO
> PASSWORDS*](#important-configuration-summary-ip-addresses-video-stream-urls-windows-accounts-port-forwarding-etc)

Basic System Description (natural language and diagram)
-------------------------------------------------------

The SitW Network was implemented as a deliverable from the research
project, ‘Exploring the potential of networked urban screens for
communities and culture’ (EPSRC Reference:EP/I031839/1).

The SitW Network consists of a network of urban screen nodes (currently
there are four), based in two UK cities. The screens are publicly
facing, located inside partner venues.

![](media/image1.jpeg){width="5.3257622484689415in"
height="3.595744750656168in"}

Each node consists of:

-   A networked Windows PC (running Windows 7 Professional), which is
    remotely administered.

-   A 46” screen (mounted vertically in portrait mode) inside a partner
    venue, i.e. behind a glass window.

-   A mechanism to enable interaction with the screen, through the glass
    window (varies from node-to-node, according to the
    glass specification).

-   A camera and speaker (both available 'off-the-shelf') operate
    through the glass, making the installation interactive.

-   A secondary camera, recording interactions 24/7 to protect the
    system and to ensure ethical research principles.

-   An optional multi-way video link between the screens via a
    customised version of an Open Source product.

-   Custom client software written to enable communication with a
    web-based schedule file, switching a program of applications, as
    required for one or more screens. This application also communicates
    with a server to share ‘interaction events’ between the screens in
    the network. Note: real-time manual override of the schedule is also
    possible (for demos, testing etc), via a custom web interface.

-   Software tools for securing the scheduled content from
    user-tampering and retaining browser ‘kiosk-mode’.

-   A physical case to contain/protect the hardware elements.

-   Decals and visual branding around the screen - design varies
    between nodes.

![](media/image2.jpeg){width="5.650060148731408in"
height="4.042553587051619in"}

The software system uses an off-the-shelf client/server infrastructure
to provide real-time multi-user functionality for applications across
the screen network (the ‘interaction server’).

To date, most of the applications implemented have been written in
HTML5/Javascript, running in the Firefox browser (full-screen mode) and
hosted on a web server. However, content need not follow this model. For
example, it might be a stand-alone client application running on each
node and (if required) making use of the interaction server.

1.  Day-to-day operation of the screens network
    -------------------------------------------

    a.  ### How do I schedule web-based content to run on the screens network?

        i.  #### Schedule file location

-   The schedule is controlled by a plain text file, currently located
    (and web visible) at:

> [*http://www.cs.nott.ac.uk/sitw/autoschedule/schedule.txt*](http://www.cs.nott.ac.uk/sitw/autoschedule/schedule.txt)

-   Remote access and relevant web server permissions will be required
    to update this file, via an SFTP tool (such as SSH).

-   This file is manually created, using the correct syntax, unless
    automatically generated by the SitW Client Scheduler Remote Control
    web app.

-   In order to relocate this file, configuration changes would be
    required to SitW Server (TO DO: Lei, is this currently possible?).

-   For the SitW Client Scheduler Remote Control web app to work,
    schedule.txt must have Permission Mode 777. If you are replacing the
    existing schedule.txt, it will inherit mode 777. If you
    delete/rename the original and upload a new schedule.txt, it is
    necessary to set the permissions back to 777.

    i.  #### Backing up and editing the schedule file

schedule.txt may be edited in any plain text editor (Windows Notepad
etc) and then overwritten via an SFTP tool.

#### Schedule file syntax guide

Refer to
[*http://www.cs.nott.ac.uk/sitw/autoschedule/schedule.txt*](http://www.cs.nott.ac.uk/sitw/autoschedule/schedule.txt)
for an example.

Summary of format:

&lt;TIME:TTTT&gt;|&lt;APP NAME&gt;|&lt;URL&gt;|&lt;VIDEO SHARE
MODE&gt;|&lt;VIDEO LAYOUT MODE&gt;|&lt;ATTRACTOR MODE&gt;

Example:

1600|App\_Firefox|http://www.cs.nott.ac.uk/sitw/experiences/soundshape/stable/notouch/|videoOn|2|AttractorOff

-   TIME: 24-hour clock in the format: TTTT.

-   APP NAME options:

> **App\_Firefox**
>
> **App\_Chrome**
>
> Hard-coded apps (without specified URL):
>
> Photo Booth experience: **App\_MM**
>
> No VIDEO SHARE MODE or VIDEO LAYOUT MODE options required.
>
> Example: 1100|App\_MM||||
>
> iSpy video only experience: **App\_iSpy**
>
> No VIDEO SHARE MODE (defaults to option 1 - Full screen (2x2 grid
> layout)) or VIDEO LAYOUT MODE options required (defaults to videoOn).
>
> Example: 1800|App\_iSpy||||

-   URL - as you might expect! Currently, works with App\_Firefox
    and App\_Chrome.

-   VIDEO SHARE MODE options:

> YawCam only no iSpy video panel: **Yawcam** (which is case
> insensitive)
>
> iSpy only no Yawcam: **iSpy** (which is case insensitive)
>
> Both YawCam and iSpy: **videoOn** or **iSpy+Yawcam**
>
> Note: VIDEO SHARE MODE is NOT required for App\_MM and App\_iSpy (see
> above).

-   VIDEO LAYOUT MODE options:

> **0** - Hide video panel
>
> **1** - Full screen (2x2 grid layout)
>
> **2** - At the bottom (4 pane/stream standard layout)
>
> **3** - Full screen (1 large local video image + 3 small remote video
> images at bottom)
>
> Note: VIDEO LAYOUT MODE is NOT required for App\_MM and App\_iSpy (see
> above).

-   ATTRACTOR MODE options are: **AttractorOff** or **AttractorOn**.

> When Attractor Mode on is set, inactivity (60 seconds) at a screen
> will cause SiTW Client to trigger Attractor Mode. This is currently
> fullscreen, mirrored video provided by iSpy. Local or remote screen
> interaction will disable Attractor Mode and the scheduled experience
> will run.

### How do I host web-based content to run on the screens network?

> Content can be hosted on any web server.
>
> Currently, the project content is hosted here:
>
> [*http://cs.nott.ac.uk/sitw/experiences/*](http://cs.nott.ac.uk/sitw/experiences/)

a.  ### How can I override the schedule file and manually control content?

    i.  #### Manual Content Selection with the SitW Client Scheduler Remote Control web app. 

To use the SitW Client Scheduler Remote Control web app, go to:

[*http://www.cs.nott.ac.uk/sitw/controller/stable/*](http://www.cs.nott.ac.uk/sitw/controller/stable/)

Password: &lt;removed for security&gt;

-   From the drop-down menu below, select either an experience (or \*\*
    AUTOSCHEDULE \*\* to go back to the automatic schedule).

-   There is no SUBMIT button, the request will be sent as soon as you
    select from the drop-down menu. Note: you won't get any visual
    feedback on the webpage that a change has been made.

-   There may be a delay or up to a minute before the screen network
    responds (as determined by the check interval for SitW Client).
    Also, the 4 screens are not time synced. So, the changeover may be a
    bit staggered.

-   Your selection will run on all screens in the SitW Network, it is
    not currently possible to select the schedule for
    individual screens.

-   If it is an experience that requires different settings (or location
    specific URLs), the code will do all of this automatically. Then all
    of the SitW clients will pick up the change within approximately
    60 seconds. Please note: there are no "file locks" currently. So, if
    several people all use the app at once, or if you keep changing
    experience rapidly, the results might be unpredictable!

-   On the drop-down menu, \*\*AUTOSCHEDULE\*\* buts it back
    on schedule.

-   The section at the bottom of the page is for more
    advanced (development) work It allows you to test new experiences on
    the network, without needing to understand the schedule file syntax.
    For example, replace
    [*http://www.cs.nott.ac.uk/sitw/experiences/soundshape/stable/*](http://www.cs.nott.ac.uk/sitw/experiences/soundshape/stable/)

> with [*http://news.bbc.co.uk*](http://news.bbc.co.uk) to run this page
> on the screens network.

Note: one limitation here is that you can only run web content on
Firefox. We don't have an option to run with Chrome.

-   You don't need to add any of the schedule file syntax to control
    iSpy and YawCam.

> The radio buttons allow you to select whether iSpy is running or not.
>
> 2-way video = standard 4 video feeds along the bottom.
>
> Transmit video only = run YawCam and stream, but don't display video.
>
> No Video is obvious!

-   If you tick "Location aware", the app will add the appropriate
    arguments to the end of the URL (for exampe: ?loc=BW), putting it in
    the correct section of schedule.txt.

-   Clicking the "Run" button will change all 4 screens, as with the
    dropdown menu.

-   To change back to schedule, use \*\*AUTOSCHEDULE\*\* from the
    dropdown menu.

How it works:

The server-side code for the app is written in PHP and it's all in the
"controller/stable" directory, with the HTML.

What's happening? - if you select an experience by name, on the web
server schedule.txt is backed up as schedule.bak.txt in the directory
"doNotDeleteForManualMode". Then the PHP code writes a new schedule.txt
file, with the selected experience running 24/7.

-   If you go to the "autoschedule" directory, containing our
    schedule.txt, you will see a sub-directory
    called "doNotDeleteForManualMode". Inside this are two files:

    -   manualMode.txt - this is just used by the SitW Client Scheduler
        Remote Control web app to retain state. It will contain "true"
        if the app has manually selected an experience. This file should
        not require any manual intervention.

    -   schedule.bak.txt - when the app engages manual mode, this will
        be a backup of the current auto schedule. It will be used to
        automatically restore back to schedule, when auto is selected
        from the app. If there is ever a problem with the app, it should
        be possible to manually recover the schedule from here.

        i.  #### Keyboard switching to a local copy of the schedule file

For testing purposes, it is possible to run a local copy of schedule.txt
on a node PC, rather than the online schedule. In SitW Client, the
keyboard shortcut for switching between a local and online version of
schedule.txt is \[Ctr\] + \[\_\] (ctrl and underscore keys).

a.  ### How do I remotely monitor/administer the screens network?

    i.  #### Maintenance via TeamViewer

We use TeamViewer Host v7.0.17271.

A licenced copy is recommended, as this prevents pop-up screen messages
appearing on the node screen, after a remote session.

[*http://download.teamviewer.com/download/version\_7x/TeamViewer\_Host\_Setup.exe*](http://download.teamviewer.com/download/version_7x/TeamViewer_Host_Setup.exe)

Note: the Host version is required to prevent visible windows, even in a
licenced copy.

##### How to enable remote keyboard shortcuts

When working remotely in TeamViewer, it is often useful to use keyboard
shortcuts.

For example, \[Windows key\] to get access to the Windows Start menu,

\[Ctrl\] + \[F5\]: refresh browser window

\[Ctrl\] + \[F4\]: kill browser window

To enable this, click Actions menu (top of TeamViewer) &gt; Send key
combinations.

##### How to transfer files to a node PC

In a TeamViewer remote session, click the icon that looks like documents
(top right) and then click File transfer.

##### How to use text chat with a colleague on-site

In a TeamViewer remote session, click Audio/Video &gt; Chat.

This is very useful for remote communication with a team member on site,
at a node.

#### Screen Remote Control via NEC PC Control Utility PD1 tool

The 46’ screen models that we use for the network are:

NEC MultiSync X461HB (HD Ready/720p 1360 x 768)

NEC MultiSync X462HB (Full HD/1080p 1920 x 1080)

Note: all screens are standardised to the resolution portrait 768 x 1360
(9:16). So, the X462HB screens are running at less than their potential
Full HD.

NEC provide a Windows-based remote control application (NEC PC Control
Utility PD1 tool) for these screen models, allowing multiple functions
including: power on/off, channel select, input select etc. This tool is
available free from here:
[*http://www.nec-display.com/dl/en/dp\_soft/pccu\_pd1.html*](http://www.nec-display.com/dl/en/dp_soft/pccu_pd1.html)

At each node, the screen is connected to the network and listens on a
fowarded port for incoming connections from an instance of the NEC PC
Control Utility PD1 tool.

This software provides a method for maintaining the screens, while they
are not public-facing.

To remotely access and control a screen (when first used):

-   Run NEC PC Control Utility PD.

-   Click Tool &gt; Communication Settings &gt; New Setting

-   Enter the public IP address that has been configured at the venue
    with port 7142 forwarded to the screen (see port-forwarding
    information elsewhere in this guide).

-   Click OK.

-   Repeat until each of the screens in the network has been added.

To remotely control a screen (in this example, turn the screen on/off):

-   Note: it can take the NEC PC Control Utility PD1 tool a while to
    refresh and detect the screens after starting. Initially, the screen
    names are grey and no details (name, status, inputs etc) appear in
    the bottom left panel. Once connected, the text is black and
    clicking on a name will display the screen’s details. Right-click on
    the required screen and then click Control &gt; Power &gt; Power On
    (or Power Off, as appropriate).

    i.  #### UNION Server remote administration via the Web

        1.  ##### UNION Server - the ‘interaction server’ 

Interaction between screen applications is provided by the free version
of UNION Server:
[*http://www.unionplatform.com/*](http://www.unionplatform.com/) This is
hosted on our own Windows XP Virtual Machine at: &lt;removed for
security&gt;. We use UNION Server v1.x series and the client code in our
applications may not be compatible with later/current releases of UNION.

##### How to quickly check if our UNION Server is running, without credentials

Go to -
[*http://www.unionplatform.com/check/index-1.x.html*](http://www.unionplatform.com/check/index-1.x.html).

Enter the server details as:

Host: &lt;removed for security&gt;

Port: 8080

Click Go.

If all is well, you should get back: Connected to \[&lt;removed for
security&gt;\] on port \[8080\]. Connection type: WEBSOCKET. Ping:
\[Loading\].

If you need to stop, start, debug, check who's using the server, then
read on...

##### How to remotely administer UNION server

It can be accessed in two ways: 1. On a web page that I've set up 2. By
running a local Shockwave movie/Windows .exe.

\# Web access (the easiest way):

Go to:

[*http://www.cs.nott.ac.uk/sitw/servers/union/admin/*](http://www.cs.nott.ac.uk/sitw/servers/union/admin/)

Login details below.

\# Local client method-

Go here to download one of the admin clients:

[*http://www.cs.nott.ac.uk/sitw/servers/union/admin/downloads/*](http://www.cs.nott.ac.uk/sitw/servers/union/admin/downloads/)

Either download Windows .exe shockwave projector version and run locally
(Flash security settings might need changing)

or download shockwave file and run locally (Flash security settings
might need changing)

For all methods, use the following details:

Host: \[&lt;removed for security&gt;\]

Port: 9110

Password: &lt;removed for security&gt;

Tick remember password

##### Stopping and restarting UNION Server when installed as a Windows Service using Remote Desktop

Note: UNION Server is configured to run as a Windows Service (see later
section on UNION Server configuration). This means that you can log in
and out using both UoN Computer Science account credentials OR the admin
account for the machine itself. In either case, logging out afterwards
ensures that others can access the server. UNION Server will continue to
run in the background.

Note: UNION Server will also restart with Windows XP. So, following
scheduled patching, the server should recover on its own.

When testing changes to UNION Server’s configuration, you will need to
stop and then restart it. This is achieved using Remote Deskop and the
admin account for the Virtual Machine that hosts UNION Server:
\[&lt;removed for security&gt;\]

-   Remote Desktop into \[&lt;removed for security&gt;\], using the
    Windows admin a/c for this machine:

    -   username: \[&lt;removed for security&gt;\]

    -   pwd: &lt;removed for security&gt;

-   Use the UNION Server stop server batch file to kill UNION Server.

-   Stop the startserver service.

-   Start the startserver service.

-   Log out of snnadmin.

    a.  ### Regular maintenance tasks

        i.  #### Regular screens check via Team Viewer

<!-- -->

-   Using TeamViewer’s Computers & Contacts panel, visually check that
    all screens and SitWVServer are showing as online.

-   Using TeamViewer, connect to each screen in turn and then:

    -   Check if currently scheduled experience is displayed.

    -   In each screen, if iSpy is running for the current experience,
        test that ‘mouse event detector’ for Attractor is working. Click
        somewhere on the browser and check that interaction events are
        detected in iSpy (yellow frame around feed flashes in response
        to click).

    -   Check for pop-ups, update reminders etc.

    -   &lt;Every few checks&gt;Confirm that the TouchFoil driver
        is running.

-   Using TeamViewer, connect to SitWVServer and check that all IP
    cameras are recording.

-   Using NEC PC Control Utility PD1, check that each screen is powered
    'on' (rather than accidentally left in standby, after a
    previous session).

-   Using a browser, check that UNION Server is running:

    -   [\[&lt;removed for security&gt;\]
        */union/admin/*](http://www.cs.nott.ac.uk/sitw/servers/union/admin/)

    -   Instructions elsewhere in this document.

    -   If it connects, it’s working...

        i.  #### Reviewing user added content for suitability (Moment Machine etc)

Unmoderated content will require regular monitoring.

For example, Moment Machine has an admin interface for checking images:

[*http://* \[&lt;removed for
security&gt;\]*:2221/?id=adminPage*](http://pdnet.inf.unisi.ch:2221/?id=adminPage)

#### On-site screen checks

At least once a week a visit to each venue is advised.

#### Video Server maintenance

Video Serve is a desktop PC, which is running in MRL for 7/24.

An un-customized iSpy (v4.5.4.0) is running on this PC to record the
video streams from 4 onsite IP cameras. In iSpy we can monitor 4 video
image windows. Each window connects to an IP camera. By right clicking
on the video window, we can do configuration (e.g. set camera address,
name, time tag, mirror image, etc), and start/stop recording. The 4
video streams are being recorded in E:\\SitwIPCam\_iSpy\\video\\&lt;Node
name&gt;.

Each video file keeps 24-hour period video image. According to
agreement, we only keep 7 days video recording. Therefore we need to do
cleanup in about every 2 weeks time.

Video Server is also used to record the onscreen actions of each node.
All onscreen clicks at each node will be recorded in log files in this
format:

Node Name | Date and Time | running app | coordinates of click

These log files are being stored in
E:\\yl\\SitwUsageLog\\log\\logActions.

Each log file keeps 24-hour period actions.

#### A suggested timetable for checks 

It is suggested that you perform the above listed tasks on a daily
basis.

1.  Troubleshooting and problem solving
    -----------------------------------

    a.  ### How do I disable security features to fault find on a node PC?

        i.  #### Secure Lockdown

When Inteset Secure Lockdown is enabled, you will **NOT** be able to
browse the web or do anything else, without first disabling lockdown.
This requires restarting Windows and will take a few minutes.

As keyboard shortcuts are also disabled, it will not be possible to
quickly reload a failed web page.

Some things are still possible in lockdown mode. For example, iSpy’s
right-click options are still available BUT it is very difficult to
trigger these without a mouse.

What stops users from browsing in Firefox, is the kiosk mode, rather
than Secure Lockdown. If a user can break out of kiosk mode (as seems to
be possible in Google Presentation slideshows), then it is not totally
impossible that they could still browse.

However, even if they manage to close applications down, they can’t
start anything new. They will end up with a black desktop, without
icons, Task Bar, Start Menu etc.

What Secure Lockdown can do:

-   Let only one Master Application start (although this application can
    start other apps)

-   Removes the Windows Taskbar and Start button

-   Removes Desktop right-click menu

-   Removes Task Manager access

-   Removes CTRL-ALT-Delete functions

-   Removes System shutdown or logoff

-   Removes Windows Ease of Access features

-   Removes Windows Help and Support

What Secure Lockdown cannot do:

-   Lockdown the features of any program that is started automatically
    by Windows, or is started by the Master Application that Secure
    Lockdown starts.

-   Prevent the closing of any program, except for the Master
    Application (and I found that even this isn’t always reliable...ask
    me for details).

To disable lockdown mode for maintenance or ‘free browsing’ - either
onsite with a keyboard or remotely via TeamViewer:

-   If you are connecting to a node remotely using TeamViewer, make your
    connection and then click Actions (on the grey TeamViewer toolbar at
    the top of the screen) and then tick ‘Send key combinations’ (you
    will need to do this each time that you connect). You might also
    need to left-click somewhere in the TeamViewer window, to get focus
    for the keyboard.

-   Press \[Alt\] + \[Shift\] + \[s\] Note: I found in TeamViewer that
    only the \[Shift\] key on the right-hand side of the keyboard worked
    for this!

-   In the Secure Lockdown window, enter the password (it should be the
    same as the Windows user account password for the machine that you
    are working on).

-   Click Apply.

-   Untick ‘Disable secure lockdown’.

-   Click Apply.

-   Click Yes to confirm that you want to disable Secure Lockdown.

-   Click OK to restart Windows. You might get an error about closing an
    application, if so just click OK. Windows will restart. This may
    take longer than expected. Via TeamViewer you may have to wait up to
    five minutes before it becomes available to connect again.

-   After Windows restarts with lockdown mode disabled (and TeamViewer
    has reconnected, if you are working remotely), you may see that
    Firefox and iSpy will automatically start. This is because they
    automatically start both in lockdown and non-lockdown modes. If you
    want to make changes, you will need to close this down. As Firefox
    is in Kiosk mode, you will need to press \[F4\] to close Firefox (if
    using TeamViewer, remember to re-enable ‘Send key
    combinations’ first!).

-   Next, close the Scheduler by right-clicking on the Task Bar entry
    (the yellow Python one, not the console entry) and clicking Close.
    iSpy should now also shutdown.

-   Now you can make your changes!

-   If you need to run Firefox not in kiosk mode, hold \[Shift\] and
    click (or double-click depending on the location of the icon) on any
    Firefox icon.

-   You will get a window asking if you want to use Firefox Safe Mode.

-   Use Firefox! Note: when you are finished, you do not need to
    re-enable kiosk mode. Just close Firefox and the next time it starts
    (or is started by the scheduler) it will go back into kiosk mode.

To enable lockdown mode after maintenance or ‘free browsing’ - either
onsite with a keyboard or remotely via TeamViewer:

-   Click Start and then either click Secure Lockdown (if it is visible
    on the Start menu) or type “Secure” and then press \[Enter\] to
    search for Secure Lockdown.

-   You will see a message confirming that Secure Lockdown is running
    and that you need to press \[Alt\] + \[Shift\] + \[s\] to access it.

-   Click OK (?) to dismiss this window.

-   Press \[Alt\] + \[Shift\] + \[s\]

-   In the Secure Lockdown window, enter the password (it should be the
    same as the Windows user account password for the machine that you
    are working on).

-   Click Apply.

-   Tick ‘Enable secure lockdown’.

-   Click Apply.

-   Click Yes to confirm that you want to enable Secure Lockdown.

-   Click OK to restart Windows.

-   Windows will restart. This may take longer than expected. Via
    TeamViewer you may have to wait up to five minutes before it becomes
    available to connect again.

-   When it restarts, the machine should be in lockdown mode and Firefox
    and iSpy should automatically start.

    i.  #### Firefox Kiosk Mode plugin

R-Kiosk is a Firefox plugin that puts the browser in Kiosk-Mode:

[*https://addons.mozilla.org/en-us/firefox/addon/r-kiosk/*](https://addons.mozilla.org/en-us/firefox/addon/r-kiosk/)

Whereas Secure Lockdown limits what a user can do in Windows, R-Kiosk
limits behaviour inside Firefox.

Most keyboard shortcuts are suppressed, but the following will still
work:

-   Reload current page (inc. refresh cache): press \[Ctrl\] + \[F5\]

-   Close Firefox: press \[Alt\] + \[F4\] (or \[Ctrl\] + \[F4\])

If you need manual access to the browser’s address bar and other
functions (either on-site or via TeamViewer), you will need to run
Firefox in Safe Mode:

Press and hold \[Shift\] and then click on any Firefox shortcut.

To completely disable R-Kiosk:

Go into Firefox safe mode and then go to Firefox &gt; Addons &gt;
Extensions.

Disable is available as an option for R-Kiosk.

a.  ### Where do I find the log files?

    i.  #### UNION Server logging

Log into the UNION Server VM in Remote Desktop (Computer Science account
credentials).

Log files may be found in: C:\\union\\Union Server\\

By default, UNION keeps the last five days’ logs.

The can be modified here:

C:\\union\\Union Server\\lib\\log4j.properties

Change this line:

Edit log4j.appender.union.MaxBackupIndex=5

And restart UNION Server.

Reading UNION Server/UPC logs

Identifying individual SiTW nodes in UNION log files:

Broadway: \[&lt;removed for security&gt;\]

NAE: \[&lt;removed for security&gt;\]

The Mill: \[&lt;removed for security&gt;\]

Leytonstone: \[&lt;removed for security&gt;\]

The remote admin console for UNION server: this is likely to be in the
IP range:

\[&lt;removed for security&gt;\] for example: \[&lt;removed for
security&gt;\]. This is treated as a client by the server, but is only
acting as a passive watcher.

Note: Client IDs change on each connection, they do not persist from
session to session. Therefore, they are of limited value beyond the
scope of each evaluation session.

UNION logging formats:

There are two types of log: Log and UPC Messages.

Both contain the same UPC (Union Procedure Call) message format in XML,
but the rest of the formatting differs.

These formats are:

Log format:

&lt;YYYY-MM-DD&gt; &lt;HH:MM:SS&gt;,&lt;ClientID&gt; &lt;LOG LEVEL&gt; -
&lt;DESCRIPTION OF EVENT&gt; \[&lt;UPC MESSAGE IN XML&gt;\]

For example:

2012-10-30 11:31:37,140 DEBUG - Server sending to client \[1003\]
message
\[&lt;U&gt;&lt;M&gt;S2C\_ROOM\_ATTR\_UPDATE(u9)&lt;/M&gt;&lt;L&gt;&lt;A&gt;&lt;!\[CDATA\[sitw.music\_1\]\]
&gt;&lt;/A&gt;&lt;A&gt;1003&lt;/A&gt;&lt;A&gt;&lt;!\[CDATA\[pad\_8\]\]
&gt;&lt;/A&gt;&lt;A&gt;&lt;!\[CDATA\[false\]\]
&gt;&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;\]

UPC Messages format:

Date, Time, Client ID, User ID (only if using user accounts), Address
(this is IP address), Queue Duration (ms), Processing Duration (ms), UPC
(this is the UPC message)

For example:

10/24/12 19:26:52 UTC+1, 703, , \[&lt;removed for security&gt;\], 0, 0,
&lt;U&gt;&lt;M&gt;u5&lt;/M&gt;&lt;L&gt;&lt;A&gt;sitw.music\_1&lt;/A&gt;&lt;A&gt;pad\_13&lt;/A&gt;&lt;A&gt;true&lt;/A&gt;&lt;A&gt;4&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

The Union Procedure Call Protocol Specification:

UPC messages represent different events between the UNION server and its
client.

[*http://unionplatform.com/specs/upc/*](http://unionplatform.com/specs/upc/)

Look at the Native UPC Messages in Tables 1 and 2.

The Internal Message ID column corresponds to the u numbers in the log.

For example, here is a u159 message from the log:

10/24/12 18:30:04 UTC+1, 691, , \[&lt;removed for security&gt;\], 16,
125, &lt;U&gt;&lt;M&gt;u159&lt;/M&gt;&lt;L&gt;&lt;/L&gt;&lt;/U&gt;

In Table 1, you will see that u159 is described as:

WATCH\_FOR\_PROCESSED\_UPCS

"Asks the server to notify the sending client upon processing any UPC
message. The server sends the result of the request via a u160.
Notifications are transmitted via u161. By default, u159 requires
administrator privileges."

The most relevant UPC messages to SiTW experiences (summary):

Summary of relevant UPC message (for current SiTW experiences, such as
SoundShape):

u4 JOIN\_ROOM

u6 JOINED\_ROOM

u54 ROOM\_SNAPSHOT

u37 CLIENT\_REMOVED

u131 ROOM\_OCCUPANTCOUNT\_UPDATE

u5 SET\_ROOM\_ATTR

u9 ROOM\_ATTR\_UPDATE

u74 SET\_ROOM\_ATTR\_RESULT

Not used in SoundShape, but sometimes relevant to SitW experiences:

u3 SET\_CLIENT\_ATTR

u8 CLIENT\_ATTR\_UPDATE

u73 SET\_CLIENT\_ATTR\_RESULT

The most relevant UPC messages to SiTW experiences (detail and
examples):

Client joining the experience

Client to Server (a request): u4 JOIN\_ROOM

Server to Client (a confirmation): u6 JOINED\_ROOM

Server to Client (to enable persistence of state): u54 ROOM\_SNAPSHOT

Server to Clients (updating all Clients that a Client has joined or
left): u131 ROOM\_OCCUPANTCOUNT\_UPDATE

A client requesting to join the experience:

This was Leytonstone contacting the server and requesting to join
SoundShape-

10/24/12 19:14:14 UTC+1, 701, , \[&lt;removed for security&gt;\], 0, 47,
&lt;U&gt;&lt;M&gt;u4&lt;/M&gt;&lt;L&gt;&lt;A&gt;sitw.music\_1&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

It is a u4 message, which means JOIN\_ROOM (a room is an experience, in
sitw terms!).

sitw.music\_1 is SoundShape. Remember that SoundShape reloads every 15
minutes (to prevent network problems from leaving a failed web page on
screen). So, this doesn't mean that Leytonstone wasn't in SoundShape
before 19:14.

Server informing that number of clients in experience has changed:

&lt;U&gt;&lt;M&gt;S2C\_ROOM\_OCCUPANTCOUNT\_UPDATE(u131)&lt;/M&gt;&lt;L&gt;&lt;A&gt;&lt;!\[CDATA\[sitw.music\_1\]\]
&gt;&lt;/A&gt;&lt;A&gt;1&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

Server confirming that a client has joined the experience:

&lt;U&gt;&lt;M&gt;S2C\_JOINED\_ROOM(u6)&lt;/M&gt;&lt;L&gt;&lt;A&gt;&lt;!\[CDATA\[sitw.music\_1\]\]
&gt;&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

A new client getting an update on the status of all SoundShape pads:

&lt;U&gt;&lt;M&gt;S2C\_ROOM\_SNAPSHOT(u54)&lt;/M&gt;&lt;L&gt;&lt;A&gt;&lt;/A&gt;&lt;A&gt;&lt;!\[CDATA\[sitw.music\_1\]\]
&gt;&lt;/A&gt;&lt;A&gt;1&lt;/A&gt;&lt;A&gt;0&lt;/A&gt;&lt;A&gt;pad\_19|false|pad\_18|true|pad\_17|true|pad\_16|false|pad\_15|true|pad\_14|true|pad\_13|true|\_MAX\_CLIENTS|-1|pad\_12|true|pad\_11|true|pad\_10|false|pad\_8|true|pad\_9|false|pad\_23|false|pad\_22|true|pad\_25|false|pad\_24|false|pad\_7|false|pad\_6|false|pad\_21|false|pad\_5|false|pad\_20|true|pad\_4|true|pad\_3|false|pad\_2|false|pad\_1|true&lt;/A&gt;&lt;A&gt;1001&lt;/A&gt;&lt;A&gt;&lt;/A&gt;&lt;A&gt;0&lt;/A&gt;&lt;A&gt;&lt;!\[CDATA\[\_ROLES|0|68|\_CT|1351596319934|36\]\]
&gt;&lt;/A&gt;&lt;A&gt;&lt;!\[CDATA\[\]\]
&gt;&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

Client leaving the experience

Note: Clients don't normally request to leave, they just disappear.

u37 CLIENT\_REMOVED

Updating all Clients that a Client has joined or left:

Server to Clients: u131 ROOM\_OCCUPANTCOUNT\_UPDATE

Example:

2012-10-31 09:14:55,554 DEBUG - Server sending to client \[1071\]
message
\[&lt;U&gt;&lt;M&gt;S2C\_CLIENT\_REMOVED(u37)&lt;/M&gt;&lt;L&gt;&lt;A&gt;&lt;!\[CDATA\[sitw.music\_1\]\]
&gt;&lt;/A&gt;&lt;A&gt;1072&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;\]

One Client changing something in an experience (in the case of
SoundShape, this is pressing pads)

Client to Server (a request): u5 SET\_ROOM\_ATTR

Server to All Clients (a confirmation): u9 ROOM\_ATTR\_UPDATE u9

Server to Originating Client (a confirmation): u74
SET\_ROOM\_ATTR\_RESULT

A music pad is turned on (sounding and flashing):

This uses UPC message u5 - SET\_ROOM\_ATTR - "Asks the server to set a
room attribute for the specified room."

Steve explains: the UNION server retains the state of each music pad,
whether it is true (playing) or false (off). When a new client (screen
node) connects to the UNION server, it can then get an immediate update
on the status of all music pads. Without this, the screen pads could all
be in different states, depending on when the node logged into the
experience.

This is someone at The Mill touching and turning on pad 13 -

10/24/12 19:26:52 UTC+1, 703, , \[&lt;removed for security&gt;\], 0, 0,
&lt;U&gt;&lt;M&gt;u5&lt;/M&gt;&lt;L&gt;&lt;A&gt;sitw.music\_1&lt;/A&gt;&lt;A&gt;pad\_13&lt;/A&gt;&lt;A&gt;true&lt;/A&gt;&lt;A&gt;4&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

There are 25 pads arranged in a 5x5 grid. As pads are numbered from
columns (left to right) and then from rows (top to bottom), pad 13 is
the third pad from the left on the third row down.

A music pad is turned off (not sounding or flashing):

This is someone at The Mill touching and turning off pad 23 -

10/24/12 19:26:40 UTC+1, 703, , \[&lt;removed for security&gt;\], 0, 0,
&lt;U&gt;&lt;M&gt;u5&lt;/M&gt;&lt;L&gt;&lt;A&gt;sitw.music\_1&lt;/A&gt;&lt;A&gt;pad\_23&lt;/A&gt;&lt;A&gt;false&lt;/A&gt;&lt;A&gt;4&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

There are 25 pads arranged in a 5x5 grid. As pads are numbered from
columns (left to right) and then from rows (top to bottom), pad 23 is
the third pad from the bottom right.

The Server checking clients are still connected

Approximately every 5 seconds.

Server to Client (a request - tell me if you're still there!): u3 \_PING

Client to Server (a confirmation - I'm here!): u2 CLIENT\_HEARTBEAT

This is the Server asking Broadway Cinema if it’s still there:

10/24/12 19:26:47 UTC+1, 702, , \[&lt;removed for security&gt;\], 0, 0,
&lt;U&gt;&lt;M&gt;u3&lt;/M&gt;&lt;L&gt;&lt;A&gt;702&lt;/A&gt;&lt;A&gt;&lt;/A&gt;&lt;A&gt;\_PING&lt;/A&gt;&lt;A&gt;14&lt;/A&gt;&lt;A&gt;&lt;/A&gt;&lt;A&gt;0&lt;/A&gt;&lt;A&gt;false&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

This is Broadway Cinema confirming to the Server that it’s still there:

0/24/12 19:26:57 UTC+1, 702, , \[&lt;removed for security&gt;\], 0, 0,
&lt;U&gt;&lt;M&gt;u2&lt;/M&gt;&lt;L&gt;&lt;A&gt;CLIENT\_HEARTBEAT&lt;/A&gt;&lt;A&gt;702&lt;/A&gt;&lt;A&gt;&lt;/A&gt;&lt;A&gt;67&lt;/A&gt;&lt;/L&gt;&lt;/U&gt;

#### SitW Client logging

For monitoring system behavior and for debugging purpose, important
events at each node are being recorded locally into log files. Generally
the log includes information below:

Date and time

System start up / shutdown / restart

System initialization

App start up and parameters

Onscreen mouse action

Enter / Quit attractor mode

Error messages

For example:

*2014-03-15 11:30:39 ------------ SitW Scheduler v9.0 ------------*

*2014-03-15 11:30:39 ////////////////////*

*2014-03-15 11:30:39 \*\*\*\*\*\* NAE(NA) \*\*\*\*\*\**

*2014-03-15 11:30:39 ////////////////////*

*2014-03-15 11:30:39 \*\*\*\*\*\* Web Schedule Mode \*\*\*\*\*\**

*2014-03-15 11:30:39 \*\*\*\*\*\* Day Schedule Changed \*\*\*\*\*\**

*2014-03-15 11:30:40 Run Program 9 - \['1130', 'app\_ispy', '', '', '',
'attractoron', '', '', '', ''\]*

*2014-03-15 11:30:40 (((((( Mouse click @ (20, 20) ))))))*

*2014-03-15 11:30:41 (((((( Mouse click @ (460, 1062) ))))))*

*2014-03-15 11:30:45 (((((( Mouse click @ (451, 1066) ))))))*

*2014-03-15 11:30:46 (((((( Mouse click @ (1113, 494) ))))))*

*2014-03-15 11:31:47 &lt;&lt;&lt; Enter ATTRACTOR Mode &gt;&gt;&gt;*

*2014-03-15 11:31:55 &lt;&lt;&lt; Quit ATTRACTOR Mode &gt;&gt;&gt;*

*2014-03-15 11:32:02 ------------ Quit Scheduler ------------*

Log files are being stored into

NAE and Broadway - D:\\yl\\SitwScheduler\\log\\logEvent

Leytonstone and Mill - C:\\yl\\SitwScheduler\\log\\logEvent

Each log file keeps 24-hour period information.

a.  ### Known issues and solutions

    i.  #### Windows User account corruption at The Mill and how to recover

Symptoms:

-   Unable to reach The Mill in TeamViewer.

-   No IPcam stream from The Mill.

-   When you connect with Remote Desktop, you see a version of the
    Windows user account which appears not to have any of our
    applications (iSpy, YawCam, Firefox, TeamViewer, scheduler:
    all missing). It looks like a brand new user account.

Solution 1: in Remote Desktop, press \[CTRL\]+\[ALT\]+\[END\].

Click LogOff and Remote Desktop shuts down.

Now, try connecting with TeamViewer, you should be back in the correct
version of the user account.

Note: after using Remote Desktop, the iSpy panel is always in the wrong
position. Run the OLD\_isy.exe version in c:\\program files\\ispy\\ispy
to reposition the panel and then close it.

Run the scheduler and ispy should now be in the correct position

Solution 2: use System Restore and restore back to last know good
restore point: this works, but you might lose any changes made since the
last restore point.

#### How to manually close the iSpy video panel (grey frame)

Right-click on the grey strip at the right-hand edge of iSpy and then
click Exit.

#### How fix iSpy when the stream from the local USB camera (via YawCam) has frozen

Is it necessary to disable Inteset Secure Lockdown to do this? NO

Is it necessary to reboot Windows from TeamViewer (with Secure Lockdown
left enabled)? YES

This happens when YawCam continues to stream a single frame, without
updating from the USB camera. It happens occasionally, after the system
has been running for several days.

Using Team Viewer, it can be fixed by rebooting the computer, without
disabling Secure Lockdown. If you are at a node and can’t use
TeamViewer, then you WILL need to disable Secure Lockdown, as reboot is
not possible.

If you are connecting to a node remotely using TeamViewer, make your
connection and then click Actions (on the grey TeamViewer toolbar at the
top of the screen) and then click Remote Reboot &gt; Reboot.

If prompted by TeamViewer if you want to wait for partner to reconnect,
say yes.

When Windows restarts, YawCam should be streaming correctly

#### Keyboard shortcuts for closing crashed Firefox kiosk mode browser windows.

Press \[Alt\] + \[F4\] (or \[Ctrl\] + \[F4\]).

a.  ### What can I do if a screen node is unreachable via TeamViewer?

    i.  #### Node PC recovery via Windows Remote Desktop

Using Windows remote Desktop, connect to the Node PC, using the
appropriate Windows account.

#### Contacting a venue to request manual reboot of a node PC 

> &lt;TO DO: basic training for venue staff?&gt;

a.  #### Where do I find important configuration settings?

    i.  ##### SitW Client

        1.  ###### SitwScheduler.ini

NAE and Broadway - D:\\yl\\SitwScheduler\\cfg\\SitwScheduler.ini

Leytonstone and Mill - C:\\yl\\SitwScheduler\\cfg\\SitwScheduler.ini

i.  ##### iSpy video panel

    1.  ###### iSpy video stream configuration

Stream data can be found here on each node:

C:\\Users\\&lt;user name&gt;\\AppData\\Roaming\\iSpy\\XML\\config.xml

##### UNION Server

Most of the configuration files can be found on \[&lt;removed for
security&gt;\] at: C:\\union\\Union Server\\lib\\

##### Touch Foil configuration and calibration

More information about Touch Foil device driver and user guide can be
downloaded from:

<http://www.visualplanet.biz/support/download.php>

It is using driver MA7 at Broadway and driver MA9 at Leytonstone and the
Mill.

Here we use driver version MA7 as a sample:

-   Starting the Driver Control Program

> To start the driver, double click on the shortcut MA7\_Control on the
> desktop

-   Configuring USB Communications

> Select the Comms tab
>
> Connect to a free USB port
>
> Select USB option in the PORT section
>
> Tick the Open box in the Status section
>
> Make sure the driver box called Present is red indicating that the
> driver has loaded When the driver recognizes the touchfoil, the Open,
> Active and Valid boxes will go red
>
> Sample time adjustment is used to set the touchfoil to work through
> different thickness of material, for example, sample time of 15 is the
> highest thickness setting. The default value of 5 should enable the
> touchfoil to work through glass between 4-12mm thick

![](media/image3.jpeg){width="2.9879483814523184in"
height="2.97297353455818in"}

-   Calibration

> Select the Calib tab
>
> Click with the mouse the Start Calibration box
>
> You will see the following on the screen; three targets will appear in
> turn like the one shown above:
>
> Touch and hold your finger on the centre of each target. Remove your
> finger only when the next target appears
>
> If the touch calibration is not correct after this procedure, please
> run the process again and adjust your finger position on the targets
> to compensate for any misalignment

  ![](media/image4.jpeg){width="2.84830271216098in" height="2.8198195538057744in"}   ![](media/image5.jpeg){width="2.925112642169729in" height="1.8170964566929133in"}
  ---------------------------------------------------------------------------------- -----------------------------------------------------------------------------------

-   Adjusting the Touch Sensitivity Level

> Select the Sense tab:
>
> First set the coarse sensitivity bar to approximately 50% by dragging
> the bar with your mouse
>
> Set the Press Threshold level so the background movement of the Finger
> Pressure moving red bar does not go beyond the press threshold level,
> by dragging the bar with your mouse (it will not move fully to the
> left hand side)
>
> Touch the screen to see if the Finger Pressure red bar goes above the
> Press Threshold level. This action creates a touch
>
> If the Finger Pressure bar does not go above the Press Threshold level
> when you touch the screen then increase coarse sensitivity in small
> increments only until the Finger Pressure red bar goes above the Press
> Threshold level

![](media/image6.jpeg){width="3.0872747156605422in"
height="3.079557086614173in"}

-   Setting the Touch Output to suit the Application Requirements

> Select the output tab
>
> Select the required mouse control for your application - Click on
> Release
>
> To enable the touch function on the screen check the Enable selected
> control box

![](media/image7.jpeg){width="3.007574365704287in" height="3.0in"}

-   Saving the Configuration Settings

> Select File
>
> Click on Save to save the current settings
>
> ![](media/image8.jpeg){width="2.9756944444444446in"
> height="2.9309470691163604in"}

##### Phidgets Interface configuration and calibration

Phidgets Interface is used at NAE, where the Touch Foil does not work.
Phidgets interface is composed by 5 light sensors and a controller
board. It works as a key-pad to control the cursor on the screen.

  ![](media/image9.jpeg){width="3.0871423884514435in" height="2.252252843394576in"}   ![](media/image10.jpeg){width="2.321855861767279in" height="2.585586176727909in"}
  ----------------------------------------------------------------------------------- -----------------------------------------------------------------------------------

Phidgets device driver can be downloaded from:

<http://www.phidgets.com/docs/Operating_System_Support>

-   Attach Phidgets Interface on the shop window beside the screen and
    facing outward

-   Install Phidgets driver on PC

-   Connect USB cable from Phidgets Interface to a free USB port on PC

-   Start Phidgets Interface software at
    D:\\yl\\SitwPhidgetsKey\\run.bat

Phidgets Interface has been well tuned to get best performance. In case
users need to customize its behavior, there is a configuration file
locates at

D:\\yl\\SitwPhidgetsKey\\cfg\\SitwPhidgetsKey.ini

Parameters and current settings:

Sensitivity = 0.70

- Value range from 0 to 1. Higher value gets higher sensitivity

MovingPace = 7

- Cursor moving pace

SampleInterval\_Key = 50

- Sampling interval for checking key press (in milli second)

SampleInterval\_Env = 10000

- Sampling interval for checking environment brightness (in milli
second)

Log\_Action = Yes

- Turn on/off action log

Log\_Brightness = Yes

- Turn on/off brightness sensors reading log

a.  #### LAN and WAN configuration for nodes (router, IP addresses, port forwarding)

    i.  ##### Port Forwarding summary for a node

The port configuration on a node should be similar to this, where
xx.xx.xx.xx is the static public IP address of the router:

-   Port 3389 forwarded to the node PC for Remote Desktop, for
    connection to it at:

    -   xx.xx.xx.xx

-   Port 81 forwarded to the IPcam, so that it can be reached externally
    on:

    -   http://&lt;ipcam user&gt;:&lt;ipcam pass&gt;@xx.xx.xx.xx
        :81/videostream.cgi

-   Port 82 forwarded to the Yawcam application on our PC so that it can
    be reached externally on:

    -   http://xx.xx.xx.xx :82/video.mjpg?q=30&fps=33&id=0.5

-   Note: The Mill is configured to port 83, as 82 seemed to be reserved
    for something else.

-   Port 7142 forwarded to the screen's local IP address (should be on
    it’s default 192.168.0.10). So that the screen can be reached using
    the PC Control Utility PD1.

Note:

If you are accessing the screens network (for video recording, screen
remote control, RDP administration etc) from behind a firewall, you may
also have to open the following ports on any machines being used:

IP Camera Access (81), YawCam video stream (82,83), Remote Desktop
Protocol (3389) and NEC PC Control Utility PD1 (7142)

##### Testing Correct Port Forwarding with the NetCat tool

You can test a node to check the required ports are open.

NetCat is a great tool for this.

Search for the Windows version (nc111nt.zip) or try:

[*https://yesanshare.googlecode.com/files/nc111nt.zip*](https://yesanshare.googlecode.com/files/nc111nt.zip)

Best instructions:

[*http://www.catonmat.net/blog/unix-utilities-netcat/*](http://www.catonmat.net/blog/unix-utilities-netcat/)

Using Command Prompt (from the same directory as NetCat):

Node static public IPs:

Broadway: \[&lt;removed for security&gt;\]

NAE: \[&lt;removed for security&gt;\]

The Mill \[&lt;removed for security&gt;\]

Leytonstone: \[&lt;removed for security&gt;\]

Testing for NEC Utility port:

nc -v -n -z -w 1 &lt;node static public IP&gt; 7142

Pass:

(UNKNOWN) \[&lt;node static public IP&gt;\] 7142 (?) open

Fail:

(UNKNOWN) \[&lt;node static public IP&gt;\] 7142 (?): TIMEDOUT

Testing for IPcam port:

nc -v -n -z -w 1 &lt;node static public IP&gt; 81

Pass:

(UNKNOWN) \[&lt;node static public IP&gt;\] 81 (?) open

Fail:

(UNKNOWN) \[&lt;node static public IP&gt;\] 81 (?): TIMEDOUT

Testing for Remote Desktop port:

nc -v -n -z -w 1 &lt;node static public IP&gt; 3389

Pass:

(UNKNOWN) \[&lt;node static public IP&gt;\] 3389 (?) open

Fail:

(UNKNOWN) \[&lt;node static public IP&gt;\] 3389 (?): TIMEDOUT

And ports 82 and 83 for YawCam video streams.

a.  #### Node PC configuration

    i.  ##### List of software to install on a new node PC

-   Firefox

-   Chrome

-   Java 7

-   Adobe Flash Player

-   Adobe Shockwave Player

-   Python & Tools

Python: python-2.7.3.msi

> wxPython: wxPython2.9-win32-2.9.4.0-py27.exe
>
> NumPy: numpy-1.6.1-win32-superpack-python2.7.exe
>
> SciPy: scipy-0.9.0-win32-superpack-python2.7.exe
>
> Win32API: pywin32-217.win32-py2.7.exe

-   TeamViewer Host v7.0.57223 (doesn’t need licence for host, only
    connecting client) - NOTE: versions of host above v7 (v8+) may not
    work with our licence clients! Get it here:
    [*http://www.cs.nott.ac.uk/sitw/software/TeamViewer\_Host\_7\_0\_57223\_THIS\_IS\_THE\_ONE\_FOR\_OUR\_LICENCES.exe*](http://www.cs.nott.ac.uk/sitw/software/TeamViewer_Host_7_0_57223_THIS_IS_THE_ONE_FOR_OUR_LICENCES.exe)

-   TouchFoil driver (if using TouchFoil) – MA7 / MA9

-   NEC PC Control Utility PD 1 (if using NEC screen)

-   SiTW Client

-   Phidgets mouse driver thingy (if required for non-touch
    foil location)

-   iSpy (SiTW custom build)

-   Inteset Secure Lockdown v2 - product key: \[&lt;removed for
    security&gt;\]

-   R-Kiosk (Firefox addon):
    [*https://addons.mozilla.org/en-us/firefox/addon/r-kiosk/*](https://addons.mozilla.org/en-us/firefox/addon/r-kiosk/)

-   YawCam

-   Winrar

    i.  ##### Firefox configuration (plugin updates disabled etc)

Disable Firefox plugin update reminder:

At the Firefox address line, type: about:config and press \[Enter\].

Search for: plugins.update

set: plugins.update.notifyUser = false

Disable Firefox plugin deactivated warning:

Seems to prevent this:

"Some plugins have been deactivated for your safety"

At the Firefox address line, type: about:config and press \[Enter\].

Search for: extensions.blocklist.enabled

set: extensions.blocklist.enabled = false

Disable auto update in FireFox:

Click Tools &gt; Options &gt; Advanced &gt; Update tab

Click "Never check for updates"

Untick: "Use a background service to install updates"

Hide the FireFox plugins infobar (warning about plugins being out of
date):

Type - "about:config" into the address bar of the browser, confirm the
info dialog, then search for the preference named
"plugins.hide\_infobar\_for\_outdated\_plugin" & double-click it in
order to toggle it to "true".

##### Windows configuration (resolution, update disabled, pop-ups etc)

Windows resolution:

Set to: 1360 x 768

Flash Player:

Go to Start &gt; Control Panel.

Disable Flash Player automatic updates

Java:

Go to Start &gt; Control Panel.

Disable Java automatic updates

QuickTime:

Go to Start &gt; Control Panel.

Disable Quicktime automatic updates (if it’s installed)

Windows update:

Go to Start and search for Windows Update.

Disable Windows Update’s automatic update features.

Instructions for installing SSL certificate in Chrome to allow camera
access:

Certificate is here zipped: \[&lt;removed for security&gt;\]

1\) Copy the unzipped certificate (pdnet.inf.unisi.ch.cer) somewhere on
the machine (e.g., desktop).

2\) Open Chrome and go to the Settings panel.

3\) In the Settings panel click on "Show advanced settings" and scroll to
the "HTTPS/SSL Manage certificates". Click and open the "Manage
certificates" option.

4\) This will open the "Certificates" window. In this window go to the
"Trusted Root Certification Authorities" tab and click on the "Import"
Button.

Password is the same as the username, i.e.,

password: screensinthewild

Set home pages for Firefox and Chrome.

TeamViewer &gt; options:

Security &gt;

Random password (for spontaneous access) - Disabled (no random password)

Advanced &gt; Advanced settings for connections to this computer

Tick: Automatically minimise local TeamViewer Panel

Note: this is not actually set at Broadway...so maybe not necessary?

Windows power options

Turn the display off: Never

Put the computer to sleep: Never

##### Yawcam configuration

Tested with version 0.3.8 not latest version...

Settings &gt; Output &gt; Stream

Port: 82

Stream type: MJPEG

Scale to: 320 x 240

Image quality: 30%

Additional settings

Maximum connections: 10

ImageProducer rate: 10fps

Settings &gt; Startup

Tick Start Stream ouput

Tick Hide to traybar at start

Untick Check for new versions

Untick Show preview

Untick all others

  ![](media/image11.jpeg){width="3.0460126859142607in" height="2.2792793088363954in"}   ![](media/image12.jpeg){width="3.0577854330708663in" height="2.2792793088363954in"}
  ------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------

a.  #### Node hardware configuration

    i.  ##### Enable/disable audio system

        1.  ###### Schedule audio mute and unmute in Windows 7

How to automatically mute/unmute Windows 7 audio at scheduled times:

-   Download nircmd from:
    [*http://www.nirsoft.net/utils/nircmd.html*](http://www.nirsoft.net/utils/nircmd.html)

-   Unzip and run (as admin): nircmd.exe

-   Confirm copy into Windows dir.

-   Test that Windows 7 can mute and unmute, from Command Line:

    -   Mute:

    -   nircmd.exe mutesysvolume 1

    -   Unmute:

    -   nircmd.exe mutesysvolume 0

    -   First...to schedule Mute in (WIndows) Task Scheduler:

-   Start Task Scheduler by clicking Start and then typing
    “Task Scheduler”.

-   Click Action &gt; Create Task. Note: NOT basic task.

-   Under General Tab, add name...”Mute Audio”

-   Under Triggers Tab, click New.

-   Set the drop down menu Begin the Task to “On a schedule”.

-   Set to Weekly and tick: Monday, Tuesday, Wednesday, Thursday, Friday
    (for weekdays only)

-   Click OK.

-   Under Actions Tab, click New.

-   Set to Start a Program.

-   Under Program/Script enter: nircmd.exe

-   Under Add arguments (optional) enter: mutesysvolume 1

-   Click OK &gt; OK

-   Now...to schedule Unmute in (WIndows) Task Scheduler:

-   Click Action &gt; Create Task.

-   Repeat above...using mutesysvolume 0 for the program argument

    i.  ##### Maintenance of Foscam IP cameras

A Foscam IP camera is installed at each node. It can be accessed
remotely by a web browser.

NAE: http:// \[&lt;removed for security&gt;\]:81

Name: \[&lt;removed for security&gt;\]

Password: &lt;REMOVED FOR SECURITY&gt;

Name: \[&lt;removed for security&gt;\]

Password: \[&lt;removed for security&gt;\]

Broadway: http:// \[&lt;removed for security&gt;\]:81

Name: \[&lt;removed for security&gt;\]

Password: &lt;REMOVED FOR SECURITY&gt;

Name: \[&lt;removed for security&gt;\]

Password: \[&lt;removed for security&gt;\]

Leytonstone: http://81.149.250.182:81

Name: \[&lt;removed for security&gt;\]

Password: &lt;REMOVED FOR SECURITY&gt;

Name: \[&lt;removed for security&gt;\]

Password: \[&lt;removed for security&gt;\]

Mill: http:// \[&lt;removed for security&gt;\]:81

Name: \[&lt;removed for security&gt;\]

Password: &lt;REMOVED FOR SECURITY&gt;

Name: \[&lt;removed for security&gt;\]

Password: \[&lt;removed for security&gt;\]

Please note port number 81 must be forwarded to IP camera at each local
network system. This can be done by configuring the port forwarding
settings in local network router.

After you log into the IP camera control panel successfully, you may
control the viewing angle, resolution, brightness and many other
options. More details can be found from <http://foscam.co.uk/>. IP
Camera model is Foscam FI8918W Wireless.

> ![](media/image13.jpeg){width="4.01849956255468in"
> height="2.6574814085739282in"}

a.  #### UNION Server configuration

    i.  ##### How to setup UNION Server as a Windows Service - will run without a user logged in

Download Windows Server 2003 Resource Kit Tools from here:

[*http://www.microsoft.com/en-us/download/details.aspx?id=17657*](http://www.microsoft.com/en-us/download/details.aspx?id=17657)

The only components required from this are the tools for creating a
Windows service:

srvany.exe

instsrv.exe

These can also be found here for future use:

[*https://www.dropbox.com/sh/223ejh5ule4xiyh/2\_5SSOq2cZ*](https://www.dropbox.com/sh/223ejh5ule4xiyh/2_5SSOq2cZ)

-   On the VM, put srvany.exe and instsrv.exe into a new folder:
    c:\\rktools\\

-   Open Command Prompt in C:\\union\\Union Server\\

-   In Command Prompt, run: c:\\rktools\\instsrv "startserver"
    "c:\\rktools\\srvany.exe"

-   Open the Windows Services Management Console: Start &gt; Control
    Panel &gt; Administrative Tools &gt; Services.

-   Find the new service "startserver".

-   Right-click on startserver and then click Properties.

-   On the General tab, set "Startup type" = Automatic (Set to "Manual"
    for manual startup)

-   On the Log On tab: select the "Local System account" radio button.
    Also tick the "Allow Service to Interact with the desktop" tick box.

-   Leave the Windows Services Management Console open.

-   Go to the Registry Editor: Start &gt; Run &gt; type: regedit and
    press \[Enter\].

-   Add a new registry key:

    -   HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\startserver

-   Add another new key inside the previous, so that you have:

    -   HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\startserver\\Parameters

-   Inside
    HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\startserver\\Parameters,
    create two new string values:

    -   Name: AppDirectory Type: REG\_SZ Value: C:\\union\\Union
        Server\\

    -   Name: Application Type: REG\_SZ Value: C:\\union\\Union
        Server\\startserver.bat

-   Back in the Windows Services Management Console, right-click on
    startserver in the services list and then click Start.

This should have now worked with a standard .exe, but there is a further
problem with a Java application, such as UNION Server.

By default, Java apps stop working when a user logs out.

See:

[*http://superuser.com/questions/374147/java-services-stop-working-when-user-logs-out*](http://superuser.com/questions/374147/java-services-stop-working-when-user-logs-out)

UNION Server’s original start command in C:\\union\\Union
Server\\startserver.bat is:

java -Dfile.encoding=UTF-8 -cp
lib\\union.jar;lib\\stax-api-1.0.1.jar;lib\\wstx-asl-3.2.6.jar
net.user1.union.core.UnionMain start

Change this to:

java -Xrs -Dfile.encoding=UTF-8 -cp
lib\\union.jar;lib\\stax-api-1.0.1.jar;lib\\wstx-asl-3.2.6.jar
net.user1.union.core.UnionMain start

The -Xrs flag stops the JVM from terminating on Windows user log off.

Important Configuration Summary (IP addresses, video stream URLs, Windows accounts, port forwarding etc)
--------------------------------------------------------------------------------------------------------

\[&lt;removed for security&gt;\]
