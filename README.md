> [!NOTE]
> Auric is not directly associated with [KYBER V2](https://uplink.kyber.gg/news/features-overview/), STAR WARS™ Battlefront™ II's Private Server tool. However, Auric is based on the Original Source.

Auric is a modified version of [KYBER V1](https://github.com/ArmchairDevelopers/Kyber), supporting the creation and hosting of moddable servers for STAR WARS™ Battlefront™ (2015). 

[The source code will not be available until December 24, 2025]

<h1 align="center" style="display: flex; justify-content: center; align-items: center;">
  <span style="font-size: 5rem;">Auric</span>
  <br>
  <img src="https://github.com/CargoPants503/Auric/blob/main/Libraries/Sources/imgui/Logo1.png?raw=true" width="60rem" style="margin-right: 1rem;">
</h1>




<h4 align="center">Auric is an Open-Source Private Server tool for STAR WARS™ Battlefront™ (2015)</h4>

------
In the future, Auric will have proxy support.


What's done:
* Server starting
* Networking/Joining
* NAT Punch-Through system
* UX/UI Styling (WIP)


What isn't done:
* In-Game server browser
* Direct proxy support
* Per-player team swapping
* Optimal proxy detection
* Player Kicking/moderation
* Player banning

Auric is purely for port forwarding and having people connect to your IP. Once a proxy is set up, this issue will not be necessary. Feel free to build Auric and inject it with the new launcher (the launcher has not been set up yet).

Port Forwarding is only necessary for the server hoster. Use UDP through port 25200 and 25100

**Stars and PRs are welcome!**

## Credits

Auric utilizes the following open-source projects:

- [MinHook](https://github.com/TsudaKageyu/minhook)
- [ImGUI](https://github.com/ocornut/imgui)
- [GLFW](https://glfw.org)
- [cpp-httplib](https://github.com/yhirose/cpp-httplib)
- [openssl](https://openssl.org)
- [executors](https://github.com/chriskohlhoff/executors)
- [nlohmann-json](https://github.com/nlohmann/json)

People
- CargoPants - Responsible for rewriting [Kyber V1](https://github.com/ArmchairDevelopers/Kyber)'s code to work with STAR WARS™ Battlefront™
- BattleDash - Original source code and help with IDA/x64dbg
- Andersson799 - Offset for InclusionSetting Crash fix, and for helping to correclty assigning the SocketManager
- Dangercato - Original UI/UX
- Kape1223 - Concepts for the updated UI (Not yet included on this repository)
