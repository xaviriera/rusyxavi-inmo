# RONDA 10 REFERENCE — Markup Exacto

## TORRES-COTILLAS.HTML — Secciones Principales

Secciones encontradas (líneas clave):
- L946: `<!-- HEADER -->` — `.header` con logo IM·PULSO
- L954: `<!-- CO-BRANDING BAR -->` — `.cobrand-bar` con CdU de 0 a ÉXITO
- L966: `<!-- HERO -->` — `.hero` con ficha operación + 3 fuentes
- L1021: `<!-- SECCIÓN 1: PULSO -->` — `.section` PULSO
- L~1230: `<!-- SECCIÓN 2: IMPULSO -->` — `.section` IMPULSO + veredicto IMPULSO (L1433)
- L1444: `<!-- SECCIÓN 3: NOTARIAL -->` — `.section` con 3.1–3.6
- L1559: `<!-- 3.6 Cruce Notarial × Mercado -->` — `.card` cruce
- L1587: `<!-- SECCIÓN 4: MTVV -->` — `.section` pasos 0–4
- L1787: `<!-- SECCIÓN 5: CONVERGENCIA -->` — `.section` convergencia + semáforo
- L1840: `<!-- SECCIÓN 6: VEREDICTO / LECTURA INVERSOR -->` — `.section`
- L1880: `<!-- SECCIÓN 7: CONCLUSIÓN -->` — `.section` conclusión final + `.verdict-navy`

---

## TORRES-COTILLAS — MTVV/Método Total (pasos 0-4)

