# Croqui de Campo

App offline (PWA) para levantamento e conferência em obra, no Android: malha de coordenadas como planilha, planificação gerada da planta, elementos hospedados nas faces com chave e vínculo fixos, fotos, voz e vídeo com trilha de sensores.

Parte do sistema Meta IA, frente 710 · Assistente Arquitetônico.

- **Só código.** Nenhum dado de projeto entra neste repositório. Os dados ficam no aparelho (IndexedDB) e são trocados pela pasta do projeto no Drive (`_campo/entrada` e `_campo/saida`).
- **Funciona sem internet.** O service worker guarda o app no aparelho na primeira abertura.
- **Instalar:** abrir o endereço do GitHub Pages no Chrome do Android › menu › "Adicionar à tela inicial".
- O projeto de exemplo é genérico (um ambiente 4,00 × 3,00).

Formato dos pacotes: `croqui-campo/0.2` (registros e projeto completo; instalações compatíveis com o esquema-base: clados B6, portas, relação "hospeda-em").

Licença: CC BY-NC-ND 4.0 · Cleidson Lopes.
