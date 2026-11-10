# Rizosfera — versão web

Experiência educativa sobre a rizosfera do feijão (raiz, pelos radiculares, nódulos, rizobactérias,
exsudatos e fixação biológica de nitrogênio), feita em Unity e publicada para abrir **direto no navegador**,
sem instalar nada.

**Abrir:** https://marcoantoniobarreiros.github.io/RizosferaAR/

## Como usar

1. Abra o link no celular (Chrome no Android, Safari no iPhone), ligue o som e toque em **Começar**.
2. Permita o uso da **câmera** e do **movimento do celular**.
3. Gire o celular para olhar em volta e **toque no portal** para entrar (ou segure a seta ▲).
4. Lá dentro, use ▲ ▼ para andar e **Centralizar** para ficar de frente para a raiz.
   **Toque em qualquer elemento** (raiz, pelo radicular, rizobactéria, exsudato, nódulo, N₂) para ver o nome e
   ouvir a explicação.
   **Nódulos:** o primeiro que você tocar acende na hora e começa a história do nódulo (que para se você tocar
   em outro elemento). Depois disso, um toque num nódulo mostra o nome; um segundo toque no mesmo nódulo
   (enquanto o nome está na tela) acende ou apaga.
5. Segure **↺ Recomeçar** (canto superior esquerdo) para reiniciar.

No computador: arraste com o mouse para olhar e use W/S (ou as setas) para andar.

## Diferença em relação ao app AR (APK)

Esta versão funciona em qualquer celular, inclusive os que não têm ARCore e iPhones. Mas o celular só sabe
para **onde aponta** (giroscópio), não **onde está**: o portal não fica preso ao chão e não dá para atravessá-lo
caminhando de verdade. Para a experiência completa em realidade aumentada, use o APK Android.

## Arquivos

Build WebGL do Unity 2022.3 (URP). `index.html` + `Build/` (arquivos `.unityweb` com descompressão no navegador,
compatível com o GitHub Pages).