```html
  <!-- SECCIÓN 4: MTVV -->
  <!-- ============================================ -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon" style="background: #ecfdf5; color: #10B981;">&#128300;</div>
      <div>
        <div class="section-title">4 · Método Total de Valoración de Vivienda (MTVV)</div>
        <div class="section-subtitle">Validación humana · Metodología Programa IN · Exclusivo IM·PULSO</div>
      </div>
      <span class="exclusive-tag">&#128300; Exclusivo</span>
    </div>

    <!-- Explainer MTVV -->
    <div class="mtvv-explainer">
      <strong>¿Qué es el Método Total de Valoración de Vivienda (MTVV)?</strong> Es el estudio que realiza un inversor formado en la metodología del Programa IN sobre la propia microzona y tipología de la operación. Es la validación humana que ningún algoritmo da: hablar con las inmobiliarias de la zona, buscar testigos reales y, finalmente, probar el precio publicando un anuncio de verdad para medir la respuesta del mercado.
    </div>

    <!-- Provenance -->
    <div class="provenance">
      <strong>Sobre el origen de este MTVV.</strong> El origen de este MTVV es el realizado y adjunto al in-bruto de esta oportunidad, en su fase de estudio (noviembre 2025). No es el MTVV de confirmación final de precios.
    </div>

    <!-- Paso 0 -->
    <div class="card">
      <div class="step-header">
        <div class="step-number">0</div>
        <div class="step-title">Paso 0 — Contexto del micromercado</div>
      </div>
      <div class="kpi-row">
        <div class="kpi"><div class="kpi-value">21.980</div><div class="kpi-label">Habitantes</div></div>
        <div class="kpi"><div class="kpi-value">1.307&euro;</div><div class="kpi-label">&euro;/m² del barrio</div></div>
        <div class="kpi"><div class="kpi-value">0</div><div class="kpi-label">Viviendas de 1 hab en venta</div></div>
        <div class="kpi"><div class="kpi-value">277</div><div class="kpi-label">Compraventas registradas (2024)</div></div>
      </div>
      <table class="table-mobile">
        <thead><tr><th>Parámetro</th><th>Dato</th></tr></thead>
        <tbody>
        <tr><td>Renta neta por persona</td><td data-label="Dato">12.406&euro;</td></tr>
        <tr><td>Renta neta por hogar</td><td data-label="Dato">35.033&euro;</td></tr>
        <tr><td>Precio del barrio</td><td data-label="Dato">1.307&euro;/m² (la zona más cara del municipio; las colindantes están entre 840 y 1.080&euro;/m²)</td></tr>
        <tr><td>Compraventas registradas por año</td><td data-label="Dato">147 (2018) · 160 (2019) · 257 (2020) · 264 (2021) · 249 (2022) · 210 (2023) · 277 (2024)</td></tr>
        <tr><td>Oferta de 1 habitación en venta</td><td data-label="Dato">0 viviendas (nicho sin competencia)</td></tr>
        <tr><td>Oferta de alquiler</td><td data-label="Dato">Apenas 3 pisos en todo el municipio</td></tr>
        </tbody>
      </table>
      <div class="insight insight-green">
        <strong>Conclusión del Paso 0:</strong> es la zona premium del pueblo, y el producto de 1 habitación es inexistente en la oferta actual. Eso es un hueco de mercado: demanda sin competencia.
      </div>
    </div>

    <!-- Paso 1 -->
    <div class="card">
      <div class="step-header">
        <div class="step-number">1</div>
        <div class="step-title">Paso 1 — Inmobiliarias: lo que dicen (4 consultadas)</div>
      </div>
      <table class="table-mobile">
        <thead><tr><th>Inmobiliaria</th><th>Precio</th><th>Qué dicen</th></tr></thead>
        <tbody>
        <tr><td><strong>Carmen Inmobiliaria</strong><br><span style="font-size:11px;color:#9ca3af;">644 139 002</span></td><td data-label="Precio"><strong>65.000&euro;</strong></td><td data-label="Qué dicen">"Venta de 60.000 a 70.000&euro;. Alquiler 400&euro;/mes. Target: inversores, solteros, parejas jóvenes."</td></tr>
        <tr><td><strong>Aintor Inmobiliaria</strong><br><span style="font-size:11px;color:#9ca3af;">968 624 262</span></td><td data-label="Precio"><strong>55.000&euro;</strong></td><td data-label="Qué dicen">"Pisos desactualizados de 80-90 m² se venden a 50-60.000&euro;. El tuyo, como nuevo, 60.000&euro; como mucho. Alquiler por encima de 400&euro; difícil."</td></tr>
        <tr><td><strong>Urbane</strong><br><span style="font-size:11px;color:#9ca3af;">868 610 763</span></td><td data-label="Precio"><strong>65.000&euro;</strong></td><td data-label="Qué dicen">"Venta de 60 a 70.000&euro; si la zona está bien. Alquiler 400&euro;/mes."</td></tr>
        <tr><td><strong>Templo Inmobiliaria</strong><br><span style="font-size:11px;color:#9ca3af;">722 332 706</span></td><td data-label="Precio"><strong>62.500&euro;</strong></td><td data-label="Qué dicen">"Venta de 60 a 65.000&euro; (a estudiar). Alquiler de 350 a 400&euro;/mes."</td></tr>
        </tbody>
      </table>
      <div class="insight insight-green">
        <strong>Conclusión del Paso 1:</strong> hay consenso en una horquilla de 60.000 a 70.000&euro; para un piso como nuevo, y unos 58.000-60.000&euro; de suelo para los estudios. La media de las 4 inmobiliarias es de 61.875&euro;.
      </div>
      <div class="step-price">
        <div class="sp-label">Precio del Paso 1 (inmobiliarias)</div>
        <div class="sp-value">61.875&euro;</div>
      </div>
    </div>

    <!-- Paso 2 -->
    <div class="card">
      <div class="step-header">
        <div class="step-number">2</div>
        <div class="step-title">Paso 2 — Testigos de mercado (anuncios)</div>
      </div>
      <div class="insight insight-gray" style="margin-top:0;">
        <strong>Sin testigos comparables.</strong> No hay anuncios de venta ni de alquiler de esta tipología exacta (estudios o viviendas de 1 dormitorio) en la zona. Solo aparecen 3 pisos con precios no comparables (alquiler por días). No es posible fijar un precio a partir de anuncios en este paso.
      </div>
      <div class="step-price">
        <div class="sp-label">Precio del Paso 2 (testigos)</div>
        <div class="sp-value">Sin dato</div>
        <div class="sp-note">No hay testigos comparables en la zona</div>
      </div>
    </div>

    <!-- Paso 3 -->
    <div class="card">
      <div class="step-header">
        <div class="step-number">3</div>
        <div class="step-title">Paso 3 — Hipótesis de precio</div>
      </div>
      <div style="display:grid; grid-template-columns: 1fr 1fr 1fr; gap:12px; text-align:center; margin:12px 0;" class="hypo-grid">
        <div style="background:#ecfdf5; padding:16px; border-radius:12px;">
          <div style="font-size:11px; color:#10B981; text-transform:uppercase; letter-spacing:1px; font-weight:700;">Paso 1 dice</div>
          <div style="font-size:22px; font-weight:800; color:#141B36; margin-top:4px;">61.875&euro;</div>
        </div>
        <div style="background:#f3f4f6; padding:16px; border-radius:12px;">
          <div style="font-size:11px; color:#9ca3af; text-transform:uppercase; letter-spacing:1px; font-weight:700;">Paso 2 dice</div>
          <div style="font-size:18px; font-weight:800; color:#9ca3af; margin-top:8px;">Sin dato</div>
        </div>
        <div style="background:#fff3f0; padding:16px; border-radius:12px; border:2px solid #FF4D2E;">
          <div style="font-size:11px; color:#FF4D2E; text-transform:uppercase; letter-spacing:1px; font-weight:700;">Hipótesis</div>
          <div style="font-size:22px; font-weight:800; color:#FF4D2E; margin-top:4px;">61.875&euro;</div>
        </div>
      </div>
      <div class="build-box">
        <div class="bb-title">Cómo se construye la hipótesis</div>
        <div class="bb-body">
          <div>&bull; <strong>Paso 1 (inmobiliarias):</strong> media de 61.875&euro;, con consenso en 60.000-70.000&euro;.</div>
          <div>&bull; <strong>Paso 2 (anuncios):</strong> sin testigos comparables en la zona.</div>
          <div class="bb-total">&rarr; La hipótesis de precio se apoya solo en las inmobiliarias: <strong style="color:#FF4D2E;">61.875&euro;</strong>, a falta de testigos.</div>
        </div>
      </div>
    </div>

    <!-- Paso 4 -->
    <div class="card">
      <div class="step-header">
        <div class="step-number">4</div>
        <div class="step-title">Paso 4 — Verificación con un anuncio real</div>
      </div>
      <p style="font-size: 13px; color: #4b5563; margin-bottom: 16px;">Se publicó un anuncio real en Idealista y Fotocasa el 8 de diciembre de 2025 para medir la respuesta del mercado. El precio de salida se fue ajustando:</p>

      <div class="price-evolution">
        <div class="price-step" style="background:#f3f4f6;"><div class="ps-day">Salida</div><div class="ps-price">71.500&euro;</div></div>
        <div class="price-arrow">&rarr;</div>
        <div class="price-step" style="background:#f3f4f6;"><div class="ps-day">Ajuste</div><div class="ps-price">69.900&euro;</div></div>
        <div class="price-arrow">&rarr;</div>
        <div class="price-step final"><div class="ps-day">Pico de interés</div><div class="ps-price">59.500&euro;</div></div>
      </div>

      <div class="kpi-row" style="margin-top:20px;">
        <div class="kpi"><div class="kpi-value">15</div><div class="kpi-label">Contactos totales</div></div>
        <div class="kpi"><div class="kpi-value">7</div><div class="kpi-label">Llamadas de interesados</div></div>
        <div class="kpi"><div class="kpi-value">7</div><div class="kpi-label">Emails de portales</div></div>
        <div class="kpi"><div class="kpi-value">1</div><div class="kpi-label">Oferta firme (60.000&euro;)</div></div>
      </div>

      <h4 style="margin: 20px 0 12px; color: #141B36;">Interesados reales</h4>
      <p style="font-size:12.5px; color:#6b7280; margin-bottom:12px;">De los 15 contactos, todos de nacionalidad española. Mezcla de inversores y particulares para vivir. Fechas de contacto del 8 al 22 de diciembre de 2025.</p>
      <table class="table-mobile">
        <thead><tr><th>Interesado</th><th>Perfil</th><th>Nacionalidad</th></tr></thead>
        <tbody>
        <tr><td>Nieves, Mario, Pablo, Marcelino, Pablo José, Juan, Susan</td><td data-label="Perfil">Inversor</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        <tr><td>Mª Dolores</td><td data-label="Perfil">Particular (soltera)</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        <tr><td>Agus</td><td data-label="Perfil">Particular (soltero)</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        <tr><td>Pedro</td><td data-label="Perfil">Particular (separado)</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        <tr><td>Dani</td><td data-label="Perfil">Particular (separado)</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        <tr><td>Amanda</td><td data-label="Perfil">Particular (soltera)</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        <tr><td>José Ignacio</td><td data-label="Perfil">Particular (divorciado)</td><td data-label="Nacionalidad"><svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg> España</td></tr>
        </tbody>
      </table>

      <!-- Campana de demanda -->
      <div class="demand-bell">
        <div class="db-title">&#128202; Interés según el precio de salida</div>
        <div class="db-row">
          <span style="font-weight:700; color:#141B36;">71.500&euro;</span>
          <div class="db-bar-bg"><div class="db-bar-fill" style="width:22%;"></div></div>
          <span style="font-weight:800; color:#141B36; text-align:right;">Bajo</span>
        </div>
        <div class="db-row">
          <span style="font-weight:700; color:#141B36;">69.900&euro;</span>
          <div class="db-bar-bg"><div class="db-bar-fill" style="width:50%;"></div></div>
          <span style="font-weight:800; color:#141B36; text-align:right;">Medio</span>
        </div>
        <div class="db-row">
          <span style="font-weight:700; color:#141B36;">59.500&euro;</span>
          <div class="db-bar-bg"><div class="db-bar-fill" style="width:100%;"></div></div>
          <span style="font-weight:800; color:#FF4D2E; text-align:right;">Pico</span>
        </div>
        <div class="db-foot">
          <strong style="color:#FF4D2E;">Lectura:</strong> a 71.500&euro; el interés era escaso (sobre todo inversores tanteando). A 69.900&euro; aparecieron particulares. A 59.500&euro; se produjo el pico de interés, creciente y sostenido entre particulares para vivir ("no lo ven caro"), y varias inmobiliarias dijeron tener comprador directo a ese precio. La demanda de quien quiere vivir ahí se concentra en la franja baja (59.500–63.500&euro;); los inversores tantean por arriba.
        </div>
      </div>

      <div class="step-price">
        <div class="sp-label">Veredicto del Paso 4 (verificado con anuncio real)</div>
        <div class="sp-value">179.500&euro;</div>
        <div class="sp-note">Apartamento 1 dormitorio 63.500&euro; + 2 estudios a 58.000&euro; cada uno</div>
      </div>
      <div class="insight insight-green">
        <strong>Veredicto del Paso 4:</strong> el piso de 1 dormitorio se vende sin problema en torno a 63.500&euro; (algo más negociando), y cada estudio loft alcanza unos 58.000&euro; de suelo. En total, las 3 unidades suman <strong>179.500&euro;</strong>.
      </div>

      <!-- Disclaimer fecha (en el veredicto del Paso 4) -->
      <div class="disclaimer">
        <strong>Nota sobre la fecha.</strong> Este MTVV se realizó en noviembre 2025. El mercado está en tendencia al alza, por lo que para una decisión de compra actualizada, IM·PULSO recomienda sacar un nuevo informe actualizado y un nuevo Paso 4 del método total.
      </div>
    </div>
  </div>
```

