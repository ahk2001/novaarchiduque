# 📂 DOSSIÊ ESTRATÉGICO: Nova Autoescuela Archiduque

> **Fonte única de verdade** compilada por varredura forense de arquivos locais (`dados.txt`, `assets/`), site oficial (`https://autoescuelaarchiduque.es/`), ficha do Google Maps, registros da DGT e diretórios públicos espanhóis. Todos os dados sem confirmação pública verificável estão marcados com `[A CONFIRMAR COM O CLIENTE]`.

---

## 1. 🏢 DADOS INSTITUCIONAIS & CONTATO

| Campo | Informação Verificada |
| :--- | :--- |
| **Nome Comercial** | **Nova Autoescuela Archiduque** *(também referida como `Autoescuela Archiduque` e `Nova Archiduque`)* |
| **Razão Social (Titular)** | **Proyectos Formativos Valencia S.L.** *(extraído de `/aviso-legal/`)* |
| **CIF / NIF** | **B40528085** |
| **Código DGT** | **V 1024** / **V 1024-01** *(segundo registros públicos DGT em `misfaltasdeconducir.com`)* |
| **CNAE** | **8553** — *Actividades de las escuelas de conducción y pilotaje* |
| **Slogan Principal (Castellano)** | *"Aprende a conducir en Valencia con Nova Autoescuela Archiduque"* / *"¡Tu éxito es nuestro éxito!"* / *"Estudia desde casa"* |
| **Telefone Fixo** | `[A CONFIRMAR COM O CLIENTE]` *(Não consta telefone fixo no `dados.txt` nem no site oficial. Em diretórios antigos ligados ao ponto anterior `Fernando Guillem` no mesmo endereço aparece `+34 963 57 36 12`, e em Páginas Amarillas consta `+34 961 07 72 36`; não publicar nenhum fixo sem confirmação do cliente.)* |
| **Telefone Móvel / WhatsApp** | **`+34 658 16 94 23`** *(móvel espanhol `6XX`, confirmado em `dados.txt`, `locations.kml` e no site oficial via `tel:658169423`)* |
| **Número Limpo para Código JS** | **`34658169423`** *(`[A CONFIRMAR COM O CLIENTE]` apenas se este móvel possui WhatsApp Business ativo para atendimento da secretaria, pois o site atual só usa link `tel:`)* |
| **E-mail Oficial** | `hola@autoescuelaarchiduque.es` |
| **Site Oficial Atual** | `https://autoescuelaarchiduque.es/` *(WordPress + Astra + Elementor, lançado em outubro de 2024 com apoio do programa Kit Digital / Unión Europea — NextGenerationEU)* |
| **Instagram** | `https://www.instagram.com/nova_archiduque/?__d=16d` (`@nova_archiduque`) |
| **Facebook** | `https://www.facebook.com/people/Nova-Autoescuela-Archiduque/61566866342203/` |
| **X (Twitter)** | `https://x.com/ArchiduqueNova` (`@ArchiduqueNova`, conta criada em outubro de 2024) |
| **Plataformas de Ensino (Área de Alunos)** | **Tests online:** `https://www.ponsgo.com/` \| **Aulas ao vivo:** `https://zoom.us/join` \| **Consulta de notas DGT:** Portal oficial DGT (`sedeapl.dgt.gob.es`) |

### Tom de Voz da Marca
- **Perfil comunicacional:** Próximo, jovem, motivador e acessível, combinado com clareza prática para o público profissional de transporte e logística.
- **Tratamento linguístico:** Utiliza *tuteo* direto em Espanhol da Espanha (*"adaptada a tus necesidades"*, *"¡Tu éxito es nuestro éxito!"*, *"Estudia desde casa"*), evitando formalismo excessivo, mas mantendo rigor documental nos blocos de requisitos e *Gestoría DGT*.

---

## 2. 🎨 IDENTIDADE VISUAL E DESIGN SYSTEM

### Paleta de Cores (HEX Exatos)
Valores extraídos diretamente do logotipo oficial (`assets/logo.png`, `assets/favicon.png`) e das folhas de estilo globais do site oficial (`post-9.css`, `post-10.css`, `post-19.css`, `post-61.css`):

| Papel no Design System | Cor (HEX) | Origem & Uso Recomendado |
| :--- | :--- | :--- |
| **Cor Primária (Marca)** | `#F60808` / `#F90607` | Vermelho vivo do kit global Elementor (`#F60808`) e do logotipo (`#F90607`). Usar em acentos da marca, badges, linhas de destaque e elementos de identidade visual. |
| **Cor Primária Escura (Hover / Contraste)** | `#C3071B` | Carmesim escuro presente em `post-10.css` e `post-19.css`. Ideal para estados hover, gradientes e fundos vermelhos com texto branco garantindo contraste WCAG AA. |
| **Cor Secundária (Cinza Institucional)** | `#54595F` / `#828181` | Cinza-chumbo do kit global (`#54595F`) e cinza médio da tipografia `"NOVA"` / `"AUTOESCUELA"` no logotipo (`#828181`). Usar em subtítulos, textos de apoio e ícones neutros. |
| **Cor de Conversão / Destaque (CTAs)** | `#00C853` *(Hover: `#03B048`)* | Verde vibrante utilizado nos botões e tabelas de conversão do site atual (`#00C853` / `#61CE70` no kit global). Excelente para botões de WhatsApp, envio do Formulário de Triagem e CTAs principais. |
| **Fundo Escuro / Texto Principal** | `#000000` / `#18181B` / `#3D3D3D` | Preto puro (`#000000`) usado no texto global e na fachada; grafite escuro (`#18181B` e `#3D3D3D`) recomendado para seções de contraste (Hero/Footer) e leitura confortável. |
| **Fundo Claro / Superfícies** | `#FFFFFF` / `#F9F9F9` / `#F8F3EF` | Branco puro (`#FFFFFF`) para base; `#F9F9F9` para cards de tarifas; `#F8F3EF` (areia suave) usado na barra de menu e separadores suaves. |

