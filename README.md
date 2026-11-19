# MCsumz / Marcell

**IT Support Engineer** · hardware · systems · troubleshooting

Long-time PC builder and hands-on IT enthusiast. I like knowing what happens between the hardware, the operating system, and the application — and tracing where that chain breaks. My experience spans PC hardware, homelab infrastructure, self-hosted services, and native macOS tooling.

My approach: understand the dependencies, isolate the fault, test the fix, and leave useful notes. I care about systems that stay reliable after the troubleshooting session ends.

### On the bench

- **[PS5LM-memfix](https://github.com/MCsumz/PS5LM-memfix)** — fixes for [cobanov’s PS5LM](https://github.com/cobanov/PS5LM), the LLM server for jailbroken PS5s: long chats no longer run out of memory (0.75 GiB still free after a 47.9k-token prompt), agent tool calls keep their connection, and a Qwen3.5 follow-up takes seconds instead of minutes. Tested on a PS5 Fat with Open WebUI. [Builds →](https://github.com/MCsumz/PS5LM-memfix/releases/latest)
- **[LiS Remastered FreeCam](https://github.com/MCsumz/LiS-Remastered-FreeCam)** — UE4SS camera controls for keyboard and Xbox controller. Packaged, documented, and tested in-game. [Build →](https://github.com/MCsumz/LiS-Remastered-FreeCam/releases/latest)

### Upstream

- **Merged:** [cobanov/PS5LM#88](https://github.com/cobanov/PS5LM/pull/88) — Qwen3.5 keeps earlier turns’ thinking, so a new message only appends instead of reprocessing the whole chat.
- **Offered:** [cobanov/PS5LM#98](https://github.com/cobanov/PS5LM/issues/98) — three more memfix fixes (media marker, streamed keep-alive, flash-attention scratch at load), each tested on the console.

### Homelab

A PS4 running Linux as a Podman host with a boot guard against storage corruption, a native macOS admin dashboard, and scripted updates and repo syncs across the machines.

<sub>AI-assisted development. Hands-on integration and testing. Credit to the projects these builds stand on.</sub>
