# android-res-values-i18n

**android-res-values-i18n** (**values-i18n**) is an Android library (AAR) for Android app developers.
It contains only pre-translated string resources.

So far only 10 keys are included, but each has at least 30 translations.
These are not machine-translated, but have been carefully selected by comparing many popular apps.

<br>

## How to use
### Gradle Setup

**Step 1.** Add the JitPack repository to your build file (`build.gradle` or `settings.gradle` in the project root directory)

```gradle
repositories {
    …
    maven { url 'https://jitpack.io' }
}
```

**Step 2.** Add the dependency on this library to your `app/build.gradle`

```gradle
dependencies {
    …
    implementation 'com.github.nnsrymni:android-res-values-i18n:0.2.0'
}
```

**That's it!** Now you can use translated string resources provided by the library anywhere.

```xml
<!-- res/values/strings.xml in your app -->
<resources>
    …
    <string name="action_calendar"      >@string/ny_i18n_action_calendar</string>
    <string name="action_delete"        >@string/ny_i18n_action_delete</string>
    <string name="action_edit"          >@string/ny_i18n_action_edit</string>
    <string name="action_export"        >@string/ny_i18n_action_export</string>
    <string name="action_import"        >@string/ny_i18n_action_import</string>
    <string name="action_next"          >@string/ny_i18n_action_next</string>
    <string name="action_save"          >@string/ny_i18n_action_save</string>
    <string name="action_select_all"    >@string/ny_i18n_action_select_all</string>
    <string name="action_settings"      >@string/ny_i18n_action_settings</string>
    <string name="action_today"         >@string/ny_i18n_action_today</string>
```

<br>

## Quick Reference

### `@string/ny_i18n_action_calendar`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Calendar</td></tr>
<tr><td><code>res/values-af</code></td></td><td>Afrikaans</td><td lang="af" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">የቀን መቁጠሪያ</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">التقويم</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Календар</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">ক্যালেন্ডার</td></tr>
<tr><td><code>res/values-bs</code></td></td><td>Bosnian</td><td lang="bs" dir="auto">Kalendar</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Calendari</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Kalend&aacute;ř</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Eta;&mu;&epsilon;&rho;&omicron;&lambda;ό&gamma;&iota;&omicron;</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Calendario</td></tr>
<tr><td><code>res/values-et</code></td></td><td>Estonian</td><td lang="et" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Egutegia</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">تقویم</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Kalenteri</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Calendrier</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Calendario</td></tr>
<tr><td><code>res/values-gu</code></td></td><td>Gujarati</td><td lang="gu" dir="auto">કૅલેન્ડર</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Kalendar</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Napt&aacute;r</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Calendario</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">カレンダー</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">კალენდარი</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Күнтізбе</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">ប្រតិទិន</td></tr>
<tr><td><code>res/values-kn</code></td></td><td>Kannada</td><td lang="kn" dir="auto">ಕ್ಯಾಲೆಂಡರ್</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ປະຕິທິນ</td></tr>
<tr><td><code>res/values-lt</code></td></td><td>Lithuanian</td><td lang="lt" dir="auto">Kalendorius</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Kalendārs</td></tr>
<tr><td><code>res/values-mk</code></td></td><td>Macedonian</td><td lang="mk" dir="auto">Календар</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">കലണ്ടർ</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-ne</code></td></td><td>Nepali</td><td lang="ne" dir="auto">पात्रो</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Kalendarz</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Календарь</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Kalend&aacute;r</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Koledar</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Kalendari</td></tr>
<tr><td><code>res/values-sr</code></td></td><td>Serbian</td><td lang="sr" dir="auto">Календар</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Kalendar</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">Kalender</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">ปฏิทิน</td></tr>
<tr><td><code>res/values-tl</code></td></td><td>Tagalog</td><td lang="tl" dir="auto">Kalendaryo</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">Takvim</td></tr>
<tr><td><code>res/values-uk</code></td></td><td>Ukrainian</td><td lang="uk" dir="auto">Календар</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">Taqvim</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">Lịch</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">日历</td></tr>
</table></details>

---