### Tipografia Recomendada
- **Títulos (Headings):** `Montserrat` (pesos `600`, `700`, `800`) — já utilizada como fonte dominante em todas as páginas principais do site atual (`post-10.css`, `post-19.css`, `post-61.css`).
- **Corpo de Texto (Body):** `Roboto` ou `Montserrat` (pesos `400`, `500`) — garante leitura ágil em tabelas de tarifas, requisitos da DGT e botões do formulário de triagem. *(Nota: o kit global também declara `Roboto Slab` como secundária, mas `Montserrat` + `Roboto` proporciona estética mais moderna e alinhada à fachada).*

### Mapeamento das Imagens em `assets/`

| Arquivo Local | Dimensões & Formato | Descrição Visual | Uso Recomendado & Observações de QA |
| :--- | :--- | :--- | :--- |
| `assets/logo.png` | `2048 × 516` px (RGBA transparente) | Logotipo horizontal oficial: arco vermelho + *"NOVA"* cinza + *"A"* vermelho compartilhado por *"ARCHIDUQUE"* (vermelho) e *"AUTOESCUELA"* (cinza). | **Header / Navbar e Footer.** Por ter letras em cinza médio (`#828181`) e vermelho (`#F90607`), exige fundo claro (`#FFFFFF` ou `#F8F3EF`) para legibilidade. |
| `assets/favicon.png` | `591 × 516` px (RGBA transparente) | Isotipo reduzido (*arco + "NOVA" + "A"*). | **Favicon (`<link rel="icon">`), Apple Touch Icon e avatar/selo compacto** no card do formulário de triagem. |
| `assets/homedesktop.png` | `1672 × 941` px (RGB) | Render conceitual em paisagem (16:9) de fachada moderna preta e vermelha de esquina, com vitrines temáticas (*Permiso A1, A2, A* e lista de cursos *B, A1, A2, A, CAP, Reciclaje*). | **⚠️ ALERTA CRÍTICO DE QA:** Imagem gerada por IA contendo **erro de ortografia visível** na testeira direita (*"NOVA AUTOESCUELA RACHIDUQUE"*) e textos distorcidos na vitrine esquerda. **NÃO publicar sem correção gráfica** ou substituição por fotografia real da fachada física (`[A CONFIRMAR COM O CLIENTE]`). |
| `assets/homemobile.png` | `1080 × 1920` px (RGB) | Render conceitual vertical (9:16) da mesma fachada com árvore à esquerda. | **⚠️ ALERTA CRÍTICO DE QA:** Contém o mesmo erro de grafia (*"NOVA AUTOESCUELA RACHIDUQUE"*) na testeira direita e grafia distorcida na vitrine esquerda. Corrigir ou substituir por foto real antes do lançamento. |

> **Lacuna de Ativos Visuais:** A pasta `assets/` não possui fotografias reais da fachada física, da frota (carros, motos, caminhões, ônibus), da sala de aula teórica nem dos professores. Solicitar ao cliente (`[A CONFIRMAR COM O CLIENTE]`) para elevar a confiança e evitar aparência genérica.

---

## 3. 📍 SEDE(S) FÍSICA(S), LOCALIZAÇÃO E HORÁRIOS

- **`MULTI_SEDE: NÃO`** *(Apenas **1 sede física de atendimento e aulas teóricas** em Valência. Importante: as aulas práticas de circuito cerrado para moto A e veículos pesados C/C+E/D são realizadas em pista externa em **Aldaia**).*

