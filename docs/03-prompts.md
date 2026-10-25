# Промпты для генерации визуалов (Midjourney / Flux / DALL·E / Kandinsky)

Референс: тёмный неон VR/метавселенная (фиолет, маджента, циан). Все картинки — **без текста и букв**, соотношение **16:9** (кроме аватаров команды).

## Единый стиль-суффикс

Добавлять в конец каждого промпта:

```
dark violet background, neon glow purple magenta and cyan accents,
holographic UI elements, cinematic rim lighting, high detail 3D render,
futuristic medtech aesthetic, no text, no letters, no logos, no watermark
```

## Негативный промпт

```
text, letters, numbers, watermark, logo, bright white background,
flat lighting, cartoon, low quality, jpeg artifacts, clutter, busy frame,
extra fingers, deformed hands
```

---

## Каталог иллюстраций

Нумерация — по итоговым слайдам (14 слайдов). Имена файлов совпадают
с плейсхолдерами в `index.html`.

### 01-cover.jpg — Обложка (слайд 1)
XR-шлем на фоне голографического черепа с подсвеченной анатомией нижней челюсти и тройничным нервом.

```
futuristic XR mixed-reality headset floating next to a translucent holographic
human skull with glowing mandible and nerve pathways, dental anesthesia training theme,
volumetric neon light beams, dark violet deep-space background with soft particle field,
open negative space on the left for headline, cinematic hero shot
```
`--ar 16:9`

### 02-risk.jpg — Боль / риск (слайд 2) — ТРЕБУЕТСЯ ПЕРЕГЕНЕРАЦИЯ
Слайд собран на крупных цифрах — картинка используется как фоновая декорация, поэтому на ней
недопустимы любые цифры/текст. Предыдущая версия содержала «70%» и не пригодна.

```
abstract 3D scene of medical risk: single glowing warning triangle and one
wireframe transparent syringe floating in dark violet space,
soft purple to magenta gradient with a few cyan bokeh particles,
absolutely empty composition, wide open dark areas, no text, no numbers,
no charts, no diagrams, no symbols except the warning triangle
```
`--ar 16:9`

STATUS: перегенерирована (вариант «риск 1») и вставлена фоном слайда 2.

### 03-mr.jpg — Решение: смешанная реальность (слайд 3)
Пара рук над манекеном, поверх них — голографические кости/нервы челюсти (MR-режим).

```
mixed reality dental anesthesia scene: realistic mannequin head on stand with
hands holding a carpule syringe above it, overlaid holographic mandible bone,
nerve channels and mucosa in glowing cyan and magenta wireframe,
dark violet environment, hologram scanlines, first-person training view
```
`--ar 16:9`

### 04-arch.jpg — Состав комплекса (слайд 4)
Разнесённая сцена: шлем, манекен, шприц-имитатор, трекер — парящие элементы.

```
exploded-view of a dental MR training station: XR headset, medical mannequin head,
carpule syringe simulator with optical tracking markers, small external tracking
camera unit, arranged as floating objects connected with thin neon cyan guide lines,
dark violet studio background, product-visualization style, no text
```
`--ar 16:9`

### 04-alt.jpg — Архитектурная схема (слайд 4, альтернатива)

```
abstract 3D architecture diagram: interconnected glowing cubes and nodes forming
a modular system, central bright core, thin cyan data lines, floating in dark
violet space with soft fog, tech blueprint mood, no text, no labels
```
`--ar 16:9`

### 05-bg.jpg — Фон процесса (слайд 5, опционально)
Step-timeline собирается в CSS; фон — только текстура под ноги.

```
minimal abstract background for a process slide: soft dark violet gradient with
a faint horizontal light trail flowing left to right, subtle particle dust,
generous empty center for timeline, no objects, no text
```
`--ar 16:9`

### 06-glass.jpg — Режимы (слайд 6, опционально)
3 glass-карточки рисуются в CSS.

```
three translucent glass panels floating in dark violet space, edge-lit with
purple and magenta neon, soft reflections, empty surfaces for icons, minimal,
no text, no objects
```
`--ar 16:9`

### 07-needle.jpg — Точность: игла и траектория (слайд 7)
Макро: кончик иглы + неоновая траектория + HUD-кольца.

```
macro shot of a dental syringe needle tip with a glowing cyan trajectory line
and holographic measurement rings around it, depth markers and angle indicators
as thin neon graphics, mandible hologram out of focus behind, dark violet scene,
precision-tech mood, no text
```
`--ar 16:9`

### 08-dashboard.jpg — Дашборд преподавателя (слайд 8)
Экран монитора с неоновым UI (абстрактно, без читаемого текста) + вид из шлема.

