# purplewaffle.github.io

Site oficial da **Grim Biscuit**, publicado por GitHub Pages em
<https://grimbiscuit.com/>.

Páginas estáticas, sem build e sem dependências:

| Arquivo | URL | Para quê |
| --- | --- | --- |
| `index.html` | `/` | Home do desenvolvedor — é este endereço que vai no campo *site* das lojas |
| `privacidade.html` | `/privacidade.html` | Política de privacidade (pt-BR) — URL exigida pelo Google Play Console e pelo App Store Connect |
| `privacy.html` | `/privacy.html` | Mesma política em inglês |
| `suporte.html` | `/suporte.html` | Página de suporte |
| `app-ads.txt` | `/app-ads.txt` | Autorização IAB dos vendedores de anúncio; o crawler do AdMob lê a raiz deste domínio |

## Antes de enviar um app às lojas

- [ ] Trocar `pub-0000000000000000` em `app-ads.txt` pelo ID de editor real do AdMob e
      **descomentar** a linha. Enquanto estiver comentada, o arquivo não autoriza ninguém.
- [ ] Declarar `https://grimbiscuit.com/` como site do desenvolvedor nas duas lojas
      (precisa ser o mesmo domínio que serve o `app-ads.txt`).
- [ ] Declarar `https://grimbiscuit.com/privacidade.html` como política de privacidade.
- [ ] Criar as caixas `contato@`, `suporte@` e `privacidade@grimbiscuit.com`, ou substituir
      os endereços nas quatro páginas por um e-mail que já exista.

As páginas afirmam que não existe servidor próprio, conta de usuário, analytics de terceiros
nem coleta além do AdMob. Se isso mudar no jogo, a política muda junto: declaração falsa de
privacidade é motivo de remoção nas duas lojas.
