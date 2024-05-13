---
# Deixe o título da pagina inicial vazio para usar o título do site
título: home
dados: 24/10/2022
tipo: pouso

sessões:

  - bloco: sobre.biografia
 id: sobre
 conteúdo:
 título: Biografia
      # Escola um perfil de usuário para exibir (um nome de massa dentrada `conteúdo/autores/`)
 nome de usuário: admin
  - bloco: características
 conteúdo:
 título: Habilidades
 itens:
 - nome: Geoespacial
 descrição: 70%
 ícone: globo
 icon_pack: fas
 - nome: Estatísticas
 descrição: 60%
 ícone: linha do gráfico
 icon_pack: fas
 - nome: Projeções 2D
 descrição: 100%
 ícone: desenho-polígono
 icon_pack: fas
 - nome: Microsoft Office
 descrição: 80%
 ícone: microsoft
 icon_pack: fabuloso
 - nome: Python
 descrição: 50%
 ícone: python
 icon_pack: fabuloso
 - nome: Resiliência
 descrição: 90%
 ícone: aperto de mão
 icon_pack: fas
    
  - bloco: experiência
 conteúdo:
 título: Experiência
      # Formato de dados para experiência
      # Consulte https://wowchemy.com/docs/customization/#date-format
 data_formato: janeiro de 2006
 # Experiências.
 # Adicionar/remover tantos `experiência` itens abaixo como você gosta.
 # Os campos obrigatórios são `título`, `empresa`, e `data_início`.
 # Deixar `dados_fim` vazio se for o seu empreendedor atual.
 # Comece descrições de vias linhas com YAML's `|2-` prefixo multi-linha.
 itens:
 - título: Analista de Projetos AgroCAD
 empresa: MA. Máquinas Agrícola
 empresa_url: 'https://www.mamaquinas.com.br'
 empresa_logotipo: MA
 localização: Cascavel - PR 
 dados_início: '12/04/2023'
 data_fim: ''
 descrição: - Monitoramento de equipamentos de agrícolas, gestão dos equipamentos agrícolas ativos, controle de todas as informações referente a monitoramento de equipamentos, contato proativo à clientes e venda de valor da tecnologia ao cliente.

Realizar as visitas a clientes estratégicos junto as lojas; 
Trabalhar com o projeto de tráfego direcionado na lavoura; 
Realizar paralelismo de linhas no plantio e pulverização; 
Atuar com foco na otimização da área plantada; 
Apresentar aos clientes soluções para redução de custo em combustível; 
Dar suporte a equipe de Vendas e Pós-Venda em demonstrações de produtos de tecnologia com Agrocad.


        - título: Trainee Agricultura Digital 
        empresa: Amaggi - Fazenda Independência
        empresa_url: 'https://www.amaggi.com.br/'
        company_logo: Sem-título
        localização: Santo Antônio do Leste - MT
        dados_início: '01/02/2023'
        data_fim: '30/05/2023'
        descrição: |2-
        - Implementação, manutenção e treinamento do sistema de telemetria; Projetos de linhas de plantio (controle de tráfego de operações); Conservação e manutenção de estações perigosas; Configuração de aplicação de taxa variável por pulverização e semeadora; Ferramentação (GIS): Produtividade, chuva e mapas temáticos; Configuração e configuração de monitores; Elaboração de relatórios e análise de indicadores operacionais; Calibração da folha de fertilizantes; Medição do bico de pulverização de suporte com ferramenta digital;
        

 design:
 colunas: '2'
  - bloco: realizações
 conteúdo:
      # Nota: `&tímido;` é usado para adicionar um hífen 'suave' em um cabeçalho longo.
 título: 'Realizar&tímido;mentos'
 subtítulo:
 # Formato da data: https://wowchemy.com/docs/customization/#date-format
 data_formato: janeiro de 2006
 # Realizações.
 # Adicionar/remover tantos `item` blocos abaixo como você gosta.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://drive.google.com/file/d/1yppGgk33H-9vP61uUZs5wJaD-EY4aS9x/view
          date_end: ''
          date_start: '2023-04-06'
          description: Precision agriculture. Remote sensing.
          organization: TECGRAF AGRO
          organization_url: https://tecgraf.com.br/
          title: Sistematização de Culturas utilizando o AgroCAD360 
          url: https://tecgraf.com.br/
        - certificate_url: https://drive.google.com/file/d/1rvfyIUue29tVa2Hy7k0WG8n0nb2QWM8Y/view?usp=drivesdk
          date_end: ''
          date_start: '2023-02-26'
          description: Precision agriculture.
          organization: SOLINFTEC
          organization_url: https://www.solinftec.com/pt-br/
          title: SGPA - Automated Process Management System
          url: https://www.solinftec.com/pt-br/
        - certificate_url: https://drive.google.com/file/d/1RZ00Q4xF61CdHhBP260RmpYuYp9F8LL-/view
          date_end: ''
          date_start: '2023-02-03'
          description: Precision agriculture.
          organization: SENAR-MT
          organization_url: https://ead.senar.org.br/
          title: Digital Agriculture
          url: https://ead.senar.org.br/
   
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Introduction to Precision Agriculture
          tag: Precision Farming Tools
        - name: Technological Challenge Projecte
          tag: Combination of Technological Tools  
        - name: GIS Information Systems applied to Precision Agriculture
          tag: GEOGRAPHIC INFORMATION SYSTEMS
        - name: SR or NDVI spectral indices e Unsupervised and Supervised Classification
          tag: Spectral indices
    design:
      columns: '2'
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        If you want to get in touch, send an email or use one of the resources indicated in this page.
      # Contact (add or remove contact options as necessary)
      email: murilo._.soouza@hotmail.com
      phone: 18  9  998004972
      appointment_url: 'https://calendly.com'
      address:
        street: ''
        city: Rondonópolis
        region: MT
        postcode: ''
        country: Brazil
        country_code: BR
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
    design:
      columns: '2'
---