---

## TORRES-COTILLAS — Convergencia Final (semáforo + convergence box + veredicto)

```html
  <!-- SECCIÓN 5: CONVERGENCIA -->
  <!-- ============================================ -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon" style="background: #fff3f0; color: #FF4D2E;">&#9889;</div>
      <div>
        <div class="section-title">5 · Convergencia de las fuentes</div>
        <div class="section-subtitle">Dos métodos independientes medidos por separado, comparados</div>
      </div>
    </div>

    <div class="validation-grid">
      <div class="validation-card scraping">
        <div class="v-icon">&#128225;</div>
        <div class="v-source">IMPULSO (motor automático)</div>
        <div class="v-price">189.000&euro;</div>
        <div class="v-detail">7 testigos comparables<br>Anclado en las 2 unidades del nº 17</div>
      </div>
      <div class="validation-card mtvv">
        <div class="v-icon">&#128300;</div>
        <div class="v-source">MTVV (Programa IN)</div>
        <div class="v-price">179.500&euro;</div>
        <div class="v-detail">4 inmobiliarias consultadas<br>Verificado con anuncio real</div>
      </div>
      <div class="validation-card notarial">
        <div class="v-icon">&#127963;&#65039;</div>
        <div class="v-source">Notarial (contexto)</div>
        <div class="v-price">858&euro;/m²</div>
        <div class="v-detail">110 compraventas/año<br>Suelo oficial (no converge, explicado)</div>
      </div>
    </div>

    <div class="convergence">
      <div class="conv-label">Las dos valoraciones del producto coinciden</div>
      <div class="conv-verdict">&#10003; CONVERGENCIA ALTA</div>
      <div class="conv-price">179.500&euro; — 189.000&euro;</div>
      <div class="conv-range">Diferencia: +5,3%</div>
      <div class="conv-note">
        Dos fuentes independientes —el motor automatizado de IM·PULSO y el MTVV del Programa IN— coinciden: el producto vale entre 180.000 y 190.000&euro;. Cuando dos métodos que no se hablan entre sí llegan al mismo número, el dato es fiable. Hay que tener en cuenta que había pocos testigos comparables de esta tipología exacta, lo que hace aún más valioso que ambos métodos converjan.
      </div>
    </div>

    <div class="card">
      <div class="card-title">Por qué el notarial no converge (y está bien que no lo haga)</div>
      <div class="insight insight-purple" style="margin-top:0;">
        El dato notarial (858&euro;/m²) no encaja en esta convergencia, y es lógico: mide vivienda grande de segunda mano (114 m² de media), no producto pequeño reformado. Son cosas distintas. El notarial no es la valoración del producto de esta operación, sino el <strong>suelo y contexto oficial</strong> que confirma que el mercado es real, tiene volumen y está activo. La valoración del producto la dan las otras dos fuentes, que sí convergen.
      </div>
    </div>
  </div>

  <hr class="section-divider">

  <!-- SECCIÓN 6: VEREDICTO / LECTURA INVERSOR -->
  <!-- ============================================ -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon" style="background: #141B36; color: #FF4D2E;">&#9878;&#65039;</div>
      <div>
        <div class="section-title">6 · Lectura para el inversor</div>
        <div class="section-subtitle">Síntesis de valoración y mercado · Calle D'Estoup 17</div>
      </div>
    </div>

    <div class="card" style="background: linear-gradient(135deg, #fafbfc 0%, #f3f4f6 100%); border: 2px solid #e5e7eb;">
      <ul class="conclusion-list">
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="1" x2="12" y2="23"></line><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"></path></svg></span>
          <span><strong>Valor de salida de las 3 viviendas:</strong> entre 180.000 y 190.000&euro; (motor IMPULSO 189.000&euro; y MTVV 179.500&euro;, con una diferencia de solo +5,3%).</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="23 6 13.5 15.5 8.5 10.5 1 18"></polyline><polyline points="17 6 23 6 23 12"></polyline></svg></span>
          <span><strong>Producto en el segmento de máxima liquidez:</strong> 1 habitación, tramo por debajo de 125.000&euro;, y la propia Calle D'Estoup que rota al 100%. Demanda alta: el producto pequeño se retira en torno a 30 días, frente a los 78 de media de la zona.</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg></span>
          <span><strong>Nicho confirmado:</strong> la oferta de viviendas de 1 habitación en venta es de 0 en el municipio (Paso 0 del MTVV). No hay competencia directa.</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle></svg></span>
          <span><strong>Perfil del comprador (notarial):</strong> joven (53% con menos de 40 años) y más del 90% nacional. Encaja con un producto pequeño de entrada o de inversión.</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="9 11 12 14 22 4"></polyline><path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11"></path></svg></span>
          <span><strong>El siguiente paso:</strong> el análisis de inversión detallado (costes, márgenes, rentabilidad) lo realiza el equipo aparte. Este informe valida el <strong>precio</strong> y el <strong>mercado</strong>: el producto tiene salida, hay demanda y no hay competencia.</span>
        </li>
      </ul>
    </div>
  </div>

  <hr class="section-divider">

  <!-- SECCIÓN 7: CONCLUSIÓN -->
  <!-- ============================================ -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon" style="background: #f3f4f6; color: #141B36;">&#128203;</div>
      <div>
        <div class="section-title">7 · Conclusión del estudio</div>
        <div class="section-subtitle">Resumen ejecutivo · Calle D'Estoup 17, Las Torres de Cotillas</div>
      </div>
    </div>

    <div class="card" style="background: linear-gradient(135deg, #fafbfc 0%, #f3f4f6 100%); border: 2px solid #e5e7eb;">
      <ul class="conclusion-list">
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="3 12 7 12 10 4 14 20 17 12 21 12"></polyline></svg></span>
          <span><strong>PULSO:</strong> el producto pequeño es el de mayor liquidez de la zona (1 hab/1 baño al 84,6%, tramo por debajo de 125.000&euro; entre el 82 y el 88%, Calle D'Estoup al 100% de retirada).</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 12h6l2-9 4 18 2-9h6"></path></svg></span>
          <span><strong>IMPULSO (motor automático):</strong> unos 189.000&euro; por las 3 unidades, anclado en las dos viviendas del propio número 17 (1.875–1.997&euro;/m²).</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M9.5 2A2.5 2.5 0 0 1 12 4.5v15a2.5 2.5 0 0 1-5 0V4.5A2.5 2.5 0 0 1 9.5 2z"></path><path d="M14.5 7a2.5 2.5 0 0 1 2.5 2.5v8a2.5 2.5 0 0 1-5 0"></path></svg></span>
          <span><strong>MTVV (Programa IN):</strong> 179.500&euro; (Paso 4 verificado con un anuncio real).</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg></span>
          <span><strong>Convergencia IMPULSO ↔ Método Total:</strong> +5,3%, convergencia alta. El producto vale entre 180.000 y 190.000&euro;.</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 21h18"></path><path d="M5 21V7l8-4v18"></path><path d="M19 21V11l-6-4"></path></svg></span>
          <span><strong>Notarial:</strong> 858&euro;/m² escriturado, 110 operaciones al año, comprador joven (53% con menos de 40 años). Es el suelo y contexto oficial de la zona.</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline></svg></span>
          <span><strong>Demanda alta:</strong> el producto pequeño se retira en torno a 30 días (frente a 78 de media de la zona), y el nicho de 1 habitación no tiene competencia (oferta = 0).</span>
        </li>
        <li>
          <span class="cl-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg></span>
          <span><strong>Comprador objetivo:</strong> joven (53% con menos de 40 años) y más del 90% nacional. Encaja con el producto.</span>
        </li>
      </ul>
      <div class="verdict-navy" style="margin-bottom:0;">
        <div class="verdict-icon"><svg viewBox="0 0 24 24" fill="none" stroke="#FF4D2E" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"><polyline points="3 12 7 12 10 4 14 20 17 12 21 12"></polyline></svg></div>
        <div>No opinamos del mercado: lo medimos. Y lo medimos <strong>tres veces</strong> —testigos IM·PULSO, Portal del Notariado y MTVV (Programa IN)— con <strong>tres fuentes independientes</strong>. Las dos que valoran el producto convergen.</div>
      </div>
    </div>
  </div>
```

