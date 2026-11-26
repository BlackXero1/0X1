# 0X1: Security Research Blog

Malware analysis, reverse engineering, threat intelligence and detection research by BlackXero1.

**Live site:** [https://blackxero1.github.io/0X1/](https://blackxero1.github.io/0X1/) · **RSS:** [https://blackxero1.github.io/0X1/feed.xml](https://blackxero1.github.io/0X1/feed.xml)

## Posts

| Post | Category | Type | Date |
|------|----------|------|------|
| [From Click to C2](https://blackxero1.github.io/0X1/malware-analysis/from-click-to-c2.html) | Malware Analysis · ClickFix | Deep Dive | 2026-11-26 |
| [Born in the Kernel](https://blackxero1.github.io/0X1/malware-analysis/born-in-the-kernel.html) | Malware Analysis · BYOVD | Deep Dive | 2026-11-26 |
| [The Loader Is the Malware](https://blackxero1.github.io/0X1/malware-analysis/loader-is-the-malware.html) | Malware Analysis · DLL Side-Loading | Deep Dive | 2026-11-23 |
| [Six Locks, No Key](https://blackxero1.github.io/0X1/reverse-engineering/go-dropper.html) | Reverse Engineering · Go Malware | Deep Dive | 2026-11-20 |
| [Memory Tells the Truth](https://blackxero1.github.io/0X1/dfir/memory-forensics.html) | DFIR · Memory Forensics | Research | 2026-11-20 |
| [EDR Evasion: Layers, Live](https://blackxero1.github.io/0X1/offensive/edr.html) | Offensive Research | Research | 2026-11-17 |
| [ClickFix: Two Chains, One Technique](https://blackxero1.github.io/0X1/malware-analysis/clickfix.html) | Malware Analysis · Initial Access | Case Study | 2026-11-12 |
| [Nine Front Doors, One Toolkit](https://blackxero1.github.io/0X1/malware-analysis/bitter-apt.html) | Threat Intelligence · APT | Deep Dive | 2026-08-18 |
| [The Cat-and-Mouse Game](https://blackxero1.github.io/0X1/defensive/edr-evasion.html) | Defensive · Detection Engineering | Research | 2026-08-10 |

## Structure

```
index.html                         Home page and post index (category filters)
about.html                         About
404.html                           Not-found page
feed.xml                           RSS feed
assets/post.css                    Shared post styles (related posts, byline)
reverse-engineering/go-dropper.html
dfir/memory-forensics.html
offensive/edr.html
malware-analysis/from-click-to-c2.html
malware-analysis/born-in-the-kernel.html
malware-analysis/loader-is-the-malware.html
malware-analysis/clickfix.html
malware-analysis/bitter-apt.html
defensive/edr-evasion.html
```

## Adding a post

1. Copy an existing post as the template (nav, hero byline, TOC, related posts, disclaimer, footer).
2. Add a card to `index.html` with the right `data-cat` (`malware`, `re`, `ti`, `defensive`, `offensive`) and type (Deep Dive, Case Study, Research).
3. Add an `<item>` to `feed.xml` and a row to this README.
