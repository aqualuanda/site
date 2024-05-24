---
title: 'Home'
date: 2024-05-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Aqua Luanda
      text: O próximo passo na evolução marítima!
      announcement:
        text: "Estamos em fase beta de lançamento"
        link:
          text: "Ler mais"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Toneladas de peixe em Angola no ano passado
        - statistic: "10k+"
          description: |
            Embarcações que desembarcaram nos portos
        - statistic: "3k+"
          description: |
            Espaços a retalho para venda de peixe
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Sumário
      text: O que define a nossa empresa?
      items:
        - name: Monitorização marítima
          icon: magnifying-glass
          description: Rastreamento de cardumes e volume de pesca nos portos marítimos
        - name: Monitorização ferroviária
          icon: sparkles
          description: Rastreamento da infraestrutura crítica para reduzir criminalidade por vandalismo ou responder às necessidades dos produtores agrícolas
        - name: Acessos API
          icon: code-bracket
          description: Acesso super-rápido a informação lógistica através de API que alimentam apps de telemóvel
        - name: Desenvolvimento interno
          icon: bolt
          description: Código 100% construído em Angola
        - name: Apreciado
          icon: star
          description: Mencionados com frequência na TV, radio e governo pelo esforço que desenvolvemos
        - name: Abertos a parcerias
          icon: rectangle-group
          description: Tens um projecto relevante nesta área? Fala connosco, vamos agregar valor juntos. :-)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Monitorização marítima
          text: Monitorizar a quantidade e tipo de pescado descarregado nos portos marítimos
          feature_icon: check
          features:
            - "Integra a informação dos sistemas locais para o acesso nacional"
            - "Informar através de app a quantidade e tipo de peixe desembarcado no porto"
            - "Acesso à informação em tempo real"
          # Upload image to `assets/media/` and reference the filename here
          image: barco-pesca-1.jpg
          button:
            text: Fala connosco
            url: mailto:equipa@aqualuanda.com

        - title: Monitorização ferroviária
          text: Garantir que equipamento crítico como postos de transformação, equipamento de comunicação e segurança de perímetros em locais como parques de transportes e estações são monitorizados
          feature_icon: bolt
          features:
            - "Ligação autónoma baseada em rádio LoRa"
            - "Alarmes para entrada não autorizada de pessoas em locais de remoto acesso/móvel"
            - "Reduz criminalidade por furto de material e danos na infraestrutura"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Fala connosco
            url: mailto:equipa@aqualuanda.com
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hamilton Chissuco"
          role: "Voz principal na Aqua Luanda"
          # Upload image to `assets/media/` and reference the filename here
          image: "pic1.jpg"
          text: "Estamos a desenvolver o futuro de Angola com Angola. Vamos em frente!"
    design:
      spacing:
        # Reduce bottom spacing so theo testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Entre em contacto connosco
      text: Tão fácil como 1, 2, 3
      button:
        text: Contactar
        url: mailto:equipa@aqualuanda.com
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
