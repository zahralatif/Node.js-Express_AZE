# Node.js və Express ilə Back-End proqramlarının inkişafı

## Giriş
Stack Overflow-un 2022-ci ildə keçirdiyi sorğunun nəticələrinə əsasən, developerlərin təxminən 50%-i Node.js istifadə etdiyini bildirmişdir ki, bu da onu server-side texnologiyaları arasında ən çox istifadə edilən edir. Eyni zamanda, Express ümumilikdə dördüncü ən populyar veb texnologiya olaraq siyahıya alınmış və ən populyar server-side veb framework olaraq seçilmişdir. Node.js, server-side JavaScript tətbiqlərini işlədə bilən bir runtime mühitidir, Express isə Node.js üzərində işləyən və tətbiqlərin inkişafı üçün istifadə edilən server-side JavaScript veb frameworkudur.


# Back-end və Front-end Development

## Back-end Development

Back-end development, server-side development olaraq da tanınır və istifadəçilərin görmədiyi veb saytın və ya tətbiqin hissəsini yaratmaqdan ibarətdir. Serveri, bazanı və tətbiq məntiqini idarə edir və frontend-in lazım olan məlumatlara və funksionallığa çıxışını təmin edir. 

### Back-end Development-in Əsas Komponentləri:

1. **Server**: Müştərilərə şəbəkə üzərindən resurslar, məlumatlar, xidmətlər və ya proqramlar təmin edən hardware və ya software.
2. **Database**: Asanlıqla əldə edilə bilən, idarə edilə bilən və yenilənə bilən strukturlu məlumatlar toplusu.
* *SQL Databases*: Relational bazalar, məsələn MySQL, PostgreSQL və SQLite.
* *NoSQL Databases*: Non-relational bazalar, məsələn MongoDB, Cassandra və Redis.
3. **Server-Side Proqramlaşdırma dilləri**: 
* *Node.js*: Chrome-un V8 JavaScript mühərriki üzərində qurulmuş JavaScript runtime.
* *Python*: Oxunaqlılığı və səmərəliliyi ilə tanınan yüksək səviyyəli proqramlaşdırma dili.
* *Ruby*: Sadəliyə fokuslanmış dinamik, açıq mənbəli proqramlaşdırma dili.
* *Java*: Geniş miqyaslı tətbiqlər üçün istifadə edilən çox yönlü və güclü proqramlaşdırma dili.
4. **Framework və Kitabxanalar**:
* *Express*: Minimalist və çevik Node.js veb tətbiq framework-ü.
* *Django*: Sürətli inkişafı təşviq edən yüksək səviyyəli Python veb framework-ü.
* *Ruby on Rails*: Ruby ilə yazılmış server-tərəfli veb tətbiq framework-ü.
* *Spring*: Java inkişafı üçün hərtərəfli framework.

![backend-1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/MViVvlPdNXL3L5SESrIGmA/Backend-1.png)

### Back-end Developer-in Məsuliyyətləri:

1. **Məlumatların İşlənməsi və Təhlükəsizliyi**:
   - **Məlumat Bazası Dizaynı**: Məlumatların səmərəli və təhlükəsiz saxlanmasını təmin etmək üçün məlumat bazası strukturunun dizaynı.
   - **Məlumatların Şifrələnməsi**: Məlumatların təhlükəsizliyini təmin etmək üçün şifrələmə texnologiyalarının tətbiqi.
   - **Təhlükəsizlik Protokolları**: SQL injection və digər kibertəhlükələrdən qorunmaq üçün təhlükəsizlik tədbirlərinin görülməsi.

2. **Server və Baza İdarəetməsi**:
   - **Serverlərin Quraşdırılması və İdarə Edilməsi**: Serverlərin quraşdırılması və müştəri sorğularını idarə etmək üçün optimallaşdırılması.
   - **Yedəkləmə və Bərpa**: Məlumatların itirilməsinin qarşısını almaq üçün yedəkləmə proseslərinin qurulması və bərpa strategiyalarının tətbiqi.

3. **API İnkişafı və İnteqrasiyası**:
   - **API Dizaynı**: Tətbiqlərin və xidmətlərin bir-biri ilə əlaqə saxlaması üçün API-lərin dizaynı və inkişafı.
   - **RESTful və GraphQL API-lər**: HTTP sorğuları ilə işləyən RESTful və daha effektiv məlumat sorğusu üçün GraphQL API-lərin qurulması.

4. **Proqramlaşdırma və Script Yazma**:
   - **Server-Tərəfli Kod Yazma**: JavaScript (Node.js), Python, Ruby, PHP və Java kimi dillərdə server tərəfində məntiqi işlətmək üçün kod yazma.
   - **Skript Yazma**: Serverin funksionallığını təmin etmək üçün skriptlərin yazılması və idarə edilməsi.

5. **Miqyaslana Bilən Sistemlərin İnkişafı**:
   - **Yük Paylanması**: Server yükünü tarazlaşdırmaq üçün texnologiyaların tətbiqi.
   - **Miqyaslana Bilən Baza Dizaynı**: Artan məlumat həcmini idarə edə biləcək baza strukturlarının yaradılması.

6. **Performance Optimizasiyası**:
   - **Keşləşdirmə**: Daha sürətli məlumat əldə etmək üçün məlumatların keşləşdirilməsi.
   - **Sorğu Optimizasiyası**: Daha səmərəli məlumat sorğusu üçün SQL sorğularının optimizasiya edilməsi.

