---
layout: default
title: CardioIA | Inteligencia artificial aplicada a la salud cardiovascular
---

<div class="site-shell">
  <nav class="site-nav" aria-label="Navegaci&oacute;n principal">
    <a class="wordmark" href="#inicio" aria-label="CardioIA, inicio">cardio<span>IA</span><i aria-hidden="true">.</i></a>
    <div class="nav-links">
      <a href="#proyecto">Proyecto</a>
      <a href="#metodologia">Metodolog&iacute;a</a>
      <a href="#alcance">Alcance</a>
    </div>
    <span class="project-status"><span aria-hidden="true"></span> Proyecto academico</span>
  </nav>

  <main id="inicio">
    <section class="hero" aria-labelledby="hero-title">
      <div class="hero-copy">
        <p class="eyebrow"><span class="eyebrow-mark" aria-hidden="true"></span> Facultad de Ingenier&iacute;a <span class="eyebrow-divider">/</span> Ingenier&iacute;a Mecatr&oacute;nica</p>
        <h1 id="hero-title">CardioIA: una mirada inteligente <em>al coraz&oacute;n.</em></h1>
        <p class="hero-intro">CardioIA explora c&oacute;mo el aprendizaje autom&aacute;tico puede ayudar a identificar patrones asociados a problemas card&iacute;acos a partir de datos.</p>
        <div class="hero-actions">
          <a class="button-primary" href="#metodologia">Conocer el modelo <span aria-hidden="true">&#8594;</span></a>
          <span class="model-tag"><span aria-hidden="true">&#9670;</span> XGBoost</span>
        </div>
        <p class="hero-note">Investigaci&oacute;n acad&eacute;mica en desarrollo. No sustituye la valoraci&oacute;n de un profesional de salud.</p>
      </div>

      <div class="signal-panel" aria-label="Visualizacion conceptual de datos de salud y aprendizaje automatico">
        <div class="panel-topline"><span>DATOS <b>/</b> PATRONES <b>/</b> MODELO</span><span class="live-mark"><i aria-hidden="true"></i> EXPLORACION</span></div>
        <div class="signal-heading">
          <div><span class="micro-label">ENTRADA DEL MODELO</span><h2>Se&ntilde;ales que cuentan</h2></div>
          <span class="signal-index">01 &#8212; 03</span>
        </div>
        <div class="chart-wrap">
          <div class="chart-y-label">REGISTRO ILUSTRATIVO</div>
          <svg class="ecg-chart" viewBox="0 0 540 184" role="img" aria-labelledby="chart-title chart-desc" preserveAspectRatio="none">
            <title id="chart-title">Visualizacion ilustrativa de una senal cardiaca</title>
            <desc id="chart-desc">Linea de pulso sobre una cuadricula; no representa datos de un paciente.</desc>
            <defs><pattern id="small-grid" width="18" height="18" patternUnits="userSpaceOnUse"><path d="M 18 0 L 0 0 0 18" fill="none" stroke="#dce6df" stroke-width="1"/></pattern></defs>
            <rect width="540" height="184" fill="url(#small-grid)"/>
            <path class="ecg-shadow" d="M0 98 H75 L92 96 L106 99 L119 95 L133 98 L149 97 L163 99 L176 96 L189 98 L205 97 L219 98 L232 96 L246 98 L260 97 L272 98 L283 95 L295 99 L306 96 L318 98 L329 98 L341 97 L354 98 L366 96 L379 98 L392 97 L405 98 L417 98 L430 96 L441 100 L451 92 L459 107 L472 45 L483 143 L496 83 L508 98 H540"/>
            <path class="ecg-line" d="M0 98 H75 L92 96 L106 99 L119 95 L133 98 L149 97 L163 99 L176 96 L189 98 L205 97 L219 98 L232 96 L246 98 L260 97 L272 98 L283 95 L295 99 L306 96 L318 98 L329 98 L341 97 L354 98 L366 96 L379 98 L392 97 L405 98 L417 98 L430 96 L441 100 L451 92 L459 107 L472 45 L483 143 L496 83 L508 98 H540"/>
            <circle cx="472" cy="45" r="4" class="ecg-point"/>
          </svg>
          <div class="chart-axis"><span>LECTURA DE EJEMPLO</span><span>VISUALIZACION CONCEPTUAL</span></div>
        </div>
        <div class="feature-row">
          <div class="feature-item"><span class="feature-number">01</span><span>Datos<br><b>del dataset</b></span></div>
          <span class="feature-connector" aria-hidden="true"></span>
          <div class="feature-item"><span class="feature-number">02</span><span>Patrones<br><b>identificados</b></span></div>
          <span class="feature-connector" aria-hidden="true"></span>
          <div class="feature-item feature-model"><span class="feature-number">03</span><span>Modelo<br><b>XGBoost</b></span></div>
        </div>
        <div class="panel-foot"><span>NING&Uacute;N DATO CL&Iacute;NICO REAL</span><span class="panel-foot-symbol" aria-hidden="true">+</span></div>
      </div>
      <span class="hero-index" aria-hidden="true">01 <i></i> 03</span>
    </section>

    <section class="project-strip" id="proyecto" aria-label="Resumen del proyecto">
      <div><span class="strip-label">ENFOQUE</span><strong>Inteligencia artificial aplicada</strong></div>
      <div><span class="strip-label">M&Eacute;TODO</span><strong>Clasificaci&oacute;n con XGBoost</strong></div>
      <div><span class="strip-label">PROPOSITO</span><strong>Explorar patrones cardiovasculares</strong></div>
    </section>

    <section class="method-section" id="metodologia" aria-labelledby="method-title">
      <div class="section-heading">
        <p class="eyebrow"><span class="eyebrow-mark" aria-hidden="true"></span> C&Oacute;MO FUNCIONA</p>
        <h2 id="method-title">De los datos a una<br><em>pregunta mejor.</em></h2>
      </div>
      <div class="method-content">
        <p class="method-lead">El proyecto estudia un flujo de aprendizaje supervisado: preparar un dataset, entrenar un clasificador y evaluar con rigor lo que el modelo aprende.</p>
        <div class="method-steps">
          <article class="method-step">
            <span class="step-number">01</span>
            <div><h3>Preparar los datos</h3><p>Se revisan las variables, las etiquetas y la calidad del dataset seleccionado para el estudio.</p></div>
            <span class="step-icon data-icon" aria-hidden="true"><i></i><i></i><i></i><i></i></span>
          </article>
          <article class="method-step">
            <span class="step-number">02</span>
            <div><h3>Entrenar XGBoost</h3><p>El algoritmo combina &aacute;rboles de decisi&oacute;n que aprenden, paso a paso, de los errores anteriores.</p></div>
            <span class="step-icon tree-icon" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i></span>
          </article>
          <article class="method-step">
            <span class="step-number">03</span>
            <div><h3>Evaluar con cuidado</h3><p>Se medir&aacute; el desempe&ntilde;o con datos separados y m&eacute;tricas adecuadas antes de comunicar resultados.</p></div>
            <span class="step-icon check-icon" aria-hidden="true">&#10003;</span>
          </article>
        </div>
      </div>
    </section>

    <section class="scope-section" id="alcance" aria-labelledby="scope-title">
      <div class="scope-kicker"><span class="eyebrow-mark" aria-hidden="true"></span> CIENCIA CON RESPONSABILIDAD</div>
      <div class="scope-body"><h2 id="scope-title">Una herramienta para investigar.<br><em>No para diagnosticar.</em></h2><p>Los resultados dependen de la calidad, representatividad y procedencia del dataset, adem&aacute;s de una validaci&oacute;n adecuada. Este prototipo tiene fines acad&eacute;micos: no ofrece diagn&oacute;sticos ni recomendaciones m&eacute;dicas.</p></div>
      <span class="scope-decoration" aria-hidden="true">C<span>I</span></span>
    </section>
  </main>

  <footer class="site-footer">
    <a class="wordmark footer-wordmark" href="#inicio">cardio<span>IA</span><i aria-hidden="true">.</i></a>
    <p>Proyecto de Inteligencia Artificial<br>Facultad de Ingenier&iacute;a &middot; Ingenier&iacute;a Mecatr&oacute;nica</p>
    <a class="back-top" href="#inicio">VOLVER ARRIBA <span aria-hidden="true">&#8593;</span></a>
  </footer>
</div>