### `@string/ny_i18n_action_delete`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Delete</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">ሰርዝ</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">حذف</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Изтриване</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">মুছুন</td></tr>
<tr><td><code>res/values-bs</code></td></td><td>Bosnian</td><td lang="bs" dir="auto">Izbri&scaron;i</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Suprimeix</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Slet</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">L&ouml;schen</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Delta;&iota;&alpha;&gamma;&rho;&alpha;&phi;ή</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Eliminar</td></tr>
<tr><td><code>res/values-et</code></td></td><td>Estonian</td><td lang="et" dir="auto">Kustuta</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Ezabatu</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">حذف</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Poista</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Supprimer</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Eliminar</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Izbri&scaron;i</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">T&ouml;rl&eacute;s</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Hapus</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Ey&eth;a</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Elimina</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">削除</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">წაშლა</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Жою</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">លុប</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">삭제</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ລຶບ</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Dzēst</td></tr>
<tr><td><code>res/values-mk</code></td></td><td>Macedonian</td><td lang="mk" dir="auto">Избриши</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">ഇല്ലാതാക്കുക</td></tr>
<tr><td><code>res/values-mr</code></td></td><td>Marathi</td><td lang="mr" dir="auto">हटवा</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Padam</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">Slett</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Verwijderen</td></tr>
<tr><td><code>res/values-pa</code></td></td><td>Punjabi</td><td lang="pa" dir="auto">ਮਿਟਾਓ</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Usuń</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Excluir</td></tr>
<tr><td><code>res/values-pt-rPT</code></td></td><td>Portuguese (Portugal)</td><td lang="pt-PT" dir="auto">Eliminar</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Удалить</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Odstr&aacute;niť</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Izbri&scaron;i</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Fshi</td></tr>
<tr><td><code>res/values-sr</code></td></td><td>Serbian</td><td lang="sr" dir="auto">Избриши</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Izbri&scaron;i</td></tr>
<tr><td><code>res/values-ta</code></td></td><td>Tamil</td><td lang="ta" dir="auto">நீக்கு</td></tr>
<tr><td><code>res/values-te</code></td></td><td>Telugu</td><td lang="te" dir="auto">తొలగించు</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">ลบ</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">Sil</td></tr>
<tr><td><code>res/values-uk</code></td></td><td>Ukrainian</td><td lang="uk" dir="auto">Видалити</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">O&lsquo;chirish</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">X&oacute;a</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">删除</td></tr>
<tr><td><code>res/values-zh-rHK</code></td></td><td>Chinese (Hong Kong SAR China)</td><td lang="zh-HK" dir="auto">刪除</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">刪除</td></tr>
</table></details>

---

### `@string/ny_i18n_action_edit`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Edit</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">አርትዕ</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Редактиране</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">সম্পাদনা করুন</td></tr>
<tr><td><code>res/values-bs</code></td></td><td>Bosnian</td><td lang="bs" dir="auto">Uređivanje</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Edita</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Upravit</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Rediger</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Bearbeiten</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Epsilon;&pi;&epsilon;&xi;&epsilon;&rho;&gamma;&alpha;&sigma;ί&alpha;</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Editar</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Editatu</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">ویرایش</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Muokkaa</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Modifier</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Editar</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Szerkeszt&eacute;s</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Edit</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Breyta</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Modifica</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">編集</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">რედაქტირება</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">កែសម្រួល</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ແກ້ໄຂ</td></tr>
<tr><td><code>res/values-lt</code></td></td><td>Lithuanian</td><td lang="lt" dir="auto">Redaguoti</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Rediģēt</td></tr>
<tr><td><code>res/values-mr</code></td></td><td>Marathi</td><td lang="mr" dir="auto">संपादित करा</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Edit</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">Rediger</td></tr>
<tr><td><code>res/values-ne</code></td></td><td>Nepali</td><td lang="ne" dir="auto">सम्पादन गर्नुहोस्</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Bewerken</td></tr>
<tr><td><code>res/values-pa</code></td></td><td>Punjabi</td><td lang="pa" dir="auto">ਸੰਪਾਦਨ ਕਰੋ</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Edytuj</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Editar</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Изменить</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Upraviť</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Redakto</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">Redigera</td></tr>
<tr><td><code>res/values-ta</code></td></td><td>Tamil</td><td lang="ta" dir="auto">திருத்து</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">แก้ไข</td></tr>
<tr><td><code>res/values-tl</code></td></td><td>Tagalog</td><td lang="tl" dir="auto">I-edit</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">D&uuml;zenle</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">Chỉnh sửa</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">编辑</td></tr>
<tr><td><code>res/values-zh-rHK</code></td></td><td>Chinese (Hong Kong SAR China)</td><td lang="zh-HK" dir="auto">編輯</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">編輯</td></tr>
</table></details>

