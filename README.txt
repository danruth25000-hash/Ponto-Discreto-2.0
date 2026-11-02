PONTO DISCRETO — VERSÃO 2.0 (PROJETO-FONTE)

Incluído:
- Captura da última posição GPS via Android Location Services, com permissão em tempo de execução.
- Registro offline de ponto de pesquisa com nome, coordenadas, código de amostra e observações.
- Caderno local de campo persistido no armazenamento privado do app.
- Catálogo de camadas: geologia, recursos minerais, processos ANM, bloqueios, reservas garimpeiras,
  hidrografia, solos, relevo, limites/áreas institucionais.
- Atalhos para fontes oficiais SGB, SEPLAN/RR e ANM.
- Fluxo GitHub Actions para compilar APK debug.

LIMITAÇÕES IMPORTANTES:
- Este pacote é código-fonte, não um APK já compilado.
- Este ambiente não dispõe de Android SDK/Gradle para gerar o instalador.
- Esta versão ainda NÃO incorpora mapas offline no app, nem visualizador GIS, desenho de polígonos,
  download/sincronização de camadas ou análise automática de potencial aurífero.
- O GPS pode fornecer posição sem internet, mas não substitui mapas offline previamente baixados.
- Camadas de satélite exigem cache/pacote offline e respeitam licenças dos provedores.
- Não usa localização em segundo plano; captura somente quando o usuário toca no botão.

FONTES OFICIAIS:
SGB GeoSGB: https://geosgb.sgb.gov.br/downloads/
SEPLAN/RR Mapoteca: https://seplan.rr.gov.br/mapoteca/
ANM dados abertos: https://dadosabertos.anm.gov.br/SIGMINE/PROCESSOS_MINERARIOS/RR.zip
ANM bases: https://www.gov.br/anm/pt-br/acesso-a-informacao/dados-abertos/bases-de-dados

GERAR APK:
1. Extraia o ZIP e abra a pasta no Android Studio.
2. Sincronize o Gradle.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
OU
1. Envie os arquivos para um repositório GitHub.
2. Abra Actions e execute "Build Ponto Discreto APK".
3. Baixe o artefato PontoDiscreto-RR-v2-debug.
4. Instale o APK no Android (pode ser necessário autorizar instalação dessa origem).

AVISO DE CAMPO E LEGALIDADE:
Camadas geológicas indicam contexto e potencial, não confirmam presença de ouro.
Consulte situação minerária e restrições ambientais/territoriais antes de qualquer visita,
coleta ou intervenção. Respeite propriedades privadas, unidades de conservação e terras indígenas.
