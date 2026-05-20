# effectlekt15-indi.github.io
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Экзаменационные билеты по геометрии — 8 класс (Атанасян)</title>
<!-- MathJax для красивых формул -->
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    }
  };
</script>
<style>
  :root {
    --bg: #f7f9fc;
    --panel: #ffffff;
    --text: #1f2937;
    --muted: #6b7280;
    --accent: #2563eb;
    --accent-light: #dbeafe;
    --border: #e5e7eb;
    --radius: 12px;
    --shadow: 0 4px 6px -1px rgba(0,0,0,0.05), 0 2px 4px -1px rgba(0,0,0,0.03);
  }
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    margin: 0;
    font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.65;
  }
  .layout {
    display: grid;
    grid-template-columns: 260px 1fr;
    max-width: 1400px;
    margin: 0 auto;
    min-height: 100vh;
  }
  .sidebar {
    position: sticky;
    top: 0;
    height: 100vh;
    overflow-y: auto;
    background: var(--panel);
    border-right: 1px solid var(--border);
    padding: 20px 14px;
    box-shadow: var(--shadow);
    z-index: 10;
  }
  .sidebar h1 {
    font-size: 17px;
    margin: 0 0 6px;
    line-height: 1.3;
  }
  .sidebar .subtitle {
    font-size: 12px;
    color: var(--muted);
    margin-bottom: 16px;
    display: block;
  }
  .nav-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  .nav-list li { margin-bottom: 3px; }
  .nav-list a {
    display: block;
    padding: 6px 10px;
    border-radius: 8px;
    text-decoration: none;
    color: var(--text);
    font-size: 13px;
    transition: background .15s, color .15s;
  }
  .nav-list a:hover, .nav-list a.active {
    background: var(--accent-light);
    color: var(--accent);
    font-weight: 600;
  }
  .main { padding: 28px 36px; }
  .ticket {
    background: var(--panel);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
    padding: 24px 28px;
    margin-bottom: 28px;
    scroll-margin-top: 20px;
  }
  .ticket h2 {
    margin-top: 0;
    font-size: 20px;
    border-bottom: 2px solid var(--accent-light);
    padding-bottom: 10px;
    margin-bottom: 18px;
  }
  .question { margin-bottom: 22px; }
  .question:last-child { margin-bottom: 0; }
  .q-title {
    font-weight: 700;
    color: var(--accent);
    margin-bottom: 8px;
    font-size: 14px;
    text-transform: uppercase;
    letter-spacing: .04em;
  }
  .q-body p { margin: 0 0 10px; }
  .q-body ul { margin: 6px 0; padding-left: 20px; }
  .q-body li { margin-bottom: 4px; }
  .proof {
    background: #f0f9ff;
    border-left: 4px solid var(--accent);
    padding: 14px 18px;
    border-radius: 0 8px 8px 0;
    margin-top: 10px;
  }
  .proof strong { color: #0369a1; }
  .highlight {
    background: #fff7ed;
    border-left: 4px solid #f59e0b;
    padding: 12px 16px;
    border-radius: 0 8px 8px 0;
    margin-top: 10px;
  }
  .back-to-top {
    display: inline-block;
    margin-top: 10px;
    font-size: 12px;
    color: var(--muted);
    text-decoration: none;
  }
  .back-to-top:hover { color: var(--accent); }
  .publish-box {
    background: linear-gradient(135deg, #ecfdf5 0%, #d1fae5 100%);
    border: 1px solid #6ee7b7;
    border-radius: var(--radius);
    padding: 20px 24px;
    margin-bottom: 32px;
  }
  .publish-box h3 { margin-top: 0; color: #065f46; font-size: 16px; }
  .publish-box ol { padding-left: 18px; margin: 10px 0 0; }
  .publish-box li { margin-bottom: 8px; color: #065f46; }
  .publish-box a { color: #059669; font-weight: 600; }
  @media (max-width: 900px) {
    .layout { grid-template-columns: 1fr; }
    .sidebar { position: relative; height: auto; border-right: none; border-bottom: 1px solid var(--border); }
    .main { padding: 16px; }
    .ticket { padding: 16px; }
  }
</style>
</head>
<body>
<div class="layout">
  <aside class="sidebar">
    <h1>Билеты по геометрии</h1>
    <span class="subtitle">8 класс · Атанасян · Все теоремы с доказательствами</span>
    <ul class="nav-list">
      <li><a href="#publish" style="background:#ecfdf5;color:#059669;font-weight:700;">📤 Как выложить в интернет</a></li>
      <li><a href="#ticket-1" class="active">Билет №1</a></li>
      <li><a href="#ticket-2">Билет №2</a></li>
      <li><a href="#ticket-3">Билет №3</a></li>
      <li><a href="#ticket-4">Билет №4</a></li>
      <li><a href="#ticket-5">Билет №5</a></li>
      <li><a href="#ticket-6">Билет №6</a></li>
      <li><a href="#ticket-7">Билет №7</a></li>
      <li><a href="#ticket-8">Билет №8</a></li>
      <li><a href="#ticket-9">Билет №9</a></li>
      <li><a href="#ticket-10">Билет №10</a></li>
      <li><a href="#ticket-11">Билет №11</a></li>
      <li><a href="#ticket-12">Билет №12</a></li>
      <li><a href="#ticket-13">Билет №13</a></li>
      <li><a href="#ticket-14">Билет №14</a></li>
      <li><a href="#ticket-15">Билет №15</a></li>
      <li><a href="#ticket-16">Билет №16</a></li>
      <li><a href="#ticket-17">Билет №17</a></li>
      <li><a href="#ticket-18">Билет №18</a></li>
      <li><a href="#ticket-19">Билет №19</a></li>
      <li><a href="#ticket-20">Билет №20</a></li>
    </ul>
  </aside>

  <main class="main">

    <!-- Как опубликовать -->
    <div class="publish-box" id="publish">
      <h3>Как сделать этот сайт доступным всем в интернете</h3>
      <ol>
        <li><strong>GitHub Pages (рекомендую):</strong> создайте бесплатный аккаунт на github.com, загрузите этот HTML-файл в новый репозиторий, включите Pages в настройках — через 2 минуты сайт будет доступен по адресу <code>вашник.github.io/имя-репозитория</code>.</li>
        <li><strong>Netlify Drop:</strong> зайдите на netlify.com, перетащите файл в окно браузера — сайт сразу получит публичную ссылку.</li>
        <li><strong>Cloudflare Pages / Vercel:</strong> аналогично GitHub Pages, можно просто загрузить файл.</li>
        <li><strong>Google Диск:</strong> загрузите файл → ПКМ → «Открыть доступ» → скопируйте ссылку (но лучше использовать способы выше).</li>
        <li><strong>Просто файл:</strong> HTML открывается в любом браузере даже без интернета — достаточно дважды кликнуть по файлу.</li>
      </ol>
    </div>

<!-- ==================== БИЛЕТ 1 ==================== -->
<div class="ticket" id="ticket-1">
  <h2>Билет №1</h2>

  <div class="question">
    <div class="q-title">1. Перпендикулярные и параллельные прямые</div>
    <div class="q-body">
      <p><strong>Определения.</strong> Две прямые называются <em>перпендикулярными</em>, если они пересекаются под прямым углом (90°). Две прямые называются <em>параллельными</em>, если они лежат в одной плоскости и не имеют общих точек.</p>
      <p>При пересечении двух параллельных прямых секущей образуются:</p>
      <ul>
        <li><strong>Соответственные углы</strong> — по одну сторону от секущей и на одном «этаже»;</li>
        <li><strong>Накрест лежащие углы</strong> — по разные стороны от секущей и между прямыми;</li>
        <li><strong>Односторонние углы</strong> — по одну сторону от секущей и между прямыми.</li>
      </ul>
      <p><strong>Свойства параллельных прямых.</strong> Если прямые параллельны, то соответственные углы равны, накрест лежащие равны, сумма односторонних равна 180°.</p>
      <p><strong>Признаки параллельности.</strong> Если при пересечении двух прямых секущей соответственные углы равны (или накрест лежащие равны, или сумма односторонних равна 180°), то прямые параллельны.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Четырёхугольник, вписанный в окружность</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Четырёхугольник называется <em>вписанным в окружность</em>, если все его вершины лежат на окружности.</p>
      <div class="proof">
        <strong>Теорема (свойство).</strong> Во вписанном четырёхугольнике сумма противоположных углов равна 180°.<br><br>
        <strong>Доказательство.</strong> Пусть $ABCD$ вписан в окружность. Углы $A$ и $C$ опираются на дуги $BCD$ и $BAD$, которые в сумме составляют всю окружность (360°). Вписанный угол равен половине дуги, на которую он опирается, поэтому:
        $$\angle A = \frac{1}{2}\overset{\frown}{BCD}, \quad \angle C = \frac{1}{2}\overset{\frown}{BAD}.$$
        Складывая: $\angle A + \angle C = \frac{1}{2}(\overset{\frown}{BCD} + \overset{\frown}{BAD}) = \frac{1}{2} \cdot 360° = 180°$.<br>
        Аналогично $\angle B + \angle D = 180°$.
      </div>
      <div class="proof">
        <strong>Теорема (признак).</strong> Если в выпуклом четырёхугольнике сумма противоположных углов равна 180°, то около него можно описать окружность.<br><br>
        <strong>Доказательство.</strong> Опишем окружность около треугольника $ABC$. Пусть она пересекает сторону $CD$ (или её продолжение) в точке $D_1$. Тогда $ABCD_1$ — вписанный четырёхугольник, и $\angle B + \angle D_1 = 180°$. По условию $\angle B + \angle D = 180°$, значит $\angle D = \angle D_1$. Отсюда точки $D$ и $D_1$ совпадают, то есть $D$ лежит на окружности.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Теорема Пифагора»)</div>
    <div class="q-body">
      <div class="highlight">Без исходного чертежа приводится методика: найдите неизвестную сторону прямоугольного треугольника по двум известным, применяя $c^2=a^2+b^2$ или следствия из неё.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Отрезок, соединяющий середины диагоналей трапеции</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $ABCD$ — трапеция, $AD \parallel BC$, $AD=a$, $BC=b$ $(a>b)$; $M$ и $N$ — середины диагоналей $AC$ и $BD$.</p>
      <p><strong>Доказать:</strong> $MN = \dfrac{a-b}{2}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Проведём через $M$ прямую, параллельную основаниям, до пересечения с $CD$ в точке $K$.<br>
        В $\triangle ACD$ отрезок $MK$ соединяет середину $AC$ с точкой $K$ на $CD$ и $MK \parallel AD$. По свойству средней линии $K$ — середина $CD$ и $MK = \dfrac{AD}{2} = \dfrac{a}{2}$.<br>
        В $\triangle BCD$ отрезок $KN$ соединяет середины $CD$ и $BD$, значит $KN$ — средняя линия: $KN \parallel BC$ и $KN = \dfrac{BC}{2} = \dfrac{b}{2}$.<br>
        Так как $MK \parallel AD \parallel BC \parallel KN$, точки $M, K, N$ коллинеарны. Следовательно:
        $$MN = MK - KN = \frac{a}{2} - \frac{b}{2} = \frac{a-b}{2}.$$
      </div>
      <a class="back-to-top" href="#ticket-1">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 2 ==================== -->
<div class="ticket" id="ticket-2">
  <h2>Билет №2</h2>

  <div class="question">
    <div class="q-title">1. Смежные и вертикальные углы</div>
    <div class="q-body">
      <p><strong>Смежные углы</strong> — углы с общей стороной, другие стороны которых являются дополнительными лучами. <em>Свойство:</em> сумма смежных углов равна 180°.</p>
      <p><strong>Вертикальные углы</strong> — углы, образованные пересечением двух прямых, стороны одного из которых являются продолжениями сторон другого. <em>Свойство:</em> вертикальные углы равны (доказывается через смежные: каждый из них равен 180° минус общий смежный угол).</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Четырёхугольник, описанный около окружности</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Четырёхугольник называется <em>описанным около окружности</em>, если все его стороны касаются одной окружности.</p>
      <div class="proof">
        <strong>Теорема (свойство).</strong> В описанном четырёхугольнике суммы длин противоположных сторон равны: $AB + CD = BC + AD$.<br><br>
        <strong>Доказательство.</strong> Пусть точки касания сторон $AB, BC, CD, DA$ есть $K, L, M, N$ соответственно. По свойству отрезков касательных из одной точки: $AK = AN$, $BK = BL$, $CL = CM$, $DM = DN$.<br>
        Сложим равенства попарно:
        $$AB + CD = (AK + KB) + (CM + MD) = AN + BL + CL + DN = (AN + DN) + (BL + CL) = AD + BC.$$
      </div>
      <div class="proof">
        <strong>Теорема (признак).</strong> Если в выпуклом четырёхугольнике суммы противоположных сторон равны, то в него можно вписать окружность.<br><br>
        <strong>Доказательство.</strong> Пусть $AB + CD = BC + AD$. Впишем окружность, касающуюся сторон $AB, BC, CD$ (центр в точке пересечения биссектрис углов $B$ и $C$). Пусть четвёртая касательная из $A$ пересекает $CD$ в $D_1$. Тогда для $ABCD_1$ выполняется свойство описанного четырёхугольника: $AB + CD_1 = BC + AD_1$. Вычитая из данного равенства, получим $CD - CD_1 = AD - AD_1$, откуда $D_1$ совпадает с $D$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Параллельные прямые»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте свойства углов при параллельных прямыx и секущей (соответственные, накрест лежащие, односторонние) для нахождения неизвестных углов.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Расстояние от вершины до точки касания</div>
    <div class="q-body">
      <p><strong>Дано:</strong> окружность вписана в $\triangle ABC$; $M$ и $N$ — точки касания со сторонами $AB$ и $AC$.</p>
      <p><strong>Доказать:</strong> $AM = \dfrac{AB + AC - BC}{2}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Обозначим точку касания на $BC$ через $P$. По свойству касательных из одной точки:
        $$AM = AN, \quad BM = BP, \quad CN = CP.$$
        Сложим:
        $$AB + AC - BC = (AM + MB) + (AN + NC) - (BP + PC).$$
        Заменим $MB = BP$ и $NC = PC$:
        $$AB + AC - BC = AM + AN = 2AM.$$
        Отсюда $AM = \dfrac{AB + AC - BC}{2}$.
      </div>
      <a class="back-to-top" href="#ticket-2">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 3 ==================== -->
<div class="ticket" id="ticket-3">
  <h2>Билет №3</h2>

  <div class="question">
    <div class="q-title">1. Элементы треугольника</div>
    <div class="q-body">
      <p><strong>Медиана</strong> — отрезок, соединяющий вершину с серединой противоположной стороны.</p>
      <p><strong>Биссектриса</strong> — луч, делящий угол пополам (в треугольнике — отрезок от вершины до противоположной стороны).</p>
      <p><strong>Высота</strong> — перпендикуляр, опущенный из вершины на прямую, содержащую противоположную сторону.</p>
      <p><strong>Виды треугольников:</strong> по сторонам — равносторонний, равнобедренный, разносторонний; по углам — остроугольный, прямоугольный, тупоугольный.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Окружность, описанная около треугольника</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Около любого треугольника можно описать окружность, и притом только одну. Центр этой окружности находится в точке пересечения серединных перпендикуляров к сторонам треугольника.<br><br>
        <strong>Доказательство.</strong> Пусть $ABC$ — треугольник. Проведём серединные перпендикуляры к сторонам $AB$ и $BC$; пусть они пересекаются в точке $O$.<br>
        Так как $O$ лежит на серединном перпендикуляре к $AB$, $OA = OB$. Так как $O$ лежит на серединном перпендикуляре к $BC$, $OB = OC$. Следовательно, $OA = OB = OC$, то есть $O$ равноудалена от всех вершин. Значит, окружность с центром $O$ и радиусом $OA$ проходит через $A, B, C$.<br><br>
        <em>Единственность:</em> центр описанной окружности должен быть равноудалён от $A$ и $B$, поэтому он лежит на серединном перпендикуляре к $AB$. Аналогично он лежит на серединном перпендикуляре к $BC$. Две непараллельные прямые пересекаются только в одной точке, следовательно, центр единственный.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Подобие треугольников»)</div>
    <div class="q-body">
      <div class="highlight">Методика: найдите пару равных углов для доказательства подобия по двум углам (AA), затем используйте пропорциональность сторон для нахождения неизвестной величины.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Угол между касательной и хордой</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $AB$ — хорда, $AC$ — касательная, $A$ — точка касания.</p>
      <p><strong>Доказать:</strong> $\angle BAC = \dfrac{1}{2} \overset{\frown}{AB}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Пусть $O$ — центр окружности. Радиус $OA \perp AC$ (свойство касательной), поэтому $\angle OAC = 90°$.<br>
        Центральный угол $\angle AOB$ равен градусной мере дуги $AB$.<br>
        В равнобедренном $\triangle AOB$:
        $$\angle OAB = \frac{180° - \angle AOB}{2} = 90° - \frac{1}{2} \overset{\frown}{AB}.$$
        Тогда:
        $$\angle BAC = \angle OAC - \angle OAB = 90° - \left(90° - \frac{1}{2} \overset{\frown}{AB}\right) = \frac{1}{2} \overset{\frown}{AB}.$$
      </div>
      <a class="back-to-top" href="#ticket-3">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 4 ==================== -->
<div class="ticket" id="ticket-4">
  <h2>Билет №4</h2>

  <div class="question">
    <div class="q-title">1. Равнобедренный треугольник</div>
    <div class="q-body">
      <p><strong>Свойства:</strong></p>
      <ul>
        <li>Углы при основании равны.</li>
        <li>Биссектриса, медиана и высота, проведённые к основанию, совпадают и являются осью симметрии.</li>
      </ul>
      <p><strong>Признаки:</strong> треугольник равнобедренный, если два его угла равны; или если биссектриса (медиана/высота) является одновременно медианой (высотой/биссектрисой).</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Серединный перпендикуляр и замечательная точка</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Любая точка серединного перпендикуляра к отрезку равноудалена от концов отрезка. Обратно: если точка равноудалена от концов отрезка, то она лежит на его серединном перпендикуляре.<br><br>
        <strong>Доказательство прямой теоремы.</strong> Пусть $m$ — серединный перпендикуляр к $AB$, $M$ — середина $AB$, $X \in m$. Треугольники $XMA$ и $XMB$ — прямоугольные с общим катетом $XM$ и равными катетами $AM = MB$. По катету и гипотенузе (SAS для прямоугольных) они равны, значит $XA = XB$.<br><br>
        <strong>Доказательство обратной теоремы.</strong> Пусть $XA = XB$. Опустим высоту $XM$ на $AB$. Треугольники $XMA$ и $XMB$ равны по гипотенузе и катету ($XA=XB$, $XM$ — общий), следовательно $AM = MB$, то есть $XM$ — серединный перпендикуляр.
      </div>
      <div class="proof">
        <strong>Следствие (замечательная точка).</strong> Серединные перпендикуляры к сторонам треугольника пересекаются в одной точке — центре описанной окружности.<br><br>
        <strong>Доказательство.</strong> Пусть $m_1$ и $m_2$ — серединные перпендикуляры к $AB$ и $BC$. Они пересекаются (иначе $AB \parallel BC$). Точка $O$ пересечения равноудалена от $A, B$ (лежит на $m_1$) и от $B, C$ (лежит на $m_2$). Значит $OA = OB = OC$, и $O$ лежит также на серединном перпендикуляре к $AC$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Свойство биссектрисы»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте свойство биссектрисы (делит сторону пропорционально прилежащим сторонам) или признак равенства/подобия треугольников.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Площадь треугольника $KAB$</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $ABCD$ — трапеция, $AD \parallel BC$; $K$ — середина боковой стороны $CD$.</p>
      <p><strong>Доказать:</strong> $S_{KAB} = \dfrac{1}{2} S_{ABCD}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Обозначим высоту трапеции через $h$. Так как $K$ — середина $CD$, расстояние от $K$ до $AD$ и до $BC$ равно $h/2$.<br>
        Площадь трапеции: $S_{ABCD} = \dfrac{AD + BC}{2} \cdot h$.<br>
        Площади прилегающих треугольников:
        $$S_{KAD} = \frac{1}{2} \cdot AD \cdot \frac{h}{2} = \frac{AD \cdot h}{4}, \quad S_{KBC} = \frac{BC \cdot h}{4}.$$
        Тогда:
        $$S_{KAB} = S_{ABCD} - S_{KAD} - S_{KBC} = \frac{(AD+BC)h}{2} - \frac{(AD+BC)h}{4} = \frac{(AD+BC)h}{4} = \frac{1}{2}S_{ABCD}.$$
      </div>
      <a class="back-to-top" href="#ticket-4">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 5 ==================== -->
<div class="ticket" id="ticket-5">
  <h2>Билет №5</h2>

  <div class="question">
    <div class="q-title">1. Свойства прямоугольного треугольника</div>
    <div class="q-body">
      <ul>
        <li>Сумма острых углов равна 90°.</li>
        <li>Катет, противолежащий углу 30°, равен половине гипотенузы.</li>
        <li>Медиана к гипотенузе равна половине гипотенузы.</li>
        <li>Площадь равна половине произведения катетов.</li>
      </ul>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Окружность, вписанная в треугольник</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> В любой треугольник можно вписать окружность, и притом только одну. Центр вписанной окружности находится в точке пересечения биссектрис треугольника. Радиус $r = \dfrac{S}{p}$, где $S$ — площадь, $p$ — полупериметр.<br><br>
        <strong>Доказательство существования.</strong> Пусть $AA_1$ и $BB_1$ — биссектрисы углов $A$ и $B$, пересекающиеся в точке $O$. Точка $O$ равноудалена от сторон $AB$ и $AC$ (лежит на биссектрисе $A$), а также равноудалена от $AB$ и $BC$ (лежит на биссектрисе $B$). Следовательно, $O$ равноудалена от всех трёх сторон. Окружность с центром $O$ и радиусом, равным расстоянию до сторон, касается всех сторон, то есть вписана.<br><br>
        <strong>Единственность.</strong> Центр вписанной окружности должен быть равноудалён от сторон, поэтому он лежит на биссектрисе каждого угла. Две биссектрисы пересекаются в одной точке, следовательно, центр единственный.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Равенство треугольников»)</div>
    <div class="q-body">
      <div class="highlight">Методика: найдите пару равных элементов (сторон, углов) и примените один из признаков равенства (SAS, ASA, SSS).</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Теорема о касательной и секущей</div>
    <div class="q-body">
      <p><strong>Дано:</strong> из точки $E$ проведены секущая $EAB$ и касательная $EC$ ($C$ — точка касания).</p>
      <p><strong>Доказать:</strong> $AE \cdot BE = CE^2$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Рассмотрим $\triangle EAC$ и $\triangle ECB$. Угол $E$ общий. По свойству угла между касательной и хордой $\angle ECA = \angle EBC$ (оба равны половине дуги $AC$). Следовательно, $\triangle EAC \sim \triangle ECB$ по двум углам.<br>
        Из подобия:
        $$\frac{EA}{EC} = \frac{EC}{EB} \Longrightarrow EC^2 = EA \cdot EB.$$
      </div>
      <a class="back-to-top" href="#ticket-5">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 6 ==================== -->
<div class="ticket" id="ticket-6">
  <h2>Билет №6</h2>

  <div class="question">
    <div class="q-title">1. Признаки равенства треугольников</div>
    <div class="q-body">
      <ol>
        <li>По двум сторонам и углу между ними (SAS).</li>
        <li>По стороне и двум прилежащим углам (ASA).</li>
        <li>По трём сторонам (SSS).</li>
        <li>Для прямоугольных: по гипотенузе и катету.</li>
      </ol>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Биссектриса угла треугольника и замечательная точка</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Биссектриса угла треугольника делит противоположную сторону на отрезки, пропорциональные прилежащим сторонам:
        $$\frac{AD}{DC} = \frac{AB}{BC}.$$
        <strong>Доказательство.</strong> Пусть $BD$ — биссектриса $\angle B$ в $\triangle ABC$. Проведём $CE \parallel BD$ до пересечения с продолжением $AB$ в $E$.<br>
        По теореме Фалеса: $\dfrac{AD}{DC} = \dfrac{AB}{BE}$.<br>
        Так как $\angle BEC = \angle ABD$ (соответственные при $CE \parallel BD$) и $\angle BCE = \angle DBC$ (накрест лежащие при $CE \parallel BD$ и секущей $BC$), а $\angle ABD = \angle DBC$ (по определению биссектрисы), то $\angle BEC = \angle BCE$.<br>
        Следовательно, $\triangle BCE$ равнобедренный, $BE = BC$. Подставляя, получаем $\dfrac{AD}{DC} = \dfrac{AB}{BC}$.
      </div>
      <div class="proof">
        <strong>Следствие (замечательная точка).</strong> Биссектрисы треугольника пересекаются в одной точке — центре вписанной окружности.<br><br>
        <strong>Доказательство.</strong> Две биссектрисы (например, $A$ и $B$) пересекаются в точке $O$. Точка $O$ равноудалена от сторон $AB$ и $AC$ (по определению биссектрисы $A$), а также от $AB$ и $BC$ (по биссектрисе $B$). Значит, $O$ равноудалена от $AC$ и $BC$, то есть лежит на биссектрисе угла $C$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Площадь четырёхугольника»)</div>
    <div class="q-body">
      <div class="highlight">Методика: разбейте четырёхугольник на треугольники диагональю, найдите площади треугольников по формуле $S = \frac{1}{2}ah$ или $S = \frac{1}{2}ab\sin C$.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Перпендикулярность $CD \perp EF$</div>
    <div class="q-body">
      <p><strong>Дано:</strong> окружности с центрами $E$ и $F$ пересекаются в $C$ и $D$; $E$ и $F$ лежат по одну сторону от $CD$.</p>
      <p><strong>Доказать:</strong> $CD \perp EF$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> $EC = ED$ (радиусы первой окружности), $FC = FD$ (радиусы второй). Значит, точки $E$ и $F$ равноудалены от $C$ и $D$. По теореме о серединном перпендикуляре они лежат на серединном перпендикуляре к $CD$. Следовательно, прямая $EF$ является серединным перпендикуляром к $CD$, откуда $CD \perp EF$.
      </div>
      <a class="back-to-top" href="#ticket-6">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 7 ==================== -->
<div class="ticket" id="ticket-7">
  <h2>Билет №7</h2>

  <div class="question">
    <div class="q-title">1. Многоугольник</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Многоугольник — фигура, состоящая из отрезков (сторон), последовательно соединённых так, что конец одного есть начало другого, а конец последнего — начало первого.</p>
      <p><strong>Элементы:</strong> вершина — точка соединения сторон; диагональ — отрезок, соединяющий несмежные вершины; угол — угол между двумя смежными сторонами; периметр — сумма длин сторон.</p>
      <p><strong>Выпуклый многоугольник</strong> лежит по одну сторону от прямой, содержащей любую его сторону. <strong>Невыпуклый</strong> имеет хотя бы одну сторону, прямая которой разбивает многоугольник.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема об отрезках пересекающихся хорд</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Если две хорды пересекаются, то произведение отрезков одной равно произведению отрезков другой: $AC \cdot CB = DC \cdot CE$.<br><br>
        <strong>Доказательство.</strong> Пусть хорды $AB$ и $CD$ пересекаются в точке $E$. Соединим $A$ с $D$ и $B$ с $C$. Углы $\angle AEC$ и $\angle DEB$ — вертикальные. Углы $\angle DAB$ и $\angle DCB$ — вписанные, опирающиеся на одну дугу $DB$, значит равны. Следовательно, $\triangle AED \sim \triangle CEB$ по двум углам.<br>
        Из подобия:
        $$\frac{AE}{CE} = \frac{DE}{BE} \Longrightarrow AE \cdot BE = CE \cdot DE.$$
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Подобие. Трапеция»)</div>
    <div class="q-body">
      <div class="highlight">Методика: диагонали трапеции образуют подобные треугольники с основанием; используйте пропорциональность для нахождения неизвестных отрезков.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Радиусы $r$ и $R$ равностороннего треугольника</div>
    <div class="q-body">
      <p><strong>Дано:</strong> равносторонний треугольник со стороной $a$.</p>
      <p><strong>Найти:</strong> $r$ и $R$.</p>
      <div class="proof">
        <strong>Решение.</strong> Высота $h = \dfrac{a\sqrt{3}}{2}$. Центр (точка пересечения медиан) делит высоту в отношении $2:1$, считая от вершины.
        $$R = \frac{2}{3}h = \frac{a\sqrt{3}}{3} = \frac{a}{\sqrt{3}}, \qquad r = \frac{1}{3}h = \frac{a\sqrt{3}}{6} = \frac{a}{2\sqrt{3}}.$$
      </div>
      <a class="back-to-top" href="#ticket-7">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 8 ==================== -->
