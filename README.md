# tabula-eula

Páginas públicas dos apps TabulaCar, TabulaHome e TabulaDuo, publicadas via GitHub Pages.

| Página | TabulaCar | TabulaHome | TabulaDuo |
|---|---|---|---|
| Início | `tabulacar/` | `tabulahome/` | `tabuladuo/` |
| Termos de Uso (CLUF, Parte A) | `tabulacar/termos.html` | `tabulahome/termos.html` | `tabuladuo/termos.html` |
| Aviso de Privacidade (LGPD, Parte B) | `tabulacar/privacidade.html` | `tabulahome/privacidade.html` | `tabuladuo/privacidade.html` |

Os Termos e o Aviso de Privacidade formam um só documento: a versão e a data ficam iguais nas duas páginas. Ao mudar o texto, atualize as duas.

As páginas dos três apps também ficam no Firebase Hosting, com URLs da tela de consentimento OAuth:

| App | Site | Projeto | Deploy |
|---|---|---|---|
| TabulaCar | `https://tabulacar.web.app/` | `tabulacar-512917` | `npx firebase-tools deploy --only hosting:tabulacar --project tabulacar-512917` |
| TabulaDuo | `https://tabuladuo.web.app/` | `tabuladuo` | `npx firebase-tools deploy --only hosting:tabuladuo --project tabuladuo` |
| TabulaHome | `https://tabulahome.web.app/` | `tabulahome` | `npx firebase-tools deploy --only hosting:tabulahome --project tabulahome` |

Cada site serve `/`, `/privacidade.html` e `/termos.html`. Depois de mudar o texto, publique de novo. Não apague `google19f93771f7b821b6.html`: ele mantém os sites verificados no Search Console.
