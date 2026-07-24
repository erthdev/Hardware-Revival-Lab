# MacBook Pro Mid-2012 Refurbishment Log

A long-term refurbishment, upgrade, and repurposing project for a mid-2012 MacBook Pro.

---

## Project Status

| Component                | Current Status                           |
| ------------------------ | ---------------------------------------- |
| **Status**               | Paused, but not abandoned                |
| **Current OS**           | macOS Catalina                           |
| **RAM**                  | 8 GB DDR3                                |
| **Storage**              | 256 GB STORM M.2 SATA SSD                |
| **Future OS Experiment** | OpenCore Legacy Patcher                  |
| **Future OS Target**     | Ventura or newer macOS                   |
| **Future Storage**       | 500 GB HDD via optical drive replacement |
| **Long-Term Goal**       | Possible home media server               |

---

# The Beginning

This MacBook Pro originally belonged to my sister-in-law.

At some point, it ended up sitting in a closet, unused.

It is a mid-2012 MacBook Pro, which means it is already an old machine by modern standards. However, instead of letting it remain unused, I decided to have it repaired and give it a second life.

The original plan was simple.

Repair the MacBook and give it to my girlfriend as part of my monthsary gift.

I wanted to give her something useful, but I also wanted to do something more personal than simply buying a new device.

The MacBook was already there.

It just needed some attention.

After having it repaired, I decided to continue improving it myself.

That is where the project began.

---

# Log 01: The Original Storage Setup

The MacBook originally had a **240 GB SSD** installed.

At some point, I decided to replace it with a **256 GB STORM M.2 SATA SSD** installed inside an **NGFF-to-SATA adapter**.

The 240 GB SSD was removed, and the STORM SSD became the new primary storage drive.

The STORM SSD originally had Linux Mint installed on it.

Linux Mint was working well, but I eventually decided to wipe the drive completely and move forward with a fresh macOS installation.

The Linux Mint installation was removed.

The SSD was wiped clean.

At this point, the project became a clean rebuild.

---

# Log 02: The SSD Replacement

The goal of the storage upgrade was to replace the old 240 GB SSD with the 256 GB STORM SSD and prepare it for macOS.

This was when I learned that even a relatively simple storage replacement can become an adventure when working with an old laptop.

The hardest part was not the SSD itself.

It was removing the screws.

Some of the screws on the bottom cover were incredibly difficult to remove.

They were small, tight, and had clearly experienced years of use.

I had to be extremely careful not to strip them.

The process required patience, the right tools, and a lot of trial and error.

Honestly, removing the screws was probably the most difficult physical part of the entire refurbishment.

Eventually, I managed to open the MacBook and access the internals.

The original **240 GB SSD** was removed.

The **256 GB STORM SSD** was installed.

The storage upgrade was complete.

---

# Log 03: The RAM Upgrade Attempt

After installing the new SSD, I decided to try upgrading the RAM.

The MacBook originally had two 4 GB DDR3 sticks installed.

This gave it a total of 8 GB of RAM.

I had an 8 GB DDR3 stick available, so I decided to try installing it.

Unfortunately, the MacBook did not like it.

The system started beeping three times.

At first, I thought the RAM might simply be dirty.

The MacBook had been sitting unused for a long time, so I cleaned the RAM and removed dust from the inside of the machine.

I cleaned the contacts, reseated the memory, and tried again.

The MacBook continued beeping.

After more investigation, I found that the RAM I was trying to install was **1.35 V DDR3L**.

The MacBook appeared to require **1.5 V DDR3 memory**.

That was most likely the compatibility problem.

There is still a possibility that the RAM itself was defective, but I am leaning toward the voltage difference being the main issue.

After several attempts, I decided to stop trying to force the upgrade.

I reinstalled the original two 4 GB sticks.

The MacBook returned to a stable 8 GB configuration.

At that point, I decided that 8 GB was good enough for the project.

---

# Log 04: Reformatting the New SSD

With the 256 GB STORM SSD installed, I needed to prepare it for macOS.

I booted into macOS Recovery and opened Disk Utility.

The new SSD was completely reformatted.

The old Linux Mint installation and all existing data were removed, and the drive was prepared for a fresh macOS installation.

The general process was:

1. Boot into macOS Recovery.
2. Open Disk Utility.
3. Select the new 256 GB SSD.
4. Erase the existing data.
5. Format the drive for macOS.
6. Reinstall macOS.
7. Complete the setup process.
8. Update the system.

After the installation process was completed, macOS Catalina was successfully running on the new SSD.

The MacBook was alive again.

---

# Log 05: Catalina Is Working

After reinstalling macOS Catalina, the MacBook was working perfectly.

The SSD made the machine feel much more responsive compared to using an old mechanical hard drive.

The system was stable.

The hardware was working.

The RAM was working.

The new SSD was working.

There were some warnings that certain browsers were no longer officially supported on Catalina, but the operating system itself was still usable.

At this point, I could have stopped.

The MacBook had already achieved the original goal.

It had been repaired, upgraded, and given to my girlfriend as a monthsary gift.

But I was not finished experimenting.

---

# Log 06: The OpenCore Legacy Patcher Experiment