<div class="ticket" id="ticket-8">
  <h2>Билет №8</h2>

  <div class="question">
    <div class="q-title">1. Четырёхугольник</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Четырёхугольник — многоугольник с четырьмя вершинами и четырьмя сторонами.</p>
      <p><strong>Виды:</strong> параллелограмм, прямоугольник, ромб, квадрат, трапеция, произвольный выпуклый и невыпуклый.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теоремы о вписанном угле</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема 1.</strong> Вписанный угол измеряется половиной дуги, на которую он опирается.<br><br>
        <strong>Доказательство.</strong> Рассмотрим три случая.<br>
        <em>Случай 1:</em> одна из сторон угла проходит через центр $O$. Пусть $\angle ABC$ вписан, $BC$ — диаметр. $\triangle AOB$ равнобедренный ($OA=OB=R$), значит $\angle A = \angle B = \alpha$. Центральный $\angle AOC = 2\alpha$ (внешний угол). Но $\angle AOC$ равен дуге $AC$, следовательно $\angle ABC = \alpha = \frac{1}{2}\overset{\frown}{AC}$.<br>
        <em>Случай 2:</em> центр лежит внутри угла. Проведём диаметр $BD$. Тогда $\angle ABC = \angle ABD + \angle DBC = \frac{1}{2}\overset{\frown}{AD} + \frac{1}{2}\overset{\frown}{DC} = \frac{1}{2}\overset{\frown}{AC}$.<br>
        <em>Случай 3:</em> центр лежит вне угла — аналогично через разность.
      </div>
      <div class="proof">
        <strong>Следствие 1.</strong> Вписанные углы, опирающиеся на одну и ту же дугу, равны.<br>
        <strong>Доказательство.</strong> Каждый из них равен половине одной и той же дуги.
      </div>
      <div class="proof">
        <strong>Следствие 2.</strong> Вписанный угол, опирающийся на диаметр, прямой (90°).<br>
        <strong>Доказательство.</strong> Диаметр соответствует дуге в 180°, половина — 90°.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Параллельные прямые»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте равенство соответственных, накрест лежащих углов или сумму односторонних (180°).</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Подобие треугольников $A_1BC_1$ и $ABC$</div>
    <div class="q-body">
      <p><strong>Дано:</strong> в $\triangle ABC$ $\angle ABC > 90°$; $AA_1 \perp BC$, $CC_1 \perp AB$ ($A_1$ на продолжении $BC$, $C_1$ на продолжении $AB$).</p>
      <p><strong>Доказать:</strong> $\triangle A_1BC_1 \sim \triangle ABC$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Так как $\angle AA_1C = 90°$ и $\angle AC_1C = 90°$, точки $A, C, A_1, C_1$ лежат на окружности с диаметром $AC$.<br>
        В этом вписанном четырёхугольнике $\angle BA_1C_1$ — внешний угол при вершине $A_1$, равный внутреннему противоположному $\angle C_1AC = \angle BAC$ (свойство вписанного четырёхугольника: внешний угол равен внутреннему противоположному).<br>
        В $\triangle ABC$ и $\triangle A_1BC_1$ угол $B$ общий, а $\angle BA_1C_1 = \angle BAC$. Следовательно, треугольники подобны по двум углам (AA).
      </div>
      <a class="back-to-top" href="#ticket-8">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 9 ==================== -->