---

## TORRES-COTILLAS — Cruce IMPULSO×NOTARIADO Card

```html
    <!-- 3.6 Cruce Notarial × Mercado -->
    <div class="card" style="background: linear-gradient(135deg, #f5f3ff 0%, #fff3f0 100%); border: 2px solid #ddd6fe;">
      <div class="card-title" style="display:flex; align-items:center; gap:10px; flex-wrap:wrap;">
        <span style="background:#8B5CF6; color:white; width:28px; height:28px; border-radius:8px; display:inline-flex; align-items:center; justify-content:center; font-size:14px;">&#127963;&#65039;</span>
        <span>&times;</span>
        <span style="background:#FF4D2E; color:white; width:28px; height:28px; border-radius:8px; display:inline-flex; align-items:center; justify-content:center; font-size:14px;">&#128225;</span>
        <span>3.6 Cruce Notarial &times; Mercado</span>
      </div>
      <div class="card-subtitle">El valor que crea el Cambio de Uso, explicado con datos</div>
      <table class="table-mobile">
        <thead><tr><th>Indicador</th><th>Notarial (oficial)</th><th>Mercado (testigos IM·PULSO)</th><th>Lectura</th></tr></thead>
        <tbody>
        <tr><td>&euro; por m²</td><td data-label="Notarial (oficial)"><strong>858&euro;/m²</strong> (cierre real escriturado)</td><td data-label="Mercado (testigos)"><strong>~1.800&euro;/m²</strong> (producto pequeño reformado)</td><td data-label="Lectura">El producto reformado pequeño cotiza unas 2,1 veces el escriturado medio</td></tr>
        <tr><td>Tipo de producto</td><td data-label="Notarial (oficial)">Vivienda grande de 2ª mano (114 m² de media)</td><td data-label="Mercado (testigos)">Estudio / apartamento reformado de menos de 40 m²</td><td data-label="Lectura">Son tipologías distintas: no se comparan directamente</td></tr>
        </tbody>
      </table>
      <div style="margin-top: 18px; padding: 18px 20px; background: #141B36; border-radius: 12px; color: white;">
        <div style="font-size: 11px; text-transform: uppercase; letter-spacing: 1.5px; opacity: 0.6; margin-bottom: 8px; font-weight: 700;">Conclusión del cruce</div>
        <div style="font-size: 14px; line-height: 1.6;">
          La diferencia entre los <strong style="color:#FF4D2E;">858&euro;/m²</strong> escriturados de media y los <strong style="color:#FF4D2E;">~1.800&euro;/m²</strong> del producto pequeño reformado <strong>es el valor que crea el Cambio de Uso</strong>: transformar un local en producto pequeño reformado de alta rotación. No es especulación, es reposicionamiento de formato. El notariado marca el suelo real de la zona; el Cambio de Uso coloca el producto en una categoría de precio por m² superior por formato y estado.
        </div>
      </div>
    </div>
```

---

## TORRES-COTILLAS — Banderas SVG Inline (NL/GB/PL flags en tabla nacionalidades L1517-1526)

```html
<!-- MARRUECOS -->
<svg class="flag" viewBox="0 0 60 40"><rect width="60" height="40" fill="#c1272d"/><polygon fill="none" stroke="#006233" stroke-width="1.6" points="30,13.5 32.6,21.6 25.7,16.6 34.3,16.6 27.4,21.6"/></svg>

<!-- CHINA -->
<svg class="flag" viewBox="0 0 30 20"><rect width="30" height="20" fill="#de2910"/><g fill="#ffde00"><polygon points="5,2 6.18,5.6 2.9,3.4 7.1,3.4 3.82,5.6"/></g></svg>

<!-- REINO UNIDO (GB) -->
<svg class="flag" viewBox="0 0 60 40"><clipPath id="gb"><rect width="60" height="40"/></clipPath><rect width="60" height="40" fill="#012169"/><g clip-path="url(#gb)"><path d="M0,0 60,40M60,0 0,40" stroke="#fff" stroke-width="8"/><path d="M0,0 60,40M60,0 0,40" stroke="#C8102E" stroke-width="4"/><path d="M30,0 V40M0,20 H60" stroke="#fff" stroke-width="12"/><path d="M30,0 V40M0,20 H60" stroke="#C8102E" stroke-width="7"/></g></svg>

<!-- ITALIA -->
<svg class="flag" viewBox="0 0 6 4"><rect width="2" height="4" fill="#009246"/><rect x="2" width="2" height="4" fill="#fff"/><rect x="4" width="2" height="4" fill="#ce2b37"/></svg>

<!-- PAÍSES BAJOS (NL) -->
<svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#21468B"/><rect width="6" height="2.67" fill="#fff"/><rect width="6" height="1.33" fill="#AE1C28"/></svg>

<!-- ESPAÑA (en tabla Paso 4 interesados) -->
<svg class="flag" viewBox="0 0 6 4"><rect width="6" height="4" fill="#c60b1e"/><rect y="1" width="6" height="2" fill="#ffc400"/></svg>
```

---

## BENIARBEIG.HTML — Secciones Principales

Secciones encontradas (líneas clave):
- L615: `<!-- HEADER -->` — `<header class="header">` con logo + badge
- L623: `<!-- HERO -->` — `<section class="hero">` con h1, subtitle, op-ficha 6 cells, hero-sources, hero-cita
- L683: `<!-- DISCLAIMER PULSO -->` — aviso muestra pequeña
- L688: `<!-- SECCIÓN 1: PULSO -->` — `.section` con KPIs + Bloques 1A/2A/3A/4A/6A/TOP5/alquiler/sin muestra
- L1230: `<!-- SECCIÓN 2: IMPULSO -->` — `.section` Tipologías A/B/C/D + valoraciones
- L1587: `<!-- SECCIÓN 3: NOTARIADO -->` — `.section` con notarial-grid + perfil + tendencia + cruce
- L1737: `<!-- SECCIÓN 4: CONTACTOS -->` — `.section` contactos inmobiliarias por tipología
- L1894: `<!-- SECCIÓN 5: MÉTODO TOTAL -->` — `.section` MTVV pasos 0-4 + convergence box
- L2013: `<!-- FOOTER -->` — `<footer class="footer">`

