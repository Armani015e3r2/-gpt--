<section class="feature-card" aria-labelledby="feature-title">
  <style>
    .feature-card {
      max-width: 900px;
      margin: 0 auto;
      padding: clamp(16px, 3vw, 28px);
      background: #ffffff;
      border-radius: 18px;
      box-shadow:
        0 10px 30px rgba(15, 23, 42, 0.08),
        0 2px 8px rgba(15, 23, 42, 0.05);
      display: grid;
      gap: clamp(14px, 2.5vw, 22px);
    }

    .feature-media img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 14px;
      object-fit: cover;
      background: #f3f4f6;
    }

    .feature-content {
      display: grid;
      gap: 14px;
      text-align: left;
    }

    .feature-title {
      font-size: clamp(20px, 2.2vw, 28px);
      line-height: 1.2;
      letter-spacing: -0.02em;
      color: #0f172a;
      margin: 0;
    }

    .feature-list {
      list-style: none;
      padding: 0;
      margin: 0;
      display: grid;
      gap: 10px;
    }

    .feature-item {
      display: grid;
      grid-template-columns: 10px 1fr;
      align-items: start;
      gap: 10px;
      font-size: clamp(14px, 1.6vw, 16px);
      color: #334155;
    }

    .feature-dot {
      width: 8px;
      height: 8px;
      margin-top: 6px;
      border-radius: 50%;
      background: #f59e0b;
      box-shadow: 0 0 0 4px rgba(245, 158, 11, 0.15);
    }

    .feature-cta {
      justify-self: center;
      margin-top: 6px;
      padding: 12px 20px;
      min-width: 160px;
      border: none;
      border-radius: 12px;
      background: #0f172a;
      color: #ffffff;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: transform 0.15s ease, box-shadow 0.2s ease, opacity 0.2s ease;
      box-shadow: 0 8px 20px rgba(15, 23, 42, 0.18);
    }

    .feature-cta:hover {
      transform: translateY(-2px);
      box-shadow: 0 12px 28px rgba(15, 23, 42, 0.24);
      opacity: 0.98;
    }

    .feature-cta:active {
      transform: translateY(0);
      box-shadow: 0 6px 14px rgba(15, 23, 42, 0.18);
    }

    .feature-cta:focus-visible {
      outline: none;
      box-shadow:
        0 0 0 3px rgba(15, 23, 42, 0.25),
        0 8px 20px rgba(15, 23, 42, 0.18);
    }

    @media (min-width: 768px) {
      .feature-card {
        padding: 28px;
        gap: 22px;
      }
      .feature-content {
        gap: 16px;
      }
    }
  </style>

  <div class="feature-media">
    <!-- Замените src на свой путь к картинке -->
    <img
      src="images/calculator.jpg"
      alt="Калькулятор — пример интерфейса"
      loading="lazy"
    />
  </div>

  <div class="feature-content">
    <h2 id="feature-title" class="feature-title">Считайте быстрее и проще</h2>

    <ul class="feature-list">
      <li class="feature-item">
        <span class="feature-dot" aria-hidden="true"></span>
        <span>Мгновенные расчёты без лишних шагов</span>
      </li>
      <li class="feature-item">
        <span class="feature-dot" aria-hidden="true"></span>
        <span>Удобный интерфейс на любом устройстве</span>
      </li>
      <li class="feature-item">
        <span class="feature-dot" aria-hidden="true"></span>
        <span>Сохраняйте время и избегайте ошибок</span>
      </li>
    </ul>

    <button class="feature-cta" type="button">Начать</button>
  </div>
</section>
