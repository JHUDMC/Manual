# Systems 

The DMC uses several different software systems for internal projects and patron access.

When working on the Front Desk computer, you should log into all systems as yourself, using your own JHED, and log out when done (the easiest way to do this is to log out of the dmcadmin account)

### Overview

#### BookIt
BookIt is the equipment and space reservation system the DMC uses. All patrons and staff use BookIt to track inventory and check it out.

#### Discord
The DMC's Discord server is the Virtual Front Desk for patrons asking questions. Its staff-only channels are also frequently used for discussions, announcements, and shift sub requests.

#### Email (Outlook)
dmcstaff@jhu.edu is the shared mailbox from which Student Staff can respond to and initiate conversations with patrons. It should be open and monitored during Front Desk shifts.

#### Tasks
Tasks is the DMC project management system. Here we organize team projects, submit repair tickets, and purchase requests. It’s built into Teams (though functionality is better in the browser: https://tasks.office.com/)

#### J-Card Reader
The J-Card reader lives on the Front Desk and accepts J-Cash payments (the preferred method of payment at the DMC). The J-Card reader has a point-of-sale interface that automatically tallies totals for various DMC printing and consumable products. 

#### Credit Card Reader
The DMC has a portable wireless credit card reader that operates on cellular data. We use this device to accept payment from people without J-Cash for a small fee. We can also use it to accept payment at events if needed. 

#### RealVNC
RealVNC is the system we use to remote into the gaming computers in the LaB so we don’t have to go upstairs. Typically, this is used to enter an admin password to install/update a game. 

#### HIPPO
HIPPO is our internal server for DMC files and can be accessed when you are connected to the Hopkins network (on campus, or through VPN). It lives in the back of the cage on the networking rack and should always remain powered on. It can be accessed at: smb://HW-DMC-HIPPO/Project

#### Teams Files
“Teams – DMC Stustaff”  is where we store commonly-accessed documents such as shared passwords, consumable purchase tracking spreadsheets, and some DMC project files.

#### HopkinsGroups

#### Social Media

---
## BookIt

## Discord

## Email (Outlook)
All Student Staff has acccess to the dmcstaff@jhu.edu email account and should be monitoring and responding to the inbox during a Front Desk shift.

To access the account:

1. Go to outlook.office.com and log in with YOUR JHED/password.
2. Click the round initials/profile picture button in the top. 
3. Click "Open another mailbox" and type dmcstaff@jhu.edu in the dialogue
4. The dmcstaff@jhu.edu mailbox should open in a new tab.

When signed in you can also access the mailbox by navigating to https://outlook.office.com/mail/dmcstaff@jhu.edu/

*Please use the BROWSER-based system rather than adding it to your desktop Outlook app – this will make sure we can see all the same things (sometimes "sent" emails do not show up to other users if sent from the desktop app)*

You may use the DMC account to respond to patron-initiated questions, or to initiate emails to patrons with questions or reminders about their bookings (e.g. late returns or confirming renewals).

Pro Staff will also forward anything we'd like you to reply to or see on shift. This may include:
- Requests for help from students – like you might answer on Discord #help channel
- Routine requests with easy-to-answer questions from University affiliates/non-patrons about our services.

**Always feel free to copy digitalmedia@jhu.edu on your response if you're unsure or if Pro Staff should follow up.**

#### Email Best Practices:

- Respond with your name + “& The DMC” at the bottom of the email (e.g. “Quack & The DMC”). Only send the email after you've taken action; for example, renewing a booking in BookIt.

- After you respond to an email, please *Archive* it (NOT Delete it).

- If you open but do not act on an email, mark it "unread" in the Inbox.

- If an email is time sensitive and you have questions before you respond to it, reach out to Pro Staff or fellow Student Staff.

- If an email is sitting as "read" in the Inbox but you're unsure if it's been acted upon, check to see if there's a reply in the "Sent" box.

- Use Outlook's ["My Templates"](https://answers.microsoft.com/en-us/outlook_com/forum/all/outlook-web-access-my-templates/b0d7f655-31a1-4c7f-bb22-10373498aca9) feature to quickly access language for common emails (like late item reminders).

#### Using the calendar:
The shared calendar will help us track all kinds of appointments in the DMC, especially those that reserve lab space or require student staff attention or attendance. This is especially important for special events or those in which the entire lab is reserved (like for a workshop session). 

## J-Card Reader
If the J-Card reader enters "continuous check-in mode," do the following:
1. Tap on the screen's corners in this order: top left, bottom right, top right, bottom left.
2. Enter the code `3817`.

If you need to log into the J-Card wedge after a reboot, choose "Jason Charney" as the user and enter code "3817."

## Credit Card Reader

## RealVNC
- Patrons do not have admin rights on DMC/Gaming Loft computers and therefore must request the support of DMC staff to install software or games
- DMC Staff are permitted to install software on DMC computers, but must use common sense! (please don't install a Yahoo! toolbar etc.)

If a Patron asks for software to be installed or updated on a Gaming Loft PC and needs an administrator password...
1.	Use your best judgement to determine if the program is malicious or not. If you have any doubts, tell the Patron you are unable to install the software and will ask IT to handle it.
2.	Ask the patron which computer they are using and find it in the RealVNC Viewer client installed on the Front Desk computer. Connect to it.
3.	Enter the password `dmcgaming`. You should now be able to move the mouse around and type on their screen.
4.	Download and install the software on the machine if it is not yet installed.
5.	When prompted for admin credentials in Windows, use **YOUR** normal JHED/password combination as the user.


## HIPPO
HIPPO is our internal server for DMC files and can be accessed when you are connected to the Hopkins network (on campus, or through VPN). It lives in the back of the cage and should remain on at all times. If there is a power outage or if it turns off for some reason, you can turn it back on by pressing the button on the top of the device.

![HIPPO reset button location](https://github.com/JHUDMC/Manual/blob/db4b649fa9b4992ea7d706ed3a5f14cad90362c9/media/HIPPO.jpg)

### Connecting to HIPPO
**Mac:**
- Open Finder
- In the Menu Bar Select Go > Connect to Server (or press Cmd+K)
- Type the following path: `smb://HW-DMC-HIPPO/Project`
- Click "Connect"
- Enter your JHED and password

**Windows:**
- Open the File Explorer
- In the address bar, type the following path: `\\hw-dmc-hippo\Project`
- Press the Enter key
- Enter your JHED and password to connect
- *NB: You might need to enter JHED@jh.edu instead of just your JHED for Windows.*

If those file paths don't work for some reason, try the IP address (`10.166.42.124`) instead of "HW-DMC-HIPPO"

### HIPPO Shares
| Share (HIPPO/[x]) | Subfolders                               | Permissions                          |
|-------------------|------------------------------------------|--------------------------------------|
| /Project          | Events and Projects<br>PR<br>Circulation | ProStaff; StuStaff                   |
| /Workshop         |                                          | Write: ProStaff<br>Read only: anyone |
| /Admin            |                                          | ProStaff                             |
| /Archive          |                                          | Prostaff                             |
| /StaffHomes       | /Jason<br>/Travis<br>/Tony               | Jason<br>Travis<br>Tony              |

### Events and Projects
All files related to events and projects should live in their own folder on `HIPPO/Project/Events and Projects.`

When a new project is started, add a folder in the current year with the following naming convention:
`[Year]/[date]_[project name]/`


## Teams Files

## HopkinsGroups

## Social Media