### Sede Única — Patraix / Archiduque Carlos (Valência)
- **Endereço Completo:** Calle de l'Arxiduc Carles (C/ del Archiduque Carlos), 111, Bajo, 46014 València, Valencia, España *(Bairro de Patraix / zona Tres Forques)*.
- **Coordenadas Geográficas:** `39.4608423, -0.3991411`
- **Link Direto do Google Maps (Oficial de `dados.txt`):**
  [Abrir ficha Nova Archiduque no Google Maps](https://www.google.com/maps/place/Nova+Archiduque/@39.4631802,-0.4275334,14z/data=!4m10!1m2!2m1!1sautoescuela!3m6!1s0xd604f8acf9aea73:0x6f55257b75124fc3!8m2!3d39.4608423!4d-0.3991411!15sCgthdXRvZXNjdWVsYVoNIgthdXRvZXNjdWVsYZIBDmRyaXZpbmdfc2Nob29smgEkQ2hkRFNVaE5NRzluUzBWSlEwRm5TVVJmYlhadVFqQm5SUkFC4AEA-gEECAAQPA!16s%2Fg%2F11h6qdmxj2?entry=ttu&g_ep=EgoyMDI2MTEyMy4wIKXMDSoASAFQAw%3D%3D)
- **Link Direto por CID (para botões e código):** `https://maps.google.com/?cid=8022359523405746115`
- **Link Curto Oficial (`maps.app.goo.gl`):** `[A CONFIRMAR COM O CLIENTE]`

### Horários Oficiais de Atendimento Presencial (Secretaria)
*(Extraídos dos registros públicos no diretório `Autoescuelas Top` e `Waze`; o site atual não exibe horários na página de Contato — validar eventuais ajustes sazonais `[A CONFIRMAR COM O CLIENTE]`)*:

| Dia da Semana | Manhã | Tarde |
| :--- | :--- | :--- |
| **Lunes a Jueves** | 09:30 – 13:30 | 16:30 – 20:30 |
| **Viernes** | 09:30 – 13:30 | 16:30 – 20:00 |
| **Sábados y Domingos** | Cerrado | Cerrado |

*(Detalhe operacional extraído do site para o Permiso A: teórica presencial geralmente às sextas-feiras das `18:00` às `21:00`, e práticas de circuito/circulação de segunda a sexta no turno da manhã).*

---

## 4. 🚗 CATÁLOGO EXAUSTIVO DE SERVIÇOS E CURSOS

### 4.1. Permisos Particulares
- **Permiso B (Coche):**
  - **Modalidade confirmada:** **Manual** (o site descreve expressamente *"el uso de las luces, intermitentes, y el cambio de marchas"*).
  - **Câmbio Automático:** Não mencionado em nenhuma página do site. `[A CONFIRMAR COM O CLIENTE]` se oferecem aulas/exame com coche automático.
  - **Diferenciais locais:** Preparação prática nas zonas reais de exame da DGT em Valência (**Malilla, La Plata, El Saler**), aula virtual com testes online (`PonsGO`) e aulas teóricas online via `Zoom` + presenciais, além de modalidade de **cursos intensivos**.
- **Permisos de Moto (AM, A1, A2, A):**
  - **Permiso AM** (Ciclomotor hasta 50 cc, mínimo 15 años).
  - **Permiso A1** (Motocicletas hasta 125 cc / 11 kW, mínimo 16 años — opção **manual ou automática**).
  - **Permiso A2** (Motocicletas hasta 35 kW, mínimo 18 años — opção **manual ou automática**).
  - **Permiso A** (Motocicletas de gran cilindrada, mínimo 20 años + 2 años de A2 — curso de formación sin examen en 2 días).
  - **Pista de treino:** **NÃO possui pista própria na sede de Archiduque Carlos.** O site confirma que as práticas de circuito cerrado (`c/c`) do Permiso A realizam-se em **Aldaia** (com rota de circulação de Aldaia até Dos Aguas). Em avaliação pública de aluno sobre o A2 também consta que práticas de circuito foram realizadas mediante parceria em pista externa (zona Paterna/Moncada). `[A CONFIRMAR COM O CLIENTE]` onde são realizadas atualmente as práticas de circuito cerrado de AM/A1/A2 para informar com clareza no site.
- **Clases de Reciclaje / Perfeccionamiento:**
  - **Confirmado:** O site promove explicitamente na página inicial e no blog *"prácticas de perfeccionamiento en Valencia"* para condutores já habilitados que desejam perder o medo ou ganhar fluidez no trânsito.

### 4.2. Cursos Oficiais DGT (Recuperación de Puntos)
- **Recuperación de Puntos (12h parcial / 24h pérdida de vigencia):** **NÃO consta** no site oficial nem em listagens de centros autorizados encontrados na pesquisa. `[A CONFIRMAR COM O CLIENTE]` — não incluir no site nem no formulário de triagem sem confirmação formal de homologação DGT.

### 4.3. Permisos Profesionales, Transporte & Formação Laboral
- **Permiso C (Camión):** Teórico específico + maniobras en circuito cerrado (**en Aldaia**) + circulación. *(Nota: há um artigo de blog sobre Carnet C1, porém não há página dedicada nem tarifa de C1 — `[A CONFIRMAR COM O CLIENTE]`).*
- **Permiso C+E (Tráiler):** Conjuntos de camión y remolque pesado; circuito cerrado en **Aldaia**.
- **Permiso D (Autobús):** Vehículos de más de 9 plazas; circuito cerrado en **Aldaia**.
- **Cursos CAP (Certificado de Aptitud Profesional):**
  - **CAP Inicial (140 horas):** Mercancías o Viajeros.
  - **CAP Formación Continua (35 horas):** Renovación cada 5 años, sin examen.
- **Outros Cursos Profissionais / Laborales listados no site:**
  - **Curso de Carretillero** (operador de carretillas elevadoras).
  - **Trámite de Renovación de Tarjeta de Tacógrafo** (tacógrafo digital).
  - **Curso de Manipulador de Alimentos**.
  - **Curso de Marino Pescador** (presente em `/cursos-de-formacion-valencia/` e `/mis_cursos/`).
  - **Curso de Operador de Plataformas Elevadoras** (publicado no blog em dez/2024; confirmar se possui convocatorias abertas `[A CONFIRMAR COM O CLIENTE]`).
- **ADR (Mercancías Peligrosas):** **NÃO consta** no catálogo oficial do site. `[A CONFIRMAR COM O CLIENTE]`.

### 4.4. Gestoría Administrativa DGT *(Diferencial de Serviços)*
- Canje de permiso de conducir (nacional, internacional y europeo).
- Cambio de titularidad / Transferencias de vehículos.
- Altas y bajas temporales de vehículos.
- Matriculación de coches y motos.
- Duplicados de permisos (pérdida, robo o cambio de datos) y documentación técnica.
- Informes de tráfico, notificaciones de venta y liquidaciones de reserva de dominio.

### 4.5. Credenciamentos (LABORA / FUNDAE)
- **Centro LABORA / Cursos Bonificados FUNDAE:** **Não mencionado** em nenhuma página do site oficial. `[A CONFIRMAR COM O CLIENTE]`.
- *(Observação técnica: os selos da União Europeia / Plan de Recuperación encontrados no rodapé do site atual referem-se à subvenção do programa **Kit Digital** aplicada ao desenvolvimento do site pela agência Tandem Marketing Digital, e não a formação subvencionada para alunos).*

---

## 5. 💰 ESTRUTURA COMERCIAL E TARIFAS

Todas as tarifas abaixo foram extraídas literalmente da página `/precios/` e das fichas individuais de cada permiso em `autoescuelaarchiduque.es`:

| Curso / Permiso | Pack / Matrícula Publicada | O que Inclui no Pack | Práticas Avulsas / Bonos | Taxas DGT & Exames Publicados |
| :--- | :--- | :--- | :--- | :--- |
| **Permiso B (Coche)** | **450 €** | Matrícula, libro, aula virtual 2 meses, teórica 2 meses, trámite de expediente, traslado al 1.er examen teórico y **10 prácticas (45 min)** | Práctica 45 min: **33 €**<br>Bono 6 prácticas: **192 €**<br>Bono 10 prácticas: **310 €** | Tasa de tráfico y gestión: **97,40 €**<br>Examen práctico: **38 €** |
| **Permiso AM (Ciclomotor)** | **141,18 €** *(IVA incl.)* | Matrícula, clase teórica, libro y clave acceso a test online | Prácticas (30 min): **35 €** *(IVA incl.)* | Tasa examen: **97,40 €**<br>Examen práctico: **35 €** *(em `/precios/`)* / **30 €** *(na página do AM — ver nota)* |
| **Permiso A1 (Moto 125)** | **225,68 €** | Matrícula, curso teórico A1 y B, clave de tests online | Circuito cerrado (30 min): **35 €** *(IVA incl.)*<br>Circulación (60 min): **75 €** *(IVA incl.)* | Tasa examen: **97,32 €**<br>Examen cerrado: **35 €** *(em `/precios/`)* / **30 €** *(na página do A1)*<br>Examen circulación: **75 €** |
| **Permiso A2 (Moto)** | **74,63 €** | Matrícula y clave acceso a test online *(Libro A2 opcional: **10 €**)* | Circuito cerrado (30 min): **35 €** *(IVA incl.)*<br>Circulación (60 min): **75 €** *(IVA incl.)* | Tasa examen: **97,32 €**<br>Examen cerrado: **35 €** *(em `/precios/`)* / **30 €** *(na página do A2)*<br>Examen circulación: **75 €** |
| **Permiso A (Moto grande)** | **350 €** | Matrícula, 3h de teoría, libro, 4h circuito cerrado + 2h circulación *(tasa expediente incluida: 28,87 €)* | Incluídas no curso fechado *(Aldaia – Dos Aguas)* | Tasa expediente incluida **(28,87 €)** |
| **Permiso C (Camión)** | **850 €** *(Precio fijo)*<br>*(Ou separado: Matrícula 150 € + Teórica/libros 100 €)* | Matrícula, teórica, libro, **10 prácticas (60 min)**, 1 examen C/C y 1 examen C/A | Prácticas adicionales (60 min): **70 €**<br>Renovaciones: **180 €** | Tasa exp.: **97,32 €**<br>*(Separado: examen C/C y C/A 70 €)* |
| **Permiso C+E (Tráiler)** | **950 €** *(Precio fijo)*<br>*(Ou separado: Matrícula 150 € + Teórica/libros 100 €)* | Matrícula, teórica, libro, **10 prácticas (60 min)**, 1 examen C/C y 1 examen C/A | Prácticas adicionales (60 min): **80 €**<br>Renovación: **180 €** | Tasa exp.: **97,32 €**<br>*(Nota: na lista separada de C+E no site aparece 70 €)* |
| **Permiso D (Autobús)** | **950 €** *(Precio fijo)*<br>*(Ou separado: Matrícula 150 € + Teórica/libros 100 €)* | Matrícula, teórica, libro, **10 prácticas**, 1 examen C/C y 1 examen C/A | Prácticas adicionales: **80 €**<br>Renovación: **180 €** | Tasa exp.: **97,32 €**<br>*(Separado: examen C/C y C/A 80 €)* |
| **CAP Inicial (140h)** | **1.100 €** *(pág. C / C+E)*<br>**1.300 €** *(pág. D)* | Curso 140h Mercancías o Viajeros | — | + Tasa examen + Tasa tarjeta:<br>**1.146,07 €** *(em C/C+E)* / **1.346,07 €** *(em D)* |
| **CAP Continua (35h)** | **250 €** | Formación continua 35h *(sin examen)* | — | + Tasa tarjeta = **281,88 €** |
| **Carretillero / Tacógrafo / Manipulador / Marino Pescador / Gestoría / Perfeccionamiento** | **A consultar** | Valores não publicados online | — | A consultar segundo trâmite ou turma |

> **⚠️ Inconsistências de Preços no Site Atual (`[A CONFIRMAR COM O CLIENTE]` antes do deploy):**
> 1. O site exibe valores diferentes para a taxa de exame em circuito fechado de **AM/A1/A2** (`35 €` na página `/precios/` vs `30 €` nas páginas individuais dos cursos) e para o **CAP Inicial** (`1.146,07 €` nas páginas de C/C+E vs `1.346,07 €` na página de D).
> 2. A taxa oficial de exame da DGT publicada no site (`97,32 €` / `97,40 €`) está acima da taxa oficial atual da DGT na Espanha (ex. `94,05 €`), sugerindo possível inclusão de taxa de gestão administrativa ou tabela desatualizada. Confirmar tabela vigente com o cliente.
> 3. **Modalidades de pagamento:** O site cita *"precios especiales y facilidades de pago"*, sem detalhar aceitação de Bizum, cartão ou parcelamento (`[A CONFIRMAR COM O CLIENTE]`).

---

## 6. ⭐ PROVA SOCIAL, REPUTAÇÃO E DEPOIMENTOS

### Métricas Verificadas
- **Google Maps (`Nova Archiduque`):** Os resultados indexados do Google indicam média em torno de **`4,4 / 5` com cerca de 39 avaliações** *(não foi possível extrair os textos individuais mais recentes direto do Google Maps sem navegador automatizado devido à barreira GDPR do Google; confirmar contagem e nota exata do dia `[A CONFIRMAR COM O CLIENTE]`)*.
- **Portal *Autoescuelas Top* (`30516-autoescuela-archiduque`):** Registra **`4,1 / 5` (17 avaliações)**, composto por **`4,3 / 5` em 16 avaliações importadas do Google** + 1 avaliação direta no portal.
- **Taxa oficial de aprovados DGT (Permiso B Práctico — Código `V 1024-01`):** **`41,05%`** acumulados (*39 aptos de 95 exámenes*, segundo dados DGT compilados em `misfaltasdeconducir.com`), em linha com a média urbana de Valência.

### Instrutores e Professores Citados pelos Alunos
- **Óscar** — Elogiado nominalmente pelas aulas práticas de circuito fechado e circulação aberta de **Moto A2**.
- **"Una profesora increíble"** — Elogiada por aluno do Permiso B pela qualidade humana e didática (nome próprio não citado na avaliação pública).
- Demais docentes e secretaria: `[A CONFIRMAR COM O CLIENTE]` *(não constam nomes públicos no site nem nos diretórios).*

### Depoimentos Reais Transcritos (Espanhol da Espanha)

Os 3 depoimentos positivos abaixo foram recuperados literalmente da ficha pública (`autoescuelastop.com.es`, seção *"Las opiniones más recientes en Google"*), além de 1 trecho real de elogio docente e dos alertas críticos históricos documentados para blindagem estratégica:

1. **Cris** *(Google — Permiso A2 / Instrutor Óscar)*:
   > *"He obtenido el A2 aquí, en una semana el teórico aprobado y las prácticas de circuito cerrado y abierto con Oscar son la mejor experiencia del carnet. Muy contento, dentro de poco el A también lo sacaré aquí!"*

2. **GRI** *(Google — Curso CAP Promoción Viajeros)*:
   > *"Hice aquí el curso de formación CAP promoción viajeros y superé el examen a la primera con 25 de 25 puntos! Recientemente ha llegado mi tarjeta cap nueva con ampliación de viajeros. También esta AE tienen precios más bajos. Muy recomendable para aquellas personas quien quiere obtener CAP. Gracias."*

3. **Eduardo Martinez** *(Google — Atención general)*:
   > *"Muy buena autoescuela, con una atención cercana y agradable."*

4. **Depoimento complementar a obter (`[A CONFIRMAR COM O CLIENTE]`):**
   *(Em avaliação crítica de há ~2 anos, **Adrian Campos Tomas** elogia nominalmente uma docente — `"lo único positivo que me llevo de esta autoescuela es tener el carnet y a ver conocido una profesora INCREIBLE"` — mas o texto completo contém reclamações graves contra a administração anterior, não devendo ir para a vitrine. Recomenda-se solicitar ao cliente 1 a 3 depoimentos positivos recentes pós-outubro/2024 do painel Google Business Profile — quando assumiu a marca **Nova Archiduque** — para completar 4 a 6 cards públicos 100% favoráveis e atuais).*

### 🔍 Auditoria de Reputação (Pontos de Atenção para Copy & Triagem)
As críticas públicas encontradas no histórico ajudam a desenhar um site muito mais honesto e com menor atrito na secretaria:
1. **Gestão administrativa & horários (Adrian Campos Tomas, ~2 anos atrás):** Reclamações sobre desorganização passada na secretaria e atrito de horários — **Solução no novo site:** O **Formulário de Triagem Inteligente** já entrega à secretaria o interesse, situação e faixa de horário preferida organizados antes mesmo da primeira resposta.
2. **Transparência sobre pista externa de motos (Sergio C.M., ~3 anos atrás):** Aluno reclamou de não ter sido avisado na matrícula que as práticas do A2 aconteciam fora da capital (em pista externa / parceria) — **Solução no novo site:** Deixar claro na página/FAQ que a sede atende teoria e gestão em Patraix e que o circuito cerrado de motos/pesados acontece em pista externa (Aldaia), transformando um possível ruído em transparência de matrícula.
3. **Renovação de tarjeta de tacógrafo / conductor (Juan Manuel Moscardó Puchades, 07/08/2025):** Crítica recente (`1/5` no portal Autoescuelas Top) sobre demora/experiência na renovação da tarjeta — **Solução:** Alinhar prazos claros de tramitação na resposta automática/manual da secretaria para quem selecionar renovação de tacógrafo.

---

## 7. ⚙️ CONFIGURAÇÃO PRONTA DO FORMULÁRIO DE TRIAGEM INTELIGENTE (WHATSAPP)

> **Regra de Arquitetura:** Todos os botões de WhatsApp e CTAs de matrícula/informação do site devem acionar ou rolar suavemente até o **Formulário de Triagem Inteligente** (com pré-seleção automática via atributo `data-curso` quando disparado a partir de um card de serviço). Não utilizar links `wa.me` diretos soltos fora do formulário.

- **Número de destino no código JS:** `34658169423` *(validar com cliente se este móvel está com WhatsApp ativo `[A CONFIRMAR COM O CLIENTE]`)*
- **`MULTI_SEDE`:** `NÃO` *(omitir seleção de sede)*

### Passo 1 — Opções de Permisos / Cursos (Chips clicáveis em Castellano)
Lista restrita estritamente aos serviços reais confirmados da Nova Autoescuela Archiduque:

| Texto do Chip (UI em Castellano) | `data-curso` (para pré-seleção) | Observação |
| :--- | :--- | :--- |
| `Permiso B (Coche)` | `permiso-b` | Não especificar "(Automático)" salvo confirmação do cliente |
| `Moto (AM / A1 / A2 / A)` | `motos` | Mapeia os cards de AM, A1, A2 e A (ou usar sub-chips `Permiso AM`, `Permiso A1`, `Permiso A2`, `Permiso A`) |
| `Camión / Tráiler / Autobús (C / C+E / D)` | `profesionales` | Cobre C, C+E e D |
| `Cursos CAP (Inicial / Continua)` | `cap` | 140h Inicial e 35h Continua |
| `Carretillero / Tacógrafo / Otros cursos` | `formacion-laboral` | Inclui Carretillero, Tacógrafo, Manipulador, Marino Pescador |
| `Prácticas de perfeccionamiento` | `reciclaje` | Confirmado no site oficial |
| `Gestoría DGT (Canjes / Trámites)` | `gestoria` | Serviço forte de canjes, transferências e baixas |

*(Nota: **NÃO** incluir `Recuperación de Puntos` nem `ADR` nem `Permiso B Automático`, pois não constam nos registros da autoescola).*

### Passo 2 — Opções de Situação Atual do Aluno (Chips clicáveis em Castellano)
- `"Empiezo desde cero (teórico + práctico)"`
- `"Ya tengo el teórico aprobado (solo prácticas)"`
- `"Ya tengo carnet (perfeccionamiento / ampliar permiso)"`
- `"Curso CAP / Renovación tarjeta / Formación laboral"`
- `"Trámite de Gestoría DGT (canje, transferencia, duplicado)"`

### Passo 3 — Disponibilidade Horária e Sede (Chips clicáveis em Castellano)
- **Horários coerentes com o expediente real (`09:30–13:30` e `16:30–20:30` seg-qui / `20:00` sex):**
  - `"Mañanas (09:30 - 13:30)"`
  - `"Tardes (16:30 - 20:30)"`
  - `"Indiferente"`
- **Seleção de Sede:** **OMITIR** (`MULTI_SEDE: NÃO`).

### Template Final da Mensagem Gerada para o WhatsApp (em Castellano)

```text
Hola, vengo de la web de Nova Autoescuela Archiduque.
- Interés: {{curso}}
- Situación: {{situacion}}
- Horario preferido: {{horario}}
- Nombre: {{nombre}} (incluir linha apenas se preenchido)
¿Podríais indicarme disponibilidad y tarifas?
```

**Exemplo de snippet JS pronto para o cálculo da URL (`encodeURIComponent`):**

```javascript
const WHATSAPP_NUMBER = "34658169423";
let lines = [
  "Hola, vengo de la web de Nova Autoescuela Archiduque.",
  `- Interés: ${curso}`,
  `- Situación: ${situacion}`,
  `- Horario preferido: ${horario}`
];
if (nombre && nombre.trim() !== "") {
  lines.push(`- Nombre: ${nombre.trim()}`);
}
lines.push("¿Podríais indicarme disponibilidad y tarifas?");

const whatsappUrl = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(lines.join("\n"))}`;
```

---

## 8. ❓ FAQ PRONTO PARA FILTRAR DÚVIDAS BÁSICAS (EM CASTELLANO)

1. **¿Dónde está la autoescuela y cuál es el horario de secretaría?**
   > Estamos en **C/ de l'Arxiduc Carles, 111 (Patraix, 46014 València)**. Atendemos de **lunes a jueves de 09:30 a 13:30 h y de 16:30 a 20:30 h**, y los **viernes de 09:30 a 13:30 h y de 16:30 a 20:00 h** (sábados y domingos cerrado).

2. **¿Cómo empiezo el Permiso B y qué incluye la matrícula?**
   > Puedes solicitar plaza desde nuestro formulario de WhatsApp o pasarte por secretaría. El **pack del Permiso B (450 €)** incluye matrícula, libro, 2 meses de teórica y aula virtual (`PonsGO`), clases online por videoconferencia (`Zoom`), trámite de expediente, traslado al primer examen teórico y **10 prácticas de 45 minutos** en zonas reales de examen en Valencia (Malilla, La Plata, El Saler). *(Las tasas oficiales de la DGT y clases adicionales se detallan aparte).*

3. **¿Ofrecéis clases teóricas online y cómo funcionan las prácticas de moto y camión?**
   > Sí, puedes estudiar la teórica desde casa mediante nuestra plataforma de test online y clases en directo por videoconferencia, combinadas con atención presencial. Para los permisos que requieren **circuito cerrado** (Permiso A y vehículos pesados C, C+E y D), las prácticas de pista se realizan en **Aldaia**, con salida y coordinación desde nuestra autoescuela. *(Si buscas el A1 o A2, te indicaremos los horarios disponibles antes de matricularte).*

4. **¿Qué documentación necesito para abrir mi expediente ante la DGT?**
   > Necesitarás tu **DNI o NIE en vigor** (y residencia en España), una fotografía reciente tamaño carné y superar un **reconocimiento médico psicotécnico** en un centro autorizado (te orientamos sobre los pasos antes de presentar el expediente en Tráfico).

5. **¿Impartís cursos CAP y renovación de tarjeta de tacógrafo?**
   > Sí. Contamos con **CAP Inicial (140 h)** de mercancías o viajeros y **CAP Formación Continua (35 h, sin examen)** para renovar tu certificación cada 5 años, además de la gestión de **renovación de la tarjeta de tacógrafo**, cursos de **carretillero** y **manipulador de alimentos**. Escríbenos por el formulario para consultar próximas fechas de convocatoria.

6. **¿Puedo hacer un canje de carnet o una transferencia de vehículo con vosotros?**
   > Sí, disponemos de servicio propio de **Gestoría Administrativa DGT** en Valencia: gestionamos **canjes de permisos** nacionales, europeos e internacionales, cambios de titularidad, matriculaciones, bajas temporales, duplicados por pérdida o robo e informes de tráfico, sin que tengas que pedir cita ni hacer colas en la Jefatura.

---

## 9. 📐 DIRETRIZES RECOMENDADAS PARA A CRIAÇÃO DO SITE

### Proposta Única de Valor (UVP) em Patraix / Valência
> **"Tu centro integral de formación vial y gestoría DGT en Patraix (Valencia): desde el carnet de coche y moto con teórica online desde casa hasta permisos profesionales (C, C+E, D), cursos CAP y trámites DGT sin colas — todo con precios transparentes desde el primer día."**

### Arquitetura e Ordem Recomendada de Seções na Página Inicial
1. **Header Fixo (Fundo `#FFFFFF` / `#F8F3EF`):** Logotipo oficial (`assets/logo.png`), links âncora curtos (*Permisos, Profesionales y CAP, Precios, Gestoría, Preguntas frecuentes*), badge discreto de horário e botão CTA verde (`#00C853`) apontando para `#triagem-whatsapp`.
2. **Hero Section (Forte impacto local):**
   - Headline em Castellano focada em Valência/Patraix e clareza de atendimento.
   - Subheadline destacando estudo em casa (`PonsGO + Zoom`) + prácticas nas zonas de exame (Malilla, La Plata, El Saler) + transparência de preços.
   - CTA primário levando ao **Formulário de Triagem** + CTA secundário *"Ver tarifas y packs"*.
   - *(Visual: NÃO usar `homedesktop.png` sem corrigir o typo "RACHIDUQUE" — usar foto real ou composição limpa em CSS/ícones até o cliente enviar fotos reais).*
3. **Seção "Elige tu permiso" (Permisos Particulares com `data-curso` + Preços Transparentes):**
   - Cards para **Permiso B (450 €)**, **Permiso A1 (225,68 €)**, **Permiso A2 (74,63 €)**, **Permiso A (350 €)**, **Permiso AM (141,18 €)** e **Prácticas de Perfeccionamiento**.
   - Cada card mostra o que inclui, o valor claro e um botão *"Consultar disponibilidad"* que pré-seleciona o `data-curso` e leva ao Formulário de Triagem.
4. **Seção "Formación Profesional, CAP y Empleo" (Diferencial B2B/B2C de alto ticket):**
   - Cards para **Camión C (850 €)**, **Tráiler C+E (950 €)**, **Autobús D (950 €)**, **CAP Inicial (140h)**, **CAP Continua (35h — 250 € + tasa)** e cursos rápidos (**Carretillero, Tacógrafo, Manipulador de Alimentos, Marino Pescador**).
   - Nota de transparência visível sobre as práticas em circuito cerrado em **Aldaia**.
5. **Seção "Gestoría Administrativa DGT sin esperas":**
   - Bloco dedicado aos trâmites de **Canje de permisos**, **Transferencias**, **Bajas temporales** e **Duplicados** — captura demanda de quem já dirige e gera receita recorrente à secretaria.
6. **Seção "Estudia a tu ritmo" (Área de Alumnos):**
   - Destaque visual para o ecossistema digital (`Tests online PonsGO`, `Clases en directo por Zoom`, `Consulta de nota DGT`).
7. **Seção "Opiniones reales de nuestros alumnos" (Prova Social):**
   - Exibir o selo do Google Maps, o destaque ao instrutor **Óscar** (motos) e ao alto índice de aprovação nos cursos **CAP**, exibindo os 3 depoimentos reais verificados + espaço para mais avaliações recentes validadas com o cliente.
8. **Seção Principal de Conversão — Formulário de Triagem Inteligente (`#triagem-whatsapp`):**
   - Passo 1 (Curso/Permiso) → Passo 2 (Situação Atual) → Passo 3 (Horário Preferido) → Nome (opcional) → Preview ao vivo da mensagem → Botão verde `#00C853` *"Enviar consulta por WhatsApp"*.
9. **Seção Localização, Mapa & FAQ:**
   - Mapa incorporado da C/ de l'Arxiduc Carles, 111 (`39.4608423, -0.3991411`), tabela limpa de horários presenciais (L-J / V / Fines de semana) e acordeão com as 6 perguntas frequentes em Castellano.
10. **Footer Legal (LSSICE / RGPD Espanha):**
    - Dados obrigatórios: *Proyectos Formativos Valencia S.L. — CIF: B40528085 — C/ de l'Arxiduc Carles, 111, Patraix, 46014 València — hola@autoescuelaarchiduque.es — +34 658 16 94 23*, além de links para *Aviso Legal, Política de Privacidad, Política de Cookies* e redes sociais (Instagram, Facebook, X).

---

### 📋 Checklist de Pendências (`[A CONFIRMAR COM O CLIENTE]`)
Antes de publicar a versão final do site, confirmar com os responsáveis da **Nova Autoescuela Archiduque**:
1. **WhatsApp ativo:** Confirmar se o número móvel `+34 658 16 94 23` atende WhatsApp Business diariamente e se há algum telefone fixo oficial para exibir ao lado.
2. **Tabela de Preços & Divergências do site atual:**
   - Confirmar valor exato do exame em circuito cerrado de AM/A1/A2 (`30 €` vs `35 €`).
   - Confirmar valor atualizado do **CAP Inicial** (`1.146,07 €` vs `1.346,07 €`).
   - Confirmar taxa oficial da DGT vigente (`97,40 €` / `97,32 €` no site atual vs `94,05 €` oficial vigente) e formas de pagamento aceitas (Bizum, cartão, parcelamento).
3. **Serviços não confirmados no site:**
   - Oferecem **Permiso B Automático**?
   - Oferecem **Permiso C1** (citado em artigo de blog, ausente nas tarifas)?
   - Oferecem cursos **ADR**, **Recuperación de Puntos DGT** ou formação bonificada **FUNDAE / LABORA**?
   - O curso de **Operador de Plataformas Elevadoras** (publicado no blog) tem turmas ativas?
4. **Logística de Motos (A1 / A2):** Confirmar o local exato onde se realizam as práticas de circuito cerrado de A1/A2 (se em Aldaia como o Permiso A, ou outro circuito) para alinhar a expectativa do aluno.
5. **Horários e Link Curto do Maps:** Confirmar se o expediente (`09:30–13:30` e `16:30–20:30` seg-qui; até `20:00` sexta) permanece igual no período atual e obter o link curto `maps.app.goo.gl`.
6. **Fotos reais & Mais depoimentos:** Solicitar fotografias reais da fachada atual (em substituição aos renders `homedesktop.png` / `homemobile.png` com typo), frota de carros/motos/caminhões, equipe e mais 2–3 avaliações recentes do Google Maps (pós-outubro 2024).
