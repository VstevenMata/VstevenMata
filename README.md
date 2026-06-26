<div align="center">

```
██████╗ ███████╗██╗   ██╗    ███████╗██╗   ██╗██╗     ██╗      ███████╗████████╗ █████╗  ██████╗██╗  ██╗
██╔══██╗██╔════╝██║   ██║    ██╔════╝██║   ██║██║     ██║      ██╔════╝╚══██╔══╝██╔══██╗██╔════╝██║ ██╔╝
██║  ██║█████╗  ██║   ██║    █████╗  ██║   ██║██║     ██║█████╗███████╗   ██║   ███████║██║     █████╔╝ 
██║  ██║██╔══╝  ╚██╗ ██╔╝    ██╔══╝  ██║   ██║██║     ██║╚════╝╚════██║   ██║   ██╔══██║██║     ██╔═██╗ 
██████╔╝███████╗ ╚████╔╝     ██║     ╚██████╔╝███████╗███████╗ ███████║   ██║   ██║  ██║╚██████╗██║  ██╗
╚═════╝ ╚══════╝  ╚═══╝      ╚═╝      ╚═════╝ ╚══════╝╚══════╝ ╚══════╝   ╚═╝   ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
```

</div>

---

```nix
{ config, pkgs, ... }:
{
  user = {
    name   = "Steven Mata";
    role   = "Full-Stack Developer";
    status = "Systems Engineering Student";
  };
}
```

---

```nix
# flake.nix — Clínica La Fuente

{
  description = "Medical administration platform";

  outputs = { ... }: {
    modules = [
      "patient-doctor-management"
      "appointment-scheduling"
      "clinical-history"
      "medication-inventory"
      "real-time-notifications-sse"
      "roles-admin-receptionist-doctor"
    ];

    url = "https://www.clinicamedicalafuente.com";
  };
}
```

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=VstevenMata&show_icons=true&theme=tokyonight&hide_border=true&border_radius=6&rank_icon=github&title_color=00ff41&icon_color=cc0077&text_color=888888&bg_color=0d1117" />
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VstevenMata&layout=compact&theme=tokyonight&hide_border=true&border_radius=6&langs_count=6&title_color=00ff41&bg_color=0d1117&text_color=888888" />

</div>

---

<div align="center">

```nix
networking.hostName = "VstevenMata";  # github.com/VstevenMata
```

</div>
