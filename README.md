# Leve Tube

Versão leve do YouTube para TV box fraco (Android TV), sem anúncios.

Feita a partir do **SmartTube**, de Yuriy Liskov (https://github.com/yuliskov/SmartTube),
sob a **licença MIT**. Os avisos de licença originais estão em `LICENSE`,
`MediaServiceCore/LICENSE` e `SharedModules/LICENSE`.

## O que muda em relação ao original
- Só 32 bits (armeabi-v7a): APK menor, roda em quase todo TV box
- Padrões leves: 720p AVC, buffer baixo, sem miniaturas ao avançar
- Nome, ícone e pacote próprios (`com.gabriel.levetube`), instala junto com o original

O APK é compilado pelo GitHub Actions (Releases).
