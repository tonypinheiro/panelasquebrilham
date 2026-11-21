# Barraca da Francisca

Site da Barraca da Francisca (Panelas que brilham), na Forquilha, em São Luís: pedido pelo WhatsApp ou iFood, cardápio, endereço e horário.

## Como editar (sem mexer em código)

1. Entre em **app.pagescms.org** com a conta do GitHub e abra este repositório.
2. **Cardápio**: adicione, apague, esconda ou arraste os pratos. Preço, descrição e foto são opcionais. Cada prato ganha um botão "Pedir" que abre o WhatsApp com o nome do prato já escrito.
3. **Informações**: nome, frase, aviso do dia, WhatsApp, iFood, redes, endereço, horário e CNPJ.
4. Clique em **Salvar**. O site atualiza em 1 ou 2 minutos.

## Domínio próprio

Hoje o endereço é tonypinheiro.github.io/panelasquebrilham. Para usar um domínio próprio (ex.: barracadafran.com.br):

1. Registre o domínio no registro.br.
2. Aponte o DNS para o GitHub Pages e configure o domínio em Settings → Pages.
3. Em `_config.yml`, troque `baseurl: /panelasquebrilham` por `baseurl: ""` e `url` pelo novo endereço.

## Organização

```
_data/config.yml    informações (o editor altera este arquivo)
_data/cardapio.yml  pratos (o editor altera este arquivo)
.pages.yml          formulários do editor Pages CMS
index.html          a página, montada a partir de _data
404.html            página de "não encontrado"
assets/img/         logo e fotos (as que você sobe pelo editor vão para cá)
assets/brand/       ícones e imagem de compartilhamento
assets/fonts/       fontes Lilita One e Nunito
```

## Créditos

A versão anterior usava o template Hub Links, de Eric Hayashi (licença MIT). Esta versão foi reescrita do zero e não usa código do template.

Ícones das marcas: [Simple Icons](https://simpleicons.org) (CC0). Fontes: Lilita One e Nunito (SIL Open Font License, ver `assets/fonts/OFL.txt`).
