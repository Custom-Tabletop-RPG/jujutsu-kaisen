Drücke `Strg`+ `P` zum drucken.

<div class="character-sheet">
  <div>
    <label>Name <input type="text" /></label>
    <label>Klan <input type="text" /></label>
    <label>Fluchtechnik <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
    <label>Rang <input type="text" /></label>
    <label>Fluchkraft <input type="text" /></label>
    <label>Trefferpunkte <input type="text" /></label>
  </div>
  <div>
    <label style="width: 100%">Tags</label>
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
    <input type="text" />
  </div>
</div>
<br />
<div class="jujutsu">
  <h2>Fähigkeiten</h2>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
  <div>
    <label>Name <input type="text" /></label>
    <label>Erfahrung <input type="text" /></label>
  </div>
</div>

<style>
  @media print {
    .character-sheet {
      max-height: 100vh !important;
    }

    br {
      page-break-before: always;
      height: 0;
    }

    .markdown-body > p,
    .markdown-body > h1,
    .markdown-body > .footer {
      display: none !important;
      visibility: collapse !important;
    }
  }

  .character-sheet {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
  }

  .character-sheet > div,
  .jujutsu > div {
    page-break-inside: avoid;
    border: 4px solid #00000040;
    border-radius: 1rem;
    padding: 0.5rem 0.75rem;
    display: flex;
    gap: 0.25rem 1rem;
    flex-direction: row;
    flex-wrap: wrap;
  }

  .character-sheet > div p {
    margin: 0.2rem 0;
  }

  .jujutsu {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    margin: 0 auto;
  }
</style>
