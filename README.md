# GA — STATUS IMPERIAL

Projeto Android inicial do GA, com painel pessoal, perfil, central musical e funcionamento offline para as telas locais.

## Como gerar o APK pelo GitHub
1. Envie os arquivos e pastas deste projeto para a raiz do repositório `GA-Imperial-ID` (incluindo `.github/workflows/build.yml`).
2. Abra a aba **Actions** no GitHub.
3. Escolha **Build GA Status Imperial APK** e clique em **Run workflow**. Também compila quando houver push na branch `main` ou `master`.
4. Quando terminar, abra a execução concluída e baixe o artefato `GA-STATUS-IMPERIAL-debug-apk`.
5. Extraia o ZIP do artefato e instale `app-debug.apk` no Moto G15. Se o Android pedir, permita instalação desse arquivo pelo app usado para abri-lo.

## O que já funciona
- Painel preto/vermelho com identidade GA.
- Navegação entre Início, Perfil e Central Musical.
- Conteúdo básico local, sem exigir internet para abrir as telas.
- Compilação de APK de depuração pelo GitHub Actions.

## Limites desta versão
- É um APK de depuração, ainda não uma versão assinada para publicação na Play Store.
- A central musical é uma área de atalhos/ideias; links reais e reprodução de áudio ainda precisam ser configurados.
- O perfil é demonstrativo e não tem edição nem sincronização na nuvem.
