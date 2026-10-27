# 🎮 AGMM — All GameModes Modified

**Novas possibilidades para suas partidas de Among Us.**

AGMM é um mod de **Among Us** que reúne modos de jogo, funções e opções personalizadas para variar a experiência das partidas. Este repositório disponibiliza os arquivos da **Release 1.0**, com a DLL avulsa e um pacote de instalação para a edição Steam no Windows.

[⬇️ Baixar Release 1.0](https://github.com/KyroshKazehara/AGMM---All-GameModes-Modified/releases/tag/v1.0) · [🐛 Relatar um problema](https://github.com/KyroshKazehara/AGMM---All-GameModes-Modified/issues)

## 📦 Qual arquivo baixar?

| Arquivo | Indicado para |
| --- | --- |
| **Agmm - Steam-1.0.zip** | Instalação do pacote Steam, incluindo BepInEx, runtime e o plugin AGMM. |
| **AGMM(Release 1.0).dll** | Atualização manual do plugin em uma instalação BepInEx compatível já configurada. |

A DLL incluída no ZIP é idêntica à DLL avulsa desta release.

## 🚀 Instalação — pacote Steam

1. Feche o Among Us.
2. Na Steam, abra **Among Us → Gerenciar → Explorar arquivos locais**.
3. Baixe e extraia `Agmm - Steam-1.0.zip`.
4. Copie o **conteúdo** da pasta `Agmm - Steam-1.0` para a pasta do jogo, ao lado de `Among Us.exe`.
5. Confira se `BepInEx`, `dotnet`, `doorstop_config.ini` e `winhttp.dll` estão na pasta do jogo.
6. Inicie o jogo e aguarde o carregamento do BepInEx e do mod.

## 🔧 Instalação — DLL avulsa

Com o jogo fechado e o BepInEx compatível instalado, coloque `AGMM(Release 1.0).dll` em `BepInEx/plugins/`. Ao atualizar, remova a versão anterior do plugin para evitar carregar duas cópias do AGMM. A DLL avulsa não inclui o carregador nem o runtime presentes no ZIP.

## ℹ️ Compatibilidade

- O pacote disponibilizado é destinado ao **Among Us para Steam no Windows**.
- A versão exata do jogo compatível com estes arquivos ainda não foi documentada neste repositório. A numeração **Release 1.0** identifica esta distribuição.
- Compatibilidade com outras lojas, sistemas e versões do jogo não foi validada aqui.

## 🐛 Suporte

Abra uma [issue](https://github.com/KyroshKazehara/AGMM---All-GameModes-Modified/issues) informando a versão do jogo, o arquivo instalado, o que aconteceu e os passos para reproduzir. Se necessário, anexe o log do BepInEx após revisar dados pessoais.

## Créditos

AGMM significa **All GameModes Modified**. O pacote utiliza BepInEx e Unity Doorstop. Among Us pertence à Innersloth; este repositório não é afiliado à Innersloth.
