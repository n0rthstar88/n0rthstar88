# Hi, I'm James

I'm a Technical Support Lead at Vero Networks, a fiber internet provider. At home I run a homelab and build the tools that keep it running, from monitoring agents to Linux desktop apps. I'm looking for systems administration, infrastructure engineering and agentic AI roles.

🌐 [hufflabs.dev](https://hufflabs.dev) · 📫 [james@hufflabs.dev](mailto:james@hufflabs.dev)

## HuffLabs, my homelab

A self-hosted environment I designed, secured and run day to day.

| Area | What I run |
|---|---|
| Virtualization | Proxmox VE with LXC containers and VMs, Docker |
| Storage and backups | TrueNAS SCALE with ZFS, scheduled guest backups, encrypted restic backups |
| Networking | Self-hosted DNS with filtering, reverse proxy with TLS, Tailscale, Cloudflare Tunnels |
| Identity and security | Authentik single sign-on, role-based firewall rules, fail2ban, recurring security audits |
| Monitoring | Checkmk, plus a [Python watchdog](https://github.com/n0rthstar88/homelab-watchdog) I built that sends alerts and takes commands in Discord |
| AI agents | An [on-call agent](https://github.com/n0rthstar88/homelab-oncall-agent) for critical alerts: known problems get an allowlisted fix, and anything else goes to AI triage, limited by a gatekeeper that logs every command and rate-limits fixes |
| Automation | Python, Bash, Lua, Go, systemd |
| Operations | Runbooks, incident write-ups and disaster recovery documentation |

## Projects

- [Homelab On-Call Agent](https://github.com/n0rthstar88/homelab-oncall-agent): self-healing monitoring for Proxmox and Checkmk, with AI triage behind a security gatekeeper

  <a href="assets/projects/oncall-triage.webp"><img align="top" src="assets/projects/oncall-triage.webp" width="480" alt="On-call agent triage report in Discord, with example host names"></a>

- [Homelab Watchdog](https://github.com/n0rthstar88/homelab-watchdog): security and availability monitor with change-based Discord alerts and commands, in plain Python

  <a href="assets/projects/watchdog-alert.webp"><img align="top" src="assets/projects/watchdog-alert.webp" width="420" alt="Watchdog alerts in Discord, with example host names and addresses"></a>
  <br><a href="assets/projects/watchdog-ping.webp"><img align="top" src="assets/projects/watchdog-ping.webp" width="760" alt="Watchdog answering a ping command in Discord"></a>

- [HuffLabs RO](https://github.com/n0rthstar88/hufflabs-ro): a private game server for friends, reachable only over Tailscale, with an invite-only sign-up site, Windows and Linux installers, and a self-updating launcher that verifies signed updates. In Go, tested on Linux and Windows in GitHub Actions, with versioned releases

  <a href="assets/projects/ro-launcher.webp"><img align="top" src="assets/projects/ro-launcher.webp" width="370" alt="HuffLabs RO launcher downloading an update"></a>
  <a href="assets/projects/ro-signup.webp"><img align="top" src="assets/projects/ro-signup.webp" width="370" alt="HuffLabs RO invite-only sign-up page"></a>

- [PeripheralHub](https://github.com/n0rthstar88/peripheralhub): GTK4 app for keyboard, mouse, display and battery settings on Linux

  <a href="assets/projects/peripheralhub-lighting.webp"><img align="top" src="assets/projects/peripheralhub-lighting.webp" width="370" alt="PeripheralHub keyboard lighting settings"></a>
  <a href="assets/projects/peripheralhub-dpi.webp"><img align="top" src="assets/projects/peripheralhub-dpi.webp" width="370" alt="PeripheralHub mouse DPI stages"></a>

- [Snap Layouts for Omarchy](https://github.com/n0rthstar88/omarchy-snap-layouts): drag a window to the top of the screen to pick a layout

  <a href="assets/projects/snap-picker.webp"><img align="top" src="assets/projects/snap-picker.webp" width="370" alt="Dragging a window to the top of the screen shows layout choices"></a>
  <a href="assets/projects/snap-snapped.webp"><img align="top" src="assets/projects/snap-snapped.webp" width="370" alt="Windows snapped into a three-pane layout"></a>

- [Dark Magic](https://github.com/gravestench/dark-magic/pulls?q=is%3Apr+is%3Amerged+author%3An0rthstar88): 18 merged pull requests to an open-source Diablo II engine in Go and Lua

  <a href="assets/projects/darkmagic-code.webp"><img align="top" src="assets/projects/darkmagic-code.webp" width="370" alt="Dark Magic Lua code under the project's candle logo: kill experience scaled by level difference"></a>
  <a href="assets/projects/darkmagic-prs.webp"><img align="top" src="assets/projects/darkmagic-prs.webp" width="370" alt="18 merged pull requests in the Dark Magic repository, each passing CI"></a>

