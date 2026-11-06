# tabula-eula

Páginas públicas dos apps TabulaCar, TabulaHome e TabulaDuo, publicadas via GitHub Pages.

| Página | TabulaCar | TabulaHome | TabulaDuo |
|---|---|---|---|
| Início | `tabulacar/` | `tabulahome/` | `tabuladuo/` |
| Termos de Uso (CLUF, Parte A) | `tabulacar/termos.html` | `tabulahome/termos.html` | `tabuladuo/termos.html` |
| Aviso de Privacidade (LGPD, Parte B) | `tabulacar/privacidade.html` | `tabulahome/privacidade.html` | `tabuladuo/privacidade.html` |

Os Termos e o Aviso de Privacidade formam um só documento: a versão e a data ficam iguais nas duas páginas. Ao mudar o texto, atualize as duas.

As páginas do TabulaCar também ficam no Firebase Hosting (site `tabulacar` do projeto `tabulacar-512917`): `https://tabulacar.web.app/`, `/privacidade.html` e `/termos.html`. São as URLs da tela de consentimento OAuth. Depois de mudar o texto, publique de novo com `npx firebase-tools deploy --only hosting`. Não apague `google19f93771f7b821b6.html`: ele mantém o site verificado no Search Console.