---

### `@string/ny_i18n_action_export`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Export</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">تصدير</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Експортиране</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">রপ্তানি করুন</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Exportovat</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Eksport&eacute;r</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Exportieren</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Epsilon;&xi;&alpha;&gamma;&omega;&gamma;ή</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Exportar</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Esportatu</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Vie</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Exporter</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Exportar</td></tr>
<tr><td><code>res/values-gu</code></td></td><td>Gujarati</td><td lang="gu" dir="auto">નિકાસ કરો</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Izvoz</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Export&aacute;l&aacute;s</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Ekspor</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Flytja &uacute;t</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Esporta</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">エクスポート</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">ექსპორტი</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Экспорттау</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">내보내기</td></tr>
<tr><td><code>res/values-lt</code></td></td><td>Lithuanian</td><td lang="lt" dir="auto">Eksportuoti</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Eksportēt</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Exporteren</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Eksportuj</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Exportar</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Exportovať</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Izvozi</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Eksporto</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Izvezi</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">Exportera</td></tr>
<tr><td><code>res/values-te</code></td></td><td>Telugu</td><td lang="te" dir="auto">ఎగుమతి చేయి</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">ส่งออก</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">导出</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">匯出</td></tr>
</table></details>

---

### `@string/ny_i18n_action_import`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Import</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">استيراد</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Импортиране</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">আমদানি করুন</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Importa</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Import&eacute;r</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Importieren</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Epsilon;&iota;&sigma;&alpha;&gamma;&omega;&gamma;ή</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Importar</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Inportatu</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">وارد کردن</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Importer</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Importar</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Import&aacute;l&aacute;s</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Impor</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Flytja inn</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Importa</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">インポート</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">នាំចូល</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">가져오기</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ນຳເຂົ້າ</td></tr>
<tr><td><code>res/values-lt</code></td></td><td>Lithuanian</td><td lang="lt" dir="auto">Importuoti</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Importēt</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Import</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Importeren</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Importuj</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Importar</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Importovať</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Uvozi</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Importo</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Uvezi</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">Importera</td></tr>
<tr><td><code>res/values-ta</code></td></td><td>Tamil</td><td lang="ta" dir="auto">இறக்கு</td></tr>
<tr><td><code>res/values-te</code></td></td><td>Telugu</td><td lang="te" dir="auto">దిగుమతి చేయి</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">นำเข้า</td></tr>
<tr><td><code>res/values-uk</code></td></td><td>Ukrainian</td><td lang="uk" dir="auto">Імпортувати</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">Import qilish</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">Nhập</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">导入</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">匯入</td></tr>
</table></details>

---

### `@string/ny_i18n_action_next`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Next</td></tr>
<tr><td><code>res/values-af</code></td></td><td>Afrikaans</td><td lang="af" dir="auto">Volgende</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">ቀጣይ</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">التالي</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Напред</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">পরবর্তী</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Seg&uuml;ent</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Dal&scaron;&iacute;</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">N&aelig;ste</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Weiter</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Epsilon;&pi;ό&mu;&epsilon;&nu;&omicron;</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Siguiente</td></tr>
<tr><td><code>res/values-et</code></td></td><td>Estonian</td><td lang="et" dir="auto">J&auml;rgmine</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Hurrengoa</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">بعدی</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Seuraava</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Suivant</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Seguinte</td></tr>
<tr><td><code>res/values-gu</code></td></td><td>Gujarati</td><td lang="gu" dir="auto">આગલું</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Dalje</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Tov&aacute;bb</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Berikutnya</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">&Aacute;fram</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Avanti</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">次へ</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Келесі</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">បន្ទាប់</td></tr>
<tr><td><code>res/values-kn</code></td></td><td>Kannada</td><td lang="kn" dir="auto">ಮುಂದೆ</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">다음</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Tālāk</td></tr>
<tr><td><code>res/values-mk</code></td></td><td>Macedonian</td><td lang="mk" dir="auto">Следно</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">അടുത്തത്</td></tr>
<tr><td><code>res/values-mr</code></td></td><td>Marathi</td><td lang="mr" dir="auto">पुढील</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Seterusnya</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">Neste</td></tr>
<tr><td><code>res/values-ne</code></td></td><td>Nepali</td><td lang="ne" dir="auto">अर्को</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Volgende</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Dalej</td></tr>
<tr><td><code>res/values-pt-rPT</code></td></td><td>Portuguese (Portugal)</td><td lang="pt-PT" dir="auto">Seguinte</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Далее</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Ďalej</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Naprej</td></tr>
<tr><td><code>res/values-sr</code></td></td><td>Serbian</td><td lang="sr" dir="auto">Даље</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Dalje</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">N&auml;sta</td></tr>
<tr><td><code>res/values-ta</code></td></td><td>Tamil</td><td lang="ta" dir="auto">அடுத்து</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">ถัดไป</td></tr>
<tr><td><code>res/values-tl</code></td></td><td>Tagalog</td><td lang="tl" dir="auto">Susunod</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">İleri</td></tr>
<tr><td><code>res/values-uk</code></td></td><td>Ukrainian</td><td lang="uk" dir="auto">Далі</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">Keyingisi</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">Tiếp theo</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">下一步</td></tr>
<tr><td><code>res/values-zh-rHK</code></td></td><td>Chinese (Hong Kong SAR China)</td><td lang="zh-HK" dir="auto">下一步</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">下一步</td></tr>
</table></details>