7. **Bacarıqlı Əlaqə və Komanda İşbirliyi**:
   - **Komanda Əlaqəsi**: Frontend developerlar və digər komanda üzvləri ilə effektiv əməkdaşlıq.
   - **Sənədləşdirmə**: Yazılmış kodların və proseslərin sənədləşdirilməsi.

![backend-2](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/Qhj5N3YPD4eCcd7iSA95pQ/Backend-2.png)



## Front-end Development

Front-end development, client-side development olaraq da tanınır və istifadəçilərin birbaşa qarşılıqlı əlaqə qurduğu veb saytın və ya tətbiqin hissəsini yaratmaqdan ibarətdir. Bu, istifadəçinin vizual olaraq təcrübə etdiyi və qarşılıqlı əlaqə qurduğu hər şeyi əhatə edir.

### Front-end Development-in Əsas Komponentləri:

1. **HTML (HyperText Markup Language)**: Veb səhifələrin strukturu, başlıqlar, paraqraflar, şəkillər və bağlantılar kimi elementlərin tərtib edilməsi.
2. **CSS (Cascading Style Sheets)**: Veb səhifələrin dizaynı, düzülüş, rənglər, şriftlər və responsive-lik daxil olmaqla stilin müəyyənləşdirilməsi.
3. **JavaScript**: Veb səhifələrdə formalar, animasiyalar və dinamik məzmun yeniləmələri kimi interaktiv xüsusiyyətlərin təmin edilməsi.
4. **Framework və Kitabxanalar**:
   - **React**: İstifadəçi interfeysləri qurmaq üçün JavaScript kitabxanası.
   - **Angular**: Veb tətbiqləri qurmaq üçün TypeScript əsaslı framework.
   - **Vue.js**: İstifadəçi interfeysləri qurmaq üçün inkişaf edən JavaScript framework-ü.

![frontend-1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/rddWsb0t8rXd9nlaMG7DoQ/Frontend-1.png)

### Front-end Developer-in Məsuliyyətləri:

1. **İstifadəçi Təcrübəsinin Təmin Edilməsi**:
   - **Təcrübənin Dizaynı**: İstifadəçi interfeysi və dizayn prinsipləri əsasında istifadəçi dostu və estetik cəhətdən xoş bir təcrübə yaratmaq.
   - **Responsive Dizayn**: Tətbiqin müxtəlif ekran ölçülərinə uyğun olaraq optimallaşdırılması.

2. **İnteraktiv Elementlərin İnkişafı**:
   - **JavaScript Kodlaşdırması**: Formlar, animasiyalar və digər dinamik xüsusiyyətlər üçün JavaScript kodlarının yazılması.
   - **Asinxron Məlumat Yüklənməsi**: AJAX və Fetch API-ləri istifadə edərək məlumatların serverdən alınması və yenilənməsi.

3. **Təhlükəsiz və Performanslı Veb Tətbiqlərin Yaradılması**:
   - **Kodun Performansını Təmin Etmək**: Yük vaxtını azaltmaq və istifadəçi təcrübəsini artırmaq üçün optimizasiya işlərinin aparılması.
   - **Təhlükəsizlik Tədbirləri**: XSS (Cross-Site Scripting) və digər təhlükəsizlik zəifliklərinə qarşı mühafizə tədbirlərinin görülməsi.

4. **Dizayn və İnkişaf Üçün Alətlərin İstifadəsi**:
   - **Version Control**: Git kimi alətlərdən istifadə edərək kod versiyalarının idarə edilməsi.
   - **Frontend Frameworklərin İstifadəsi**: React, Angular və Vue.js kimi frameworklərdən istifadə edərək sürətli və effektiv inkişaf.

5. **Komanda ilə Əməkdaşlıq**:
   - **Layihə Planlaşdırılması**: Backend developerlar və dizaynerlərlə birlikdə layihənin məqsəd və tələblərinə uyğun inkişafın təmin edilməsi.
   - **Geri Dönüşlərin Əldə Edilməsi**: İstifadəçilərin və komanda üzvlərinin fikirlərini toplayaraq tətbiqin təkmilləşdirilməsi.

![frontend-2](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/NrlSmmPp0FA22OCoUgIo3A/front-3.png)


----------------------------------------------

# Node.js (ümumi giriş)

## Full-stack Tətbiqi

Full-stack tətbiqi aşağıdakı komponentləri əhatə edir:

#### Müştəri Tərəfi:

İstifadəçilərin qarşılıqlı əlaqə qurduğu veb sayt və mobil tətbiqlər.

#### Server Tərəfi:

Müştəri tərəfindən edilən sorğuları işləyir və cavabları müştəriyə göndərir. Bulud server, tətbiq serveri və məlumat bazasını yerləşdirir.

![node-1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0220EN-SkillsNetwork/Readings/images/client_server.png)

### Open Source and Cross-Platform:

JavaScript, HTML səhifələrinin müştəri tərəfində doğrulanması üçün idealdır, çünki çox yönlü və platformalar-arası uyğunluğa malikdir. İstifadəsinin asanlığını nəzərə alaraq, JavaScript server tərəfi kodlaşdırma üçün də uyğunlaşdırıldı və nəticədə Node.js meydana gəldi. Node.js bir işləmə mühiti kimi fəaliyyət göstərir və xüsusi lisenziyaya ehtiyac duymur. Bununla yanaşı, açıq mənbə təbiəti sayəsində Node.js üçün çox sayda paket və kitabxana inkişaf etdirilmişdir. Üstəlik, Node.js kodu Linux, Windows və Mac OSX kimi müxtəlif əməliyyat sistemlərində problemsiz şəkildə işləyə bilər.

### V8 Engine:

Yazdığınız hər bir kod parçası işlənməli və maşın tərəfindən oxunan formaya çevrilməlidir. Node.js dünyasında, JavaScript kodu Google V8 mühərriki ilə icra edilir. V8, yüksək performansı ilə tanınan və Google tərəfindən inkişaf etdirilən açıq mənbə mühərrikidir, eyni zamanda bütün Google Chrome brauzerlərində inteqrasiya edilmişdir. Bundan əlavə, müasir brauzerlər, məsələn, Microsoft Edge və Firefox, Node.js kodunu icra etmək üçün V8 mühərrikini istifadə edir.

### Event-Driven, Asynchronous, Non-Blocking, Single-Threaded: 

Server prosesləri "single-threaded" və ya "multi-threaded" olaraq təsnif edilə bilər. Single-threaded mühitdə yalnız bir əmrlə işlənir, multi-threaded mühitdə isə eyni anda birdən çox əmrlə işlənir. Single-threaded olmasına baxmayaraq, Node.js asinxron və bloklanmayan təbiəti ilə performansda mükəmməldir. Bu o deməkdir ki, bir proses icra edilərkən proqramın tamamlanmasını gözləməyə ehtiyac yoxdur. Node.js hadisə-əsaslıdır (event-driven), yəni şəbəkədən oxumaq və ya məlumat bazasına və ya fayl sisteminə daxil olmaq kimi giriş/çıxış (I/O) əməliyyatı yerinə yetirildikdə bir hadisə işlənilir. Bu bloklanmayan davranış serverin cavabdeh qalmasını və eyni anda bir neçə işi yerinə yetirməsini təmin edir, multi-threaded mühitə bənzəyir.

### JSON Payload

JSON (JavaScript Object Notation) "açar-dəyər cütləri" *("key-value pairs")* şəklində formatlanmışdır. Payload (yük) müştəri ilə server arasında ötürülən məlumatları təmsil edir. Müştəri serverə məlumat göndərmək istədikdə, bunu JSON obyektində edir.

```json
{
    "name": "John",
    "age": "24",
    "email": "johnparker@gmail.com"
}
```

Yuxarıdakı obyekt JSON-dur. Bu məlumat sorğu daxilində göndərildikdə, dəyərləri sadəcə `request.name` və s. istifadə edərək çıxarıla bilər.

Eyni şəkildə, cavab da JSON şəklində göndərilir.

```json
{
    "status": "ok",
    "message": "Successfully added"
}
```

### Express Framework-ü

Node.js server yaratmaq üçün paketlər təqdim etsə də, Express framework-ü API-lər və endpointlər yaratma prosesini sadələşdirir. API endpointi müştəridən serverə edilən sorğu üçün xüsusi bir giriş nöqtəsidir.

--------------------------------------------------------

## Node.js-in Full-stack Development-də Üstünlükləri

1. **Birləşdirilmiş Dili**: Node.js-in istifadə edilməsi, inkişaf etdiricilərə həm müştəri tərəfində, həm də server tərəfində JavaScript-dən istifadə etməyə imkan tanıyır. Bu, fərqli dillər arasında keçid etmə ehtiyacını azaldır və inkişaf prosesini daha uyğun və səlis edir.

2. **Davamlı Alətlər**: Node.js istifadə edərkən test etmə və asılılıq idarəetmə alətlərini həm müştəri tərəfi, həm də server tərəfi kodu üzərində tətbiq edə bilərsiniz. Bu, NPM-dən paket idarəetməsi üçün istifadə etməyi də əhatə edir.

3. **İcma və Resurslar**: Node.js geniş və aktiv bir icmaya malikdir, bu da əhatəli öyrənmə resursları və dəstək deməkdir. Peşəkar inkişaf etdiricilərin 50%-dən çoxu Node.js-dən istifadə edir, bu da onun populyarlığını və faydalılığını əks etdirir.

4. **JavaScript İnkişaf etdiriciləri üçün Asan Keçid**: Əgər JavaScript ilə tanışsınızsa, Node.js-ə keçid backend inkişafı üçün yeni bir dili öyrənməkdən daha hamar olacaq.

5. **Asinxron Proqramlaşdırma**: Node.js single-threaded, bloklanmayan I/O modeli və hadisə-əsaslı arxitekturadan istifadə edir, bu da çox sayda eyni anda əlaqəni effektiv şəkildə idarə edə bilir.

6. **Performans**: Google V8 mühərriki üzərində qurulan Node.js, sürətli işləmə və yüksək yükləmə tələb edən senarilərdə mükəmməl nəticələr verir, məsələn, onlayn oyunlar, çat tətbiqləri və real-vaxt məlumat emalı.

7. **Mikroservislərlə Uyğunluq**: Node.js mikroservis memarlığı ilə yaxşı uyğun gəlir, burada xidmətlər kiçik, fokuslanmış və miqyaslana biləndir.

8. **Paketsiz İmkanlar**: NPM qeydiyyatı geniş seçimi olan paketlər təqdim edir, inkişaf imkanlarını artırır və tətbiqlərin yaradılma prosesini sürətləndirir.

---------------------------------------------------------------------

## Node.js-də Import və Require

Node.js-də modullar, tətbiqin müxtəlif hissələrində təkrar istifadə edilə bilən funksionallığın özündə saxlayan, müstəqil bölmələrdir. Bu modullar fərdi fayllar və ya çoxsaylı fayl və qovluqlardan ibarət kolleksiyalar ola bilər. Modulyar yanaşma mürəkkəb kodun idarə edilə bilən hissələrə bölünməsinə və kodun təkrar istifadəsinin təşviq edilməsinə kömək edir.