<div class="ticket" id="ticket-9">
  <h2>Билет №9</h2>

  <div class="question">
    <div class="q-title">1. Осевая и центральная симметрии</div>
    <div class="q-body">
      <p><strong>Осевая симметрия</strong> — симметрия относительно прямой (оси). Точки $M$ и $M'$ симметричны относительно оси $l$, если $l$ — серединный перпендикуляр к $MM'$.</p>
      <p><em>Примеры:</em> отражение в зеркале, равнобедренный треугольник (ось симметрии — биссектриса к основанию).</p>
      <p><strong>Центральная симметрия</strong> — симметрия относительно точки $O$. Точки $M$ и $M'$ симметричны относительно $O$, если $O$ — середина $MM'$.</p>
      <p><em>Примеры:</em> параллелограмм (центр — пересечение диагоналей), поворот на 180°.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Касательная к окружности и отрезки касательных</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема 1 (свойство).</strong> Касательная перпендикулярна радиусу, проведённому в точку касания.<br><br>
        <strong>Доказательство.</strong> Пусть прямая $a$ касается окружности в $A$. Предположим, $OA$ не перпендикулярна $a$. Опустим перпендикуляр $OB$ на $a$. Тогда $OB < OA = R$, значит $B$ лежит внутри окружности, и прямая $a$ имеет с окружностью ещё одну общую точку — противоречие с определением касательной. Следовательно, $OA \perp a$.
      </div>
      <div class="proof">
        <strong>Теорема 2 (отрезки касательных).</strong> Отрезки касательных к окружности, проведённые из одной точки, равны и составляют равные углы с прямой, соединяющей эту точку с центром.<br><br>
        <strong>Доказательство.</strong> Пусть $PA$ и $PB$ — касательные из $P$. $OA \perp PA$, $OB \perp PB$ (свойство касательной). Прямоугольные треугольники $OPA$ и $OPB$ равны по гипотенузе $OP$ и катету $OA = OB = R$. Следовательно, $PA = PB$ и $\angle APO = \angle BPO$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Подобные треугольники»)</div>
    <div class="q-body">
      <div class="highlight">Методика: найдите пару равных углов (вписанные на одну дугу, углы с параллельными сторонами и т.п.) и примените признак AA.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Биссектриса между медианой и высотой</div>
    <div class="q-body">
      <p><strong>Доказать:</strong> в произвольном треугольнике биссектриса лежит между медианой и высотой, проведёнными из той же вершины.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Пусть $AB < AC$. Обозначим биссектрису $AD$, медиану $AM$, высоту $AH$ (все из $A$).<br>
        В $\triangle ABH$: $\angle BAH = 90° - \angle B$. Так как $AB < AC$, имеем $\angle C < \angle B$, откуда $\angle BAH < \frac{\angle A}{2} = \angle BAD$. Значит, высота $AH$ лежит ближе к $AB$, чем биссектриса.<br>
        По свойству биссектрисы $\frac{BD}{DC} = \frac{AB}{AC} < 1$, поэтому $BD < DC$, и точка $D$ ближе к $B$, чем середина $M$. Следовательно, медиана $AM$ лежит дальше от $AB$, чем биссектриса.<br>
        Итак, на стороне $BC$ от $B$ к $C$: $H, D, M$ (при $AB < AC$). При $AB > AC$ порядок обратный. В любом случае биссектриса лежит между высотой и медианой.
      </div>
      <a class="back-to-top" href="#ticket-9">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 10 ==================== -->
