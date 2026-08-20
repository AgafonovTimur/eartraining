# Слух / Ear Trainer / 耳朵训练

**Language / Язык / 语言:** [Русский](#русский) | [English](#english) | [中文](#中文)

---

## Русский

### Слух

Приложение для тренировки и развития слуха: угадывание нот, интервалов и аккордов на слух. Есть поддержка MIDI-клавиатуры.

#### 1. Функции приложения

**Три режима тренировки**
- Ноты — проигрывается одна нота, нужно выбрать какая.
- Интервалы — проигрываются две ноты (интервал), нужно выбрать, какой это интервал (например, «большая терция»).
- Аккорды — проигрывается аккорд (несколько нот одновременно), нужно выбрать аккорд.

**Как отвечать**
Ответ можно дать несколькими способами одновременно:
- Мышью/нажатие на ноты — нажать на клавиши пианино на экране (или на кнопку с названием интервала/аккорда).
- Клавиатурой компьютера — клавиши A–G обозначают ноты (раскладка клавиатуры не важна, работает и русская, и английская).
- MIDI-клавиатурой — если подключить MIDI-клавиатуру, можно играть ответ прямо на ней.

**Проверка ответа**
- После ответа приложение подсвечивает зелёным правильные ноты и красным — неправильные (в том числе если ноты нажаты не в том порядке).
- Если ответ неверный, показывается пояснение: что было нажато и что нужно было нажать (нота, направление интервала, октава, обращение аккорда — смотря что не так).
- После правильного ответа приложение само переходит к следующему вопросу.

**Настройки**
Для каждого режима можно выбрать:
- какие ноты/интервалы/аккорды использовать в тренировке (можно несколько сразу, приложение будет чередовать их случайно);
- от какой ноты (нот) строить интервал/аккорд;
- в каких октавах играть вопрос;
- для аккордов — какое обращение аккорда использовать и насколько широко могут быть «растянуты» ноты аккорда;
- для интервалов — направление (вверх/вниз) и насколько широко может быть «растянут» интервал (в пределах одной октавы или шире).

**Звук**
- Можно слушать звук прямо в браузере (выбор из набора инструментов: рояль, гитара, скрипка, труба, флейта, хор и другие) или выводить звук через MIDI в DAW (нужен виртуальный кабель вроде Loopbe или аналог).
- Регулировка громкости.

**MIDI**
- Подключение внешней MIDI-клавиатуры для ответа.
- Приложение реагирует на колесо (питч-бенд) MIDI-клавиатуры: покрутить колесо вверх — повторить вопрос, покрутить вниз — новый вопрос.

**Прочее**
- 5 цветовых тем оформления и 2 варианта цвета для правильных/неправильных ответов (обычный и «неоновый» с подсветкой).
- 3 языка интерфейса: русский, English, 简体中文 (определяется автоматически по языку браузера, можно переключить вручную).
- На мобильных устройствах часть функционала не работает. Приложение задумывалось под ПК.

#### 2. Горячие клавиши

| Клавиша | Действие |
|---|---|
| **A, B, C, D, E, F, G** | Ввод ответа нотой (нота нажимается как на пианино). Работает независимо от раскладки клавиатуры. |
| **Shift + буква нот** | Диез (например, Shift+D — D♯). |
| **Пробел, затем буква ноты** | Бемоль (например, пробел, потом G — G♭). |
| **Пробел** (после того, как ответ уже дан) | Перейти к следующему вопросу. |
| **Колесо мыши вверх** | Повторить текущий вопрос. |
| **Колесо мыши вниз** | Перейти к новому вопросу (можно в любой момент, даже до ответа). |
| **Средняя кнопка мыши** или **Y (Н)** | Открыть/закрыть панель настроек. |
| **Тап двумя пальцами** (на телефоне/планшете) | Открыть/закрыть панель настроек. |

#### 3. Что можно поменять через меню (панель настроек в приложении)

**Выбор режима** — вкладки «Ноты» / «Интервалы» / «Аккорды» вверху страницы.

**Что тренировать:**
- нота(ы) / интервал(ы) / аккорд(ы) — что именно должно попадаться в вопросах;
- нота, от которой строить интервал или аккорд;
- обращения аккорда (для аккордов, у которых это применимо);
- направление интервала (вверх/вниз);
- ширина интервала и ширина аккорда;
- октава(ы), в которых звучит вопрос;
- проверка октавы — «точная» или «любая».

**Расположение и вид:**
- расположение панели настроек — слева / по центру / справа;
- тема оформления (5 вариантов);
- цвет ответа — обычный или «неоновый» со свечением.

**Язык интерфейса** — русский / English / 简体中文.

**Звук:**
- вывод звука — через браузер («Онлайн») или через MIDI-выход в DAW (нужен виртуальный кабель Loopbe или аналог);
- при выводе через браузер — выбор инструмента (тембра) и громкости;
- при выводе через MIDI — выбор MIDI-выхода, MIDI-канала и значения velocity.

**MIDI-вход** — подключение MIDI-клавиатуры кнопкой «Подключить MIDI» и выбор конкретного MIDI-устройства, если их несколько.

Чтобы подключить звук из своего приложения или DAW:
1. Указать вход для миди — ваша миди клавиатура.
2. Указать выход для миди — в Loopbe это Internal MIDI.
3. В DAW/вашей программе (например, Pianoteq) выбрать Internal MIDI как входной сигнал. С клавиатуры не передаётся никакой сигнал в DAW/вашу программу. Нажатие срабатывает в программе, а она уже шлёт сигнал миди в DAW/вашу программу с выбранной velocity в настройках. Pitch bend не передаётся, поэтому искажения сигнала не будет. Если слышите что-то лишнее — смотрите входы в DAW/вашей программе. Подключить можно любой инструмент, использующий миди.

#### 4. Что можно поменять только через настройки внутри файла

Эти параметры не выведены в меню — их можно поменять, открыв файл и отредактировав блок в начале `<script>` (отмечен комментарием «НАСТРОЙКИ ТРЕНАЖЁРА»):

```js
window.EAR_TRAINER_CONFIG = {
  velocityMin: 50,             // минимальная громкость (velocity) ноты при воспроизведении вопроса
  velocityMax: 100,            // максимальная громкость (velocity) ноты при воспроизведении вопроса
  noteDurationMs: 900,         // длительность звучания одной ноты, в миллисекундах
  chordStrumMs: 0,             // задержка между нотами аккорда при проигрывании
  defaultMidiChannel: 1,       // MIDI-канал, который выбран по умолчанию для вывода звука через MIDI
  midiAnswerDebounceMs: 350,   // сколько ждать после последней нажатой на MIDI-клавиатуре ноты, прежде чем проверить ответ
};
```

---

---

## English

### Ear Trainer

An app for training and developing your ear: recognizing notes, intervals, and chords by ear. MIDI keyboard support included.

#### 1. App features

**Three training modes**
- Notes — a single note is played; you pick which one it is.
- Intervals — two notes (an interval) are played; you pick which interval it is (e.g., "major third").
- Chords — a chord (several notes at once) is played; you pick the chord.

**How to answer**
You can answer in several ways at once:
- Mouse/click — click the on-screen piano keys (or a button with the interval/chord name).
- Computer keyboard — the A–G keys represent notes (keyboard layout doesn't matter, works on both Russian and English layouts).
- MIDI keyboard — if connected, you can play your answer directly on it.

**Answer checking**
- After answering, the app highlights correct notes in green and wrong ones in red (including when notes are pressed in the wrong order).
- If the answer is wrong, an explanation is shown: what was pressed and what should have been pressed (note, interval direction, octave, chord inversion — whichever applies).
- After a correct answer, the app automatically moves to the next question.

**Settings**
For each mode you can choose:
- which notes/intervals/chords to use in practice (several at once, the app will alternate them randomly);
- which note(s) to build the interval/chord from;
- which octaves the question is played in;
- for chords — which inversion to use and how widely the chord notes can be "spread";
- for intervals — direction (up/down) and how widely the interval can be "spread" (within one octave or wider).

**Sound**
- You can listen right in the browser (choice of instruments: piano, guitar, violin, trumpet, flute, choir, and others) or output sound via MIDI to a DAW (requires a virtual cable like LoopBe or similar).
- Volume control.

**MIDI**
- Connect an external MIDI keyboard to answer.
- The app responds to the MIDI keyboard's pitch-bend wheel: rolling it up repeats the question, rolling it down loads a new question.

**Other**
- 5 color themes and 2 color styles for correct/incorrect answers (normal and "neon" glow).
- 3 interface languages: Russian, English, Simplified Chinese (auto-detected from browser language, can be switched manually).
- Some functionality doesn't work on mobile devices. The app was designed for PC.

#### 2. Keyboard shortcuts

| Key | Action |
|---|---|
| **A, B, C, D, E, F, G** | Answer with a note (pressed like on a piano). Works regardless of keyboard layout. |
| **Shift + note letter** | Sharp (e.g., Shift+D — D♯). |
| **Space, then note letter** | Flat (e.g., Space, then G — G♭). |
| **Space** (after already answering) | Go to the next question. |
| **Mouse wheel up** | Repeat the current question. |
| **Mouse wheel down** | Go to a new question (works at any time, even before answering). |
| **Middle mouse button** or **Y** | Open/close the settings panel. |
| **Two-finger tap** (on phone/tablet) | Open/close the settings panel. |

#### 3. What you can change via the menu (in-app settings)

**Mode selection** — the "Notes" / "Intervals" / "Chords" tabs at the top of the page.

**What to practice:**
- note(s) / interval(s) / chord(s) — what should appear in the questions;
- the note to build the interval or chord from;
- chord inversions (for chords where applicable);
- interval direction (up/down);
- interval width and chord width;
- octave(s) the question is played in;
- octave checking — "exact" (must guess the exact octave played) or "any" (octave doesn't matter).

**Layout and appearance:**
- settings panel position — left / center / right;
- theme (5 options);
- answer color — normal or "neon" glow.

**Interface language** — Russian / English / Simplified Chinese.

**Sound:**
- sound output — through the browser ("Online") or via MIDI output to a DAW (requires a virtual cable like LoopBe or similar);
- for browser output — choice of instrument (timbre) and volume;
- for MIDI output — choice of MIDI output, MIDI channel, and velocity value.

**MIDI input** — connect a MIDI keyboard with the "Connect MIDI" button and select a specific MIDI device if there's more than one.

To route sound into your own app or DAW:
1. Set the MIDI input to your MIDI keyboard.
2. Set the MIDI output — in LoopBe this is "Internal MIDI".
3. In your DAW/app (e.g., Pianoteq) select "Internal MIDI" as the input. No signal is sent from the keyboard directly to the DAW/app. The keypress is processed by this app, which then sends a MIDI signal to the DAW/app with the velocity set in the settings. Pitch bend is not passed through, so there's no signal distortion. If you hear anything unexpected, check the inputs in your DAW/app. Any MIDI-capable instrument can be connected this way.

#### 4. What can only be changed via in-file settings

These settings aren't exposed in the menu — you can change them by opening the file and editing the block near the top of `<script>` (marked with the comment "НАСТРОЙКИ ТРЕНАЖЁРА" / "TRAINER SETTINGS"):

```js
window.EAR_TRAINER_CONFIG = {
  velocityMin: 50,             // minimum velocity of the note when playing the question
  velocityMax: 100,            // maximum velocity of the note when playing the question
  noteDurationMs: 900,         // how long a single note plays, in milliseconds
  chordStrumMs: 0,             // delay between chord notes when played (0 = all notes at once; higher = a "strummed" chord)
  defaultMidiChannel: 1,       // default MIDI channel used for MIDI sound output
  midiAnswerDebounceMs: 350,   // how long to wait after the last MIDI note press before checking the answer
};
```

---

---

## 中文

### 耳朵训练

一款用于训练和提升听力的应用：通过听力辨别音符、音程和和弦。支持 MIDI 键盘。

#### 1. 应用功能

**三种训练模式**
- 音符——播放一个音符，需要选出是哪一个。
- 音程——播放两个音符（一个音程），需要选出是哪种音程（例如"大三度"）。
- 和弦——播放一个和弦（多个音符同时响起），需要选出是哪个和弦。

**作答方式**
可以同时用多种方式作答：
- 鼠标点击音符——点击屏幕上的钢琴键（或点击带有音程/和弦名称的按钮）。
- 电脑键盘——A–G 键代表音符（键盘布局无关紧要，俄语和英语布局都可用）。
- MIDI 键盘——若已连接 MIDI 键盘，可直接在其上演奏答案。

**答案检查**
- 作答后，应用会将正确音符高亮为绿色，错误音符高亮为红色（包括音符按下顺序不对的情况）。
- 若答案错误，会显示说明：实际按下了什么、应该按下什么（音符、音程方向、八度、和弦转位——具体取决于错在哪里）。
- 答对后，应用会自动进入下一题。

**设置**
每种模式都可以设置：
- 训练中使用哪些音符/音程/和弦（可同时选多个，应用会随机切换）；
- 从哪个（些）音符构建音程/和弦；
- 题目在哪些八度中播放；
- 对于和弦——使用哪种转位，以及和弦音符可以"展开"多宽；
- 对于音程——方向（上行/下行），以及音程可以"展开"多宽（限于一个八度内还是更宽）。

**声音**
- 可以直接在浏览器中听声音（可选乐器：钢琴、吉他、小提琴、小号、长笛、合唱等），也可以通过 MIDI 输出到 DAW（需要 LoopBe 之类的虚拟声卡）。
- 音量调节。

**MIDI**
- 连接外部 MIDI 键盘作答。
- 应用会响应 MIDI 键盘的滚轮（弯音轮）：向上转动重复当前题目，向下转动切换到新题目。

**其他**
- 5 种配色主题，以及正确/错误答案的 2 种颜色风格（普通和带光效的"霓虹"）。
- 3 种界面语言：俄语、English、简体中文（根据浏览器语言自动检测，也可手动切换）。
- 移动设备上部分功能无法使用。该应用主要面向电脑设计。

#### 2. 快捷键

| 按键 | 操作 |
|---|---|
| **A, B, C, D, E, F, G** | 用音符作答（按下方式如同弹钢琴）。与键盘布局无关。 |
| **Shift + 音符字母** | 升号（例如 Shift+D — D♯）。 |
| **空格，然后音符字母** | 降号（例如空格后按 G — G♭）。 |
| **空格**（已作答后） | 进入下一题。 |
| **鼠标滚轮向上** | 重复当前题目。 |
| **鼠标滚轮向下** | 切换到新题目（任意时刻均可，包括作答前）。 |
| **鼠标中键** 或 **Y** | 打开/关闭设置面板。 |
| **双指点击**（手机/平板） | 打开/关闭设置面板。 |

#### 3. 通过菜单可更改的内容（应用内设置）

**模式选择**——页面顶部的"音符"/"音程"/"和弦"标签页。

**训练内容：**
- 音符/音程/和弦——题目中具体出现哪些内容；
- 构建音程或和弦的起始音符；
- 和弦转位（适用于相关和弦）；
- 音程方向（上行/下行）；
- 音程宽度和和弦宽度；
- 题目播放的八度；
- 八度检查方式——"精确"（需猜中实际播放的八度）或"任意"（八度不作要求）。

**布局和外观：**
- 设置面板位置——左 / 居中 / 右；
- 主题（5 种）；
- 答案颜色——普通或带光效的"霓虹"。

**界面语言**——俄语 / English / 简体中文。

**声音：**
- 声音输出方式——通过浏览器（"在线"）或通过 MIDI 输出到 DAW（需要 LoopBe 之类的虚拟声卡）；
- 浏览器输出时——选择乐器（音色）和音量；
- MIDI 输出时——选择 MIDI 输出、MIDI 通道和 velocity 值。

**MIDI 输入**——通过"连接 MIDI"按钮连接 MIDI 键盘，若有多个设备可选择具体的 MIDI 设备。

要将声音接入自己的应用或 DAW：
1. 将 MIDI 输入设为你的 MIDI 键盘。
2. 将 MIDI 输出设为对应设备——在 LoopBe 中为 Internal MIDI。
3. 在你的 DAW/程序（例如 Pianoteq）中，将 Internal MIDI 设为输入信号。键盘本身不会向 DAW/程序传送任何信号；按键会在本应用中触发，再由本应用按设置中的 velocity 值向 DAW/程序发送 MIDI 信号。弯音（Pitch bend）不会被传送，因此不会造成信号失真。如果听到多余的声音，请检查 DAW/程序中的输入设置。可连接任何支持 MIDI 的乐器。

#### 4. 只能通过文件内部设置更改的内容

这些参数未在菜单中开放——可以打开文件，编辑 `<script>` 开头处标有注释"НАСТРОЙКИ ТРЕНАЖЁРА"（训练器设置）的代码块来修改：

```js
window.EAR_TRAINER_CONFIG = {
  velocityMin: 50,             // 播放题目时音符的最小力度（velocity）
  velocityMax: 100,            // 播放题目时音符的最大力度（velocity）
  noteDurationMs: 900,         // 单个音符的播放时长（毫秒）
  chordStrumMs: 0,             // 播放和弦时音符之间的延迟（0 表示所有音符同时响起；数值越大越像"扫弦"式的分开演奏）
  defaultMidiChannel: 1,       // MIDI 声音输出默认使用的 MIDI 通道
  midiAnswerDebounceMs: 350,   // 在 MIDI 键盘上最后一个音符按下之后，等待多久再检查答案
};
```