Modulun daxilindəki kodu xarici tətbiqdə istifadə etmək üçün inkişaf etdiricilər `require()` və ya `import()` ifadələrindən istifadə edirlər. Bu iki üsul arasındakı seçim istifadə olunan modul spesifikasiyasından asılıdır. Node.js əsasən iki modul spesifikasiyasını dəstəkləyir: CommonJS və ES modulları.

#### Modul Spesifikasiyaları

1. **CommonJS**:
   - **Node.js-də Default**: Node.js, JavaScript kodunu standart olaraq CommonJS modulları kimi qəbul edir.
   - **Sintaksis**: Modulları import etmək üçün `require()` istifadə edir.
   - **Export**: Funksionallığı export etmək üçün `module.exports` istifadə edir.

2. **ES Modulları**:
   - **Node.js-də Aktivləşdirmək**: ES modullarını `.mjs` fayl uzantısından istifadə etməklə aktivləşdirmək mümkündür.
   - **Sintaksis**: Modulları gətirmək üçün `import` və funksionallığı əlçatan etmək üçün `export` istifadə edir.
   
#### `require` və `import` Arasındakı Əsas Fərqlər

1. **Kodda Yerləşmə (Placement in Code)**:
   - **require**: Faylın hər hansı bir yerində, o cümlədən funksiyalar və şərtli ifadələr daxilində çağırıla bilər.
   - **import**: Faylın əvvəlində çağırılmalı və şərtli olaraq yüklənə bilməz.

2. **Bağlama (Binding)**:
   - **require**: Dinamik olaraq bağlanır, yəni modul həlli icra vaxtında baş verir. Funksiyaların təriflərinə əlaqələndirilməsindəki səhvlər yalnız kod icra olunduqda aşkar edilə bilər.
   - **import**: Statik olaraq bağlanır, səhvlərin tərtib vaxtında aşkar olunmasına imkan verir, bu da daha yaxşı səhv yoxlamasını təmin edir.

3. **Sinxron və Asinxron (Synchronous vs. Asynchronous)**:
   - **require**: Sinxron, modulları xətti, bloklaşdırıcı şəkildə yükləyir və işləyir.
   - **import**: Asinxron, modulların paralel olaraq yüklənməsinə imkan verir, bu da iri miqyaslı tətbiqlərdə performansı artırır.

#### Nümunə Kod

**CommonJS Nümunəsi**:

*CommonJS ilə Export*:
```javascript
// message.js
module.exports = "Hello programmers";
```

*CommonJS ilə Import*:
```javascript
// main.js
let msg = require('./message.js');
console.log(msg); // Nəticə: Hello programmers
```

**ES Modulları Nümunəsi**:

*ES Modulları ilə Export*:
```javascript
// module.mjs
const a = 1;
export { a as myValue };
```

*ES Modulları ilə Import*:
```javascript
// main.mjs
import { myValue } from './module.mjs';
console.log(myValue); // Nəticə: 1
```

### Nəticə

- **Modullar**: Node.js-də özündə kodu saxlayan və təkrar istifadəni və idarə olunmasını təşviq edən müstəqil bölmələrdir.
- **Spesifikasiyalar**: CommonJS və ES modulları, fərqli import/export sintaksisi ilə.
- **require vs. import**:
  - `require`: Dinamik, sinxron, hər yerdə istifadə edilə bilər.
  - `import`: Statik, asinxron, faylın əvvəlində istifadə edilməlidir.
  
Bu iki import metodunun fərqlərini və müvafiq istifadə hallarını başa düşmək, Node.js tətbiqlərində daha səmərəli və səhvsiz kod yazmağa kömək edir.

----------------------------------------------------------------

## Server-Side JavaScript-ə Giriş

JavaScript, veb inkişafında ən təsirli proqramlaşdırma dillərindən biri olmuşdur. Əvvəlcə statik veb səhifələrə dinamik davranış əlavə etmək üçün yaradılan JavaScript, indi həm müştəri, həm də server tərəflərində işləyən çox yönlü bir dildir. 

#### JavaScript-in Mənşəyi və İnkişafı

- **Müştəri Tərəfli Başlanğıclar**: JavaScript ilk olaraq veb brauzerlər daxilində icra olunmaq üçün yaradıldı və statik HTML səhifələrini dinamik, interaktiv xüsusiyyətlərlə zənginləşdirdi.
- **İnterpretasiya Edilən Dil**: Kompilyasiya olunan dillərdən fərqli olaraq, JavaScript interpretasiya edilir, yəni icra edilmədən əvvəl kompilyasiya mərhələsinə ehtiyac yoxdur.
- **Java ilə Əlaqəsi Yoxdur**: Adına və oxşar sintaksisinə baxmayaraq, JavaScript Java proqramlaşdırma dilindən törəmə deyil.
- **Geniş Dəstək**: Bütün müasir veb brauzerlər JavaScript-i dəstəkləyir, onu veb inkişafı üçün hər yerdə mövcud bir vasitə halına gətirir.

#### Ənənəvi Veb Tətbiqi Axını

1. **İstifadəçi İnterfeysi (UI)**: HTML və CSS istifadə edilərək yaradılır.
2. **Müştəri Tərəfli Məntiq**: İstifadəçi UI ilə qarşılıqlı əlaqə yaratdıqda, JavaScript müştəri tərəfli iş məntiqini idarə edir.
3. **Veb Xidmət Sorğusu**: JavaScript serverə sorğular göndərir, adətən JSON üzərindən HTTP istifadə olunur.
4. **Server Tərəfli Emal**: Ənənəvi olaraq, server tərəfli emal Java və ya PHP kimi dillərdən istifadə etməklə həyata keçirilirdi.
5. **Cavab**: Server sorğunu emal edir və müştəriyə məlumat qaytarır.