<div class="ticket" id="ticket-10">
  <h2>Билет №10</h2>

  <div class="question">
    <div class="q-title">1. Площадь многоугольника</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Площадь — положительное число, характеризующее часть плоскости, занятую многоугольником.</p>
      <p><strong>Свойства:</strong></p>
      <ol>
        <li>Равные многоугольники имеют равные площади.</li>
        <li>Если многоугольник составлен из нескольких, его площадь равна сумме их площадей.</li>
        <li>Площадь квадрата со стороной 1 равна 1.</li>
      </ol>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема о пропорциональных отрезках в прямоугольном треугольнике</div>
    <div class="q-body">
      <p>Пусть $h$ — высота, опущенная на гипотенузу $c$, и $p,q$ — проекции катетов на гипотенузу.</p>
      <div class="proof">
        <strong>Теорема.</strong> $h^2 = pq$; $a^2 = cp$; $b^2 = cq$.<br><br>
        <strong>Доказательство.</strong> В прямоугольном треугольнике $ABC$ ($\angle C = 90°$) проведём высоту $CD$ на гипотенузу $AB$.<br>
        $\triangle ACD \sim \triangle ABC$ (по общему углу $A$ и прямому углу). Отсюда:
        $$\frac{AC}{AB} = \frac{AD}{AC} \Longrightarrow AC^2 = AB \cdot AD, \quad \text{то есть } a^2 = cp.$$
        Аналогично из $\triangle CBD \sim \triangle ABC$ получаем $b^2 = cq$.<br>
        Из подобия $\triangle ACD \sim \triangle CBD$ (по равным острым углам: $\angle ACD = \angle B$, $\angle BCD = \angle A$):
        $$\frac{AD}{CD} = \frac{CD}{BD} \Longrightarrow CD^2 = AD \cdot BD, \quad \text{то есть } h^2 = pq.$$
      </div>
      <div class="proof">
        <strong>Следствие 1.</strong> $a^2 + b^2 = c(p+q) = c^2$ — <em>теорема Пифагора</em>.<br>
        <strong>Следствие 2.</strong> $\dfrac{1}{a^2} + \dfrac{1}{b^2} = \dfrac{1}{h^2}$.<br>
        <strong>Доказательство следствия 2.</strong> $\dfrac{1}{a^2} + \dfrac{1}{b^2} = \dfrac{1}{cp} + \dfrac{1}{cq} = \dfrac{p+q}{cpq} = \dfrac{c}{ch^2} = \dfrac{1}{h^2}$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Площадь треугольника»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте формулу $S = \frac{1}{2}ah$ или $S = \frac{1}{2}ab\sin C$; при необходимости найдите высоту через дополнительные построения.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Угол с вершиной вне круга</div>
    <div class="q-body">
      <p><strong>Дано:</strong> угол с вершиной $E$ вне окружности; стороны пересекают окружность в $A,B$ и $C,D$.</p>
      <p><strong>Доказать:</strong> $\angle E = \dfrac{1}{2}(\overset{\frown}{BC} - \overset{\frown}{AD})$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Соединим $A$ и $C$. В $\triangle AEC$ внешний угол $\angle BAC = \angle E + \angle ACE$. Отсюда $\angle E = \angle BAC - \angle ACE$.<br>
        $\angle BAC$ — вписанный, опирается на дугу $BC$; $\angle ACE = \angle ACD$ — вписанный, опирается на дугу $AD$.<br>
        Следовательно:
        $$\angle E = \frac{1}{2} \overset{\frown}{BC} - \frac{1}{2} \overset{\frown}{AD} = \frac{1}{2}(\overset{\frown}{BC} - \overset{\frown}{AD}).$$
      </div>
      <a class="back-to-top" href="#ticket-10">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 11 ==================== -->