---

### `@string/ny_i18n_action_save`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Save</td></tr>
<tr><td><code>res/values-af</code></td></td><td>Afrikaans</td><td lang="af" dir="auto">Stoor</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">አስቀምጥ</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">حفظ</td></tr>
<tr><td><code>res/values-bs</code></td></td><td>Bosnian</td><td lang="bs" dir="auto">Sačuvaj</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Desa</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Uložit</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Gem</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Speichern</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Alpha;&pi;&omicron;&theta;ή&kappa;&epsilon;&upsilon;&sigma;&eta;</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Guardar</td></tr>
<tr><td><code>res/values-et</code></td></td><td>Estonian</td><td lang="et" dir="auto">Salvesta</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Gorde</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">ذخیره</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Tallenna</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Enregistrer</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Gardar</td></tr>
<tr><td><code>res/values-gu</code></td></td><td>Gujarati</td><td lang="gu" dir="auto">સાચવો</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Spremi</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Ment&eacute;s</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Simpan</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Vista</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Salva</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">保存</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">შენახვა</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Сақтау</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">រក្សាទុក</td></tr>
<tr><td><code>res/values-kn</code></td></td><td>Kannada</td><td lang="kn" dir="auto">ಉಳಿಸಿ</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">저장</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ບັນທຶກ</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Saglabāt</td></tr>
<tr><td><code>res/values-mk</code></td></td><td>Macedonian</td><td lang="mk" dir="auto">Зачувај</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">സംരക്ഷിക്കുക</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Simpan</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">Lagre</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Opslaan</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Zapisz</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Salvar</td></tr>
<tr><td><code>res/values-pt-rPT</code></td></td><td>Portuguese (Portugal)</td><td lang="pt-PT" dir="auto">Guardar</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Сохранить</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Uložiť</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Shrani</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Ruaj</td></tr>
<tr><td><code>res/values-sr</code></td></td><td>Serbian</td><td lang="sr" dir="auto">Сачувај</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Sačuvaj</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">Spara</td></tr>
<tr><td><code>res/values-ta</code></td></td><td>Tamil</td><td lang="ta" dir="auto">சேமி</td></tr>
<tr><td><code>res/values-te</code></td></td><td>Telugu</td><td lang="te" dir="auto">సేవ్ చేయి</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">บันทึก</td></tr>
<tr><td><code>res/values-tl</code></td></td><td>Tagalog</td><td lang="tl" dir="auto">I-save</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">Kaydet</td></tr>
<tr><td><code>res/values-uk</code></td></td><td>Ukrainian</td><td lang="uk" dir="auto">Зберегти</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">Saqlash</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">Lưu</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">保存</td></tr>
<tr><td><code>res/values-zh-rHK</code></td></td><td>Chinese (Hong Kong SAR China)</td><td lang="zh-HK" dir="auto">儲存</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">儲存</td></tr>
</table></details>

---

