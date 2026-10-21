# Instalação manual dos scripts Excalidraw Automate

Guia do pacote documentado: **Converter-contas 2.9.21 RC2 + Assistente de Resolução 3.0.13 RC1** · 21/10/2026. Este arquivo é apenas documentação: o instalador deve ser baixado separadamente, a partir da Release correspondente. As versões ainda se identificam internamente como RC; publicação pública depende de autorização do responsável e verificações aplicáveis. Preserve a instalação anterior até concluir a conferência.

## O que você está instalando

Converter-contas e Assistente são scripts executados pelo plugin Excalidraw no Obsidian. Não são, neste pacote, um plugin nativo independente. Os arquivos .md contêm código executável; leia a origem antes de executá-los.

## Antes da instalação

1. Escolha uma entrega explicitamente aprovada pelo responsável e confirme seu par de versões e SHA-256. Não use uma RC por ser numericamente maior.
2. Faça backup do cofre e dos dois pares de scripts atuais fora da pasta ativa. Preserve sessões desejadas antes de fechar: a conversa em memória pode ser descartada.
3. Instale e ative Excalidraw em Configurações → Plugins da comunidade do Obsidian. A ativação envolve confiar em código de terceiros.
4. Nas configurações do Excalidraw, localize a pasta do Script Engine. Use uma subpasta do cofre; a raiz não serve como pasta de scripts segundo a documentação oficial. Os nomes exatos das opções podem variar conforme versão/idioma.
5. Para este par de scripts, confira **Obsidian 1.11.5+ e SecretStorage nativo compatível**, além do Excalidraw com Script Engine e renderização matemática. Não há número mínimo único do Excalidraw estabelecido por esta entrega: verifique as capacidades exigidas no dispositivo.

## Copiar e abrir

Após a escolha da versão e o backup, extraia somente os arquivos instaláveis aprovados. Copie para a pasta configurada:

- Converter-contas.md
- Converter-contas.svg
- Assistente de Resolução.md
- Assistente de Resolução.svg

Mantenha os pares e nomes exatos; não misture versões. Não copie relatórios, fontes, patches, continuidade ou checkpoints para essa pasta. Não coloque estes .md na pasta .obsidian/plugins.

Feche os scripts e reinicie Obsidian após a troca para limpar registros em memória. Abra um desenho Excalidraw e use a paleta de comandos para localizar os scripts; atribua atalhos se desejar. Não execute por abertura automática durante o teste inicial.

## Teste inicial sem API

Abra o Converter e confira o layout. Abra o Assistente no mesmo desenho; use colagem de LaTeX ou expressão de teste já disponível, sem reconhecimento remoto. Teste seleção, lupa, comparação e cancelamento. Confirme que cancelar mantém o original. Teste a transferência opcional somente depois de revisar e autorizar o contexto. Falha de importação nativa exige verificar capacidades ou usar colagem; não é prova de incompatibilidade total.

Windows/Monitor e Samsung/Android horizontal são os alvos citados na documentação local. Mobile, teclado, S Pen e MathJax exigem teste físico; não se promete compatibilidade universal nem paridade vertical. Registre as versões reais e o primeiro desvio no canal de feedback que o responsável disponibilizar; não compartilhe credenciais.

## Gemini

Não é necessário cadastrar chave para o teste local. Reconhecimento por Gemini e conversa enviam conteúdo ao Google e podem consumir cota/custos. Nunca distribua chaves junto aos scripts nem as registre em feedback. A configuração por dispositivo e armazenamento protegido devem seguir a entrega escolhida, sem substituir proteção por notas sincronizadas. Elegibilidade não é concedida pelo cadastro de uma chave. Antes de qualquer disponibilização com IA, leia os termos e resolva a adequação de público/finalidade/região. Não anuncie uso irrestrito por estudantes.

## Atualização, remoção e recuperação

Atualização manual: preserve a cópia anterior, substitua o conjunto aprovado completo e reinicie. Se falhar, feche os scripts, retire os arquivos novos da pasta ativa, restaure os quatro arquivos da cópia anterior e reinicie. Confirme hash/versão e teste sem API. Remover os quatro arquivos retira os scripts; não apague desenhos ou dados do cofre para desinstalar. Credenciais devem ser removidas pelo mecanismo da própria entrega, quando necessário.

## Fontes

- [Script Engine e pasta de scripts](https://github.com/zsviczian/obsidian-excalidraw-plugin/blob/master/docs/ExcalidrawScriptsEngine.md)
- [Termos Gemini API](https://ai.google.dev/gemini-api/terms)
- [Regiões elegíveis](https://ai.google.dev/gemini-api/docs/available-regions)

Documento montado a partir das instruções fornecidas em 21/10/2026. A integridade dos links/imagens do pacote documental foi conferida; isso não é teste físico de instalação no dispositivo de um novo estudante.