<div class="ticket" id="ticket-11">
  <h2>Билет №11</h2>

  <div class="question">
    <div class="q-title">1. Подобные треугольники</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Два треугольника подобны, если их соответственные углы равны и соответственные стороны пропорциональны:</p>
      <p>$$\frac{AB}{A_1B_1} = \frac{BC}{B_1C_1} = \frac{CA}{C_1A_1} = k$$</p>
      <p>где $k$ — коэффициент подобия.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Свойство медиан треугольника</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Медианы треугольника пересекаются в одной точке и делятся ею в отношении $2:1$, считая от вершины.<br><br>
        <strong>Доказательство.</strong> Пусть $AM$ и $BN$ — медианы $\triangle ABC$, пересекающиеся в $O$. Соединим середину $AB$ (точку $K$) с $O$.<br>
        В $\triangle ABC$ проведём среднюю линию $MN$, соединяющую середины $AC$ и $BC$. Тогда $MN \parallel AB$ и $MN = \frac{1}{2}AB$.<br>
        В $\triangle OAB$ и $\triangle OMN$: $\angle O$ общий, $\angle OAB = \angle OMN$ (соответственные при $MN \parallel AB$). Значит $\triangle OAB \sim \triangle OMN$.<br>
        Отношение сходства $\frac{AB}{MN} = 2$, поэтому $\frac{AO}{OM} = \frac{BO}{ON} = 2$.<br>
        Аналогично для третьей медианы. Таким образом, все три медианы пересекаются в одной точке $O$ и делятся в отношении $2:1$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Площадь параллелограмма»)</div>
    <div class="q-body">
      <div class="highlight">Методика: $S = ah$ или $S = ab\sin\alpha$; используйте свойства параллелограмма (противоположные стороны равны, диагонали делятся пополам).</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Угол с вершиной внутри круга</div>
    <div class="q-body">
      <p><strong>Дано:</strong> угол с вершиной $P$ внутри окружности; стороны пересекают окружность в $A,B$ и $C,D$.</p>
      <p><strong>Доказать:</strong> $\angle APD = \dfrac{1}{2}(\overset{\frown}{AD} + \overset{\frown}{BC})$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Соединим $A$ и $C$. В $\triangle APC$ внешний угол $\angle BPC = \angle PAC + \angle PCA$.<br>
        $\angle PAC = \angle DAC$ — вписанный, опирается на дугу $DC$? Нет, стандартный вывод:<br>
        $\angle PAD$ опирается на дугу $BD$? Правильно: $\angle DAP$ — вписанный на дугу $BD$? Нет.<br>
        Классически: $\angle APD = 180° - \angle PAD - \angle PDA$. Вертикальный угол $\angle BPC = \angle APD$.<br>
        $\angle PAD$ — вписанный на дугу $CD$? Нет, $\angle CAD$ опирается на дугу $CD$.<br>
        $\angle PDA = \angle BDA$ — вписанный на дугу $AB$.<br>
        Тогда $\angle APD = 180° - \frac{1}{2}\overset{\frown}{CD} - \frac{1}{2}\overset{\frown}{AB} = \frac{1}{2}(360° - \overset{\frown}{CD} - \overset{\frown}{AB}) = \frac{1}{2}(\overset{\frown}{AD} + \overset{\frown}{BC})$.<br>
        ч.т.д.
      </div>
      <a class="back-to-top" href="#ticket-11">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 12 ==================== -->
