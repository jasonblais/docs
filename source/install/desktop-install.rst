..  _desktop-install:

Mattermost Desktop Installation
===============================

Native desktop application for `Mattermost <http://www.mattermost.org/>`_ running on Windows, Mac and Linux.

Originally created as "electron-mattermost" by Yuya Ochiai. Developed using `Electron <http://electron.atom.io/>`_

Windows
---------------

To set up the Mattermost desktop application for Windows 7, 8 and 10:

1. Download `the latest release <https://github.com/mattermost/desktop/releases>`_ of Mattermost Desktop

   Find the file ending in ``-win64.zip`` if you're running a x64 version of Windows and ``-win32.zip`` if you're running an older 32-bit version.

2. From the ``\Downloads`` directory right-click on the file and select "Extract All..."

   - Change the extract folder from ``C:\Users\(currentuser)\Downloads\mattermost-desktop-1.1.1-win64`` to ``C:\Users\(currentuser)\AppData\Local`` where ``(currentuser)`` will be the name of your user account.
   - Check the "Show extracted files when complete" checkbox.
   - Click the "Extract" button.
   - Look for the new application directory at ``C:\Users\(currentuser)\AppData\Local\mattermost-desktop...``.
   - Remove the version number by renaming the ``mattermost-desktop...`` application directory to ``mattermost-desktop``.
   - If a ``mattermost-desktop`` directory already exists then you are upgrading Mattermost, and need to quit Mattermost if it is running and then delete the ``mattermost-desktop`` directory. After that you can rename the ``mattermost-desktop...`` directory to ``mattermost-desktop``. Don't worry, no settings will be lost, they are stored elsewhere.

3. Go to the ``\mattermost-desktop`` application directory and find the file named ``Mattermost``.

   - Right-click the file and select "Pin to Taskbar" to make the application available from your Windows task bar.
   - Right-click the file and select "Pin to Start Menu" to make the application available from your Windows Start menu.
   - Double-click the file to open the application.

4. Configure the application to interact with your teams.

   - Open **Settings Page**. If you use the application for the first time, **Settings Page** should appear automatically. Otherwise, press ``Alt`` key to bring up the menu at the top of the window, then click ``File -> Settings``.
   - For each Mattermost team you'd like to use, enter its **Name** and **URL** then click **Add**
   - Click **Save** to save your setting

You're now ready to use **Mattermost Desktop** to interact with multiple teams from one desktop application.

Download Links
---------------

Locations of compiled builds for latest releases

- `Mattermost Desktop v1.2.1 - Win32 <https://github.com/mattermost/desktop/releases/download/v1.2.1/mattermost-desktop-1.2.1-win32.zip>`_
- `Mattermost Desktop v1.2.1 - Win64 <https://github.com/mattermost/desktop/releases/download/v1.2.1/mattermost-desktop-1.2.1-win64.zip>`_
