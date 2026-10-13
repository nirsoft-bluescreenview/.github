# BlueScreenView - Read the Minidump After Windows Crashes

![BlueScreenView minidump list with a bugcheck and highlighted driver](https://bluescreenview.com/wp-content/uploads/2026/05/Logi_Options__1_-removebg-preview.png)

## At a Glance

When Windows bluescreens, it can write a small dump under the usual minidump folder. BlueScreenView lists those files. You open one and read the bugcheck, the time, and the highlighted drivers. The highlighted name is a clue, not a verdict. A driver can appear because it was loaded, not because it was guilty. Note the code and the name, then update or remove the thing you can actually identify. Do not delete a system driver because it is in the list.

- Dump time and bugcheck code
- Loaded drivers for that crash
- Highlighted modules as suspects to investigate
- No automatic repair
- No dump, no answer, until crash dumps are enabled

1. Confirm a minidump exists after the crash.
2. Open the newest file, not a dump from last year.
3. Write down the bugcheck and the highlighted name.
4. If the name is a third-party driver you recognize, update or uninstall that product.
5. If the name is a core Windows file, look at the hardware and the last driver you added before you delete system files.

## Fits

A PC that bluescreened and wrote dumps. A poor fit for a freeze with no dump. A poor fit for a cleaner that claims it will stop crashes. A poor fit if you treat every listed driver as malware.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows with minidumps enabled |
| Files | At least one dump from the crash you care about |
| Rights | Enough to read the minidump folder |
| Next step | A driver update or a hardware test, not another viewer |

## Fixes

The list is empty. Dumps are disabled or the crash was a hard power loss.
The highlighted driver is a Windows file. Do not delete it. Note the code and what changed that day.
Several dumps name different drivers. Look for the one that repeats, and for the device you installed before the first date.
A new dump appears after you updated the suspect. The update did not fix it, or a different fault remains.
You wanted a full memory analysis. This is the quick view. Keep the dump if someone else will inspect it.

[![Open BlueScreenView](https://img.shields.io/badge/Open-BlueScreenView-334155?style=flat-square&logo=windows&logoColor=white)](https://bettywilsona221.github.io/.github/bluescreenview)

## The Newest Dump, Then the Repeating Name

Open the minidump from the crash you care about, not a file from last year that happens to sit in the same folder. Write down the bugcheck code, the time, and the highlighted module. If the highlighted name is a driver you installed, update or remove that product and see whether a new dump appears. If the highlighted name is a Windows component, do not delete it. Note what hardware or driver changed that day.

Several dumps that name different drivers are not five root causes until you look at the dates. A single third-party name that shows up every time is the better lead. A PC that freezes with no dump will show an empty list. Enable minidumps if you want the next crash to be readable. This viewer does not stop the crash.

- Newest file first
- Bugcheck and highlighted name written down
- Third-party repeats treated as the lead
- Windows files left on disk
- Empty list means no dump, not a healthy PC
- The dump kept if someone else will inspect it
- No cleaner run as a substitute for the note

| Highlight | Next step |
|---|---|
| A vendor driver you know | Update or uninstall it, then watch for a new dump |
| A Windows component | Look at the last change, not at deleting system files |
| A different name every time | Compare dates and hardware |
| Nothing in the list | Dumps are off, or the machine lost power |

BlueScreenView is the quick read. It is not a full memory debugger, and it is not a repair button.

## Repeat Offenders, Not Every Loaded Driver

A driver in the dump list was in memory. That is not guilt. Look for the same third-party name on the newest dumps, then update or remove that product. A Windows file in the highlight is a reason to remember what changed that day, not a reason to delete it. If the folder is empty, dumps are disabled or the machine lost power. The next crash can be made readable. This window will not stop it.

- Newest dump only
- Code and name written down
- Repeats preferred over one-off names
- System files left in place
- The dump kept for a deeper look
- No cleaner treated as the fix

## Phrase List

bluescreenview, nirsoft bluescreenview, minidump bugcheck, bluescreenview windows, read windows dump, highlighted driver crash, minidump folder, bluescreen which driver