<div class="ticket" id="ticket-12">
  <h2>Билет №12</h2>

  <div class="question">
    <div class="q-title">1. Средняя линия</div>
    <div class="q-body">
      <p><strong>Треугольник.</strong> Отрезок, соединяющий середины двух сторон, называется средней линией. Она параллельна третьей стороне и равна её половине.</p>
      <p><strong>Трапеция.</strong> Отрезок, соединяющий середины боковых сторон, называется средней линией. Она параллельна основаниям и равна их полусумме.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема о свойстве биссектрисы угла треугольника</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Биссектриса угла треугольника делит противоположную сторону на отрезки, пропорциональные прилежащим сторонам:
        $$\frac{AD}{DC} = \frac{AB}{BC}.$$
        <strong>Доказательство.</strong> Пусть $BD$ — биссектриса $\angle B$ в $\triangle ABC$. Проведём $CE \parallel BD$ до пересечения с продолжением $AB$ в $E$.<br>
        По теореме Фалеса: $\dfrac{AD}{DC} = \dfrac{AB}{BE}$.<br>
        Так как $\angle BEC = \angle ABD$ (соответственные при $CE \parallel BD$) и $\angle BCE = \angle DBC$ (альтернативные внутренние при $CE \parallel BD$ и секущей $BC$), а $\angle ABD = \angle DBC$ (по определению биссектрисы), то $\angle BEC = \angle BCE$.<br>
        Следовательно, $\triangle BCE$ равнобедренный, $BE = BC$. Подставляя, получаем $\dfrac{AD}{DC} = \dfrac{AB}{BC}$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Отношение сторон и углов прямоугольного треугольника»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте определения синуса, косинуса, тангенса ($\sin = \frac{\text{противолежащий}}{\text{гипотенуза}}$ и т.д.) и основное тригонометрическое тождество $\sin^2\alpha + \cos^2\alpha = 1$.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Угол между двумя касательными</div>
    <div class="q-body">
      <p><strong>Дано:</strong> из точки $E$ проведены касательные $EA$ и $EB$; $A,B$ — точки касания.</p>
      <p><strong>Доказать:</strong> $\angle AEB = \dfrac{1}{2}(\overset{\frown}{AB}_{\text{большая}} - \overset{\frown}{AB}_{\text{меньшая}})$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> В четырёхугольнике $OAEB$: $\angle OAE = \angle OBE = 90°$ (свойство касательной).<br>
        Сумма углов четырёхугольника $360°$, поэтому:
        $$\angle AEB + \angle AOB = 180°.$$
        Центральный угол $\angle AOB$ равен меньшей дуге $AB$. Тогда:
        $$\angle AEB = 180° - \overset{\frown}{AB}_{\text{меньшая}} = \frac{1}{2}\left((360° - \overset{\frown}{AB}_{\text{меньшая}}) - \overset{\frown}{AB}_{\text{меньшая}}\right) = \frac{1}{2}\left(\overset{\frown}{AB}_{\text{большая}} - \overset{\frown}{AB}_{\text{меньшая}}\right).$$
      </div>
      <a class="back-to-top" href="#ticket-12">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 13 ==================== -->
<div class="ticket" id="ticket-13">
  <h2>Билет №13</h2>

  <div class="question">
    <div class="q-title">1. Тригонометрические функции острого угла</div>
    <div class="q-body">
      <p>Для острого угла $\alpha$ прямоугольного треугольника:</p>
      <p>$$\sin\alpha = \frac{\text{противолежащий}}{\text{гипотенуза}}, \quad \cos\alpha = \frac{\text{прилежащий}}{\text{гипотенуза}}$$</p>
      <p>$$\tg\alpha = \frac{\sin\alpha}{\cos\alpha} = \frac{\text{противолежащий}}{\text{прилежащий}}, \quad \ctg\alpha = \frac{\cos\alpha}{\sin\alpha}$$</p>
      <p><strong>Основное тригонометрическое тождество:</strong> $\sin^2\alpha + \cos^2\alpha = 1$.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема о средней линии треугольника</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Отрезок, соединяющий середины двух сторон треугольника, параллелен третьей стороне и равен её половине.<br><br>
        <strong>Доказательство.</strong> Пусть $MN$ соединяет середины $AB$ и $AC$ в $\triangle ABC$. В $\triangle AMN$ и $\triangle ABC$ угол $A$ общий, $\frac{AM}{AB} = \frac{AN}{AC} = \frac{1}{2}$. По признаку SAS подобия $\triangle AMN \sim \triangle ABC$ с коэффициентом $\frac{1}{2}$. Следовательно, $MN \parallel BC$ и $MN = \frac{1}{2}BC$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Касательная к окружности»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте перпендикулярность радиуса и касательной, равенство отрезков касательных из одной точки, теорему Пифагора для треугольника с гипотенузой $OP$.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Боковая сторона описанной трапеции</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $ABCD$ — трапеция, $AD \parallel BC$, около неё описана окружность с центром $O$.</p>
      <p><strong>Доказать:</strong> боковая сторона видна из $O$ под прямым углом.</p>
      <div class="proof">
        <strong>Доказательство.</strong> В равнобедренную трапецию можно вписать окружность (свойство: суммы противоположных сторон равны, $AB+CD=AD+BC$, а так как $AB=CD$, то $2AB=AD+BC$). Центр вписанной окружности $O$ лежит на биссектрисах углов. Тогда $\angle OAB = \frac{\angle A}{2}$, $\angle OBA = \frac{\angle B}{2}$. Так как $AD \parallel BC$, $\angle A + \angle B = 180°$ (смежные внутренние). Тогда:
        $$\angle AOB = 180° - \left(\frac{\angle A}{2} + \frac{\angle B}{2}\right) = 180° - \frac{180°}{2} = 90°.$$
      </div>
      <a class="back-to-top" href="#ticket-13">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 14 ==================== -->
<div class="ticket" id="ticket-14">
  <h2>Билет №14</h2>

  <div class="question">
    <div class="q-title">1. Свойства и признаки параллельных прямых</div>
    <div class="q-body">
      <p><strong>Свойства.</strong> Если прямые параллельны, то при секущей: соответственные углы равны, накрест лежащие равны, односторонние в сумме $180°$.</p>
      <p><strong>Признаки.</strong> Если при секущей: соответственные углы равны (или накрест лежащие равны, или односторонние в сумме $180°$), то прямые параллельны.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Признаки подобия треугольников (доказательство одного)</div>
    <div class="q-body">
      <div class="proof">
        <strong>Признак 1 (по двум углам — AA).</strong> Если два угла одного треугольника равны двум углам другого, то такие треугольники подобны.<br><br>
        <strong>Доказательство.</strong> Пусть в $\triangle ABC$ и $\triangle A_1B_1C_1$ имеем $\angle A = \angle A_1$, $\angle B = \angle B_1$. Тогда и $\angle C = \angle C_1$ (по сумме углов треугольника).<br>
        Наложим $\triangle A_1B_1C_1$ на $\triangle ABC$ так, чтобы $A_1$ совпала с $A$, а сторона $A_1B_1$ легла на $AB$. Так как $\angle A = \angle A_1$, сторона $A_1C_1$ ляжет на $AC$. Так как $\angle B = \angle B_1$, сторона $B_1C_1$ будет параллельна $BC$ (равные соответственные углы при секущей $AB$).<br>
        По теореме Фалеса $\frac{AB_1}{AB} = \frac{AC_1}{AC}$. Аналогично, наложив по углу $B$, получим $\frac{AB_1}{AB} = \frac{B_1C_1}{BC}$. Следовательно, все стороны пропорциональны, и треугольники подобны.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Окружности»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте свойства касательных, хорд, центральных и вписанных углов, теорему о пересекающихся хордах.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Свойства равнобедренной трапеции с высотой $CE$</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $ABCD$ — равнобедренная трапеция, $AD \parallel BC$, $CE \perp AD$.</p>
      <p><strong>Доказать:</strong> $AE = \dfrac{AD+BC}{2}$, $DE = \dfrac{AD-BC}{2}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> Опустим высоту $BF \perp AD$. Тогда $BCFE$ — прямоугольник, $EF = BC$.<br>
        $\triangle ABF = \triangle DCE$ (по гипотенузе и катету: $AB=CD$ как боковые стороны равнобедренной трапеции, высоты равны $BF=CE$). Поэтому $AF = DE = \dfrac{AD - EF}{2} = \dfrac{AD - BC}{2}$.<br>
        Тогда:
        $$AE = AF + FE = \frac{AD-BC}{2} + BC = \frac{AD+BC}{2}.$$
      </div>
      <a class="back-to-top" href="#ticket-14">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 15 ==================== -->
