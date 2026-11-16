# 📂 DOSSIÊ ESTRATÉGICO: AUTOESCOLA TARADELL

> **Documento-fonte oficial para o desenvolvimento do novo site de alta conversão.**  
> **Metodologia:** Varredura local (`dados.txt`, `assets/`), extração direta do site oficial (`autoescolataradell.cat`) e pesquisa de registros públicos (eInforma, diretórios locais, DGT).  
> **Regra de Factualidade:** Todos os dados não confirmados publicamente ou protegidos por renderização dinâmica (ex.: texto literal de resenhas no Google Maps) estão sinalizados como `[A CONFIRMAR COM O CLIENTE]`.

---

## 1. 🏢 DADOS INSTITUCIONAIS & CONTATO

| Campo | Informação Verificada |
| :--- | :--- |
| **Nome Comercial** | **Autoescola Taradell** |
| **Razão Social** | **Autoscola Taradell Comunitat de Bens (C.B.)** |
| **CIF / NIF** | `E58144478` |
| **Ano de Fundação** | **1983** (mais de 40 anos de trajetória na comarca de Osona) |
| **Slogan Principal (Castellano)** | *"Tu autoescuela en Taradell desde 1983. Teórica 24h y prácticas a tu ritmo: ¡dinos dónde estás y te pasamos a buscar!"* |
| **Slogan Original (Català, site atual)** | *"La teva autoescola, des de 1983."* / *"Autoescola Taradell, el teu centre de formació viària a Osona."* |
| **Telefone Fixo** | `+34 938 80 03 14` (`93 880 03 14`) |
| **WhatsApp Principal (`dados.txt`)** | `+34 621 26 28 25` (`621 262 825`) |
| **WhatsApp Secundário (Site oficial)** | `+34 628 60 71 24` (`628 607 124`) |
| **E-mail** | `autoescolataradell@gmail.com` |
| **Site Atual** | [https://www.autoescolataradell.cat/](https://www.autoescolataradell.cat/) |
| **Instagram** | [@autoescolataradell.cat](https://www.instagram.com/autoescolataradell.cat/) |
| **Facebook** | [Autoescola Taradell (Facebook)](https://www.facebook.com/Autoescola-Taradell-470505006466550/) |
| **Centro de Exame DGT** | Jefatura Provincial de Tráfico de Barcelona – Centro de Exámenes de **Vic** (Osona) |

### Tom de Voz da Marca
- **Familiar, próximo e acessível:** Autoescola histórica de bairro/município (desde 1983), onde o aluno é tratado pelo nome, sem burocracia fria.
- **Jovem e prático:** Forte apelo visual no Instagram com fotos dos recém-aprovados segurando a placa **"L"** gigante, além de vídeos educativos de mecânica.
- **Resolutivo e flexível:** Foco total em eliminar barreiras de tempo e deslocamento (*"Aula 24h"*, *"Clases online en directo"*, *"Te vamos a buscar para las prácticas"*).

---

## 2. 🎨 IDENTIDADE VISUAL E DESIGN SYSTEM

### Paleta de Cores (Extraída do Logotipo Oficial `assets/logo.png` e do Site Atual)

| Função no Design System | Cor | Código HEX | Origem / Uso Recomendado |
| :--- | :--- | :--- | :--- |
| **Cor Primária** | Turquesa Petróleo | `#00AFAF` | Extraída diretamente de `assets/logo.png` e `assets/favicon.png`. Usar em cabeçalhos, ícones, badges, bordas de destaque e identidade dos carros. |
| **Cor Secundária / Acento** | Ciano Elétrico | `#18D5D7` | Extraída do CSS do site oficial atual (`autoescolataradell.cat`). Usar em gradientes sutis, hovers e elementos interativos. |
| **Cor de Conversão / CTA** | Verde WhatsApp / Aprovado | `#16A34A` *(ou `#25D366` para botões WhatsApp)* | Contraste vibrante alinhado ao verde oficial da placa **"L"** (presente nas fotos de aprovados) e ao canal principal de matrícula (WhatsApp). |
| **Fundo Escuro / Texto Principal** | Grafite Carvão | `#373835` | Extraída da tipografia de `assets/logo.png` (complementada por `#454545` no site atual). Ideal para títulos, rodapé e textos de alta legibilidade. |
| **Texto Secundário** | Cinza Neutro | `#4F4F4F` | Extraída do site oficial para parágrafos, subtítulos e metadados. |
| **Fundo Claro / Superfícies** | Branco Puro / Cinza Gelo | `#FFFFFF` / `#F5F5F5` | Extraídas do site oficial (`#FFFFFF`, `#F5F5F5`, `#F2F2F2`). Usar para cards limpos, seções alternadas e respiro visual. |

### Tipografia Recomendada
- **Títulos (Headings):** `Plus Jakarta Sans` ou `Outfit` (geométrica, moderna e amigável, harmonizando com a logomarca em caixa baixa `autoescola taradell`). *Alternativa alinhada ao site atual:* `Roboto` (Bold/Black).
- **Corpo de Texto (Body):** `Inter` ou `Roboto` (400 Regular / 500 Medium), garantindo leitura rápida em dispositivos móveis e tabelas de pacotes.

### Mapeamento Completo de Imagens (`assets/`)

| Arquivo (Caminho Relativo) | Descrição Visual | Uso Recomendado no Novo Site |
| :--- | :--- | :--- |
| `assets/logo.png` | Logotipo oficial: ícone circular turquesa (`#00AFAF`) com monograma branco e texto `autoescola taradell` em grafite (`#373835`). | Navbar (Header), Rodapé e materiais institucionais. |
| `assets/favicon.png` | Ícone circular turquesa (`#00AFAF`) com monograma branco isolado. | Favicon do site e ícone de app/atalho mobile. |
| `assets/homedesktop.jpeg` | Foto ampla e ensolarada da frota completa estacionada: **2 Volkswagen Golf brancos** adesivados da Autoescola Taradell + **1 scooter prata** + **1 moto Honda preta** + **1 moto Yamaha vermelha/preta**. | **Hero Banner (Desktop)** – transmite imediatamente frota moderna, variedade (carro + motos) e credibilidade local. |
| `assets/homemobile.png` | Versão vertical da frota (2 carros brancos com placa L e moto preta ao centro) otimizada para telas verticais. | **Hero Banner (Mobile)** ou seção de "Nuestra Flota". |
| `assets/aula-teorica-taradell.png` | Sala de aula teórica iluminada com alunos sentados em mesa em U branca e azul. | Seção **"Metodología y Aula 24h"** (ilustração de aulas presenciais e ambiente acolhedor). |
| `assets/aprobado-fachada-1.png` | Jovem recém-aprovado segurando placa "L" gigante e placa "L" normal em frente à vitrine da autoescola (onde se lê *"CLASSES ONLINE O PRESENCIALS"*). | Seção **"Prueba Social / Nuevos Conductores"** e fachada/vitrine. |
| `assets/aprobado-fachada-2.png` | Jovem recém-aprovado segurando placa "L" gigante e placa normal na porta da autoescola. | Galeria / Carrossel de aprovados. |
| `assets/aprobado-mural-1.png` | Aluna sorridente segurando placa "L" gigante diante do mural de fotos de aprovados da autoescola. | Carrossel de aprovados / Seção Permiso B. |
| `assets/aprobado-mural-2.png` | Aluna jovem segurando placa "L" gigante diante do mural de fotos de aprovados. | Carrossel de aprovados / Depoimentos. |
| `assets/aprobado-mural-3.png` | Aluno jovem segurando placa "L" gigante diante do mural de fotos de aprovados. | Carrossel de aprovados. |
| `assets/aprobado-mural-4.png` | Aluno adulto segurando placa "L" gigante diante do mural de fotos de aprovados. | Carrossel de aprovados (mostra diversidade de faixas etárias). |

---

## 3. 📍 SEDE FÍSICA, LOCALIZAÇÃO E HORÁRIOS

- **Endereço Completo:** Carrer de Sant Sebastià, 37, 08552 Taradell, Barcelona (Catalunya, España).  
  *(Nota: Alguns diretórios externos como Trustlocal listam o nº 31, porém o site oficial e os registros empresariais confirmam o **nº 37**).*
- **Coordenadas GPS:** `41.8741935, 2.2879517`
- **Link Direto Google Maps:** [Ver Autoescola Taradell en Google Maps](https://www.google.com/maps/place/Autoescola+Taradell/@41.8741935,2.2879517,17z/data=!3m1!4b1!4m6!3m5!1s0x12a4d83c2932a745:0xe99cc665413b042c!8m2!3d41.8741935!4d2.2879517!16s%2Fg%2F12qgxs226?entry=ttu&g_ep=EgoyMDI2MTExMC4wIKXMDSoASAFQAw%3D%3D)

### Horários Oficiais de Atendimento
- **Secretaria Presencial (Oficina):**
  - **Segunda a Sexta-feira (Lunes a Viernes):**
    - Manhã: `11:00 h – 13:00 h`
    - Tarde: `17:15 h – 20:00 h` *(na página de contato também consta `17:00 h – 20:00 h` conforme temporada)*
- **Aula de Informática / Testes (Teórica 24h):**
  - **Segunda a Domingo (Lunes a Domingo), 24 horas por dia**, mediante **tarjeta clave** entregue ao aluno matriculado (serviço exclusivo na comarca de Osona).
- **Aulas Teóricas Online em Direto:**
  - **Terça a Quinta-feira (Martes a Jueves):** `12:30 h – 13:15 h` *(nota: a página "Permisos i cursos" menciona segunda a quinta das `12:15 h` às `13:00 h` — `[A CONFIRMAR COM O CLIENTE]` o horário vigente para unificar no novo site)*.
- **Aulas Práticas:**
  - **Horários combinados (horas convenidas)** com flexibilidade e **serviço de recolha do aluno** (*"¡Dinos dónde estás y te pasamos a buscar!"*).

---

## 4. 🚗 CATÁLOGO EXAUSTIVO DE SERVIÇOS E CURSOS

> Todos os títulos e descrições abaixo estão redigidos em **Espanhol da Espanha (Castellano)** com base estrita no catálogo verificado em `autoescolataradell.cat/about`. Serviços não listados no site atual estão sinalizados para confirmação.

### 4.1. Permisos Particulares (Oferta Principal Confirmada)

1. **Permiso B (Coche)**
   - **Requisitos:** Edad mínima 18 años. Autoriza a conducir turismos y furgonetas de hasta 3.500 kg de MMA.
   - **Cambio Manual / Automático:** En la flota visualizada (`homedesktop.jpeg`) se observan dos Volkswagen Golf; confirmar si disponen de opción en cambio automático `[A CONFIRMAR COM O CLIENTE]`.
   - **Packs Oficiales Publicados:**
     - **Pack B 10 Horas:** Matrícula + Teórica (aula 24h y clases en directo) + Tasas y tramitación + 1 examen teórico + 1 examen de circulación + **10 clases prácticas de 60 minutos**.
     - **Pack B 20 Horas:** Matrícula + Teórica + Tasas y tramitación + 1 examen teórico + 1 examen de circulación + **20 clases prácticas de 60 minutos**.
   - **Diferencial:** Servicio de recogida del alumno en el punto acordado (*"Dinos dónde estás y te vamos a buscar"*).

2. **Permiso AM (Ciclomotores)**
   - **Requisitos:** Edad mínima 15 años. Ciclomotores de 2 o 3 ruedas y cuadriciclos ligeros.
   - **Pack 2H Publicado:** Matrícula + Teórica + Tasas y tramitación + 1 examen teórico + 1 examen de pistas + **2 clases prácticas en pista de 60 minutos**.

3. **Permiso A1 (Motocicletas hasta 125 cc)**
   - **Requisitos:** Edad mínima 16 años. Motocicletas con cilindrada máxima de 125 cm³.
   - **Pack 6H Publicado:** Matrícula + Teórica + Tasas y tramitación + 1 examen teórico + 1 examen de pistas + 1 examen de circulación + **3 prácticas en pista (60 min) + 3 prácticas de circulación (60 min)**.

4. **Permiso A2 (Motocicletas > 125 cc)**
   - **Requisitos:** Edad mínima 18 años. Motocicletas de cilindrada superior a 125 cm³ (hasta 35 kW).
   - **Pack 4H Publicado:** Matrícula + Teórica + Tasas y tramitación + 1 examen teórico + 1 examen de pistas + 1 examen de circulación + **2 prácticas en pista (60 min) + 2 prácticas de circulación (60 min)**.

5. **Permiso A (Motocicletas de cualquier cilindrada)** e **Pista Própria Homologada**
   - Não aparece listado na página `/about` do site atual. `[A CONFIRMAR COM O CLIENTE]` se oferecem o Permiso A e se utilizam pista própria ou compartilhada para as manobras de AM/A1/A2.

### 4.2. Cursos Oficiais DGT (Recuperação de Pontos)
- **Recuperación Parcial de Puntos (12 horas) / Recuperación Total del Permiso (24 horas):**
  - O site oficial possui link direto para **Consulta de Puntos DGT** e menção a **Compra Online de Cursos**, e o diretório Trustlocal cita *"recuperación de carné"*. Contudo, não há página detalhada de datas/homologação de centro recuperador de pontos no site atual.
  - Status: `[A CONFIRMAR COM O CLIENTE]` se são centro autorizado DGT para cursos de sensibilización y reeducación vial (12h/24h) presencialmente ou via parceria.

### 4.3. Permisos Profesionales & Transporte
- **Camión C, Tráiler C+E, Autobús D, CAP Inicial (140h) / CAP Continuo (35h), ADR (Mercancías Peligrosas), Carretillas Elevadoras y Tacógrafo Digital:**
  - Não constam no catálogo atual do site `autoescolataradell.cat`.
  - Status: `[A CONFIRMAR COM O CLIENTE]` (a autoescola aparenta ter foco 100% em permisos particulares B, AM, A1, A2, mas deve-se validar se há parcerias para CAP/C/C+E).

### 4.4. Credenciamentos Especiais (LABORA / SOC / FUNDAE)
- **Centro LABORA / SOC (Servei d'Ocupació de Catalunya) ou Formação Bonificada FUNDAE:**
  - Não há menção no site oficial (nota: LABORA é o órgão da Comunidade Valenciana; na Catalunha o equivalente seria SOC).
  - Status: `[A CONFIRMAR COM O CLIENTE]`.

### 4.5. Serviços Complementares Confirmados no Site
- **Aula de Informática 24h (Teórica 24 Horas):** Acesso livre 7 dias por semana com cartão-chave.
- **Vídeos de Mecánica en Instagram:** Conteúdo educativo para revisão pré-exame prático.
- **Gestión de Trámites DGT:** Consulta de notas de examen y saldo de puntos desde la web.

---

## 5. 💰 ESTRUTURA COMERCIAL E TARIFAS

O site oficial apresenta os pacotes estruturados (Pack B 10h, Pack B 20h, Pack AM 2h, Pack A1 6h, Pack A2 4h) **sem exposição pública de valores em Euros (€)**, direcionando o interessado para atendimento personalizado ou módulo de compra online.

| Produto / Serviço | O que Inclui (Confirmado) | Tarifa Sugerida para Exibição no Site |
| :--- | :--- | :--- |
| **Pack B – 10 Horas** | Matrícula, teórica 24h, taxas/tramitação, 1 exame teórico, 1 exame de circulação + 10 aulas práticas (60 min). | `Consultar tarifa por WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Pack B – 20 Horas** | Matrícula, teórica 24h, taxas/tramitação, 1 exame teórico, 1 exame de circulação + 20 aulas práticas (60 min). | `Consultar tarifa por WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Pack AM / A1 / A2** | Matrícula, teórica, taxas/tramitação, exames + horas práticas em pista e circulação conforme pack. | `Consultar tarifa por WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Prácticas Sueltas / Reciclaje** | Aulas práticas avulsas de 60 minutos (com recolha combinada). | `Consultar tarifa por WhatsApp` `[A CONFIRMAR COM O CLIENTE]` |
| **Tasas Oficiales DGT** | Incluídas nos packs publicados (1ª convocatória). | `Consultar condiciones y renovaciones` |
| **Modalidades de Pagamento** | Compra online disponível no site atual; pagamentos presenciais na secretaria. | `[A CONFIRMAR COM O CLIENTE]` (Bizum, tarjeta, efectivo, financiación/pago fraccionado) |

---

## 6. ⭐ PROVA SOCIAL, REPUTAÇÃO E DEPOIMENTOS

- **Nota Média Pública:** **4,9 / 5 estrelas** (com dezenas de avaliações em fichas locais e Google Maps) e **8,7 / 10** em agregadores como Trustlocal (20+ resenhas). `[A CONFIRMAR COM O CLIENTE: número exato e atualizado de resenhas no painel do Google Business Profile]`.
- **Pontos Mais Elogiados (Resumo Fático das Plataformas):**
  - Trato familiar, próximo e paciência da equipe docente.
  - Flexibilidade de horários (aula 24h e aulas online em direto).
  - Facilidade do serviço de recolha para as aulas práticas.
  - Preparação sólida para os exames no centro DGT de Vic.
- **Nomes dos Instrutores e Professores:**
  - Não foram encontrados nomes próprios indexados publicamente no site oficial nem nos trechos indexados das resenhas.
  - Status: `[A CONFIRMAR COM O CLIENTE]` (solicitar nomes dos professores de teórica e prática para humanizar a seção "Nuestro Equipo").
- **Depoimentos Reais (Google Reviews):**
  - *Nota técnica:* Sem automação de navegador, o Google Maps não expõe o texto literal completo de cada resenha individual via requisição HTTP simples. Para evitar qualquer alucinação, **não foram criados depoimentos fictícios**.
  - **Ação necessária antes do deploy (`[A CONFIRMAR COM O CLIENTE]`):** Copiar 4 a 6 resenhas literais em espanhol/catalão diretamente da ficha do Google Maps para preencher os cards abaixo:
    1. `[Depoimento Real #1 – Nome do Aluno / Instrutor citado – A CONFIRMAR COM O CLIENTE]`
    2. `[Depoimento Real #2 – Nome do Aluno / Instrutor citado – A CONFIRMAR COM O CLIENTE]`
    3. `[Depoimento Real #3 – Nome do Aluno / Instrutor citado – A CONFIRMAR COM O CLIENTE]`
    4. `[Depoimento Real #4 – Nome do Aluno / Instrutor citado – A CONFIRMAR COM O CLIENTE]`
- **Prova Social Visual Já Disponível (`assets/`):** 6 fotos reais de alunos aprovados com a placa **"L"** gigante e o mural de aprovados da autoescola, prontas para uso imediato no site.

---

## 7. 📲 ARQUITETURA DE CONVERSÃO & LINKS DE WHATSAPP

Todos os links utilizam o WhatsApp principal informado em `dados.txt` (**+34 621 26 28 25**) no padrão oficial `https://wa.me/34621262825?text=...` com mensagens prontas em **Espanhol da Espanha (Castellano)**:

1. **Link Geral de Matrícula (Permiso B – Coche):**
   - **CTA sugerido:** *"¡Quiero sacarme el carnet B!"*
   - **Mensagem:** `¡Hola! Me gustaría recibir información sobre precios y horarios para matricularme en el Permiso B (Pack 10h o 20h) en Autoescola Taradell.`
   - **URL:**
     ```text
     https://wa.me/34621262825?text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20recibir%20informaci%C3%B3n%20sobre%20precios%20y%20horarios%20para%20matricularme%20en%20el%20Permiso%20B%20(Pack%2010h%20o%2020h)%20en%20Autoescola%20Taradell.
     ```

2. **Link para Permisos de Moto (AM / A1 / A2):**
   - **CTA sugerido:** *"Consultar Carnet de Moto"*
   - **Mensagem:** `¡Hola! Quiero información sobre los packs y prácticas de moto (AM, A1 o A2) en Autoescola Taradell.`
   - **URL:**
     ```text
     https://wa.me/34621262825?text=%C2%A1Hola!%20Quiero%20informaci%C3%B3n%20sobre%20los%20packs%20y%20pr%C3%A1cticas%20de%20moto%20(AM%2C%20A1%20o%20A2)%20en%20Autoescola%20Taradell.
     ```

3. **Link para Recuperação de Pontos DGT / Cursos Especiais:** *(usar se confirmado com o cliente)*
   - **CTA sugerido:** *"Recuperar Puntos DGT"*
   - **Mensagem:** `¡Hola! Necesito información sobre fechas y disponibilidad para el curso de recuperación de puntos DGT (12h o 24h).`
   - **URL:**
     ```text
     https://wa.me/34621262825?text=%C2%A1Hola!%20Necesito%20informaci%C3%B3n%20sobre%20fechas%20y%20disponibilidad%20para%20el%20curso%20de%20recuperaci%C3%B3n%20de%20puntos%20DGT%20(12h%20o%2024h).
     ```

4. **Link para Aulas Práticas Avulsas ou Reciclagem:**
   - **CTA sugerido:** *"Reservar Prácticas / Reciclaje"*
   - **Mensagem:** `¡Hola! Me gustaría consultar disponibilidad para clases prácticas sueltas o de reciclaje y saber cómo funciona el servicio de recogida.`
   - **URL:**
     ```text
     https://wa.me/34621262825?text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20consultar%20disponibilidad%20para%20clases%20pr%C3%A1cticas%20sueltas%20o%20de%20reciclaje%20y%20saber%20c%C3%B3mo%20funciona%20el%20servicio%20de%20recogida.
     ```

---

## 8. 📐 DIRETRIZES RECOMENDADAS PARA A CRIAÇÃO DO SITE

### Proposta Única de Valor (UVP) em Taradell e Comarca de Osona
> ***"La autoescuela de confianza en Taradell desde 1983, con aula de teórica abierta las 24 horas (única en Osona), clases online en directo y servicio de recogida a domicilio para tus prácticas."***

Esse posicionamento une **tradição (40+ anos)** com **comodidade moderna (24h + recolha)**, resolvendo as duas maiores objeções dos alunos na comarca de Osona: falta de tempo para ir fazer testes em horário comercial e dificuldade de deslocamento até a sede ou até Vic.

### Arquitetura e Ordem Recomendada das Seções (Landing Page de Alta Conversão)

1. **Header Sticky + Barra de Contato Rápido:**
   - Logo (`assets/logo.png`), links âncora (*Permisos*, *Aula 24h*, *Aprobados*, *Contacto*) e botão verde destacado de WhatsApp (*"Matrícula por WhatsApp"*).
2. **Hero Section (Acima da Dobra):**
   - Fundo com `assets/homedesktop.jpeg` (desktop) / `assets/homemobile.png` (mobile) com overlay escuro sutil para contraste.
   - Badge: *"Desde 1983 en Taradell · ★ 4,9 en Google"*.
   - Título H1 em Espanhol: *"Tu carnet a la primera en Taradell y Osona"*.
   - Subtítulo destacando o diferencial único: *"Aula de teórica abierta 24h, clases online en directo y te pasamos a buscar para las prácticas."*
   - 2 CTAs: Primário verde (*"Pedir información por WhatsApp"*) + Secundário (*"Ver Packs y Permisos"*).
3. **Barra de Diferenciais Rápidos (Trust Strip):**
   - `40+ años de experiencia` | `Aula Informática 24h (Única en Osona)` | `Clases Online en Directo` | `Servicio de Recogida`.
4. **Seção de Permisos e Packs (Foco em Conversão):**
   - Cards limpos com borda turquesa (`#00AFAF`) para **Permiso B (Pack 10h e Pack 20h)** em destaque, seguidos por **Permiso AM (15 años)**, **Permiso A1 (16 años)** e **Permiso A2 (18 años)** — cada card listando exatamente o que inclui e botão direto para o WhatsApp pré-preenchido correspondente.
5. **Seção "Metodología 24h & Clases en Directo":**
   - Foto da sala de aula (`assets/aula-teorica-taradell.png`), explicação do cartão-chave 24h de segunda a domingo e horários das aulas ao vivo + link para vídeos de mecânica no Instagram.
6. **Seção "Muro de Aprobados & Opiniones Reales":**
   - Galeria/Carrossel com as 6 fotos reais dos alunos com a placa **"L"** (`aprobado-fachada-1.png` a `131530.png`) + espaço para os 4–6 depoimentos reais do Google Maps (assim que confirmados com o cliente).
7. **Seção "Trámites DGT & Consultas Rápidas":**
   - Botões úteis mantendo a funcionalidade do site atual: *Consultar Nota de Examen DGT* e *Consultar Saldo de Puntos DGT*.
8. **Seção Localização, Horários e Rodapé:**
   - Mapa interativo / link Google Maps (`C/ Sant Sebastià, 37, Taradell`), horários de secretaria, telefones (`93 880 03 14` / `621 262 825` / `628 607 124`), e-mail, Instagram, Facebook e botão flutuante permanente do WhatsApp.