---

## BENIARBEIG — Portada Completa

```html
<!-- ==================== HEADER ==================== -->
<header class="header">
  <div class="header-inner">
    <img src="https://assets.cdn.filesafe.space/9FLX4fUFluqRQ8w19kzs/media/697e322e1311f62a92201cc6.png" alt="IM·PULSO">
    <span class="badge">Informe V2 · Datos reales</span>
  </div>
</header>

<!-- ==================== HERO ==================== -->
<section class="hero">
  <h1>Informe IM·PULSO · V2</h1>
  <p class="subtitle">Av. del Vergel 5, Beniarbeig (CP 03778) · Edificio 20 viviendas + 20 plazas · obra parada</p>
  <p class="subtitle-2">Asking 750.000 € · Datos generados 19/06/2026</p>

  <div class="op-ficha">
    <div class="op-cell">
      <div class="op-key">Tipo operación</div>
      <div class="op-val">Segregación<small>Edificio → 20 unidades</small></div>
    </div>
    <div class="op-cell">
      <div class="op-key">Activo</div>
      <div class="op-val">1.755 m²<small>Obra parada / a terminar</small></div>
    </div>
    <div class="op-cell">
      <div class="op-key">Asking price</div>
      <div class="op-val">750.000 €<small>+ gastos ITP, notaría</small></div>
    </div>
    <div class="op-cell">
      <div class="op-key">Valoración (17 uds)</div>
      <div class="op-val" style="color:#FF4D2E;">2.702.000 €<small>3 uds sin valorar (sin muestra)</small></div>
    </div>
    <div class="op-cell">
      <div class="op-key">Notariado zona</div>
      <div class="op-val">1.636 €/m²<small>+9,3% variación anual</small></div>
    </div>
    <div class="op-cell">
      <div class="op-key">Rotación mercado</div>
      <div class="op-val">76% global<small>324 anuncios · 12 meses</small></div>
    </div>
  </div>

  <div class="hero-sources" style="align-items:stretch;">
    <div class="source-pill" style="border:2px solid rgba(16,185,129,0.3);">
      <div class="sp-icon">📡</div>
      <div class="sp-title" style="color:#10B981;">PULSO</div>
      <div style="font-size:12px;font-weight:700;color:white;margin:4px 0 2px;">Latido del Mercado</div>
      <div class="sp-desc">el pulso del mercado, DÓNDE comprar</div>
    </div>
    <div class="source-pill" style="border:2px solid rgba(255,77,46,0.3);">
      <div class="sp-icon">🎯</div>
      <div class="sp-title" style="color:#FF4D2E;">IMPULSO</div>
      <div style="font-size:12px;font-weight:700;color:white;margin:4px 0 2px;">Valoración del ACTIVO</div>
      <div class="sp-desc">hacia la decisión correcta, CUÁNTO pagar</div>
    </div>
    <div class="source-pill" style="border:2px solid rgba(107,114,128,0.3);opacity:0.7;">
      <div class="sp-icon">🔗</div>
      <div class="sp-title" style="color:rgba(255,255,255,0.7);">MÉTODO TOTAL</div>
      <div style="font-size:12px;font-weight:700;color:rgba(255,255,255,0.5);margin:4px 0 2px;">Integración pendiente de hacer</div>
      <div class="sp-desc">PULSO + IMPULSO + MTVV unificados</div>
    </div>
  </div>

  <p class="hero-cita">"PULSO te dice DÓNDE comprar. IMPULSO te dice CUÁNTO pagar."</p>
</section>
```

---

## BENIARBEIG — Bloque 1A PULSO

