# Blake Dolin

personal blog and homepage.

created by [blake@dolinit.com](mailto:blake@dolinit.com)

## Contact Me

- [LinkedIn](https://www.linkedin.com/in/blakedolin)
- [Discord](https://discord.com/users/231844849433706506)
- [Signal](https://signal.me/#eu/zdjy_96_9ivRGo3XpHJSsNIP73o49SIrvQ7w-By81Jrm4FhqJCxBHLqaKMZSHeJm)
- [PGP Key](Blake_Dolin_Pubkey.asc "Fingerprint: 0920CD4F5BA69E6AF25271786B8F7D1DEFD9D974")

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