### `@string/ny_i18n_action_select_all`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Select all</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">ሁሉንም ምረጥ</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Selecciona-ho tot</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Vybrat v&scaron;e</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Epsilon;&pi;&iota;&lambda;&omicron;&gamma;ή ό&lambda;&omega;&nu;</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Seleccionar todo</td></tr>
<tr><td><code>res/values-et</code></td></td><td>Estonian</td><td lang="et" dir="auto">Vali k&otilde;ik</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Hautatu guztiak</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">انتخاب همه</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Valitse kaikki</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Seleccionar todo</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Odaberi sve</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Pilih semua</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Velja allt</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">すべて選択</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Барлығын таңдау</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">모두 선택</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Atlasīt visu</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">എല്ലാം തിരഞ്ഞെടുക്കുക</td></tr>
<tr><td><code>res/values-mr</code></td></td><td>Marathi</td><td lang="mr" dir="auto">सर्व निवडा</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Pilih semua</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Alles selecteren</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Selecionar tudo</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Vybrať v&scaron;etko</td></tr>
<tr><td><code>res/values-sr</code></td></td><td>Serbian</td><td lang="sr" dir="auto">Изабери све</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Izaberi sve</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">เลือกทั้งหมด</td></tr>
<tr><td><code>res/values-tl</code></td></td><td>Tagalog</td><td lang="tl" dir="auto">Piliin lahat</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">T&uuml;m&uuml;n&uuml; se&ccedil;</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">Chọn tất cả</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">全选</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">全選</td></tr>
</table></details>

---

### `@string/ny_i18n_action_settings`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Settings</td></tr>
<tr><td><code>res/values-af</code></td></td><td>Afrikaans</td><td lang="af" dir="auto">Instellings</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Настройки</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">সেটিংস</td></tr>
<tr><td><code>res/values-bs</code></td></td><td>Bosnian</td><td lang="bs" dir="auto">Postavke</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Configuraci&oacute;</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Nastaven&iacute;</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">Indstillinger</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Einstellungen</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Rho;&upsilon;&theta;&mu;ί&sigma;&epsilon;&iota;&sigmaf;</td></tr>
<tr><td><code>res/values-es-rUS</code></td></td><td>Spanish (United States)</td><td lang="es-US" dir="auto">Configuraci&oacute;n</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Ezarpenak</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">تنظیمات</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">Asetukset</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Param&egrave;tres</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Configuraci&oacute;n</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Postavke</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Be&aacute;ll&iacute;t&aacute;sok</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">Stillingar</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Impostazioni</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">設定</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">პარამეტრები</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Параметрлер</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">ការកំណត់</td></tr>
<tr><td><code>res/values-kn</code></td></td><td>Kannada</td><td lang="kn" dir="auto">ಸೆಟ್ಟಿಂಗ್&zwnj;ಗಳು</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">설정</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ການຕັ້ງຄ່າ</td></tr>
<tr><td><code>res/values-lt</code></td></td><td>Lithuanian</td><td lang="lt" dir="auto">Nustatymai</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">Iestatījumi</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">ക്രമീകരണം</td></tr>
<tr><td><code>res/values-mr</code></td></td><td>Marathi</td><td lang="mr" dir="auto">सेटिंग्ज</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">Innstillinger</td></tr>
<tr><td><code>res/values-ne</code></td></td><td>Nepali</td><td lang="ne" dir="auto">सेटिङहरू</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Instellingen</td></tr>
<tr><td><code>res/values-pa</code></td></td><td>Punjabi</td><td lang="pa" dir="auto">ਸੈਟਿੰਗਾਂ</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Ustawienia</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Configura&ccedil;&otilde;es</td></tr>
<tr><td><code>res/values-pt-rPT</code></td></td><td>Portuguese (Portugal)</td><td lang="pt-PT" dir="auto">Defini&ccedil;&otilde;es</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Настройки</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Nastavenia</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Nastavitve</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">Inst&auml;llningar</td></tr>
<tr><td><code>res/values-te</code></td></td><td>Telugu</td><td lang="te" dir="auto">సెట్టింగ్&zwnj;లు</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">การตั้งค่า</td></tr>
<tr><td><code>res/values-tl</code></td></td><td>Tagalog</td><td lang="tl" dir="auto">Mga Setting</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">Ayarlar</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">Sozlamalar</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">设置</td></tr>
<tr><td><code>res/values-zh-rHK</code></td></td><td>Chinese (Hong Kong SAR China)</td><td lang="zh-HK" dir="auto">設定</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">設定</td></tr>
</table></details>