#### Node.js və Server-Side JavaScript

Node.js, JavaScript-in imkanlarını server tərəfinə qədər genişləndirir və inkişaf etdiricilərə həm müştəri, həm də server tərəfli kodu JavaScript-də yazmağa imkan verir. Node.js ilə proses belə görünür:

1. **İstifadəçi İnterfeysi (UI)**: HTML və CSS istifadə edilərək yaradılır.
2. **Müştəri Tərəfli Məntiq**: JavaScript müştəri tərəfli iş məntiqini idarə edir.
3. **Veb Xidmət Sorğusu**: Müştəri tərəfli JavaScript tətbiqi, JSON formatında məlumat göndərərək HTTP sorğusu edir.
4. **REST Veb Xidməti**: Sorğunu serverdə qarşılayan RESTful xidmət.
5. **Node.js Serveri**: Başqa bir backend dilində yazılmış tətbiqi çağırmaq əvəzinə, Node.js serveri sorğunu JavaScript istifadə edərək emal edir.

#### Node.js-in Faydaları

- **Birləşmiş Dil**: İnkişaf etdiricilər həm müştəri, həm də server tərəflərində JavaScript istifadə edə bilər, bu da inkişaf prosesini sadələşdirir.
- **Miqyasa Uyğunluq**: Node.js çoxsaylı eyni vaxtlı əlaqələri səmərəli şəkildə idarə etmək üçün nəzərdə tutulmuşdur, bu da onu miqyasa uyğun tətbiqlər üçün uyğun edir.
- **Minimal Alətlər Dəsti**: Node.js server tətbiqlərini yaratmaq üçün minimal alətlər dəsti ilə sürətli inkişafı təmin edir.

### Yekun

- **JavaScript**: Əvvəlcə müştəri tərəfli dil kimi, indi Node.js ilə server tərəfli inkişafda istifadə olunur.
- **Node.js**: Server tərəfli JavaScript-i təmin edən, miqyasa uyğun, səmərəli və sürətli server tətbiqlərinin inkişafını mümkün edən bir framework.
- **Birləşmiş İnkişaf**: Həm müştəri, həm də server tərəfli kodu JavaScript-də yazmaq, inkişaf axınını sadələşdirir və yeni inkişaf etdiricilər üçün öyrənmə əyrisini azaldır.

---------------------------------------------------

## Node.js ilə Veb Server Yaratmaq

Node.js, JavaScript-dən istifadə edərək miqyaslana bilən, eyni zamanda işləyə bilən server tətbiqləri qurmaq üçün güclü bir server-tərəf runtime mühitdir. Bu, hadisə idarə olunan, bloklamayan I/O modelinə əsaslanır, bu da onu məlumat-intensive real vaxt tətbiqləri üçün yüngül və səmərəli edir. 

#### Əsas Konsepsiyalar

1. **Single-Threaded Event Loop**: Node.js, hadisələr və callback funksiyaları vasitəsilə I/O əməliyyatlarını asinxron şəkildə idarə edən single-threaded hadisə döngüsündə işləyir.
2. **Modules**: Node.js-də hər bir JavaScript faylı bir moduldur. Node.js, müxtəlif funksiyaları asanlaşdırmaq üçün HTTP modulu kimi daxili istifadə modulları ilə təmin olunur.

#### Addım-addım Bələdçi