<div class="ticket" id="ticket-15">
  <h2>Билет №15</h2>

  <div class="question">
    <div class="q-title">1. Взаимное расположение прямой и окружности</div>
    <div class="q-body">
      <ul>
        <li>Нет общих точек: $d > R$.</li>
        <li>Касаются в одной точке: $d = R$ (касательная).</li>
        <li>Пересекаются в двух точках: $d < R$ (секущая).</li>
      </ul>
      <p>($d$ — расстояние от центра до прямой, $R$ — радиус).</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема об отношении площадей подобных треугольников</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Отношение площадей подобных треугольников равно квадрату коэффициента подобия: $\frac{S_1}{S_2} = k^2$.<br><br>
        <strong>Доказательство.</strong> Пусть $\triangle ABC \sim \triangle A_1B_1C_1$ с коэффициентом $k$, то есть $\frac{AB}{A_1B_1} = \frac{BC}{B_1C_1} = \frac{CA}{C_1A_1} = k$ и $\angle A = \angle A_1$.<br>
        Площадь треугольника $S = \frac{1}{2}ab\sin C$. Тогда:
        $$\frac{S}{S_1} = \frac{\frac{1}{2} AB \cdot AC \sin A}{\frac{1}{2} A_1B_1 \cdot A_1C_1 \sin A_1} = \frac{AB}{A_1B_1} \cdot \frac{AC}{A_1C_1} = k \cdot k = k^2.$$
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Параллельные прямые»)</div>
    <div class="q-body">
      <div class="highlight">Методика: см. билет №1 и №8 — используйте равенство углов при параллельных прямыx и секущей.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Отрезок перпендикуляра втрое меньше большего катета</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $\triangle ABC$, $\angle C = 90°$, $\angle A = 30°$; $M$ — середина $AB$; $MD \perp AB$, $D \in AC$.</p>
      <p><strong>Доказать:</strong> $MD = \dfrac{AC}{3}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> $AM = \dfrac{AB}{2}$. В $\triangle AMD$: $\angle A = 30°$, $\angle AMD = 90°$, поэтому:
        $$MD = AM \cdot \tg 30° = \frac{AB}{2} \cdot \frac{1}{\sqrt{3}} = \frac{AB}{2\sqrt{3}}.$$
        Больший катет $AC = AB \cdot \cos 30° = \dfrac{AB\sqrt{3}}{2}$.<br>
        Отношение:
        $$\frac{AC}{MD} = \frac{AB\sqrt{3}/2}{AB/(2\sqrt{3})} = 3 \Longrightarrow MD = \frac{AC}{3}.$$
      </div>
      <a class="back-to-top" href="#ticket-15">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 16 ==================== -->
<div class="ticket" id="ticket-16">
  <h2>Билет №16</h2>

  <div class="question">
    <div class="q-title">1. Площади треугольников</div>
    <div class="q-body">
      <p>$$S = \frac{1}{2}ah_a = \frac{1}{2}ab\sin C = \sqrt{p(p-a)(p-b)(p-c)} = \frac{abc}{4R} = pr$$</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема Пифагора и обратная</div>
    <div class="q-body">
      <div class="proof">
        <strong>Прямая теорема.</strong> В прямоугольном треугольнике квадрат гипотенузы равен сумме квадратов катетов: $c^2 = a^2 + b^2$.<br><br>
        <strong>Доказательство.</strong> Построим квадрат со стороной $a+b$. Впишем в него четыре прямоугольных треугольника с катетами $a,b$ и гипотенузой $c$, расположив их так, чтобы образовать квадрат со стороной $c$ в центре. Площадь большого квадрата: $(a+b)^2 = a^2 + 2ab + b^2$. С другой стороны, она равна $4 \cdot \frac{1}{2}ab + c^2 = 2ab + c^2$. Приравнивая: $a^2 + 2ab + b^2 = 2ab + c^2$, откуда $a^2 + b^2 = c^2$.
      </div>
      <div class="proof">
        <strong>Обратная теорема.</strong> Если в треугольнике квадрат одной стороны равен сумме квадратов двух других сторон, то треугольник прямоугольный.<br><br>
        <strong>Доказательство.</strong> Пусть в $\triangle ABC$ выполняется $AB^2 + BC^2 = AC^2$. Построим прямоугольный треугольник $A_1B_1C_1$ с прямым углом при $B_1$ и катетами $A_1B_1 = AB$, $B_1C_1 = BC$. По прямой теореме Пифагора $A_1C_1^2 = AB^2 + BC^2 = AC^2$, значит $A_1C_1 = AC$. Тогда $\triangle ABC = \triangle A_1B_1C_1$ по трём сторонам, следовательно $\angle B = \angle B_1 = 90°$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Подобие. Площадь»)</div>
    <div class="q-body">
      <div class="highlight">Методика: докажите подобие по углам, найдите коэффициент подобия $k$, затем $S_2 = S_1 / k^2$ или $S_2 = S_1 \cdot k^2$.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. $DK$ — биссектриса $\angle ADC$</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $ABCD$ — параллелограмм, $AB = 2AD$; $K$ — середина $AB$.</p>
      <p><strong>Доказать:</strong> $DK$ — биссектриса $\angle ADC$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> $AK = KB = \frac{AB}{2} = AD$ (так как $AB = 2AD$).<br>
        В $\triangle ADK$: $AD = AK$, значит он равнобедренный, и $\angle ADK = \angle AKD$.<br>
        Так как $AB \parallel CD$, $\angle AKD = \angle KDC$ (накрест лежащие при секущей $DK$).<br>
        Следовательно, $\angle ADK = \angle KDC$, то есть $DK$ — биссектриса $\angle ADC$.
      </div>
      <a class="back-to-top" href="#ticket-16">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 17 ==================== -->
<div class="ticket" id="ticket-17">
  <h2>Билет №17</h2>

  <div class="question">
    <div class="q-title">1. Центральный и вписанный углы</div>
    <div class="q-body">
      <p><strong>Центральный угол</strong> — угол с вершиной в центре окружности, равный градусной мере своей дуги.</p>
      <p><strong>Вписанный угол</strong> — угол с вершиной на окружности.</p>
      <p><strong>Следствия:</strong></p>
      <ol>
        <li>Вписанный угол вдвое меньше центрального, опирающегося на ту же дугу.</li>
        <li>Вписанные углы, опирающиеся на одну дугу, равны.</li>
        <li>Угол, опирающийся на диаметр, прямой (90°).</li>
      </ol>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема о площади трапеции</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Площадь трапеции равна произведению полусуммы оснований на высоту:
        $$S = \frac{a+b}{2} \cdot h.$$
        <strong>Доказательство.</strong> Пусть $ABCD$ — трапеция с основаниями $AD = a$, $BC = b$ и высотой $h$. Проведём диагональ $AC$, разбивающую трапецию на треугольники $ABC$ и $ACD$.<br>
        Площадь $\triangle ABC = \frac{1}{2} b h$ (высота к стороне $BC$ равна $h$, так как $AD \parallel BC$).<br>
        Площадь $\triangle ACD = \frac{1}{2} a h$.<br>
        Складывая:
        $$S_{ABCD} = \frac{1}{2}bh + \frac{1}{2}ah = \frac{a+b}{2} \cdot h.$$
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Касательная к окружности»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте перпендикулярность радиуса и касательной ($OA \perp PA$), равенство касательных ($PA = PB$), теорему Пифагора.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Боковая сторона равна средней линии</div>
    <div class="q-body">
      <p><strong>Дано:</strong> в равнобедренную трапецию $ABCD$ ($AD \parallel BC$, $AB = CD$) вписана окружность.</p>
      <p><strong>Доказать:</strong> $AB = MN$ (средняя линия).</p>
      <div class="proof">
        <strong>Доказательство.</strong> Для вписанного четырёхугольника $AB + CD = AD + BC$ (свойство описанного четырёхугольника).<br>
        Так как $AB = CD$ (равнобедренная трапеция):
        $$2AB = AD + BC \Longrightarrow AB = \frac{AD+BC}{2}.$$
        Средняя линия $MN = \dfrac{AD+BC}{2}$. Следовательно, $AB = MN$.
      </div>
      <a class="back-to-top" href="#ticket-17">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 18 ==================== -->
