# Modelo para Apresentação do Lab02 - Data Flow & Mensagens

## Tarefa sobre catálogo de componentes

[Notebook](/lab02/notebook/components-01-catalog.ipynb)

## Tarefa Web Components 1

```html
<dcc-trigger label="Mundo"
             action="noticia/mundo/politica"
             value="news world politics">
</dcc-trigger>

<dcc-trigger label="Brasil P"
             action="noticia/brasil/politica"
             value="news brazil politics">
</dcc-trigger>

<dcc-trigger label="Brasil E"
             action="noticia/brasil/esporte"
             value="news brazil sport">
</dcc-trigger>

<dcc-trigger label="Bahia"
             action="noticia/bahia/esporte"
             value="news bahia sport">
</dcc-trigger>

<dcc-lively-talk id="doctor"
                 character="doctor"
                 speech="I heard about a ">
  <subscribe-dcc topic="noticia/+/politica"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="nurse"
                 character="nurse"
                 speech="I heard about a ">
  <subscribe-dcc topic="noticia/brasil/#"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="patient"
                 character="patient"
                 speech="I heard about a ">
  <subscribe-dcc topic="noticia/#"></subscribe-dcc>
</dcc-lively-talk>
```

## Tarefa Web Components 2

```html
<dcc-trigger label="News" action="next/rss">
</dcc-trigger>

<dcc-rss source="https://www.wired.com/category/science/feed" publish="rss/science">
  <subscribe-dcc topic="next/rss" role="step"></subscribe-dcc>
</dcc-rss>

<dcc-rss source="https://www.wired.com/category/design/feed" publish="rss/design">
  <subscribe-dcc topic="next/rss" role="step"></subscribe-dcc>
</dcc-rss>

<dcc-aggregator publish="aggregate/science" quantity="3">
  <subscribe-dcc topic="rss/science"></subscribe-dcc>
</dcc-aggregator>

<dcc-lively-talk id="doctor"
                 character="doctor"
                 speech="I heard about ">
  <subscribe-dcc topic="aggregate/science"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="nurse"
                 character="nurse"
                 speech="I heard about ">
  <subscribe-dcc topic="rss/science"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="patient"
                 character="patient"
                 speech="I heard about ">
  <subscribe-dcc topic="rss/design"></subscribe-dcc>
</dcc-lively-talk>
```