# Blake Dolin

personal blog and homepage.

created by [blake@dolinit.com](mailto:blake@dolinit.com)

## Services

[Status Page](https://status.dolinit.com)

### Media

- [Media Server](https://jellyfin.dolinit.com)
- [Media Requests](https://jellyseerr.dolinit.com)
- [Transmission](https://rpc.dolinit.com)

### Gaming

- [Foundry VTT](https://foundry.dolinit.com)
- [Minecraft Server](minecraft.dolinit.com:25565)
  - Runs the [Prominence II RPG Hasturian Era](https://www.curseforge.com/minecraft/modpacks/prominence-2-rpg) Modpack from CurseForge

### Admin

- [Admin Console](https://webmin.dolinit.com)
- [Portainer](https://portainer.dolinit.com)
- [Traefik](https://traefik.dolinit.com)

## Contact Me

- [Resume](/resume.html)
- [LinkedIn](https://www.linkedin.com/in/blakedolin)
- [Discord](https://discord.com/users/231844849433706506)
- [Signal](https://signal.me/#eu/zdjy_96_9ivRGo3XpHJSsNIP73o49SIrvQ7w-By81Jrm4FhqJCxBHLqaKMZSHeJm)
- [PGP Key](assets/Blake_Dolin_Pubkey.asc "Fingerprint: 0920CD4F5BA69E6AF25271786B8F7D1DEFD9D974")

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