I started looking into **OpenCore Legacy Patcher**, commonly referred to as OCLP.

The idea was to install a newer version of macOS that is not officially supported on the mid-2012 MacBook Pro.

The initial target was **macOS Ventura**.

I wanted to see if the old MacBook could run a more modern version of macOS.

However, I immediately ran into a problem.

The macOS installer was approximately **12.2 GB**.

The largest USB storage I had available was only around **8 GB**.

Because of that, I could not simply create the installer using the storage I had available.

---

## The Partition Idea

At one point, I considered using a partition on the internal SSD itself as a boot or installation source.

Technically, this seemed like a possible workaround.

However, I eventually decided against it.

The MacBook was already running perfectly with Catalina, and using a partition of the same drive for the installation process could introduce unnecessary risks.

If something went wrong during the process, I could potentially compromise the working operating system and make recovery more difficult.

Because I did not have a proper external drive available for the experiment, I decided that the risk was not worth it.

The idea was abandoned.

The OCLP experiment was paused.

---

# Log 07: The Decision to Stop

At this point, I decided to leave Catalina installed.

The MacBook was working perfectly.

There was no reason to risk destroying a stable system just to force an upgrade when I did not have the right storage available yet.

I decided that it was better to wait.

The plan became to acquire a **1 TB drive** in the future.

That drive would then be used as an experimental boot drive.

This would allow me to experiment with newer versions of macOS while keeping the internal Catalina installation safe.

---

# Log 08: The 1 TB Future Plan

The plan for the future 1 TB drive is to use it as a boot drive for a newer version of macOS.

The first target will probably be **macOS Ventura**.

I may eventually experiment with even newer versions, including Sequoia.

The advantage of using the 1 TB drive is that I can experiment without immediately destroying the stable Catalina installation on the internal SSD.

If the newer macOS installation works, then great.

If it fails, I can simply return to the internal Catalina installation.

Once the experimentation is finished, the 1 TB drive can eventually be repurposed as external storage.

---

# Log 09: The Future Secondary Storage Upgrade

Another planned upgrade is to add a secondary internal storage drive.

The MacBook has an optical drive that can potentially be replaced with a drive caddy.

The plan is to remove the optical drive and replace it with a **500 GB hard disk drive**.

This would allow the MacBook to have additional internal storage without removing the primary 256 GB SSD.

The planned configuration would be:

```text
256 GB STORM SSD
└── Main operating system

500 GB HDD
└── Movies and media storage
```

The optical drive replacement will be a future hardware project of its own.

---

# Log 10: The Future Media Server Idea

The MacBook may eventually become more than just a laptop.

One of the future plans is to use the additional 500 GB HDD for movie storage.

The long-term idea is to configure the MacBook as a small home media server.

The planned setup could eventually include:

* The **256 GB SSD** for the operating system.
* A **500 GB HDD** installed in place of the optical drive for movies and media.
* The **1 TB drive** for experimentation and future storage.
* **Moonfin** as part of the media setup.

The final goal is to turn the old MacBook Pro into a small home media server.

This would give the MacBook another purpose beyond simply being an old laptop.

---

# Current Status

The MacBook Pro is currently working with:

* A **256 GB STORM M.2 SATA SSD** installed through an NGFF-to-SATA adapter.
* **8 GB of RAM** using the original 2 x 4 GB DDR3 sticks.
* **macOS Catalina**.
* A clean macOS installation.
* A future OpenCore Legacy Patcher experiment planned.
* A future 1 TB experimental boot drive planned.
* A future 500 GB HDD planned as secondary internal storage.
* A future optical drive replacement planned.
* A possible future Moonfin media server setup.

The MacBook is currently stable.

For now, I am stopping the project at this stage.

Not because the project failed.

The opposite is true.

The MacBook is working.

The original goal was to repair an old MacBook Pro that had been sitting unused in a closet and give it to my girlfriend as part of my monthsary gift.

That goal has already been accomplished.

Everything beyond that is now an extra project.

---

# Final Thoughts For Now

This project started with an old MacBook Pro sitting unused in a closet.

It was repaired and given a new purpose.

Then I started upgrading it.

Then I started troubleshooting it.

Then I started experimenting with operating systems.

Now I am planning storage upgrades and a possible home media server.

This is how these projects always happen.

You start with:

> "I am just going to repair this old laptop."

Then suddenly you are:

> "What if I install a newer version of macOS?"

Then:

> "What if I use a 1 TB drive?"

Then:

> "What if I replace the optical drive with a 500 GB HDD?"

Then:

> "What if I turn it into a media server?"

The project is currently paused.

The MacBook is working perfectly with Catalina.

The next phase will begin when I acquire the 1 TB drive.

After that, I can continue experimenting with OpenCore Legacy Patcher while keeping the current system as safe as possible.

Until then, the MacBook is officially back in service.

**Project status: Paused, but not abandoned.**

**Next phase: 1 TB drive, OpenCore Legacy Patcher, and newer macOS experimentation.**

**Long-term goal: Keep this mid-2012 MacBook Pro useful for as many more years as possible.**

The MacBook is old.

But it is definitely not finished yet.
