<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Умный органайзер школьника — презентация</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: #1a2a3a;
            color: #333;
            padding: 30px 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .presentation {
            max-width: 1200px;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
        }
        
        .slide {
            width: 1024px;
            min-height: 576px;
            background: white;
            border-radius: 40px;
            box-shadow: 0 30px 50px rgba(0,0,0,0.3);
            padding: 50px 60px;
            position: relative;
            transition: transform 0.2s;
            display: flex;
            flex-direction: column;
        }
        
        .slide-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            border-bottom: 3px solid #2a7faa;
            padding-bottom: 15px;
        }
        
        .slide-title {
            font-size: 42px;
            font-weight: 700;
            color: #0d3b5e;
            letter-spacing: -0.5px;
        }
        
        .slide-number {
            font-size: 24px;
            color: #aaa;
            font-weight: 300;
        }
        
        .slide-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        
        h2 {
            font-size: 36px;
            color: #2a7faa;
            margin-bottom: 30px;
            font-weight: 600;
        }
        
        h3 {
            font-size: 28px;
            color: #0d3b5e;
            margin-bottom: 20px;
        }
        
        ul, ol {
            font-size: 24px;
            line-height: 1.6;
            margin-left: 40px;
            color: #1e2f3f;
        }
        
        li {
            margin: 15px 0;
        }
        
        p {
            font-size: 26px;
            line-height: 1.5;
            margin: 15px 0;
            color: #1e2f3f;
        }
        
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            margin-top: 20px;
        }
        
        .grid-3 {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin-top: 30px;
        }
        
        .card {
            background: #f0f7fc;
            padding: 30px 25px;
            border-radius: 30px;
            text-align: center;
            box-shadow: 0 8px 20px rgba(0,60,100,0.08);
        }
        
        .card h4 {
            font-size: 28px;
            color: #2a7faa;
            margin-bottom: 15px;
        }
        
        .card p {
            font-size: 22px;
            margin: 10px 0;
        }
        
        .stat-number {
            font-size: 56px;
            font-weight: 800;
            color: #f07c4a;
            line-height: 1;
            margin-bottom: 10px;
        }
        
        .stat-label {
            font-size: 22px;
            color: #3b5e7a;
        }
        
        .chart {
            display: flex;
            align-items: flex-end;
            gap: 30px;
            justify-content: center;
            height: 250px;
            margin-top: 40px;
        }
        
        .bar {
            width: 90px;
            background: #2a7faa;
            border-radius: 20px 20px 0 0;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            align-items: center;
            color: white;
            font-weight: bold;
            font-size: 22px;
            padding-bottom: 15px;
            transition: 0.2s;
        }
        
        .bar-label {
            margin-top: 15px;
            font-size: 22px;
            color: #1e2f3f;
        }
        
        .badge {
            background: #eef3f9;
            padding: 20px 25px;
            border-radius: 40px;
            font-size: 26px;
            margin: 10px 0;
        }
        
        .product-img {
            background: #d9e8f5;
            width: 100%;
            height: 300px;
            border-radius: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 36px;
            color: #2a7faa;
            font-weight: bold;
            border: 3px dashed #2a7faa;
            margin: 30px 0;
        }
        
        .footer-note {
            margin-top: 30px;
            color: #7a8b9f;
            font-size: 22px;
            text-align: center;
        }
        
        @media (max-width: 1100px) {
            .slide {
                width: 95%;
                padding: 30px;
            }
        }
    </style>
