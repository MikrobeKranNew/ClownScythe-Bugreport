# 🩸 ClownPierce's Scythe — Bug Reports & Issues

Welcome to the official bug-reporting repository for **ClownPierce's Scythe**, a Minecraft Fabric mod that brings a powerful scythe, blood-based abilities, unique enchantments, kill progression, and a challenging underground boss dungeon to Minecraft.

This repository is dedicated to **reporting bugs, tracking issues, collecting feedback, and suggesting improvements** related to the mod.

If you've encountered a bug, experienced unexpected behavior, or have an idea that could improve the mod, you're in the right place!

<p align="center">
  <a href="https://modrinth.com/mod/clownscythe">
    <img src="https://img.shields.io/badge/Modrinth-Download-1bd96a?style=for-the-badge&logo=modrinth&logoColor=white" alt="Download on Modrinth">
  </a>
  <a href="../../issues">
    <img src="https://img.shields.io/badge/GitHub-Report%20an%20Issue-181717?style=for-the-badge&logo=github&logoColor=white" alt="Report an issue">
  </a>
</p>

---

## 📌 Table of Contents

- [About the Mod](#-about-the-mod)
- [What Can I Report?](#-what-can-i-report)
- [Before Opening an Issue](#-before-opening-an-issue)
- [How to Report a Bug](#-how-to-report-a-bug)
- [Information to Include](#-information-to-include)
- [Getting Your Minecraft Logs](#-getting-your-minecraft-logs)
- [Troubleshooting](#-troubleshooting)
- [Feature Requests and Suggestions](#-feature-requests-and-suggestions)
- [Issue Guidelines](#-issue-guidelines)
- [Known Limitations](#-known-limitations)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Links and Resources](#-links-and-resources)
- [Disclaimer](#disclaimer)

---

## 🩸 About the Mod

**ClownPierce's Scythe** is a Minecraft mod inspired by ClownPierce and the creator Doctor4t. It introduces a powerful weapon with unique combat mechanics, unlockable abilities, custom enchantments, and an underground dungeon featuring waves of enemies and a final boss.

### Main Features

- **Clown's Scythe:** A powerful melee weapon that pulls enemies toward the wielder, restores health through lifesteal, and tracks kills.
- **Kill Progression:** Earn kills with the scythe to unlock damage milestones, Blood Aura abilities, notifications, and custom death messages.
- **Blood Aura:** Unlock increasingly powerful combat buffs at 50 and 100 kills.
- **Blood Beam:** Fire a blood-based beam that damages enemies and can transfer certain negative status effects.
- **Custom Enchantments:** Six unique enchantments designed specifically for the scythe.
- **Clown Boss Dungeon:** Explore a five-floor underground dungeon filled with enemies, traps, treasure, and progressively harder encounters.
- **Scythe Guardian:** Fight a powerful boss with multiple attacks, custom visuals, and a second phase.
- **Advancements:** Unlock achievements by progressing through the scythe's abilities and defeating the dungeon.
- **Client-Side Features:** Enjoy HUD indicators, particle effects, notifications, and custom boss rendering.
- **Configuration:** Customize supported mechanics using the Mod Menu configuration screen and configuration file.

For the complete feature list, installation instructions, downloads, and release information, visit the official project page:

**[ClownPierce's Scythe on Modrinth](https://modrinth.com/mod/clownscythe)**

---

## 🐛 What Can I Report?

You can use this repository to report issues related to any part of the mod.

### Gameplay and Combat

- The scythe deals incorrect damage.
- Lifesteal does not work as expected.
- Enemies are not pulled toward the player.
- Kill progression does not update correctly.
- Blood Aura abilities fail to unlock or activate.
- Blood Beam does not fire, deal damage, or transfer status effects correctly.
- Custom enchantments do not behave as intended.
- Cooldowns, health costs, or combat effects are incorrect.

### Dungeon and Boss

- The Blood Compass does not behave correctly.
- The dungeon fails to generate or generates incorrectly.
- Dungeon rooms, corridors, gates, or secret passages are broken.
- Enemy waves fail to start, progress, or finish.
- Dungeon progression becomes stuck.
- Dungeon state is lost after restarting the world or server.
- The Scythe Guardian fails to spawn, behaves incorrectly, or cannot be defeated.
- Boss attacks, phases, animations, or drops do not work correctly.
- Multiplayer dungeon progression behaves unexpectedly.

### Client and Visual Issues

- HUD indicators display incorrect information.
- Particles are missing or appear in the wrong location.
- The boss model, texture, or animations render incorrectly.
- Advancement progress does not update.
- Notifications or tooltips are missing or incorrect.
- The game crashes when opening a screen or performing an action.

### Configuration and Compatibility

- A configuration option does not work.
- Configuration values reset unexpectedly.
- The Mod Menu configuration screen fails to open.
- The mod conflicts with another mod.
- A dedicated server crashes or behaves incorrectly.
- The game crashes during startup, world loading, or gameplay.

If an issue is related to the mod, please report it even if you are unsure whether it is a bug.

---

## 🔍 Before Opening an Issue

Before submitting a new report, please take a moment to check the following.

1. **Search existing issues.** Someone else may have already reported the same problem.
2. **Check your mod version.** Make sure you're using a version intended for your Minecraft version.
3. **Verify your installation.** Confirm that Fabric Loader and Fabric API are installed correctly.
4. **Read the mod description.** Some mechanics have specific requirements, unlock conditions, or configurable behavior.
5. **Check your configuration.** A disabled feature or customized value may explain the behavior.
6. **Try to reproduce the issue.** If possible, repeat the same actions and see whether the bug happens again.
7. **Test without other mods if practical.** This can help identify compatibility conflicts.

You do not need to perform every troubleshooting step before reporting a serious issue. If the game crashes, a world becomes corrupted, or the problem prevents you from playing, please report it with the information you have available.

---

## 📝 How to Report a Bug

To submit a bug report:

1. Open the [GitHub Issues page](../../issues).
2. Check whether the issue has already been reported.
3. Click **New issue**.
4. Select the bug-report template if one is available.
5. Give the issue a clear, descriptive title.
6. Describe what happened and how to reproduce it.
7. Include your Minecraft version, mod version, loader version, relevant logs, and other useful details.
8. Submit the issue and respond to follow-up questions if necessary.

### Good Issue Titles

Use a title that describes the problem as clearly as possible.

**Good examples:**

- `[Combat] Lifesteal stops working after rejoining a world`
- `[Blood Beam] Beam does not damage entities on a dedicated server`
- `[Dungeon] Enemy waves fail to advance after the last enemy dies`
- `[Boss] Scythe Guardian disappears after restarting the server`
- `[Configuration] Blood Beam cooldown setting is ignored`
- `[Crash] Game crashes when generating the dungeon`

**Avoid vague titles such as:**

- `Help`
- `Bug`
- `It doesn't work`
- `Please fix`
- `Something is broken`

A descriptive title makes issues easier to search, understand, and investigate.

---

## 📋 Information to Include

The more relevant information you provide, the easier it is to investigate a bug.

| Information | What to provide |
|---|---|
| Mod version | The exact ClownPierce's Scythe version |
| Minecraft version | Your exact Minecraft version |
| Mod loader | Fabric, including its version |
| Fabric API | Installed version |
| Java version | Java version used to launch Minecraft |
| Environment | Singleplayer, LAN, or dedicated server |
| Other mods | Other installed mods, especially those affecting combat, entities, world generation, or rendering |
| Steps to reproduce | The exact actions that trigger the problem |
| Expected behavior | What you thought should happen |
| Actual behavior | What happened instead |
| Logs | Relevant error messages, stack traces, or crash reports |
| Reproducibility | Whether the issue happens every time or only occasionally |

You can leave information out if it is unavailable, but please provide as much as you reasonably can.

### Example Bug Report

The following example demonstrates the level of detail that makes a report useful. It is a fictional example, not a confirmed issue.

**Title:** `[Dungeon] Enemy waves do not advance after defeating all enemies`

**Description:**

The dungeon wave progression appears to stop after all enemies in an encounter have been defeated.

**Steps to reproduce:**

1. Start a world with the required mod dependencies installed.
2. Locate and enter the Clown Boss Dungeon.
3. Enter a floor's challenge room and start an encounter.
4. Defeat every enemy in the current wave.
5. Wait for the next wave to begin.

**Expected behavior:**

The next wave should begin after the current wave has been cleared.

**Actual behavior:**

No new wave begins, and the encounter appears to remain stuck.

**Environment:**

- Minecraft version: `1.20.1`
- ClownPierce's Scythe version: `[your version]`
- Fabric Loader version: `[your version]`
- Fabric API version: `[your version]`
- Java version: `[your version]`
- Environment: `Singleplayer`
- Other mods: `[list installed mods]`

**Reproducibility:** `Happens consistently / happens occasionally`

**Logs or screenshots:**

`[Attach relevant logs, screenshots, or crash reports here.]`

---

## 📂 Getting Your Minecraft Logs

Logs are particularly useful for diagnosing crashes, unexpected behavior, and compatibility problems.

### Latest Log

Your latest Minecraft log is usually located at:

**Windows**
```text
%appdata%\.minecraft\logs\latest.log
```

**Linux**
```text
~/.minecraft/logs/latest.log
```

**macOS**
```text
~/Library/Application Support/minecraft/logs/latest.log
```

If you use a custom Minecraft launcher or game directory, your logs may be stored somewhere else. Check your launcher's instance settings.

### Crash Reports

Crash reports are usually stored in:

```text
.minecraft/crash-reports/
```

Open the crash report corresponding to the time of the crash and attach it to your issue.

### What Should I Upload?

Depending on the problem, useful files include:

- `latest.log`
- The relevant crash report
- A screenshot or short video showing the issue
- A list of installed mods and their versions
- Relevant configuration files
- Steps that reliably reproduce the issue

You can drag and drop supported files directly into a GitHub issue.

For large logs, use a reputable paste service or attach the file if GitHub supports it. Include a link in your report.

**Privacy reminder:** Logs can contain usernames, local file paths, server addresses, and other identifying information. Review your files and remove private information before publishing them. Never upload passwords, access tokens, session credentials, or other secrets.

---

## 🛠️ Troubleshooting

Before or after reporting an issue, the following steps may help.

### The Game Crashes on Startup

- Confirm that your Minecraft version is supported by the installed mod version.
- Check that Fabric Loader and Fabric API are installed correctly.
- Make sure you are using a compatible Java version.
- Remove duplicate or outdated copies of the mod JAR.
- Check `latest.log` and the crash report for the first relevant error.

### The Scythe or Its Abilities Do Not Work

- Verify that you are using the correct item.
- Check whether the ability requires a specific kill milestone, cooldown, or resource.
- Review the mod's configuration settings.
- Test the behavior in a fresh world if it is safe and practical to do so.
- Include the exact action that causes the problem in your report.

### The Dungeon Is Stuck

- Check whether enemies remain in the current encounter.
- Verify that the encounter has actually started.
- Allow time for the game to update its encounter state.
- Record the floor, wave, and approximate location where the problem occurs.
- Avoid deleting world files or manually modifying saved data before backing up the world.

### The Boss Is Missing or Behaves Incorrectly

- Check whether the relevant dungeon encounter has been completed and the boss should be present.
- Record what happened immediately before the boss disappeared or became unresponsive.
- If the issue occurs after restarting a world or server, include that detail.
- Attach relevant server and client logs when possible.

### The Problem Only Happens with Other Mods

- Record the names and versions of the mods involved.
- Try to reproduce the problem with a smaller set of mods, if practical.
- Include logs from the affected environment.
- Do not assume that a particular mod is responsible until there is evidence supporting that conclusion.

These are general troubleshooting suggestions, not guarantees that the underlying problem can be resolved without a fix.

---

## 💡 Feature Requests and Suggestions

Ideas and constructive feedback are welcome!

If you have a suggestion for improving ClownPierce's Scythe, open an issue and clearly label it as a feature request or suggestion.

Useful suggestions might include:

- Additional scythe abilities or combat mechanics.
- Improvements to kill progression and Blood Aura.
- New enchantments or balance adjustments.
- Additional dungeon encounters, rooms, or rewards.
- Improvements to the Scythe Guardian fight.
- More configuration options.
- Better multiplayer behavior.
- Improved tooltips, HUD elements, or accessibility.
- Performance improvements or compatibility enhancements.

When submitting a suggestion, explain:

1. **The idea:** What would you like to see added or changed?
2. **The motivation:** What problem would it solve, or how would it improve gameplay?
3. **The implementation:** If you have one, describe a possible way to implement it.
4. **The trade-offs:** If relevant, explain any balance, performance, or compatibility concerns.

Please remember that suggestions are not guaranteed to be implemented. Development time, technical limitations, balance, and the overall direction of the mod may affect whether an idea is accepted.

---

## 📏 Issue Guidelines

To keep this repository useful and organized, please follow these guidelines.

### Be Respectful

Treat the creator and other community members with respect. Constructive criticism is welcome; harassment, personal attacks, and insults are not.

### One Issue per Report

Please create a separate issue for each unrelated bug. If you discover multiple symptoms that appear to have the same underlying cause, explain the connection in your report.

### Provide Useful Information

Reports such as "it is broken" are difficult to investigate. Whenever possible, provide reproduction steps, logs, version information, and screenshots.

### Do Not Spam

Avoid repeatedly opening identical issues, posting irrelevant comments, or tagging the creator unnecessarily.

If an existing issue describes your problem, add a comment with your additional information instead of creating a duplicate.

### Stay on Topic

Keep discussion focused on the reported bug, proposed feature, or relevant technical details.

### Be Patient

This mod is a passion project developed in spare time. Issues may not receive an immediate response, and fixes may take time.

**Opening an issue does not guarantee an immediate response or a fix in the next release.**

### Keep Discussions in GitHub

Whenever possible, keep technical information, reproduction steps, and relevant follow-up questions in the corresponding GitHub issue. This helps preserve context and allows others experiencing the same problem to contribute useful information.

---

## ⚠️ Known Limitations

Please keep the following in mind when reporting issues.

- **Compatibility:** The Modrinth project page lists Minecraft Java Edition versions 1.20.1–1.20.6 and Fabric as supported. Check the project's available releases for the exact version you need.
- **Dependencies:** Fabric Loader and Fabric API are required for the documented supported setup. Mod Menu is recommended for in-game configuration.
- **Configuration:** Changing configuration values may alter the behavior of abilities, damage, cooldowns, progression, and other mechanics.
- **Multiplayer:** Some mechanics, including dungeon progression, involve shared server-side state. Bugs may behave differently in singleplayer and multiplayer.
- **Third-party mods:** Compatibility with every possible combination of mods cannot be guaranteed.
- **Development schedule:** Updates and fixes are not released on a guaranteed schedule.

If your issue occurs on a Minecraft version or setup that is not listed as supported, you may still report it. Please mention that the setup is unsupported so it can be investigated with the appropriate context.

---

## ❓ Frequently Asked Questions

### Where can I download the mod?

Download the mod from its official Modrinth project page:

**[Download ClownPierce's Scythe](https://modrinth.com/mod/clownscythe)**

### Is this repository where I download the mod?

No. This repository is intended for bug reports, issue tracking, and suggestions. Downloadable mod releases are available on Modrinth.

### Do I need to include a crash report?

Not always. Crash reports are particularly useful for crashes, while `latest.log`, screenshots, videos, and reproduction steps can also help investigate bugs that do not crash the game.

### What if I cannot reproduce the issue?

You can still report it. Explain what you were doing when it happened, how frequently it occurs, and any details that might help identify the cause.

### What if someone has already reported my bug?

Open the existing issue and add any relevant information you have, such as additional reproduction steps, logs, or details about your Minecraft setup.

### Can I request new features here?

Yes. Please clearly identify your issue as a feature request and explain the idea and its benefits.

### How long will it take to fix my bug?

There is no guaranteed timeframe. I work on the mod in spare time, and the complexity and priority of each issue can vary.

### What if I discover a security or privacy vulnerability?

Do not publicly post sensitive exploit details, private credentials, or personal information. Contact me privately through an issue, where you say, you found one, please include your Discord username, so I can DM you.

### Where can I ask other questions?

For downloads and general project information, start with the [Modrinth project page](https://modrinth.com/mod/clownscythe).

---

## 🔗 Links and Resources

| Resource | Link |
|---|---|
| Modrinth Project | [ClownPierce's Scythe](https://modrinth.com/mod/clownscythe) |
| Report a Bug | [Open GitHub Issues](../../issues) |
| View Existing Issues | [Browse Issues](../../issues) |
| Create a New Issue | [New Issue](../../issues/new) |
| Minecraft | [Official Minecraft Website](https://www.minecraft.net/) |
| Fabric | [Fabric Loader and Documentation](https://fabricmc.net/) |
| Fabric API | [Fabric API on Modrinth](https://modrinth.com/mod/fabric-api) |
| Mod Menu | [Mod Menu on Modrinth](https://modrinth.com/mod/modmenu) |

---

<a id="disclaimer"></a>
## ⚖️ Disclaimer

ClownPierce's Scythe is a community-created Minecraft modification inspired by the work of Doctor4t.

This GitHub repository is intended for issue tracking and community feedback. It is not necessarily the source-code repository for the mod, and submitting an issue does not imply that the submitter has permission to redistribute, modify, or relicense the mod.

Please refer to the [official Modrinth project page](https://modrinth.com/mod/clownscythe) for the project's current license, permissions, supported releases, and official information.

Minecraft is a trademark of Mojang Studios. This project is not an official Minecraft product and is not approved by or associated with Mojang Studios or Microsoft.

---

## ❤️ Thank You!

Thank you for taking the time to report bugs, share suggestions, and help improve the mod.

Detailed reports and constructive feedback make it easier to identify problems, improve stability, and provide a better experience for everyone.

**Found a bug? [Open an issue on GitHub](../../issues/new).**

Enjoy the scythe! ❤️