---

### `@string/ny_i18n_action_today`

Can be used for:
- buttons
- menu items

<details open><table>
<tr><th>Directory</th><th>Locale</th><th>Translation</th></tr>
<tr><td><code>res/values</code></td></td><td>(default)</td><td lang="en-US" dir="auto">Today</td></tr>
<tr><td><code>res/values-af</code></td></td><td>Afrikaans</td><td lang="af" dir="auto">Vandag</td></tr>
<tr><td><code>res/values-am</code></td></td><td>Amharic</td><td lang="am" dir="auto">ዛሬ</td></tr>
<tr><td><code>res/values-ar</code></td></td><td>Arabic</td><td lang="ar" dir="auto">اليوم</td></tr>
<tr><td><code>res/values-bg</code></td></td><td>Bulgarian</td><td lang="bg" dir="auto">Днес</td></tr>
<tr><td><code>res/values-bn</code></td></td><td>Bangla</td><td lang="bn" dir="auto">আজ</td></tr>
<tr><td><code>res/values-bs</code></td></td><td>Bosnian</td><td lang="bs" dir="auto">Danas</td></tr>
<tr><td><code>res/values-ca</code></td></td><td>Catalan</td><td lang="ca" dir="auto">Avui</td></tr>
<tr><td><code>res/values-cs</code></td></td><td>Czech</td><td lang="cs" dir="auto">Dnes</td></tr>
<tr><td><code>res/values-da</code></td></td><td>Danish</td><td lang="da" dir="auto">I dag</td></tr>
<tr><td><code>res/values-de</code></td></td><td>German</td><td lang="de" dir="auto">Heute</td></tr>
<tr><td><code>res/values-el</code></td></td><td>Greek</td><td lang="el" dir="auto">&Sigma;ή&mu;&epsilon;&rho;&alpha;</td></tr>
<tr><td><code>res/values-es</code></td></td><td>Spanish</td><td lang="es" dir="auto">Hoy</td></tr>
<tr><td><code>res/values-et</code></td></td><td>Estonian</td><td lang="et" dir="auto">T&auml;na</td></tr>
<tr><td><code>res/values-eu</code></td></td><td>Basque</td><td lang="eu" dir="auto">Gaur</td></tr>
<tr><td><code>res/values-fa</code></td></td><td>Persian</td><td lang="fa" dir="auto">امروز</td></tr>
<tr><td><code>res/values-fi</code></td></td><td>Finnish</td><td lang="fi" dir="auto">T&auml;n&auml;&auml;n</td></tr>
<tr><td><code>res/values-fr</code></td></td><td>French</td><td lang="fr" dir="auto">Aujourd'hui</td></tr>
<tr><td><code>res/values-gl</code></td></td><td>Galician</td><td lang="gl" dir="auto">Hoxe</td></tr>
<tr><td><code>res/values-gu</code></td></td><td>Gujarati</td><td lang="gu" dir="auto">આજે</td></tr>
<tr><td><code>res/values-hr</code></td></td><td>Croatian</td><td lang="hr" dir="auto">Danas</td></tr>
<tr><td><code>res/values-hu</code></td></td><td>Hungarian</td><td lang="hu" dir="auto">Ma</td></tr>
<tr><td><code>res/values-in</code></td></td><td>Indonesian</td><td lang="id" dir="auto">Hari ini</td></tr>
<tr><td><code>res/values-is</code></td></td><td>Icelandic</td><td lang="is" dir="auto">&Iacute; dag</td></tr>
<tr><td><code>res/values-it</code></td></td><td>Italian</td><td lang="it" dir="auto">Oggi</td></tr>
<tr><td><code>res/values-ja</code></td></td><td>Japanese</td><td lang="ja" dir="auto">今日</td></tr>
<tr><td><code>res/values-ka</code></td></td><td>Georgian</td><td lang="ka" dir="auto">დღეს</td></tr>
<tr><td><code>res/values-kk</code></td></td><td>Kazakh</td><td lang="kk" dir="auto">Бүгін</td></tr>
<tr><td><code>res/values-km</code></td></td><td>Khmer</td><td lang="km" dir="auto">ថ្ងៃនេះ</td></tr>
<tr><td><code>res/values-kn</code></td></td><td>Kannada</td><td lang="kn" dir="auto">ಇಂದು</td></tr>
<tr><td><code>res/values-ko</code></td></td><td>Korean</td><td lang="ko" dir="auto">오늘</td></tr>
<tr><td><code>res/values-lo</code></td></td><td>Lao</td><td lang="lo" dir="auto">ມື້ນີ້</td></tr>
<tr><td><code>res/values-lt</code></td></td><td>Lithuanian</td><td lang="lt" dir="auto">&Scaron;iandien</td></tr>
<tr><td><code>res/values-lv</code></td></td><td>Latvian</td><td lang="lv" dir="auto">&Scaron;odien</td></tr>
<tr><td><code>res/values-mk</code></td></td><td>Macedonian</td><td lang="mk" dir="auto">Денес</td></tr>
<tr><td><code>res/values-ml</code></td></td><td>Malayalam</td><td lang="ml" dir="auto">ഇന്ന്</td></tr>
<tr><td><code>res/values-mr</code></td></td><td>Marathi</td><td lang="mr" dir="auto">आज</td></tr>
<tr><td><code>res/values-ms</code></td></td><td>Malay</td><td lang="ms" dir="auto">Hari ini</td></tr>
<tr><td><code>res/values-nb</code></td></td><td>Norwegian Bokmål</td><td lang="nb" dir="auto">I dag</td></tr>
<tr><td><code>res/values-ne</code></td></td><td>Nepali</td><td lang="ne" dir="auto">आज</td></tr>
<tr><td><code>res/values-nl</code></td></td><td>Dutch</td><td lang="nl" dir="auto">Vandaag</td></tr>
<tr><td><code>res/values-pa</code></td></td><td>Punjabi</td><td lang="pa" dir="auto">ਅੱਜ</td></tr>
<tr><td><code>res/values-pl</code></td></td><td>Polish</td><td lang="pl" dir="auto">Dzisiaj</td></tr>
<tr><td><code>res/values-pt</code></td></td><td>Portuguese</td><td lang="pt" dir="auto">Hoje</td></tr>
<tr><td><code>res/values-ru</code></td></td><td>Russian</td><td lang="ru" dir="auto">Сегодня</td></tr>
<tr><td><code>res/values-sk</code></td></td><td>Slovak</td><td lang="sk" dir="auto">Dnes</td></tr>
<tr><td><code>res/values-sl</code></td></td><td>Slovenian</td><td lang="sl" dir="auto">Danes</td></tr>
<tr><td><code>res/values-sq</code></td></td><td>Albanian</td><td lang="sq" dir="auto">Sot</td></tr>
<tr><td><code>res/values-sr</code></td></td><td>Serbian</td><td lang="sr" dir="auto">Данас</td></tr>
<tr><td><code>res/values-b+sr+Latn</code></td></td><td>Serbian (Latin)</td><td lang="sr-Latn" dir="auto">Danas</td></tr>
<tr><td><code>res/values-sv</code></td></td><td>Swedish</td><td lang="sv" dir="auto">I dag</td></tr>
<tr><td><code>res/values-ta</code></td></td><td>Tamil</td><td lang="ta" dir="auto">இன்று</td></tr>
<tr><td><code>res/values-th</code></td></td><td>Thai</td><td lang="th" dir="auto">วันนี้</td></tr>
<tr><td><code>res/values-tr</code></td></td><td>Turkish</td><td lang="tr" dir="auto">Bug&uuml;n</td></tr>
<tr><td><code>res/values-uk</code></td></td><td>Ukrainian</td><td lang="uk" dir="auto">Сьогодні</td></tr>
<tr><td><code>res/values-uz</code></td></td><td>Uzbek</td><td lang="uz" dir="auto">Bugun</td></tr>
<tr><td><code>res/values-vi</code></td></td><td>Vietnamese</td><td lang="vi" dir="auto">H&ocirc;m nay</td></tr>
<tr><td><code>res/values-zh-rCN</code></td></td><td>Chinese (China)</td><td lang="zh-CN" dir="auto">今天</td></tr>
<tr><td><code>res/values-zh-rHK</code></td></td><td>Chinese (Hong Kong SAR China)</td><td lang="zh-HK" dir="auto">今天</td></tr>
<tr><td><code>res/values-zh-rTW</code></td></td><td>Chinese (Taiwan)</td><td lang="zh-TW" dir="auto">今天</td></tr>
</table></details>
