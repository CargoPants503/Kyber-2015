> [!WARNING]
> This version of KYBER is not directly associated with [KYBER V2](https://uplink.kyber.gg/news/features-overview/), which has been under private development, with a whole host of new and improved features for STAR WARS™ Battlefront™ II (2017).

This version has been modified to support the creation and hosting of moddable servers for STAR WARS™ Battlefront™ (2015).

<h1 align="center"><img src="https://kyber.gg/logo2.svg" width="30rem"> Kyber</h1>

<h4 align="center">This port of Kyber is an Open-Source Private Server tool for STAR WARS™ Battlefront™ (2015).</h4>
<br>
<p align="center">
  <a href="https://twitter.com/BattleDashBR"><img src="https://img.shields.io/badge/Twitter-@BattleDashBR-1da1f2.svg?logo=twitter"></a>
  <a href="https://discord.gg/kyber">
      <img src="https://img.shields.io/discord/305338604316655616.svg?label=Discord&logo=discord&color=778cd4">
  </a>
  
</p>

------
In the future, this port for STAR WARS™ Battlefront™ (2015) will have proxy support.


What's done:
* Server starting
* Networking/Joining
* NAT Punch-Through system
* UX/UI Styling (WIP)


What isn't done:
* In-Game server browser
* Direct proxy support
* Per-player team swapping
* Player kicking/moderation
* Optimal proxy detection
* Built-in mod verification (currently handled at the proxy level, meaning it's unavailable if you direct-connect)
* Kick messages (currently if you are kicked by the server admin you just get sent back to the menu with no indication of why)
* Player banning
* Database handling at the proxy level

This port of Kyber is purely for port forwarding and having people connect to your IP. Once a proxy is set up, this issue will not occure. Feel free to build Kyber and inject it with the new launcher (/Launcher, will need a few modifications to run your own dll).

**Stars and PRs are welcome!**

## Credits

Kyber utilizes the following open-source projects:

- [MinHook](https://github.com/TsudaKageyu/minhook)
- [ImGUI](https://github.com/ocornut/imgui)
- [GLFW](https://glfw.org)
- [cpp-httplib](https://github.com/yhirose/cpp-httplib)
- [openssl](https://openssl.org)
- [executors](https://github.com/chriskohlhoff/executors)
- [nlohmann-json](https://github.com/nlohmann/json)

People
- BattleDash - Teaching me (CargoPants/Nuuby)
- Andersson799 - Offset for InclusionSetting Crash, correclty assigning the SocketManager
