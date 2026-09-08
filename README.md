# NetmodX

Xray-only root TPROXY VPN client for ARM64 rooted Android (Magisk / KernelSU).

- Display: **NetmodX**
- applicationId: `com.netmodx.app`
- Engine: [eichgee/Xray-core](https://github.com/eichgee/Xray-core) v25.5.16 (shipped as `libxray.so`)
- Capture: root **TPROXY** (`dokodemo` + `IP_TRANSPARENT`/`SO_MARK`), no VpnService / TUN
- Root: in-app `su` (Magisk/KSU)

## Tabs
1. **Proxy** — import from `vless://` / `vmess://` (also QR/file/clipboard), create, edit, delete.
2. **Log** — live Xray core log, clear, refresh.
3. **Settings** — DNS (through-tunnel Fast mode), share via hotspot, start on boot.