```html
<!-- ==================== SECCIÓN 1: PULSO ==================== -->
<div class="section">
  <div class="section-header">
    <div class="section-icon" style="background:#fff3f0;">📡</div>
    <div>
      <div class="section-title">1 · PULSO — Latido del mercado</div>
      <div class="section-subtitle">Periodo 06/05/2025 – 10/06/2026 · 324 anuncios · rotación 76%</div>
    </div>
    <span class="zone-badge pulso">PULSO</span>
  </div>

  <!-- KPIs globales -->
  <div class="kpi-row">
    <div class="kpi">
      <div class="kpi-value">324</div>
      <div class="kpi-label">Anuncios totales</div>
    </div>
    <div class="kpi">
      <div class="kpi-value">76%</div>
      <div class="kpi-label">Rotación global</div>
    </div>
    <div class="kpi">
      <div class="kpi-value">445.457 €</div>
      <div class="kpi-label">Precio medio venta</div>
    </div>
    <div class="kpi">
      <div class="kpi-value">249.750 €</div>
      <div class="kpi-label">Precio mediana venta</div>
    </div>
  </div>

  <!-- BLOQUE 1A: Por tipo de vivienda -->
  <div class="card">
    <div class="card-title">Bloque 1A · Por tipo de vivienda — Venta</div>
    <div class="card-subtitle">202 publicados · 157 retirados (78%) · 45 activos</div>
    <div class="legend">
      <span class="lg-item"><span class="lg-dot" style="background:#FF4D2E;"></span> Fila PULSO (tipología dominante en volumen)</span>
      <span class="lg-item"><span class="lg-dot" style="background:#3B82F6;"></span> Tipología de la operación (Piso y Ático)</span>
    </div>
    <table>
      <thead>
        <tr>
          <th>Tipo</th>
          <th>Publicados</th>
          <th>Retirados</th>
          <th>% Rotación</th>
          <th>Activos</th>
        </tr>
      </thead>
      <tbody>
        <tr class="highlight">
          <td><strong>Chalet</strong> <span class="mark mark-pulso">PULSO</span></td>
          <td><strong>130</strong> (64%)</td>
          <td><strong>104</strong></td>
          <td><strong>80%</strong></td>
          <td><strong>26</strong></td>
        </tr>
        <tr>
          <td>Piso <span class="mark mark-tipo">Tipología operación</span></td>
          <td>45 (22%)</td>
          <td>37</td>
          <td>82%</td>
          <td>8</td>
        </tr>
        <tr>
          <td>Casa Rural</td>
          <td>13 (6%)</td>
          <td>6</td>
          <td>46%</td>
          <td>7</td>
        </tr>
        <tr>
          <td>Dúplex</td>
          <td>7 (3%)</td>
          <td>5</td>
          <td>71%</td>
          <td>2</td>
        </tr>
        <tr>
          <td>Ático <span class="mark mark-tipo">Tipología operación</span></td>
          <td>4 (2%)</td>
          <td>3</td>
          <td>75%</td>
          <td>1</td>
        </tr>
        <tr>
          <td>Estudio</td>
          <td>2 (1%)</td>
          <td>2</td>
          <td>100%</td>
          <td>0</td>
        </tr>
        <tr>
          <td>Obra Nueva</td>
          <td>1 (0%)</td>
          <td>0</td>
          <td>0%</td>
          <td>1</td>
        </tr>
      </tbody>
    </table>
    <div class="insight insight-orange">
      <strong>Lectura:</strong> Chalet domina en volumen (64% del total). Mayor rotación por tipo: Piso (82%) y Chalet (80%). Menor rotación: Casa Rural (46%). El mercado de Beniarbeig es fundamentalmente un mercado de chalets.
    </div>
  </div>

  <!-- BLOQUE 2A: Por nº dormitorios -->
  <div class="card">
    <div class="card-title">Bloque 2A · Por nº de dormitorios — Venta</div>
    <div class="card-subtitle">201 publicados · 157 retirados (78%) · 44 activos</div>
    <table>
      <thead>
        <tr>
          <th>Dormitorios</th>
          <th>Publicados</th>
          <th>Retirados</th>
          <th>% Rotación</th>
          <th>Activos</th>
        </tr>
      </thead>
      <tbody>
        <tr class="highlight">
          <td><strong>3 dormitorios</strong> <span class="mark mark-pulso">PULSO</span></td>
          <td><strong>85</strong> (42%)</td>
          <td><strong>66</strong></td>
          <td><strong>78%</strong></td>
          <td><strong>19</strong></td>
        </tr>
        <tr>
          <td>4 dormitorios</td>
          <td>49 (24%)</td>
          <td>39</td>
          <td>80%</td>
          <td>10</td>
        </tr>
        <tr>
          <td>2 dormitorios</td>
          <td>35 (17%)</td>
          <td>30</td>
          <td>86%</td>
          <td>5</td>
        </tr>
        <tr>
          <td>5 dormitorios</td>
          <td>18 (9%)</td>
          <td>11</td>
          <td>61%</td>
          <td>7</td>
        </tr>
        <tr>
          <td>1 dormitorio</td>
          <td>7 (3%)</td>
          <td>6</td>
          <td>86%</td>
          <td>1</td>
        </tr>
        <tr>
          <td>Loft (0 hab)</td>
          <td>4 (2%)</td>
          <td>4</td>
          <td>100%</td>
          <td>0</td>
        </tr>
      </tbody>
    </table>
    <div class="insight insight-orange">
      <strong>Lectura:</strong> Mayor rotación: 2 dormitorios (86%) y 1 dormitorio (86%). Menor: 5 dormitorios (61%). El PULSO del mercado es 3 dormitorios por volumen; en rotación ganan las tipologías más pequeñas.
    </div>
  </div>

  <!-- BLOQUE 3A: Por dormitorios x baños -->
  <div class="card">
    <div class="card-title">Bloque 3A · Por dormitorios × baños — Venta</div>
    <div class="card-subtitle">177 publicados · 142 retirados (80%) · 35 activos</div>
    <table>
      <thead>
        <tr>
          <th>Dorm / Baños</th>
          <th>Publicados</th>
          <th>Retirados</th>
          <th>% Rotación</th>
          <th>Activos</th>
        </tr>
      </thead>
      <tbody>
        <tr class="highlight">
          <td><strong>3 dorm / 2 baños</strong> <span class="mark mark-pulso">PULSO</span></td>
          <td><strong>64</strong> (36%)</td>
          <td><strong>50</strong></td>
          <td><strong>78%</strong></td>
          <td><strong>14</strong></td>
        </tr>
        <tr>
          <td>4 dorm / 3 baños</td>
          <td>25 (14%)</td>
          <td>22</td>
          <td>88%</td>
          <td>3</td>
        </tr>
        <tr>
          <td>2 dorm / 1 baño</td>
          <td>23 (13%)</td>
          <td>19</td>
          <td>83%</td>
          <td>4</td>
        </tr>
        <tr>
          <td>4 dorm / 2 baños</td>
          <td>12 (7%)</td>
          <td>9</td>
          <td>75%</td>
          <td>3</td>
        </tr>
        <tr>
          <td>3 dorm / 3 baños</td>
          <td>12 (7%)</td>
          <td>10</td>
          <td>83%</td>
          <td>2</td>
        </tr>
        <tr>
          <td>2 dorm / 2 baños</td>
          <td>12 (7%)</td>
          <td>11</td>
          <td>92%</td>
          <td>1</td>
        </tr>
        <tr>
          <td>5 dorm / 1 baño</td>
          <td>10 (6%)</td>
          <td>6</td>
          <td>60%</td>
          <td>4</td>
        </tr>
        <tr>
          <td>5 dorm / 2 baños</td>
          <td>6 (3%)</td>
          <td>4</td>
          <td>67%</td>
          <td>2</td>
        </tr>
        <tr>
          <td>1 dorm / 1 baño</td>
          <td>6 (3%)</td>
          <td>5</td>
          <td>83%</td>
          <td>1</td>
        </tr>
        <tr>
          <td>Loft / 1 baño</td>
          <td>3 (2%)</td>
          <td>3</td>
          <td>100%</td>
          <td>0</td>
        </tr>
      </tbody>
    </table>
    <div class="insight insight-orange">
      <strong>Lectura:</strong> Mayor rotación: 2d/2b (92%) y 4d/3b (88%). El PULSO del mercado es 3d/2b por volumen (36%). La tipología de la operación (2d/2b) tiene la rotación más alta de todas las estudiadas.
    </div>
  </div>

  <!-- BLOQUE 4A: Por tramos de precio -->
  <div class="card">
    <div class="card-title">Bloque 4A · Por tramos de precio — Venta</div>
    <div class="card-subtitle">193 publicados · 153 retirados (79%) · Precio medio: 445.457 € · Mediana: 249.750 €</div>
    <table>
      <thead>
        <tr>
          <th>Tramo de precio</th>
          <th>Publicados</th>
          <th>Retirados</th>
          <th>% Rotación</th>
          <th>Activos</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Hasta 100.000 €</td>
          <td>2 (1%)</td>
          <td>2</td>
          <td>100%</td>
          <td>0</td>
        </tr>
        <tr class="highlight">
          <td><strong>100.000 – 200.000 €</strong> <span class="mark mark-pulso">PULSO</span></td>
          <td><strong>62</strong> (32%)</td>
          <td><strong>53</strong></td>
          <td><strong>85%</strong></td>
          <td><strong>9</strong></td>
        </tr>
        <tr>
          <td>200.000 – 300.000 €</td>
          <td>53 (27%)</td>
          <td>40</td>
          <td>75%</td>
          <td>13</td>
        </tr>
        <tr>
          <td>300.000 – 400.000 €</td>
          <td>6 (3%)</td>
          <td>5</td>
          <td>83%</td>
          <td>1</td>
        </tr>
        <tr>
          <td>400.000 – 500.000 €</td>
          <td>16 (8%)</td>
          <td>15</td>
          <td>94%</td>
          <td>1</td>
        </tr>
        <tr>
          <td>500.000 – 600.000 €</td>
          <td>12 (6%)</td>
          <td>7</td>
          <td>58%</td>
          <td>5</td>
        </tr>
        <tr>
          <td>600.000 – 700.000 €</td>
          <td>8 (4%)</td>
          <td>5</td>
          <td>63%</td>
          <td>3</td>
        </tr>
        <tr>
          <td>700.000 – 800.000 €</td>
          <td>16 (8%)</td>
          <td>12</td>
          <td>75%</td>
          <td>4</td>
        </tr>
        <tr>
          <td>800.000 – 900.000 €</td>
          <td>16 (8%)</td>
          <td>12</td>
          <td>75%</td>
          <td>4</td>
        </tr>
        <tr>
          <td>900.000 € – 1 M€</td>
          <td>2 (1%)</td>
          <td>2</td>
          <td>100%</td>
          <td>0</td>
        </tr>
      </tbody>
    </table>
    <div class="insight insight-orange">
      <strong>Lectura:</strong> Demanda concentrada en 100K–200K€ (32% del volumen, 85% rotación). Mayor rotación absoluta: 400K–500K€ (94%), aunque con menor volumen. Menor rotación: 500K–600K€ (58%). El precio de la operación (750K€ asking) cae en tramo 700–800K€: rotación del 75%, activos acumulados.
    </div>
  </div>

  <!-- BLOQUE 6A: Otros activos -->
  <div class="card">
    <div class="card-title">Bloque 6A · Otros activos — Venta</div>
    <div class="card-subtitle">96 publicados · 66 retirados (69%) · 30 activos</div>
    <table>
      <thead>
        <tr>
          <th>Tipo de activo</th>
          <th>Publicados</th>
          <th>Retirados</th>
          <th>% Rotación</th>
          <th>Activos</th>
        </tr>
      </thead>
      <tbody>
        <tr class="highlight">
          <td><strong>Garaje</strong> <span class="mark mark-pulso">PULSO</span></td>
          <td><strong>56</strong> (58%)</td>
          <td><strong>46</strong></td>
          <td><strong>82%</strong></td>
          <td><strong>10</strong></td>
        </tr>
        <tr>
          <td>Terreno</td>
          <td>30 (31%)</td>
          <td>16</td>
          <td>53%</td>
          <td>14</td>
        </tr>
        <tr>
          <td>Locales o Naves</td>
          <td>9 (9%)</td>
          <td>4</td>
          <td>44%</td>
          <td>5</td>
        </tr>
        <tr>
          <td>Edificio</td>
          <td>1 (1%)</td>
          <td>0</td>
          <td>0%</td>
          <td>1</td>
        </tr>
      </tbody>
    </table>
    <div class="insight insight-orange">
      <strong>Lectura:</strong> Garaje domina en volumen (58%) y en rotación (82%). Las 20 plazas de garaje del edificio tienen mercado activo. Terreno: rotación moderada (53%). Edificios: sin operaciones registradas en el período.
    </div>
  </div>
</div>
```

