---
title: Precios
slug: pricing
sections:
  - title:
      text: Precios Flexibles
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is the subtitle for the pricing section
    plans:
      - title: Inicialización
        price: 29€
        details: Pago Único
        description: >-
          Empieza a conocer la importancia de los datos en tu negocio con un enfoque sencillo.
          Comienza con una herramienta básica para iniciar el camino hacia la optimización de tu empresa.

        features:
          - Registro básico de ventas
          - Recopilación de datos básicos de clientes (nombre, contacto, etc.)
          - Informes simples para comenzar a comprender el rendimiento
          - Acceso a soporte básico para resolver dudas iniciales
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Continuar con el plan
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Básico
        price: 179€
        details: por mes
        description: >-
          Da el siguiente paso hacia la transformación digital de tu negocio. Con el Plan Básico, no solo recopilarás datos,
          sino que los convertirás en herramientas clave para el crecimiento. Empieza a tomar decisiones informadas que te permitirán   
          optimizar tu negocio y alcanzar nuevas metas.

        features:
          - Análisis mensual de ventas, clientes y productos para mejorar tu rendimiento.
          - Reportes detallados con datos claves y recomendaciones de optimización.
          - Herramientas accesibles para que puedas comprender los patrones de tu negocio.
          - Soporte continuo para ayudarte a aprovechar al máximo la información recopilada.
        image:
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
          type: ImageBlock
        actions:
          - label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Enterprise
        price: Avanzado
        details: por mes
        description: >-

        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five

        image:
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
          type: ImageBlock
        actions:
          - label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