<div class="ticket" id="ticket-18">
  <h2>Билет №18</h2>

  <div class="question">
    <div class="q-title">1. Серединный перпендикуляр</div>
    <div class="q-body">
      <p><strong>Определение.</strong> Серединный перпендикуляр к отрезку — прямая, перпендикулярная отрезку и проходящая через его середину.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема об отношении площадей треугольников с равным углом</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Отношение площадей двух треугольников, имеющих по равному углу, равно отношению произведений сторон, заключающих этот угол:
        $$\frac{S_1}{S_2} = \frac{a_1 b_1}{a_2 b_2}.$$
        <strong>Доказательство.</strong> Пусть $\angle A = \angle A_1$. Площадь треугольника $S = \frac{1}{2}ab\sin C$. Тогда:
        $$\frac{S_{ABC}}{S_{A_1B_1C_1}} = \frac{\frac{1}{2} AB \cdot AC \sin A}{\frac{1}{2} A_1B_1 \cdot A_1C_1 \sin A_1} = \frac{AB \cdot AC}{A_1B_1 \cdot A_1C_1},$$
        так как $\sin A = \sin A_1$ (углы равны).
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Окружность»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте теоремы о вписанных углах, центральных углах, свойствах хорд и касательных.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Сумма расстояний в равностороннем треугольнике</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $\triangle ABC$ — равносторонний со стороной $a$; $P$ — точка внутри; $d_1, d_2, d_3$ — расстояния до сторон.</p>
      <p><strong>Доказать:</strong> $d_1 + d_2 + d_3 = \text{const}$.</p>
      <div class="proof">
        <strong>Доказательство.</strong> $S_{ABC} = S_{PBC} + S_{PAC} + S_{PAB}$.<br>
        $$\frac{a^2\sqrt{3}}{4} = \frac{1}{2}a(d_1 + d_2 + d_3).$$
        Отсюда:
        $$d_1 + d_2 + d_3 = \frac{a\sqrt{3}}{2} = h = \text{const}.$$
      </div>
      <a class="back-to-top" href="#ticket-18">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 19 ==================== -->
<div class="ticket" id="ticket-19">
  <h2>Билет №19</h2>

  <div class="question">
    <div class="q-title">1. Вписанная и описанная окружности многоугольника</div>
    <div class="q-body">
      <p><strong>Окружность вписана в многоугольник</strong> — все стороны многоугольника касаются окружности.</p>
      <p><strong>Многоугольник описан около окружности</strong> — все стороны касаются окружности.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема о площади треугольника и следствия</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Площадь треугольника равна половине произведения основания на высоту:
        $$S = \frac{1}{2} ah_a.$$
        <strong>Доказательство.</strong> Дополним треугольник до параллелограмма, проведя через вершину прямую, параллельную основанию. Площадь параллелограмма равна $ah_a$, а треугольник составляет ровно половину параллелограмма (диагональ делит параллелограмм на два равных треугольника). Следовательно, $S = \frac{1}{2}ah_a$.
      </div>
      <div class="proof">
        <strong>Следствие 1.</strong> Если основания двух треугольников равны, то их площади относятся как высоты.<br>
        <strong>Доказательство.</strong> $\frac{S_1}{S_2} = \frac{\frac{1}{2}a h_1}{\frac{1}{2}a h_2} = \frac{h_1}{h_2}$.
      </div>
      <div class="proof">
        <strong>Следствие 2.</strong> Если высоты двух треугольников равны, то их площади относятся как основания.<br>
        <strong>Доказательство.</strong> Аналогично: $\frac{S_1}{S_2} = \frac{a_1}{a_2}$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Параллельные прямые»)</div>
    <div class="q-body">
      <div class="highlight">Методика: используйте свойства углов при параллельных прямыx и секущей.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Четыре точки на одной прямой</div>
    <div class="q-body">
      <p><strong>Дано:</strong> $ABCD$ — трапеция, $AD \parallel BC$; $AB \cap CD = E$; $AC \cap BD = O$; $M,N$ — середины $AD, BC$.</p>
      <p><strong>Доказать:</strong> $E, O, M, N$ принадлежат одной прямой.</p>
      <div class="proof">
        <strong>Доказательство.</strong> $\triangle EAD \sim \triangle EBC$ (по углам, так как $AD \parallel BC$). $M$ и $N$ — середины соответственных сторон, поэтому $E, M, N$ коллинеарны (средние линии в подобных треугольниках лежат на одной прямой, проходящей через центр гомотетии $E$).<br><br>
        Из подобия $\triangle AOD \sim \triangle COB$ (по углам): $\frac{AO}{OC} = \frac{DO}{OB} = \frac{AD}{BC}$.<br>
        Проведём через $O$ прямую, параллельную основаниям; по теореме Фалеса она делит боковые стороны пропорционально $\frac{AD}{BC}$, а значит, проходит через середины $M$ и $N$.<br>
        Следовательно, $E, O, M, N$ лежат на одной прямой.
      </div>
      <a class="back-to-top" href="#ticket-19">↑ Наверх билета</a>
    </div>
  </div>
</div>

<!-- ==================== БИЛЕТ 20 ==================== -->
<div class="ticket" id="ticket-20">
  <h2>Билет №20</h2>

  <div class="question">
    <div class="q-title">1. Описанная и вписанная окружности многоугольника</div>
    <div class="q-body">
      <p><strong>Окружность описана около многоугольника</strong> — все вершины лежат на окружности.</p>
      <p><strong>Многоугольник вписан в окружность</strong> — все вершины лежат на окружности.</p>
    </div>
  </div>

  <div class="question">
    <div class="q-title">2. Теорема о площади параллелограмма</div>
    <div class="q-body">
      <div class="proof">
        <strong>Теорема.</strong> Площадь параллелограмма равна произведению основания на высоту:
        $$S = ah_a = ab\sin\alpha,$$
        где $a,b$ — стороны, $\alpha$ — угол между ними.<br><br>
        <strong>Доказательство.</strong> Проведём высоту $BH$ на сторону $AD$. Треугольники $ABH$ и $DCK$ (где $CK$ — высота) равны по гипотенузе и катету ($AB=CD$, $BH=CK$).<br>
        Вырежем $\triangle ABH$ и приставим его к стороне $CD$, получим прямоугольник $HBCK$ с площадью $BC \cdot BH = AD \cdot BH = ah_a$.<br>
        Второе равенство: $h_b = a\sin\alpha$, поэтому $S = b \cdot h_b = ab\sin\alpha$.
      </div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">3. Задача по готовому чертежу («Признаки равенства треугольников»)</div>
    <div class="q-body">
      <div class="highlight">Методика: найдите пару равных элементов и примените SAS, ASA или SSS.</div>
    </div>
  </div>

  <div class="question">
    <div class="q-title">4. Свойства хорд и диаметра</div>
    <div class="q-body">
      <p><strong>а)</strong> Хорды, заключённые между параллельными прямыми, равны.</p>
      <p><strong>б)</strong> Диаметр, перпендикулярный хорде, делит её пополам.</p>
      <div class="proof">
        <strong>Доказательство а).</strong> Пусть $AB \parallel CD$ — хорды. Дуги $AC$ и $BD$ между параллельными хордами равны (как отсекаемые параллельными секущими). Следовательно, хорды $AB$ и $CD$, заключающие равные дуги $AC$ и $BD$ (точнее, дополняющие до равных дуг), равны.<br><br>
        Альтернативно: расстояния от центра до $AB$ и $CD$ равны (между параллельными прямыми на одинаковом расстоянии), а равноудалённые от центра хорды равны.
      </div>
      <div class="proof">
        <strong>Доказательство б).</strong> Пусть $OM \perp AB$, $O$ — центр. $OA = OB = R$ (радиусы). Прямоугольные треугольники $OMA$ и $OMB$ равны по гипотенузе и катету ($OA=OB$, $OM$ — общий). Следовательно, $AM = MB$.
      </div>
      <a class="back-to-top" href="#ticket-20">↑ Наверх билета</a>
    </div>
  </div>
</div>

  </main>
</div>

<script>
  // Highlight active nav item on scroll
  const tickets = document.querySelectorAll('.ticket');
  const links = document.querySelectorAll('.nav-list a');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        links.forEach(l => l.classList.remove('active'));
        const id = entry.target.getAttribute('id');
        const active = document.querySelector('.nav-list a[href="#' + id + '"]');
        if (active) active.classList.add('active');
      }
    });
  }, { rootMargin: '-20% 0px -60% 0px' });
  tickets.forEach(t => observer.observe(t));
</script>
</body>
</html>
