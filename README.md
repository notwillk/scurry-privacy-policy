# Scurry Privacy Policy

**Last updated: November 2, 2026**

Scurry is a macOS menu bar app that moves your mouse pointer to the center of a display when you press a keyboard shortcut you've assigned to it, or choose that display from Scurry's menu.

## The short version

Scurry doesn't collect your data. Its settings stay on your Mac, and the app doesn't send anything to the developer or to anyone else.

- No accounts or sign-in
- No analytics, telemetry or crash reporting built into the app
- No ads or third-party SDKs
- No servers or other online services

Scurry contains no networking code and works without an internet connection.

## What Scurry stores on your Mac

Scurry saves these settings in its local macOS preferences:

| What | Why |
| --- | --- |
| Each connected display's system identifier (UUID) and system name, such as the monitor's model name | To recognize the display when it reconnects and to keep showing a saved display while it's disconnected |
| The shortcut you assign to a display | To restore the shortcut when Scurry launches |
| Any nickname you give a display | To show your chosen name in Settings and menus |
| Whether the first-launch guidance has been shown | To avoid showing it again |

Scurry saves a record for each display it sees, even if you never assign that display a shortcut.

Backups you've set up for your Mac, such as Time Machine, may include these settings. Those backups are controlled by you, not by Scurry.

## What Scurry uses while running

Scurry uses some information briefly to do its job. It doesn't save this information or send it anywhere:

- **Displays:** their identifiers, names, positions and sizes, to find where to move the pointer and to draw the arrangement map.
- **Pointer and mouse buttons:** the pointer's position and whether a mouse button is held down, to complete a jump safely.
- **Frontmost app:** when a jump happens, the name of the active app, to check that the jump didn't change which app is active.

## Keyboard input

Scurry doesn't log your keystrokes or watch what you type in other apps.

- **Global shortcuts:** Scurry registers its shortcuts with macOS, which tells Scurry when you press one of them. Scurry doesn't receive anything else you type in other apps.
- **Recording a shortcut:** while the recording panel is open, Scurry reads the keys you press in that panel so it can save the combination.

## Permissions

Scurry doesn't ask for Accessibility, Input Monitoring, Screen Recording, Camera, Microphone, Location, Contacts, Photos or file access permissions. Its **Identify** feature only draws labels on your screens and doesn't capture their contents.

**Launch at Login** is off by default. If you turn it on, macOS keeps track of that setting. You can turn it off in Scurry's Settings at any time.

## Deleting your data

- **A shortcut:** select **Clear** for that shortcut in Settings. This removes the shortcut but leaves the display's identifier and name saved.
- **A nickname:** clear the name field in Settings to go back to the system name.
- **Everything:** quit Scurry, then use the option below for your copy. Deleting the app alone may leave its settings on your Mac.
  - **App Store or TestFlight copy:** delete the folder `~/Library/Containers/com.notwillk.scurry`.
  - **Directly downloaded copy:** run `defaults delete com.notwillk.scurry` in Terminal.

## Apple and other services

If you get Scurry through the App Store or TestFlight, Apple handles the download and any related account information under [its own privacy policy](https://www.apple.com/legal/privacy/). Apple may give developers aggregated app statistics, and crash reports if you've chosen to share them. TestFlight also gives developers information about testers, such as install details and any feedback you send. This data comes from Apple, not from Scurry.

If you download Scurry from another site, that site's own privacy policy applies to the download.

The **Privacy Policy** link in Scurry's About window opens in your web browser. The privacy policy of the site hosting the page applies to that visit.

## Children

Scurry doesn't collect personal information from anyone, including children.

## Changes to this policy

If this policy changes, the date at the top will change too. If a future version of Scurry collects any data, this policy will be updated to say what it collects and why before that version is released.

## Contact

Questions about this policy can be sent to [scurry@notwillk.com](mailto:scurry@notwillk.com).