```
teacher's monitoring screen concept: dark UI dashboard with abstract neon charts,
video view of a student in XR headset over mannequin, glowing status bars and
graph shapes without readable text, purple cyan magenta palette, holographic
floating panels, futuristic control room, no text, no letters
```
`--ar 16:9`

### 09-market.jpg — Рынок и рост (слайд 9)
Неоновая кривая роста, столбики — абстрактно, без текста.

```
abstract 3D growth chart made of glowing neon bars and a rising light curve,
purple to magenta gradient bars with cyan highlights, coin-like glowing discs
drifting, dark violet background, business-tech infographic mood, empty space
for numbers, no text
```
`--ar 16:9`

### 10-shield.jpg — Нормативная база (слайд 10, опционально)
Светящийся щит/галка — символ норм.

```
glowing holographic shield emblem with a check mark inside, made of thin neon
lines, floating above dark violet surface with soft magenta reflections,
compliance and certification theme, minimal composition, no text, no letters
```
`--ar 16:9`

### 11-roadmap.jpg — План / roadmap (слайд 11, опционально)
Дорога вдаль с неоновыми маркерами.

```
neon road stretching into dark violet distance with glowing milestone markers
along the side, futuristic timeline path, cyan light on the horizon,
purple fog, cinematic perspective, no text, no signs
```
`--ar 16:9`

### 12-compare.jpg — Сравнение (слайд 12, опционально)
4 объекта в ряд — наш светится ярче.

```
four floating geometric objects in a row in dark violet space, one bright glowing
holographic crystal with cyan magenta inner light, three others dim grey and matte,
comparison concept, soft reflections on dark floor, no text
```
`--ar 16:9`

### 13-avatar-1/2/3.jpg — Команда (слайд 13, опционально)
Стилизованные 3D-аватары (не фотореализм) — 3 штуки, квадрат 1:1. В HTML сейчас стоят
инициалы в неоновых кругах — аватары подставляются вместо них.

```
stylized 3D avatar bust of a professional woman in medical-style jacket,
neon rim lighting purple and cyan, dark violet background, minimal futuristic
portrait, no text, front view
```
`--ar 1:1`

```
stylized 3D avatar bust of a male doctor with glasses and beard, neon rim
lighting magenta and cyan, dark violet background, minimal futuristic portrait,
no text, front view
```
`--ar 1:1`

```
stylized 3D avatar bust of a young male software developer with headset,
neon rim lighting purple and cyan, dark violet background, minimal futuristic
portrait, no text, front view
```
`--ar 1:1`

### 15-bg.jpg — Фон всех контентных слайдов (общий)

Один фон используется заливкой на всех слайдах (поверх CSS-градиентов):

```
minimal dark violet presentation background: deep #0B0620 with subtle radial
glow of purple in the upper right corner and faint magenta gradient in lower
left, soft particle field, very dark, generous empty space, no objects, no text
```
`--ar 16:9`

---

## Статус вставки (актуально)

Картированы из `visual 11` в `redesign/assets/`:

| Файл assets | Слайд | Ссылка на исходник в visual 11 |
|---|---|---|
| 01-cover.jpg | 1 | `93762026… - 1.jfif` |
| 03-mr.jpg | 3 | `9c6c1925… - 3.jfif` |
| 04-arch.jpg | 4 | `e4772ded… - 4.jfif` |
| 07-needle.jpg | 7 | `994b54ad… - 8.jfif` |
| 08-dashboard.jpg | 8 | `5189e879… - 9.jfif` |
| 13-avatar-1/2/3.jpg | 13 | `аватар -1/- 2/- 3.jfif` |
| 15-bg.jpg | все | `фон -1.jfif` (тёмный оверлей 78–88%) |

Вставлены фоновыми слоями (класс на section + тёмный оверлей 85–92%):
`s2` opt-risk (02-risk.jpg — треугольник+шприц), `s6` opt-glass (06-glass.jpg — 3 панели),
`s9` opt-market (09-market.jpg — график), `s11` opt-road (11-roadmap.jpg — дорога),
`s12` opt-compare (12-compare.jpg — кристаллы. В `s10` щит — круглая мини-иконка
(10-shield.jpg) у заголовка «Нормативная база».

Не вставлен: `04-alt.jpg` (схема кубов) — на слайде 4 уже стоит фото станции, дубль не нужен.

Не сгенерировано/не пригодно: `02-risk.jpg` — перегенерировать (см. блок выше,
в прошлой версии появился текст «70%», который против фактов слайда).

Чтобы добавить одну из опциональных: скопировать содержимое нужного блока
placeholder-а в `index.html` (искать по файлу) или попросить агента вернуть placeholder.