---

## BENIARBEIG — NOTARIADO

```html
<!-- ==================== SECCIÓN 3: NOTARIADO ==================== -->
<div class="section">
  <div class="section-header">
    <div class="section-icon" style="background:#f5f3ff;">📋</div>
    <div>
      <div class="section-title">3 · NOTARIADO — Contexto oficial</div>
      <div class="section-subtitle">CP 03778 · Pisos 2ª mano · mayo 2025 – abril 2026 · 28 operaciones reales</div>
    </div>
    <span class="zone-badge notarial">NOTARIADO</span>
  </div>

  <div class="notarial-grid">
    <div class="nat-box">
      <div class="nb-val">1.636 €/m²</div>
      <div class="nb-label">Precio escriturado</div>
    </div>
    <div class="nat-box">
      <div class="nb-val">28 ops/año</div>
      <div class="nb-label">~2 operaciones/mes</div>
    </div>
    <div class="nat-box">
      <div class="nb-val">+9,3%</div>
      <div class="nb-label">Variación anual</div>
    </div>
    <div class="nat-box">
      <div class="nb-val">150.680 €</div>
      <div class="nb-label">Importe medio escriturado</div>
    </div>
    <div class="nat-box">
      <div class="nb-val">51,5%</div>
      <div class="nb-label">Compradores extranjeros</div>
    </div>
    <div class="nat-box">
      <div class="nb-val">Julio</div>
      <div class="nb-label">Mejor mes (pico +22%)</div>
    </div>
  </div>

  <!-- Perfil comprador -->
  <div class="card">
    <div class="card-title">Perfil del comprador en Beniarbeig (CP 03778)</div>
    <div class="card-subtitle">Fuente: datos notariales mayo 2025 – abril 2026</div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:12px;">
      <div>
        <p style="font-size:12px;text-transform:uppercase;letter-spacing:1px;color:#8B5CF6;font-weight:700;margin-bottom:8px;">Origen del comprador</p>
        <table>
          <thead><tr><th>Origen</th><th>%</th></tr></thead>
          <tbody>
            <tr><td>Nacionales</td><td>48,48%</td></tr>
            <tr class="highlight"><td>🇳🇱 Países Bajos</td><td><strong>13,14%</strong></td></tr>
            <tr><td>🇬🇧 Reino Unido</td><td>10,49%</td></tr>
            <tr><td>🇵🇱 Polonia</td><td>8,46%</td></tr>
            <tr><td>Resto extranjeros</td><td>19,41%</td></tr>
          </tbody>
        </table>
      </div>
      <div>
        <p style="font-size:12px;text-transform:uppercase;letter-spacing:1px;color:#8B5CF6;font-weight:700;margin-bottom:8px;">Perfil demográfico</p>
        <table>
          <thead><tr><th>Indicador</th><th>Dato</th></tr></thead>
          <tbody>
            <tr><td>Edad dominante</td><td><strong>41–60 años (51%)</strong></td></tr>
            <tr><td>Edad más frecuente</td><td>41–50 años (25,78%)</td></tr>
            <tr><td>Mediana de edad</td><td>49 años</td></tr>
            <tr><td>Personas físicas</td><td>90,93%</td></tr>
            <tr><td>Personas jurídicas</td><td>9,1%</td></tr>
          </tbody>
        </table>
      </div>
    </div>
    <div class="insight insight-purple" style="margin-top:12px;">
      <strong>Lectura:</strong> El comprador tipo es un extranjero europeo de mediana edad (NL, UK, PL) buscando segunda residencia en la Costa Blanca. Esto valida el perfil de marketing para las unidades de la operación — orientar la campaña a compradores nórdicos y británicos con perfil 40-60 años.
    </div>
  </div>

  <!-- Tendencia histórica -->
  <div class="card">
    <div class="card-title">Tendencia histórica de precios</div>
    <div class="card-subtitle">Variación anual — CP 03778 (Beniarbeig)</div>
    <table>
      <thead>
        <tr>
          <th>Año</th>
          <th>Variación</th>
          <th>Tendencia</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>2016</td><td>+1,66%</td><td>↗</td></tr>
        <tr><td>2017</td><td>+2,90%</td><td>↗</td></tr>
        <tr><td>2018</td><td>+3,42%</td><td>↗</td></tr>
        <tr><td>2019</td><td>+4,30%</td><td>↗</td></tr>
        <tr><td>2020</td><td>-1,22%</td><td style="color:#EF4444;">↘ COVID</td></tr>
        <tr><td>2021</td><td>+6,90%</td><td>↗</td></tr>
        <tr><td>2022</td><td>+8,82%</td><td>↗↗</td></tr>
        <tr><td>2023</td><td>+5,96%</td><td>↗</td></tr>
        <tr><td>2024</td><td>+8,69%</td><td>↗↗</td></tr>
        <tr class="highlight"><td><strong>2025</strong></td><td><strong>+9,30%</strong></td><td>↗↗ Aceleración</td></tr>
      </tbody>
    </table>
    <div class="insight insight-purple" style="margin-top:8px;">
      Tendencia alcista continuada desde 2020. 2025 marca el mayor crecimiento en la serie histórica (+9,3%). Contexto favorable para la operación.
    </div>
  </div>

  <!-- Cruce IMPULSO vs Notariado -->
  <div class="card">
    <div class="card-title">Cruce IMPULSO × Notariado</div>
    <div class="card-subtitle">Validación cruzada de señales de mercado</div>
    <table>
      <thead>
        <tr>
          <th>Señal</th>
          <th>Notariado</th>
          <th>IMPULSO</th>
          <th>Lectura</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Tendencia precios</td>
          <td>+9,3% año en curso</td>
          <td>+10% en 12 meses (estimado)</td>
          <td>✅ Alcista, alineado</td>
        </tr>
        <tr>
          <td>Velocidad de mercado</td>
          <td>28 ops/año · ~2/mes</td>
          <td>Piso 1d: 49 días · Piso 2d: 110 días</td>
          <td>⚠️ Mercado lento — 20 uds = 10 meses de mercado</td>
        </tr>
        <tr>
          <td>€/m² referencia</td>
          <td>1.636 €/m² escriturado</td>
          <td>1.639–2.260 €/m² según tipología</td>
          <td>✅ IMPULSO por encima — esperable (notariado agrega todos los estados)</td>
        </tr>
        <tr>
          <td>Mejor momento venta</td>
          <td>Julio (pico +22% vs media)</td>
          <td>Piso 1d tarda 49 días → lanzar en mayo-junio</td>
          <td>✅ Lanzar en Q2 para cerrar en julio</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
```