</head>
<body>
    <div class="presentation">
        <!-- СЛАЙД 1: Введение -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Введение</span>
                <span class="slide-number">1/12</span>
            </div>
            <div class="slide-content" style="justify-content: center; text-align: center;">
                <h2 style="font-size: 56px; margin-bottom: 30px;">Умный органайзер школьника</h2>
                <p style="font-size: 32px; color: #2a7faa;">Индивидуальный проект</p>
                <div style="height: 40px;"></div>
                <p style="font-size: 28px;">Автор: [Твоё имя]</p>
                <p style="font-size: 28px;">10 класс, [школа]</p>
                <p style="font-size: 28px;">2026 г.</p>
            </div>
        </div>

        <!-- СЛАЙД 2: Актуальность -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Актуальность</span>
                <span class="slide-number">2/12</span>
            </div>
            <div class="slide-content">
                <p>В 10-11 классах нагрузка растёт:</p>
                <ul>
                    <li>сложная программа + ЕГЭ</li>
                    <li>проекты и олимпиады</li>
                    <li>долгосрочные задания</li>
                </ul>
                <p style="margin-top: 40px;">Традиционные дневники и календари <strong>не справляются</strong> — они не учитывают специфику школы и не автоматизируют планирование.</p>
                <div style="background: #f0f7fc; padding: 25px; border-radius: 40px; margin-top: 30px;">
                    <p style="font-size: 28px;">➜ Нужен инструмент, который сам распределит нагрузку</p>
                </div>
            </div>
        </div>

        <!-- СЛАЙД 3: Цель и задачи -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Цель и задачи</span>
                <span class="slide-number">3/12</span>
            </div>
            <div class="slide-content">
                <p><strong>Цель:</strong> разработать «умный» органайзер для автоматизации планирования учебной нагрузки.</p>
                <div style="margin-top: 40px;">
                    <h3>Задачи:</h3>
                    <ul>
                        <li>исследовать потребности (анкетирование)</li>
                        <li>проанализировать существующие решения</li>
                        <li>спроектировать архитектуру и интерфейс</li>
                        <li>реализовать модули на C# + WPF + SQLite</li>
                        <li>протестировать и провести апробацию</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- СЛАЙД 4: Объект и предмет -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Объект и предмет</span>
                <span class="slide-number">4/12</span>
            </div>
            <div class="slide-content">
                <div class="grid-2">
                    <div class="card" style="height: 250px;">
                        <h4>Объект</h4>
                        <p style="font-size: 28px;">программные средства для организации личного времени</p>
                    </div>
                    <div class="card" style="height: 250px;">
                        <h4>Предмет</h4>
                        <p style="font-size: 28px;">процесс разработки интеллектуального органайзера с автопланированием</p>
                    </div>
                </div>
                <p style="margin-top: 40px; font-size: 26px;"><strong>Гипотеза:</strong> специализированное приложение повысит эффективность планирования и снизит стресс у старшеклассников.</p>
            </div>
        </div>

        <!-- СЛАЙД 5: Теоретические положения -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Теоретическая база</span>
                <span class="slide-number">5/12</span>
            </div>
            <div class="slide-content">
                <ul>
                    <li>подросткам сложно планировать из-за незрелости префронтальной коры (развивается до 25 лет)</li>
                    <li>склонность к прокрастинации, трудности с оценкой времени</li>
                    <li>существующие решения либо слишком просты (бумага), либо не адаптированы под школу (Google Calendar, Todoist)</li>
                </ul>
                <p style="margin-top: 40px; background: #e6f2f9; padding: 20px; border-radius: 40px;">➜ Вывод: нужен инструмент, который компенсирует возрастные ограничения</p>
            </div>
        </div>

        <!-- СЛАЙД 6: Организация исследования -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Организация исследования</span>
                <span class="slide-number">6/12</span>
            </div>
            <div class="slide-content">
                <div class="grid-2">
                    <div>
                        <p><strong>Методы:</strong></p>
                        <ul style="font-size: 22px;">
                            <li>анкетирование (50 чел., 10-11 классы)</li>
                            <li>анализ литературы</li>
                            <li>сравнительный анализ</li>
                            <li>тестирование прототипа</li>
                        </ul>
                    </div>
                    <div>
                        <p><strong>Выборка:</strong></p>
                        <ul style="font-size: 22px;">
                            <li>3 школы Москвы</li>
                            <li>50 старшеклассников</li>
                            <li>апробация: 4 человека (2 недели)</li>
                        </ul>
                    </div>
                </div>
                <div style="margin-top: 40px;">
                    <p>📊 Анкета: 10 вопросов про забытые дедлайны, стресс, полезность автопланировщика</p>
                </div>
            </div>
        </div>

        <!-- СЛАЙД 7: Результаты опроса — часть 1 -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Результаты опроса (1)</span>
                <span class="slide-number">7/12</span>
            </div>
            <div class="slide-content">
                <p><strong>Как часто забываете о дедлайнах?</strong></p>
                <div class="chart">
                    <div style="display: flex; flex-direction: column; align-items: center;">
                        <div class="bar" style="height: 170px;">65%</div>
                        <span class="bar-label">1-2 раза в неделю</span>
                    </div>
                    <div style="display: flex; flex-direction: column; align-items: center;">
                        <div class="bar" style="height: 70px;">25%</div>
                        <span class="bar-label">1-2 раза в месяц</span>
                    </div>
                    <div style="display: flex; flex-direction: column; align-items: center;">
                        <div class="bar" style="height: 30px;">10%</div>
                        <span class="bar-label">редко</span>
                    </div>
                </div>
                <p style="margin-top: 40px;"><strong>Сложность распределения больших задач:</strong> 72% оценили на 4-5 баллов (из 5)</p>
            </div>
        </div>

        <!-- СЛАЙД 8: Результаты опроса — часть 2 -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Результаты опроса (2)</span>
                <span class="slide-number">8/12</span>
            </div>
            <div class="slide-content">
                <p><strong>Что важнее всего в органайзере?</strong></p>
                <div class="grid-3">
                    <div class="card">
                        <div class="stat-number">52%</div>
                        <p>напоминания</p>
                    </div>
                    <div class="card">
                        <div class="stat-number">45%</div>
                        <p>автопланирование</p>
                    </div>
                    <div class="card">
                        <div class="stat-number">38%</div>
                        <p>визуализация нагрузки</p>
                    </div>
                </div>
                <p style="margin-top: 40px;"><strong>Требования к интерфейсу:</strong></p>
                <ul>
                    <li>60% — максимальная простота</li>
                    <li>25% — возможность кастомизации</li>
                    <li>15% — яркий дизайн</li>
                </ul>
            </div>
        </div>

        <!-- СЛАЙД 9: Результаты опроса — часть 3 -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Результаты опроса (3)</span>
                <span class="slide-number">9/12</span>
            </div>
            <div class="slide-content">
                <p><strong>Как часто испытываете стресс из-за планирования?</strong></p>
                <div class="grid-2">
                    <div class="card">
                        <div class="stat-number">48%</div>
                        <p>часто (в период контрольных)</p>
                    </div>
                    <div class="card">
                        <div class="stat-number">32%</div>
                        <p>постоянно</p>
                    </div>
                </div>
                <p style="margin-top: 40px;"><strong>Полезность автопланировщика:</strong> 84% сказали «часто» или «крайне часто»</p>
                <p style="font-size: 28px; background: #eef; padding: 15px; border-radius: 40px; margin-top: 20px;">➜ подтверждение гипотезы</p>
            </div>
        </div>

        <!-- СЛАЙД 10: Результат работы -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Результат работы</span>
                <span class="slide-number">10/12</span>
            </div>
            <div class="slide-content">
                <ul>
                    <li>разработано приложение на C# / WPF / SQLite</li>
                    <li>модули: расписание, задания, автопланировщик, напоминания</li>
                    <li>алгоритм автоматически распределяет большие задачи по свободным окнам</li>
                </ul>
                <div class="grid-2" style="margin-top: 40px;">
                    <div class="card">
                        <p>📈 выполнено вовремя</p>
                        <div class="stat-number">+40%</div>
                    </div>
                    <div class="card">
                        <p>⬇️ забытые дедлайны</p>
                        <div class="stat-number">-60%</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- СЛАЙД 11: Продукт -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Продукт</span>
                <span class="slide-number">11/12</span>
            </div>
            <div class="slide-content">
                <div class="product-img">
                    🖥️ Умный органайзер школьника
                </div>
                <div class="grid-2">
                    <div class="card">
                        <h4>Функции</h4>
                        <p>• расписание</p>
                        <p>• задания + дедлайны</p>
                        <p>• автопланирование</p>
                        <p>• визуализация нагрузки</p>
                    </div>
                    <div class="card">
                        <h4>Технологии</h4>
                        <p>C# / WPF</p>
                        <p>SQLite</p>
                        <p>Windows</p>
                    </div>
                </div>
                <p style="margin-top: 30px;">Оценка пользователей: удобство 4.2/5, полезность 4.5/5</p>
            </div>
        </div>

        <!-- СЛАЙД 12: Заключение и перспективы -->
        <div class="slide">
            <div class="slide-header">
                <span class="slide-title">Заключение</span>
                <span class="slide-number">12/12</span>
            </div>
            <div class="slide-content">
                <p>✔ цель достигнута — органайзер работает и помогает</p>
                <p>✔ гипотеза подтверждена: снижение стресса, рост эффективности</p>
                <div style="margin-top: 40px;">
                    <h3>Перспективы:</h3>
                    <ul>
                        <li>мобильная версия (iOS/Android)</li>
                        <li>облачная синхронизация</li>
                        <li>интеграция с электронными дневниками</li>
                    </ul>
                </div>
                <div class="footer-note">
                    Спасибо за внимание!
                </div>
            </div>
        </div>
    </div>
</body>
</html>