1. **Quraşdırma**: Node.js-in quraşdırıldığına əmin olun. Siz onu [Node.js rəsmi veb saytından](https://nodejs.org/) yükləyə bilərsiniz.

2. **Yeni JavaScript Faylı Yaradın**:
   `server.js` (və ya istədiyiniz ad) adında yeni bir fayl yaradın.

3. **HTTP Modulunu İdxal Edin**:
   HTTP modulu təmin edilmiş Node.js ilə idxal edin.

   ```javascript
   const http = require('http');
   ```

4. **Serveri Yaradın**:
   Yeni server instansiyası yaratmaq üçün `http.createServer` metodundan istifadə edin. Bu metod daxil olan sorğuları idarə edən və cavabları göndərən callback funksiyasını qəbul edir.

   ```javascript
   const server = http.createServer((req, res) => {
       // Cavab HTTP başlığını HTTP statusu və Content type ilə təyin edin
       res.writeHead(200, {'Content-Type': 'text/plain'});

       // Cavab gövdəsini "Hello, World!" olaraq göndərin
       res.end('Hello, World!\n');
   });
   ```

5. **Serverin Bir Portda Dinləməsini Təmin Edin**:
   Server instansiyasında `listen` metodunu çağıraraq onu müəyyən bir portda (məsələn, 8080) dinləmək üçün qurun.

   ```javascript
   server.listen(8080, () => {
       console.log('Server http://127.0.0.1:8080/ ünvanında işləyir.');
   });
   ```

6. **Serveri İcra Edin**:
   Faylı yadda saxlayın və terminaldan Node.js istifadə edərək serveri işlədin.

   ```sh
   node server.js
   ```

   Terminalda `Server http://127.0.0.1:8080/ ünvanında işləyir.` mesajını görməlisiniz.

7. **Serverə Giriş**:
   Veb brauzerinizi açın və `http://127.0.0.1:8080/` ünvanına keçin. "Hello, World!" mesajını görməlisiniz.

#### Tam Kod Nümunəsi

Burada, Node.js ilə əsas veb server yaratmaq üçün tam kod verilmişdir:

```javascript
// HTTP modulunu idxal edin
const http = require('http');

// Serverin bir instansiyasını yaradın
const server = http.createServer((req, res) => {
    // Cavab HTTP başlığını HTTP statusu və Content type ilə təyin edin
    res.writeHead(200, {'Content-Type': 'text/plain'});

    // Cavab gövdəsini "Hello, World!" olaraq göndərin
    res.end('Hello, World!\n');
});

// Serverin 8080 portunda dinləməsini təmin edin
server.listen(8080, () => {
    console.log('Server http://127.0.0.1:8080/ ünvanında işləyir.');
});
```

### Yekun

- **Node.js**: Asinxron şəkildə I/O əməliyyatlarını idarə edən single-threaded, hadisə idarə olunan mühitdir.
- **Modullar**: Hər JavaScript faylı bir moduldur və Node.js HTTP kimi bir neçə daxili modulu əhatə edir.
- **HTTP Modulu**: HTTP sorğularını dinləyən və onlara cavab verən veb serverləri yaratmaq üçün istifadə olunur.
- **Server Yaratma**: `http.createServer()` ilə server instansiyası yaratmaq və `server.listen()` ilə müəyyən bir portda dinləməsini təmin etmək.

----------------------------------------------------------------

## Node.js Modulları ilə İş

Node.js-də modullar tətbiq inkişafının əsas hissəsidir, kodu təşkil etməyə və təkrar istifadəyə imkan verir. Bir paket, bir və ya daha çox modulların kolleksiyasıdır və `package.json` faylı paket haqqında əsas məlumatları təmin edir. Budur, Node.js modulları ilə necə işləmək haqqında ətraflı məlumat:

#### `package.json` Faylı

`package.json` faylı, layihəniz haqqında metadata, asılılıqlar, skriptlər və s. daxil olan manifest kimi xidmət edir. Budur, bir `package.json` faylının əsas strukturu:

```json
{
  "name": "today",
  "version": "1.0.0",
  "description": "A simple module to get today's date",
  "main": "lib/today.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Your Name",
  "license": "ISC"
}
```

- **name**: Paketinizin adı.
- **version**: Paketinizin versiyası.
- **main**: Paketinizin giriş nöqtəsi (məsələn, `lib/today.js`).
- **scripts**: Müxtəlif komanda skriptlərini çalışdırmaq üçün (məsələn, testlər).
- **author**: Paketinizin müəllifi.
- **license**: Paketinizin paylanma lisenziyası.

#### `require` ilə Modulları İdxal Etmək

Node.js tətbiqinizdə bir modulu istifadə etmək üçün `require` funksiyasından istifadə edərək idxal edirsiniz. Budur necə işləyir:

1. **Sadə Modul İdxalı**:
   Tutaq ki, `today.js` faylı əsas tətbiq faylınız olan `app.js` ilə eyni qovluqdadır.

   ```javascript
   // today.js
   module.exports = {
     getDate: function() {
       return new Date().toDateString();
     }
   };
   ```

   ```javascript
   // app.js
   const today = require('./today');
   console.log(today.getDate());
   ```

2. **Bir Qovluqda Varsayılan Modul**:
   Əgər modulunuz bir qovluğun içindədirsə və əsas skript `index.js` adlanırsa, onu qovluq adını göstərərək idxal edə bilərsiniz.

   ```javascript
   // mod_today/index.js
   module.exports = {
     getDayOfWeek: function() {
       const days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
       return days[new Date().getDay()];
     }
   };
   ```

   ```javascript
   // app.js
   const modToday = require('./mod_today');
   console.log(modToday.getDayOfWeek());
   ```

#### Modullardan İxrac Etmək

Başqa fayllara funksiyalar və ya dəyərləri əlçatan etmək üçün `exports` obyektindən istifadə edirsiniz. Budur bir nümunə:

```javascript
// today.js
exports.dayOfWeek = function() {
  const days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
  return days[new Date().getDay()];
};
```

Bu modulu idxal etdiyiniz zaman, `dayOfWeek` funksiyasına giriş əldə edə bilərsiniz:

```javascript
// app.js
const today = require('./today');
console.log(today.dayOfWeek());
```

#### Layihə Strukturunun Nümunəsi

Budur bir Node.js layihəsinin nümunə qovluq strukturu:

```
my-project/
├── mod_today/
│   └── index.js
├── today.js
├── app.js
└── package.json
```

- **mod_today/index.js**: Modul məntiqini ehtiva edir.
- **today.js**: Başqa bir modul faylı.
- **app.js**: Əsas tətbiq faylı.
- **package.json**: Layihə və asılılıqları haqqında məlumat verir.

### Yekun

- **package.json**: Node.js layihəniz haqqında metadata ehtiva edir.
- **Modullar**: Layihənizdə təkrar istifadə edilə bilən JavaScript kod parçalarıdır.
- **require**: Node.js-də modulları idxal etmək üçün istifadə olunur.
- **exports**: Bir moduldan funksiyalar və ya dəyərləri əlçatan etmək üçün istifadə olunur.

Kodunuzu modullara bölərək və layihənizi idarə etmək üçün `package.json` faylından istifadə edərək, miqyaslana bilən və saxlanıla bilən Node.js tətbiqləri yarada bilərsiniz.

-----------------------------------------------------------------------

## Node.js Modullarına Giriş

Node.js-də modullar, tətbiqləri effektiv şəkildə qurmaq və saxlamaq üçün təkrar istifadə edilə bilən kod parçalarıdır. Modullar üç növə bölünə bilər: əsas, yerli və üçüncü tərəf. 

#### Node.js Modullarının Növləri

1. **Əsas Modullar**:
   - **Tərif**: Node.js runtime-a daxil olan və əlavə kitabxanalara ehtiyac duymadan əsas funksionallıqları təmin edən modullar.
   - **Nümunələr**: `http`, `fs`, `os`, `path`, `util`, `url`, `querystring`.

2. **Yerli Modullar**:
   - **Tərif**: Sizin və ya inkişaf komandası tərəfindən tətbiqinizin bir hissəsi olaraq yaradılan xüsusi modullar.
   - **Nümunə**: Tarixlə bağlı funksionallıqları təmin edən `today.js` adlı bir modul.

3. **Üçüncü Tərəf Modulları**:
   - **Tərif**: Node.js icması tərəfindən yaradılan və onlayn mövcud olan modullar (məsələn, npm vasitəsilə).
   - **Nümunələr**: `express`, `axios`, `async`.

#### Əsas Modullar

Əsas modullar Node.js tətbiqləri üçün vacib funksionallıqları təmin edir. Burada bəzi mühüm nümunələr və kod nümunələri var:

1. **HTTP Modulu**:
   - **Məqsəd**: HTTP üzərindən məlumatları ötürmək.
   - **İstifadə**:

     ```javascript
     const http = require('http');
     http.createServer((req, res) => {
         res.write('Serverdən salam');
         res.end();
     }).listen(6000);
     ```

2. **FS (Fayl Sistemi) Modulu**:
   - **Məqsəd**: Fayl sistemi ilə qarşılıqlı əlaqə qurmaq.
   - **İstifadə (Asinxron oxuma)**:

     ```javascript
     const fs = require('fs');
     fs.readFile('sample.txt', 'utf8', (err, data) => {
         if (err) {
             console.error(err);
             return;
         }
         console.log(data);
     });
     ```

   - **İstifadə (Sinxron oxuma)**:

     ```javascript
     const fs = require('fs');
     const data = fs.readFileSync('content.md', 'utf8');
     console.log(data);
     ```

3. **OS Modulu**:
   - **Məqsəd**: Əməliyyat sistemi ilə qarşılıqlı əlaqə qurmaq.
   - **İstifadə**:

     ```javascript
     const os = require('os');
     console.log("Platforma: " + os.platform());
     console.log("Arxitektura: " + os.arch());
     ```

4. **Path Modulu**:
   - **Məqsəd**: Kataloq və fayl yolları ilə işləmək.
   - **İstifadə**:

     ```javascript
     const path = require('path');
     const result = path.basename('/content/index/home.html');
     console.log(result); // Çıxış: home.html
     ```

5. **Util Modulu**:
   - **Məqsəd**: Düzgünlüyü yoxlamaq və yardımçı funksiyalar üçün.
   - **İstifadə**:

     ```javascript
     const util = require('util');
     const str = 'Döngə %d dəfə icra olundu.';
     for (let i = 1; i <= 10; i++) {
         console.log(util.format(str, i));
     }
     ```

6. **URL Modulu**:
   - **Məqsəd**: URL-ləri pars etmək.
   - **İstifadə**:

     ```javascript
     const url = require('url');
     const webAddress = 'http://localhost:2000/index.html?lastName=Kent&firstName=Clark';
     const qry = url.parse(webAddress, true);
     const qrydata = qry.query;
     console.log(qrydata.firstName); // Çıxış: Clark
     ```

7. **QueryString Modulu**:
   - **Məqsəd**: URL-in sorğu sətirlərini pars etmək.
   - **İstifadə**:

     ```javascript
     const querystring = require('querystring');
     const qryParams = querystring.parse('lastName=Kent&firstName=Clark');
     console.log(qryParams.firstName); // Çıxış: Clark
     ```

#### Üçüncü Tərəf Modulları

Üçüncü tərəf modulları Node.js funksionallıqlarını genişləndirir. Bəzi məşhur nümunələr:

- **Express**: Minimal və çevik Node.js web tətbiq çərçivəsi.
- **Axios**: Browser və Node.js üçün vədəsiz HTTP müştərisi.
- **AsyncJS**: Asinxron JavaScript ilə işləmək üçün güclü funksiyalar təmin edən yardımçı modul.

Üçüncü tərəf modulları npm (Node Package Manager) vasitəsilə quraşdıra bilərsiniz:

```sh
npm install express
```

-----------------------------------------------------------------------

## Node Package Manager (NPM) 

Paket meneceri, proqram layihələrinin etibar etdiyi kitabxanalar və paketlər kimi asılılıqları idarə etmək üçün vacib bir vasitədir. Node Package Manager (NPM), Node.js üçün default paket meneceridir və bu asılılıqları effektiv şəkildə idarə etməkdə mühüm rol oynayır.

#### NPM-nin Əsas Funksiyaları

1. **Əmr Sırası İnterfeysi (CLI)**:
   - NPM, paketləri dərc etmək, yükləmək, quraşdırmaq, yeniləmək və silmək üçün komandalar təqdim edir.

2. **Onlayn Repozitoriya**:
   - NPM, JavaScript paketlərinin versiyalarını və asılılıqlarını izləyən ətraflı bir verilənlər bazasını saxlayır.

#### Asılılıqları Anlamaq

Asılılıqlar, layihənizin etibar etdiyi xarici kitabxanalar və ya paketlərdir. Bu asılılıqları əl ilə idarə etmək çətin və səhvlərə yol açan bir proses ola bilər ki, NPM bu prosesi avtomatlaşdıraraq üstünlük təşkil edir.

#### `package.json` Faylı

- **Məqsəd**: Layihə haqqında metadata, o cümlədən onun asılılıqlarını ehtiva edir.
- **Vacib Sahələr**:
  - `name`: Layihənin adı.
  - `version`: Layihənin versiya nömrəsi.

Əsas `package.json` faylı nümunəsi:

```json
{
  "name": "my-project",
  "version": "1.0.0"
}
```

#### Paketlərin Quraşdırılması

Paketlər, NPM vasitəsilə yerli və ya qlobal olaraq quraşdırıla bilər.

1. **Yerli Quraşdırma**:
   - **Əmr**: `npm install <package_name>`
   - **İzahı**: Paketi, layihənizin qovluğunda olan `node_modules` qovluğunda quraşdırır və yalnız həmin layihəyə əlçatan edir.

2. **Qlobal Quraşdırma**:
   - **Əmr**: `npm install -g <package_name>`
   - **İzahı**: Paketi qlobal olaraq quraşdırır və bu paketi maşındakı hər hansı bir layihəyə əlçatan edir. Qlobal quraşdırmaları diqqətlə istifadə edin ki, fərqli layihələr arasında versiya uyğunsuzluqlarının qarşısı alınsın.

#### Əmr Nümunələri

- **Yerli Quraşdırma**:

  ```sh
  npm install express
  ```

- **Qlobal Quraşdırma**:

  ```sh
  npm install -g express
  ```

#### Paketlərin İdarə Edilməsi

NPM, paketləri yeniləmək və silmək üçün də komandalar təqdim edir:

- **Paketin Yenilənməsi**:

  ```sh
  npm update <package_name>
  ```

- **Paketin Silinməsi**:

  ```sh
  npm uninstall <package_name>
  ```

----------------------------------------------------------------

## Asinxron I/O ilə Callback Proqramlaşdırması

### Əsas Konsepsiyalar

- **Asinxron Şəbəkə Əməliyyatları (Asynchronous Network Operations)**: Node.js-də şəbəkə əməliyyatları asinxron işləyir ki, cavab gözləyərkən prosessinq vaxtının itirilməsinin qarşısını alsın.
  
- **Non-blocking Əməliyyatlar**: Node.js-də bütün şəbəkə əməliyyatları dərhal geri qaytarılır, tətbiqin şəbəkə əməliyyatının tamamlanmasını gözləmədən prosessinqə davam etməsinə imkan verir.

- **Callback Funksiyaları**: Node.js asinxron əməliyyatların nəticələrini idarə etmək üçün callback funksiyalarından istifadə edir. Bu funksiyalar şəbəkə əməliyyatı tamamlandıqda çağırılır.

### İş Axını Nümunəsi (Workflow Example)

1. **HTTP Sorğusu**:
   - Tətbiq `HTTP.request()` funksiyasını çağırır və bu funksiya uzaq veb serverə sorğu göndərir.
   - Node.js cavabı gözləmədən sorğunun uğurla göndərildiyini göstərən nəticəni dərhal geri qaytarır.

2. **Callback İdarəetməsi (Callback Handling)**:
   - Uzaq server cavab verdikdə, Node.js `HTTP.request()` çağırışında təyin edilmiş callback funksiyanı çağırır.
   - Bu callback funksiya HTTP cavab mesajını emal edir.

### Ssenari Təhlili (Scenario Breakdown)

1. **Sadə HTTP Sorğusu**:
   - Tətbiq `HTTP.request()` funksiyasını çağırır.
   - Node.js sorğunu göndərir və uğur mesajı geri qaytarır.
   - HTTP cavabı alındıqda, Node.js təyin edilmiş callback funksiyanı çağıraraq cavabı idarə edir.

2. **Mürəkkəb Ssenari**:
   - Tətbiq xüsusi bir Node.js modulunu çağırır, bu modul `HTTP.request()` funksiyasını çağırır.
   - Modul sorğunu göndərir və control-u tətbiqə qaytarır.
   - Cavab alındıqda, Node.js moduldakı təyin edilmiş callback funksiyanı çağırır və bu funksiya `data` və `end` kimi hadisələri emal edir.

### Kod Nümunəsi

Budur, Node.js istifadə edərək HTTP sorğusu etmək üçün bir nümunə:

```javascript
const http = require('http');

const options = {
    hostname: 'api.weather.gov',
    path: '/stations/KSFO/observations/latest',
    method: 'GET',
};

const req = http.request(options, (res) => {
    let buffer = '';

    res.on('data', (chunk) => {
        buffer += chunk;
    });

    res.on('end', () => {
        console.log(buffer);
    });
});

req.on('error', (e) => {
    console.error(`Problem with request: ${e.message}`);
});

req.end();
```

### Hadisə İdarəetməsi (Event Handling)

- **Data Hadisəsi**: Hər dəfə bir data parçası alındıqda işləyir.
- **End Hadisəsi**: Cavab tam olduqda işləyir.
- **Error Hadisəsi**: Sorğuda bir səhv olduqda işləyir.

### Xülasə

- **Non-blocking Əməliyyatlar**: Node.js I/O əməliyyatlarını asinxron şəkildə idarə edir ki, tətbiq bloklanmasın.
- **Callbacklər**: Asinxron əməliyyatlardan gələn cavabları idarə etmək üçün istifadə olunur.
- **Hadisə yönümlü Arxitektura (Event-driven Architecture)**: Node.js şəbəkə əməliyyatları zamanı `data`, `end` və `error` kimi hadisələr yaradır və bu hadisələr hadisə dinləyiciləri (event listeners) vasitəsilə idarə oluna bilər.

----------------------------------------------------------------------