---

## BENIARBEIG — MTVV Actual

```html
<!-- ==================== SECCIÓN 5: MÉTODO TOTAL ==================== -->
<div class="section">
  <div class="section-header">
    <div class="section-icon" style="background:#ecfdf5;">✅</div>
    <div>
      <div class="section-title">5 · Método Total de Validación de Valor (MTVV)</div>
      <div class="section-subtitle">Validación humana complementaria al análisis automatizado · precio de referencia: 154.000 €</div>
    </div>
    <span class="zone-badge mtvv">MTVV</span>
  </div>

  <!-- Paso 0 -->
  <div class="card">
    <div class="step-header">
      <div class="step-number done">0</div>
      <div class="step-title">Paso 0 — Contexto del micromercado <span style="display:inline-block;background:#d1fae5;color:#065f46;padding:2px 10px;border-radius:6px;font-size:11px;font-weight:700;margin-left:8px;">✓ HECHO</span></div>
    </div>
    <div class="kpi-row">
      <div class="kpi"><div class="kpi-value">1.983</div><div class="kpi-label">Habitantes</div></div>
      <div class="kpi"><div class="kpi-value">+2,91%</div><div class="kpi-label">Crecimiento</div></div>
      <div class="kpi"><div class="kpi-value">1.931 €/m²</div><div class="kpi-label">Precio zona</div></div>
      <div class="kpi"><div class="kpi-value">+7,52%</div><div class="kpi-label">Mercado anual</div></div>
    </div>
    <table style="margin-top:8px;">
      <thead><tr><th>Parámetro</th><th>Dato</th></tr></thead>
      <tbody>
        <tr><td>Renta media</td><td>12.333 €/persona</td></tr>
        <tr><td>Precio colindantes / ciudad</td><td>1.708 €/m² / 2.279 €/m²</td></tr>
        <tr><td>Oferta actual en venta</td><td>13 viviendas (7 casas/chalets, 5 pisos, 1 ático)</td></tr>
        <tr><td>Target</td><td>Familias nacionales con hijos</td></tr>
        <tr><td>Comprador</td><td>80,33% nacional / 19,67% extranjero (RU, Marruecos, Italia, Alemania, Rumanía)</td></tr>
        <tr><td>Edad mediana comprador</td><td>48 años · franja 41-50: 26,44%</td></tr>
      </tbody>
    </table>
  </div>

  <!-- Paso 1 -->
  <div class="card">
    <div class="step-header">
      <div class="step-number done">1</div>
      <div class="step-title">Paso 1 — Sondeo de inmobiliarias <span style="display:inline-block;background:#d1fae5;color:#065f46;padding:2px 10px;border-radius:6px;font-size:11px;font-weight:700;margin-left:8px;">✓ HECHO</span></div>
    </div>
    <div class="insight insight-green">
      10 inmobiliarias consultadas · rango 134.543 – 154.333 €
    </div>
    <div class="step-price">
      <div class="sp-label">Conclusión Paso 1 (inmobiliarias)</div>
      <div class="sp-value">150.000 €</div>
    </div>
  </div>

  <!-- Paso 2 -->
  <div class="card">
    <div class="step-header">
      <div class="step-number done">2</div>
      <div class="step-title">Paso 2 — Testigos de anuncios <span style="display:inline-block;background:#d1fae5;color:#065f46;padding:2px 10px;border-radius:6px;font-size:11px;font-weight:700;margin-left:8px;">✓ HECHO</span></div>
    </div>
    <div class="insight insight-green">
      7 testigos analizados · rango 142.000 – 154.000 €
    </div>
    <div class="step-price">
      <div class="sp-label">Conclusión Paso 2 (testigos)</div>
      <div class="sp-value">145.000 €</div>
    </div>
  </div>

  <!-- Paso 3 -->
  <div class="card">
    <div class="step-header">
      <div class="step-number done">3</div>
      <div class="step-title">Paso 3 — Hipótesis de precio <span style="display:inline-block;background:#d1fae5;color:#065f46;padding:2px 10px;border-radius:6px;font-size:11px;font-weight:700;margin-left:8px;">✓ HECHO</span></div>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px;text-align:center;margin:12px 0;">
      <div style="background:#ecfdf5;padding:16px;border-radius:12px;">
        <div style="font-size:11px;color:#10B981;text-transform:uppercase;letter-spacing:1px;font-weight:700;">Paso 1 dice</div>
        <div style="font-size:22px;font-weight:800;color:#141B36;margin-top:4px;">150.000 €</div>
      </div>
      <div style="background:#ecfdf5;padding:16px;border-radius:12px;">
        <div style="font-size:11px;color:#10B981;text-transform:uppercase;letter-spacing:1px;font-weight:700;">Paso 2 dice</div>
        <div style="font-size:22px;font-weight:800;color:#141B36;margin-top:4px;">145.000 €</div>
      </div>
      <div style="background:#fff3f0;padding:16px;border-radius:12px;border:2px solid #FF4D2E;">
        <div style="font-size:11px;color:#FF4D2E;text-transform:uppercase;letter-spacing:1px;font-weight:700;">Hipótesis</div>
        <div style="font-size:22px;font-weight:800;color:#FF4D2E;margin-top:4px;">154.000 €</div>
      </div>
    </div>
    <div class="step-price">
      <div class="sp-label">Conclusión Paso 3 (hipótesis)</div>
      <div class="sp-value">154.000 €</div>
    </div>
  </div>

  <!-- Paso 4 -->
  <div class="card" style="border-color:#fde68a;background:#fffbeb;">
    <div class="step-header">
      <div class="step-number pending">4</div>
      <div class="step-title" style="color:#92400e;">Paso 4 — Anuncio real publicado <span style="display:inline-block;background:#fde68a;color:#92400e;padding:2px 10px;border-radius:6px;font-size:11px;font-weight:700;margin-left:8px;">FALTA POR HACER</span></div>
    </div>
    <div class="insight insight-yellow">
      Pendiente de publicar un anuncio real para verificar la respuesta del mercado al precio hipótesis de 154.000 €.
    </div>
    <div class="step-price" style="background:#92400e;">
      <div class="sp-label">Precio verificado con anuncio real</div>
      <div class="sp-value" style="color:#fde68a;">Pendiente</div>
      <div class="sp-note">Publicar anuncio y medir interés a 154.000 €</div>
    </div>
  </div>

  <!-- Precio MTVV referencia -->
  <div class="convergence">
    <div class="conv-label">Precio MTVV de referencia (Paso 4 pendiente)</div>
    <div class="conv-total">154.000 €</div>
    <div class="conv-note">Hipótesis basada en Paso 1 (inmobiliarias) + Paso 2 (testigos). Pendiente confirmación con anuncio real.</div>
    <div class="conv-warn">⚠️ Precio no confirmado hasta completar el Paso 4 — publicar anuncio real y medir respuesta del mercado.</div>
  </div>
</div>
```
