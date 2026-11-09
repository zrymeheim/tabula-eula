# tabula-eula

Páginas públicas dos apps TabulaCar, TabulaHome, TabulaDuo e TabulaPet, publicadas via GitHub Pages.

| Página | TabulaCar | TabulaHome | TabulaDuo | TabulaPet |
|---|---|---|---|
| Início | `tabulacar/` | `tabulahome/` | `tabuladuo/` | `tabulapet/` |
| Termos de Uso (CLUF, Parte A) | `tabulacar/termos.html` | `tabulahome/termos.html` | `tabuladuo/termos.html` | `tabulapet/termos.html` |
| Aviso de Privacidade (LGPD, Parte B) | `tabulacar/privacidade.html` | `tabulahome/privacidade.html` | `tabuladuo/privacidade.html` | `tabulapet/privacidade.html` |

Os Termos e o Aviso de Privacidade formam um só documento: a versão e a data ficam iguais nas duas páginas. Ao mudar o texto, atualize as duas.

Os sites existentes também ficam no Firebase Hosting. A configuração do TabulaPet está pronta para o primeiro deploy, mas o site ainda precisa ser criado no projeto Firebase:

| App | Site | Projeto | Deploy |
|---|---|---|---|
| TabulaCar | `https://tabulacar.web.app/` | `tabulacar-512917` | `npx firebase-tools deploy --only hosting:tabulacar --project tabulacar-512917` |
| TabulaDuo | `https://tabuladuo.web.app/` | `tabuladuo` | `npx firebase-tools deploy --only hosting:tabuladuo --project tabuladuo` |
| TabulaHome | `https://tabulahome.web.app/` | `tabulahome` | `npx firebase-tools deploy --only hosting:tabulahome --project tabulahome` |
| TabulaPet | `https://tabulapet.web.app/` | `tabulapet` | `npx firebase-tools deploy --only hosting:tabulapet --project tabulapet` |

Antes do primeiro deploy do TabulaPet, crie o site de Hosting `tabulapet` no projeto Firebase `tabulapet` (`firebase hosting:sites:create tabulapet --project tabulapet`). A configuração de Hosting está pronta, mas ainda não foi publicada.

Cada site serve `/`, `/privacidade.html` e `/termos.html`. Depois de mudar o texto, publique de novo. Não apague `google19f93771f7b821b6.html`: ele mantém os sites verificados no Search Console.
