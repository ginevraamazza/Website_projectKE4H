<html lang="it">
  {% include head-custom.html %}
<style>
  #container, .inner {
    max-width: 100% !important;
    margin: 0 auto !important;
    padding-left: 0 !important;
  }
</style>

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Progetto Wikidata Rimini</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .navbar {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #ffffff;
      border-bottom: 1px solid #ddd;
      z-index: 1000;
      padding: 1rem 0;
    }

    .navbar ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin: 0;
      padding: 0;
    }

    .navbar a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    main {
      padding-top: 100px; /* spazio per il menu fisso */
      padding-left: 20px;
      padding-right: 20px;
    }
  </style>
</head>

<body>

  <header class="navbar">
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#monumenti">Monumenti</a></li>
        <li><a href="#query">Query SPARQL</a></li>
        <li><a href="#contatti">Contatti</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home">
      <h1>Benvenuto nel progetto sui monumenti di Rimini</h1>
      <p>Questo progetto arricchisce Wikidata con dati semantici sui monumenti riminesi.</p>
    </section>

    <section id="monumenti">
      <h2>Monumenti selezionati</h2>
      <p>Ad esempio: Arco d'Augusto, Ponte di Tiberio, Castel Sismondo, ecc.</p>
    </section>

    <section id="query">
      <h2>Query SPARQL</h2>
      <p>Visualizza o arricchisci i dati tramite query su Wikidata.</p>
    </section>

    <section id="contatti">
      <h2>Contatti</h2>
      <p>Progetto a scopo educativo pubblicato su GitHub Pages.</p>
    </section>
  </main>

  <h1> <strong> Knowledge Engeneering for Humanities - Semantic Enrichment of Rimini's Monument Entities in the Wikidata Knowledge Graph</strong></h1>
  <p> Thisssssssssssss project aims to semantically <strong>enrich</strong> the digital representations of Rimini’s most significant monuments within the Wikidata Knowledge Graph, using techniques and tools from computer science and knowledge engineering.
The work focuses on retrieving and analyzing structured data related to the cultural heritage of Rimini, identifying missing or incomplete semantic properties (such as architectural style, building material, official websites, and inscriptions) in Wikidata items and suggesting and constructing RDF triples via SPARQL CONSTRUCT queries to enrich entities.
<br>
     We use SPARQL queries to extract, filter, and validate data:
    <br>
- To list all monuments located in Rimini and select a relevant subset.
    <br>
- To analyze the completeness of key semantic properties.
    <br>
- To cross-reference with external authoritative sources (e.g., Rimini’s municipal website and scholarly guides) for validation.  di GitHub Pages.</p>

</body>
</html>
