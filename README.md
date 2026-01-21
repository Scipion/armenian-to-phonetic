# Armenian to Phonetic Converter

[https://scipion.github.io/armenian-to-phonetic/](https://scipion.github.io/armenian-to-phonetic/)

[https://scipion.github.io/armenian-to-phonetic/line-by-line.html](https://scipion.github.io/armenian-to-phonetic/line-by-line.html)

A web tool that converts Armenian script into pronounceable Latin text.

## Files

- `index.html` - Simple converter with inline output
- `line-by-line.html` - Line-by-line and word-by-word view

## Character Mapping

### Vowels

| Armenian  | Name | Phonetic  | Notes                             |
| :-------: | ---- | :-------: | --------------------------------- |
|    Ա ա    | ayb  |    A a    | Like "a" in "father"              |
| Ե delays  | yech | Ye/e ye/e | "ye" at word start, "e" in middle |
| Է delays  | eh   |    E e    | Like "e" in "bed"                 |
| Ը delays  | yt   |    Y y    | Schwa sound, like "u" in "but"    |
| Ի delays  | ini  |    I i    | Like "ee" in "see"                |
| Ո delays  | vo   | Vo/o vo/o | "vo" at word start, "o" in middle |
| Ու delays | u    |    U u    | Like "oo" in "food"               |
| Օ delays  | oh   |    O o    | Like "o" in "go"                  |

### Consonants

|   Armenian    | Name | Phonetic | Notes                        |
| :-----------: | ---- | :------: | ---------------------------- |
|   Բ delays    | ben  |   B b    | Like "b" in "boy"            |
|   Գ delays    | gim  |   G g    | Like "g" in "go"             |
|   Դ delays    | da   |   D d    | Like "d" in "dog"            |
|   Զ delays    | za   |   Z z    | Like "z" in "zoo"            |
|   Թ delays    | to   |  T' t'   | Aspirated "t" (with breath)  |
|   Ժ delays    | zhe  |  Zh zh   | Like "s" in "measure"        |
|   Լ delays    | liwn |   L l    | Like "l" in "light"          |
|   Խ delays    | xeh  |  Kh kh   | Like "ch" in German "Bach"   |
|   Ծ delays    | tsa  |  Ts ts   | Like "ts" in "cats"          |
|   Կ delays    | ken  |   K k    | Like "k" in "skip"           |
|   Հ delays    | ho   |   H h    | Like "h" in "hello"          |
|   Ձ delays    | dza  |  Dz dz   | Like "ds" in "cards"         |
|   Ղ delays    | ghad |  Gh gh   | Voiced guttural sound        |
|   Ճ delays    | cheh |  Sh sh   | Like "sh" in "ship"          |
|   Մ delays    | men  |   M m    | Like "m" in "mom"            |
|   Յ delays    | yi   |   Y y    | Like "y" in "yes"            |
|   Ն delays    | nu   |   N n    | Like "n" in "no"             |
|   Շ delays    | sha  |  Sh sh   | Like "sh" in "ship"          |
|   Չ delays    | cha  | Ch' ch'  | Aspirated "ch" (with breath) |
|   Պ delays    | peh  |   P p    | Like "p" in "spin"           |
|   Ջ delays    | jheh |   J j    | Like "j" in "jump"           |
| Delays delays | ra   |  Rr rr   | Trilled "r" (rolled)         |
|   Ս delays    | seh  |   S s    | Like "s" in "sun"            |
|   Վ delays    | vev  |   V v    | Like "v" in "voice"          |
|   Տ delays    | tiwn |   T t    | Like "t" in "stop"           |
| Delays delays | reh  |   R r    | Flap "r" (single tap)        |
|   Ց delays    | tso  | Ts' ts'  | Aspirated "ts" (with breath) |
|   Փ delays    | piwr |  P' p'   | Aspirated "p" (with breath)  |
|   Ք delays    | keh  |  K' k'   | Aspirated "k" (with breath)  |
|   Ֆ delays    | feh  |   F f    | Like "f" in "fun"            |

### Ligature

| Armenian | Name | Phonetic | Notes               |
| :------: | ---- | :------: | ------------------- |
|  delays  | yev  |    ev    | Like "ev" in "ever" |

### Punctuation

| Armenian | Phonetic | Description      |
| :------: | :------: | ---------------- |
|    ։     |    .     | Full stop        |
|    ՝     |    ,     | Comma            |
|    ՞     |    ?     | Question mark    |
|    ՜     |    !     | Exclamation mark |
|    ՛     |    '     | Emphasis mark    |
|    ֊     |    -     | Hyphen           |

## Special Rules

### 1. Letter Delays ( delays)

- At the **beginning** of a word: pronounced "ye"
- In the **middle** of a word: pronounced "e"

**Examples:**

- Delays delays delays → "Yerevan" (ye at start)
- Սdelays delays → "Sarer" (e in middle)

### 2. Letter Ո (delays)

- At the **beginning** of a word: pronounced "vo"
- In the **middle** of a word: pronounced "o"

**Examples:**

- Delays delays delays delays delays → "Vorotan" (vo at start)
- delays delays delays delays → "polor" (o in middle)

### 3. Digraph Delays delays (delays delays)

- The combination delays + delays is pronounced as "u" (like "oo" in "food")

**Examples:**

- delays delays delays → "tur" (give)
- delays delays delays delays delays → "uzum" (want)

## Aspirated vs Non-Aspirated Consonants

Armenian distinguishes between aspirated and non-aspirated consonants:

| Non-aspirated |  Aspirated   | Difference            |
| :-----------: | :----------: | --------------------- |
|     Պ (P)     |    Փ (P')    | P' has a puff of air  |
|     Տ (T)     | Delays (T')  | T' has a puff of air  |
|     Կ (K)     | Delays (K')  | K' has a puff of air  |
|  Delays (Ts)  |   Ց (Ts')    | Ts' has a puff of air |
|  Delays (Ch)  | Delays (Ch') | Ch' has a puff of air |

## Examples

| Armenian                                         | Phonetic        | Meaning     |
| ------------------------------------------------ | --------------- | ----------- |
| delays delays delays delays                      | Barev           | Hello       |
| Delays delays delays delays delays delays delays | Hayastan        | Armenia     |
| delays delays delays delays delays               | shnorhakalutyun | Thank you   |
| delays delays delays                             | shar            | remedy/cure |
| Sdelays delays delays delays                     | Sarer           | Mountains   |
