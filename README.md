<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yurnosz Library</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0fff0; /* Light mint background color */
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #e0f7e0; /* Slightly different mint color for header */
            padding: 10px;
            text-align: center;
            font-size: 1em;
        }

        .menu {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            background-color: #e0f7e0;
        }

        .menu .book {
            text-align: center;
            cursor: pointer;
            transition: transform 0.2s;
        }

        .menu .book:hover {
            transform: scale(1.1);
        }

        .menu img {
            width: 100px;
            height: auto;
            border-radius: 10px;
        }

        .menu .profile-button {
            cursor: pointer;
            text-align: center;
            font-size: 1.2em;
            padding: 10px 20px;
            background-color: #98fb98;
            border-radius: 10px;
            transition: background-color 0.2s;
        }

        .menu .profile-button:hover {
            background-color: #76e776;
        }

        .page {
            display: none;
            width: 80%;
            margin: 2em auto;
            padding: 2em;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .page.active {
            display: block;
            animation: openBook 0.5s;
        }

        @keyframes openBook {
            from { transform: scale(0.9); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        .cover img {
            width: 300px;
            height: auto;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 3em;
            margin: 0;
        }

        h2 {
            font-size: 2em;
            margin: 0.5em 0;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            font-size: 1.2em;
            margin: 0.5em 0;
        }

        .chapter-break img {
            width: 100%;
            height: auto;
            margin: 20px 0;
        }

        .profile {
            text-align: center;
        }

        .profile img {
            width: 150px;
            height: auto;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .profile p {
            font-size: 1.2em;
        }
        
        .p {
          text-align: justify;
        }

    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        Created by Yurnosz
    </div>

    <!-- Menu -->
    <div class="menu">
        <div class="book" onclick="showBook('book1')">
            <img src="cover1.jpg" alt="Book 1">
            <p>Buku 1</p>
        </div>
        <div class="book" onclick="showBook('book2')">
            <img src="cover2.jpg" alt="Book 2">
            <p>Buku 2</p>
        </div>
        <div class="book" onclick="showBook('book3')">
            <img src="cover3.jpg" alt="Book 3">
            <p>Buku 3</p>
        </div>
        <div class="profile-button" onclick="showBook('profile')">
            Profile
        </div>
    </div>

    <!-- Book 1 -->
    <div class="page" id="book1">
        <!-- Cover Page -->
        <div class="cover">
            <img src="cover1.jpg" alt="Cover Image">
            <h2>Kuntilanak Pondok Indah</h2>
            <h3>Penulis : Annisa Haroen</h3>
        </div>
        <!-- Content of Book 1 -->
        <div class="content">
            <h2>Daftar Isi</h2>
            <ul>
                <li>Cover</li>
                <li>Sinopsis</li>
                <li>Prolog</li>
                <li>Bagian 1</li>
                <li>Bagian 2</li>
                <li>Bagian 3</li>
                <li>Bagian 4</li>
                <li>Bagian 5</li>
                <li>Bagian 6</li>
            </ul>
            <h2>Sinopsis</h2>
            <p style="text-align: justify">Dia sering menangis di tengah malam dan berdiri mematung di ujung tangga di sebuah rumah yang mewah dan kokoh, dengan cat tembok yang menguning dan mulai memudar serta halaman rumah yang tidak terurus. Dialah yang sering kalian dengar kisahnya. Sosok kuntilanak menakutkan di Pondok Indah, sosok hantu perempuan yang kerap mengganggu orang-orang di Pondok Indah. Jangan sekali-sekali kalian mencari tahu siapa kuntilanak itu, atau dia sendiri yang akan memberitahukannya lewat teror yang paling menakutkan dalam hidupmu.</p>
            <h2>Prolog</h2>
            <p style="text-align: justify">Napasnya berburu disertai keringat dingin yang keluar dari sela pori-porinya. Sudah hampir lima belas menit, dia memperhatikan keadaan sekitar yang sudah mulai sepi. Terdengar suara derikan jangkrik dan katak yang saling menyela bersembunyi di balik tumbuhan. Senjata yang a simpan di samping tempat ia terduduk tampak mengkilat terkena pantulan sinar rembulan. Setelah menghirup udara lewat hidung dan mengeluarkannya lewat mulut sebanyak dua kali, dia pun meraih senjatanya untuk diselipkan di punggungnya lalu mulai berjalan memasuki belakang rumah itu untuk menyelesaikan misinya.</p>
<p style="text-align: justify">Gadis itu mengenakan daster berwarna putih transparan sangat pendek dengan belahan cada rendah yang semakin membuatnya marah. Dengan wajah yang berbinar, gadis itu menuruni tangga. Dia tersenyum sambil membukakan pintu dan sebelum mengatakan kata sambutan, sebuah golok sudah menyayat lehernya yang memberikan luka dalam sehingga darahnya langsung menggelegak keluar.</p>
<p style="text-align: justify">Dia menyaksikan gadis itu tersungkur. Beberapa saat kemudian, dia menutup pintu di belakang lalu menguncinya. Gadis itu masih bernyawa, tetapi dia tahu bahwa gadis itu sedang sekarat. Nafasnya tersenggal dan matanya membelalak ketakutan. Dia pun menjambak rambut gadis itu lalu menariknya melalui tangga menuju kamar.</p>
<p style="text-align: justify">Dia berlutut menunggu gadis itu meregang nyawa. Tetapi gairah untuk menyakiti gadis itu semakin membuncah. Dia akan menghentikan penderitaannya dengan menebas leher gadis itu hingga terputus dari tubuhnya. Setelah merasa belum puas, dia pun kembali bersenang-senang dengan memotong kedua kakinya dan kedua tangannya hingga enam bagian.</p>
<p style="text-align: justify">Belum pernah dirinya merasakan kepuasan hingga klimaks seperti itu. Dia berdiri, pakaiannya basah oleh keringat dan darah. Dia keluar kamar dengan tenang seakan tidak pernah terjadi apa pun, dia membersihkan badannya dengan pancuran yang ada di kebun samping rumah.</p>
<p style="text-align: justify">Sepanjang jalan, dia merasakan angin malam yang perlahan menghapus keringatnya. Dia pulang ke rumah dalam keadaan senang dan puas setelah sebelumnya berhenti di sebuah jembatan untuk membuang plastik yang berisikan baju dan senjatanya sehingga polisi tidak akan menemukan bukti apa pun untuk menjebloskan dirinya ke dalam jeruji besi. Dirinya masih bisa merasakan darah korbannya yang hangat, menikmati suara isakannya dan menyaksikan setiap kesakitannya.</p>
<p style="text-align: justify">Dia pun langsung menaiki tempat tidurnya, tertawa membayangkan berita gempar yang akan di saksikan keesokan harinya sambil menikmati secangkir teh panas. Dia pun cepat-cepat menutup badannya dengan selimut lalu memejamkan matanya hingga tertidur pulas.
</p>
            <h2>Bagian 1</h2>
            <p style="text-align: justify">Tiga cangkir kopi yang Pearly habiskan malam itu belum juga mengusir kantuknya. Bahkan sudah bolak-balik ke toilet untuk membasuh wajahnya dengan air dingin, rasa kantuk masih menyelimuti matanya. Dia menyandarkan kepalanya ke sandaran kursi sambil meregangkan otot-ototnya yang tegang dan menaikkan kakinya ke atas meja.
            </p>
            <p style="text-align: justify"> Waktu menunjukkan pukul 22.47. Devon sudah closing segmen old song-nya dengan lagu penutup lemon tree dari Fool's Garden yang berarti sebentar lagi Pearly harus bersiap untuk mengudara. Sebenarnya Pearly adalah seorang insomnia. Bahkan sering dijuluki batwoman oleh pacarnya sendiri. Tetapi hari ini bisa dibilang penyakit insomnia Pearly sudah mencapai batas. Dia sama sekali belum tidur selama dua hari karena Cherise teman satu rumahnya, kemarin baru launching</p>
            <p style="text-align: justify">Cherise Spa and Boutique. Mereka mengadakan party semalaman, lalu pagi harinya Pearly langsung ke radio untuk mengudara selama dua jam lanjut dengan perawatan gratis di cherise spa.</p>
<p style="text-align: justify">Kamu sih Sayang, tadi bukannya tidur siang malah perawatan seharian." Satria kembali memijit kedua pundak Pearly.</p>
<p style="text-align: justify">"ini kan first day openingnya cherise spa sayang. Jadi gratisan deh perawatan dari ujung rambut sampai ujung kaki aku. Kan lumayan bisa hemat hampir dua jutaan. Liat nih kuku aku cantik kan? Ini warna baru namanya frizzy mango. Kuku kaki aku juga pake kutek bling-bling loh. Mau liat?" Pearly memegang ujung high heels hendak memperlihatkan warna kuku kaki barunya, tetapi ditahan oleh Satria.</p>
<p style="text-align: justify">"Udah udah gak usah. Kamu kok jadi ketularan Cherise sih? Nanti kena debu dikit aja teriaknya udah kaya kena setrum 2000 volt." Pearly tertawa sambil berdiri untuk masuk ke studio.</p>
<p style="text-align: justify">"Aku masuk dulu ya Sayang. Kamu baik baik ya tungguin akunya." Pearly membungkuk untuk mencium pipi Satria lalu berbisik.</p>
<p style="text-align: justify">"By the way aku juga di waxing loh," Pearly mengedipkan mata dan berjalan ke arah studio, dia menahan pintu studio untuk berbalik pada Satria yang mulutnya sedang menganga dengan tampang terkejut.</p>
<p style="text-align: justify">Maksud aku waxing ketiak. Hahahahaha" Pearly menutup pintu sementara Satria menghembuskan napasnya yang tertahan sambil menggelengkan kepalanya lalu tertawa.</p>
<p style="text-align: justify">"80.9 homey radio kembali bersama saya Pearly, masih dalam segmen Spooky Night. Itu dia tadi cerita dari Sonia di Cikarang yang katanya sering ngeliat penampakan pocong di pohon muncang sebelah rumahnya dan membuat semua orang yang mencoba menebangnya malah kesurupan, bahkan sampai ada yang meninggal dunia. Serem juga ya. Oke masih ditunggu penelepon selanjutnya,</p>
<p style="text-align: justify">silakan menghubungi line kita untuk menceritakan pengalaman mistis kamu atau orang terdekat kamu. Yap, sepertinya ada satu penelepon lagi halooo.."</p>
<p style="text-align: justify">"Haloo."</p>
<p style="text-align: justify">"Iya dengan siapa di mana?"</p>
<p style="text-align: justify">"Rachel di pondok indah."</p>
<p style="text-align: justify">"Oke Rachel, ini pengalaman kamu sendiri atau orang terdekat kamu?"</p>
<p style="text-align: justify">"Saya sendiri Mbak."</p>
<p style="text-align: justify">"Sip, langsung aja ke ceritanya ya. Bisa dimulai.."</p>
<p style="text-align: justify"> "Kejadiannya di rumah saya sendiri. Saya merantau dari Jogja dan baru tinggal di rumah ini hampir dua minggu. Menurut banyak orang, rumah ini ada penghuninya. Seorang wanita yang di mutilasi hingga enam bagian. Saya sih tidak takut, karena rumah seperti ini cocok untuk observasi saya dalam pembuatan project buku horror saya, biar dapet soul-nya gitu Mbak. Lagian, saya punya six sense, jadi sudah terbiasa dengan hal seperti itu. Saya juga punya kalung pelindung yang diberikan turun-temurun dari buyut saya yang terbuat dari</p>
<p style="text-align: justify">batu safir hitam, di dalamnya terdapat ayat. Saya keturunan terakhir, jadi nantinya saya akan kasih kalung ini pada anak saya atau orang yang saya percaya. Kalung ini juga bisa melindungi saya dari berbagai kejahatan makhluk apa pun. Jadi saya yakin kalau roh mereka tidak akan bisa menyakiti fisik saya."</p>
<p style="text-align: justify">"Jadi kamu pernah lihat penampakan cewek yang dibunuh itu?"</p>
<p style="text-align: justify">"Sering. Malah tiap malam wanita itu menangis dan saya selalu mencium bau amis. Kebetulan kamar yang saya pakai adalah tempat di mana wanita itu di mutilasi."</p>
<p style="text-align: justify">Gile, berani bener!</p>
<p style="text-align: justify">"Kamu bisa certain gak penampakan cewek itu kayak gimana?"</p>
<p style="text-align: justify">"Kadang saya cuman lihat kepalanya saja, bahkan potongan tubuh lainnya. Tapi saya juga pernah lihat dia secara utuh sedang berdiri di ujung tangga, tubuhnya berlumuran darah, wajahnya pucat dan matanya memancarkan kesedihan sekaligus kemarahan."</p>
 <p style="text-align: justify">Tanpa disadari, Pearly mengusap tengkuknya.</p>
 <p style="text-align: justify">"Ekspresi kamu waktu liat dia gimana sih? Kamu kaget atau pura-pura gak lihat?"</p>
 <p style="text-align: justify">"Saya gak kaget. Bahkan beberapa kali saya coba ajak dia bicara tapi dia hanya menangis,"</p>
 <p style="text-align: justify">"Hhmmm.. oke Rachel, ada yang lainnya? Mungkin penampakan lain selain wanita itu atau komu tahu tentang pembunuhnya akhirnya kayak gimana?"</p>
 <p style="text-align: justify">"Gak ada penampakan lain sih, selain nenek- nenek di halaman belakang yang suka nyisir secara slow motion gitu. Kalau soal pembunuhnya, katanya gak pernah ditemukan karena gak ada bukti yang bisa di selidiki polisi. Kayaknya cuman segitu aja deh yang mau saya ceritain."</p>
 <p style="text-align: justify">"Ok, thank you Rachel sudah berbagi cerita mistis bersama kita. Selamat malam dan sukses buat bukunya yaa."</p>
 <p style="text-align: justify">"Makasih, selamat malam."</p>
 <p style="text-align: justify">"Ya, itu dia cerita terakhir dari Rachel di Pondok Indah. Cukup membuat bulu kuduk saya merinding nih listener, tapi sayang sekali, sudah waktunya saya undur diri, kita ketemu lagi di malam jumat selanjutnya. Harap periksa jendela kamar kamu dan sudut-sudut ruangan, cause this is a spooky niiight"</p>
 <p style="text-align: justify">Pearly mematikan mikrofon dan meletakkan headset-nya lalu melesat keluar setelah meng ucapkan terima kasih kepada Billy sang produser</p>
 <p style="text-align: justify">Satria berbaring di sofa dengan kaki diangkat ke pegangan sofa dan sebuah majalah menutupi wajahnya. Sementara di sofa sebelahnya, Angga sedang menyeduh kopi dan Shena seorang gadis tomboy sedang sibuk dengan gadget-nya. Giliran mereka mengudara selama tiga jam. Dua orang kocak yang sangat menghibur dan bisa melebur rasa takut listener setelah mendengarkan spooky night.</p>
 <p style="text-align: justify">"Aaaahhh, akhirnya udah gak sabar pengen jatohin diri ke kasur Pearly mengambil cokelat panas milik Shena dan langsung meminumnya.</p>
 <p style="text-align: justify">"Yaelah, kebiasaan nih orang maen samber aja."</p>
 <p style="text-align: justify">"Sorry honey, gue males ke pantry." Pearly menyeringai. Nasib para penyiar malam karena OB hanya bekerja pada jam tujuh pagi sampai jam sebelas malam dengan pembagian dua shift.</p>
  <p style="text-align: justify">Pearly mengambil jaket kulit berwarna cokelat gelap milik Satria dari sandaran kursi, lalu melepas majalah yang menutupi wajah kekasihnya itu.</p>
 <p style="text-align: justify">"Sayaang, bangun dong kita pulang sekarang." Satria terbangun dengan mata memerah. Setelah mereguk kopi terakhir kalinya, Satria dan Pearly pun berpamitan kepada Angga dan Shena yang akan memasuki studio.</p>
 <p style="text-align: justify">Nissan Terrano milik Satria melaju mengarah ke rumah kontrakan Pearly yang hanya mencapai lima belas menit dari radio tempat Pearly bekerja. Setiap siaran malam, sudah menjadi kewajiban Satria untuk mengantar jemput Pearly semenjak kejadian perampokan yang untungnya bisa Pearly hindari berkat semprotan air cabai dari Ibunya yang selalu Pearly simpan di dalam tasnya.</p>
 <p style="text-align: justify">"Kamu langsung tidur ya Sayang, besok kalau ada apa-apa langsung telepon aku aja."</p>
  <p style="text-align: justify">"Ok Sayang, besok aku siaran jam 10 siang. Aku pergi sendiri aja deh, pulangnya aku langsung ke four hole ya, udah gatel megang stik."</p>
 <p style="text-align: justify">"Gitu dong, anak-anak juga udah kangen tuh tanding sama kamu." Satria menepikan mobilnya di depan rumah Pearly. Tampak mobil Honda swift merah milik Cherise terparkir.</p>
 <p style="text-align: justify">"Tumben tuh anak jam segini udah balik." Cherise adalah seorang DJ yang selalu diundang ke beberapa club hampir setiap malam. Sebenarnya dia sudah berhenti atas kemauan David tunangannya seorang keturunan Amerika, tetapi tetap saja naluri gila party-nya masih kenceng.</p>
 <p style="text-align: justify">"Capek kali, kemaren kan kalian sibuk seharian." kata Satria "Yaudah kamu juga istirahat gih. Jangan lupa vitaminnya diminum."</p>
 <p style="text-align: justify">"Oke pak bos, sampai besok." Pearly mencium bibir satria sekilas lalu beranjak turun. Satria memastikan Pearly mengunci pintunya, dan setelah dia melambaikan tangannya dari balik jendela, Satria pun menggas mobilnya lagi.</p>
 <p style="text-align: justify">Pearly menyalakan lampu ruang tamu dan mendapati botol wine yang isinya tinggal seperempat serta dua gelas crystal yang sudah kosong. Dia menganggap Cherise dan David telah menghabiskan malam bersama di sini. Pearly pun mengambil botol tersebut lalu pergi ke dapur untuk mengambil gelas baru. Setelahnya, Pearly memasuki kamar, melepaskan high heels, melempar tas ke kursi, melepaskan seluruh pakaiannya dan menggantinya dengan T-shirt berwarna putih saja. Dirinya terlalu lelah untuk membersihkan diri ke kamar mandi. Dia menuang wine ke dalam gelas dan menikmati setiap tegukannya, sedikit wine akan meringankan kepalanya. Pearly pun akhirnya jatuh tertidur hingga sembilan jam.</p>
 <h2>Bagian 2</h2>
  <p style="text-align: justify">"Good morning baby." Cherise menuang orange juice ke dua gelas panjang untuknya dan untuk Pearly.</p>
 <p style="text-align: justify">"Morning." Pearly menyambar salah satu gelasnya.</p>
 <p style="text-align: justify">"Cuci muka dulu kali Beb biar segeran."</p>
 <p style="text-align: justify">"Ck, minum dingin juga kan bikin seger." Sahut nya sambil meneguk minumannya hingga setengah gelas. "Tumben semalam lu pulang cepet."</p>
 <p style="text-align: justify">"Oh, biasalah si David pagi ini ada meeting sama klien-nya yang dari Seoul itu. Jadi gak bisa full party deh."</p>
 <p style="text-align: justify">"Eh, siang ini lo ada acara gak? Ke four hole yuk balik gue siaran. Udah gatel nih gue pengen ngalahin si Robby."</p>
 <p style="text-align: justify">"Ayok aja. Gue paling stand by di tempat spa. Lo jemput gue di sana aja ya."</
 <p style="text-align: justify">"Okey"</p>
 <p style="text-align: justify">Four hole adalah tempat billiard milik Satria yang berada di salah satu gedung mal. Tempat di mana Pearly dan Satria bertemu. Ketika itu Pearly mengikuti pertandingan Billiard se-provinsi DKI Jakarta. Satria terkesan ketika melihat Pearly adalah satu-satunya wanita dalam sepuluh besar dan akhirnya mendapatkan peringkat kedua. Selain itu, Phisically Pearly terlihat menarik meski tidak terlalu cantik. Tetapi wajahnya tidak membosankan dan memiliki tahi lalat di satu sisi rahangnya. Alisnya melengkung indah dengan sorot matanya yang tajam menunjukkan kekeraskepalaan dan kecerdasan. Sementara Satria berbadan tegap dan berdada bidang dengan rambutnya yang cepak dan mata seperti elang. Salah satu yang menarik dari Satria adalah senyumnya yang miring dan menampakkan sebelah lesung pipitnya.</p>
 <p style="text-align: justify">"Eh, lo inget si Sharen yang dateng ke peresmian spa gue gak? Yang gue bilang bokongnya abis di implant itu?"</p>
 <p style="text-align: justify">Pearly hanya mengangguk sambil melahap roti isi keju yang diolesi dengan mayonnaise dingin.</p>
 <p style="text-align: justify">"Rencananya, dia mau jadi franchise spa gue. Asik ga tuh? Gue ambil royalti berapa ya? Sepuluh persen masih manusiawi gak sih?"</p>
 <p style="text-align: justify">Pearly mengangguk lagi.</p>
 <p style="text-align: justify">"Hhhh.. gue minta pendapat David aja deh. Doi kan jiwa bisnis banget, tiap lahan yang dipegang dia pasti jadi emas semua. Hihi."</p>
 <p style="text-align: justify">Pearly tidak menjawab, sementara mulutnya penuh dengan roti, dia sudah mengolesi roti yang lain.</p>
 <p style="text-align: justify">"Ih dasar nih anak. Lo gak pernah belajar table manner ya? Masuk restoran Perancis, lo bisa di arak tau gak."</p>
 <p style="text-align: justify">"Lapeeeer. Lo inget gak sih kemarin kita cuman makan rujak sama kebab doang. Abis itu gue belom makan lagi sampe sekarang" Pearly kembali melahap roti ketiganya, sementara Cherise meringis.</p>
        </div>
    </div>

    <!-- Book 2 -->
    <div class="page" id="book2">
        <!-- Cover Page -->
        <div class="cover">
            <img src="cover2.jpg" alt="Cover Image">
            <h1>Coming Soon</h1>
            <h2>Author Name</h2>
        </div>
        <!-- Content of Book 2 -->
        <div class="content">
            <h2>Table of Contents</h2>
            <ul>
                <li>Cover</li>
                <li>Sinopsis</li>
                <li>Prolog</li>
                <li>Bagian 1</li>
                <li>Bagian 2</li>
                <li>Bagian 3</li>
                <li>Bagian 4</li>
                <li>Bagian 5</li>
                <li>Bagian 6</li>
            </ul>
            <h2>Synopsis</h2>
            <p style="text-align: center">Coming Soon </p>
            <h2>Prolog</h2>
            <p style="text-align: center">Coming Soon</p>
            <h2>Bagian 1</h2>
            <p style="text-align: center">Coming Soon</p>
        </div>
    </div>

    <!-- Book 3 -->
     <div class="page" id="book3">
        <!-- Cover Page -->
        <div class="cover">
            <img src="cover3.jpg" alt="Cover Image">
            <h1>Coming Soon</h1>
            <h2>Author Name</h2>
        </div>
        <!-- Content of Book 2 -->
        <div class="content">
            <h2>Table of Contents</h2>
            <ul>
                <li>Cover</li>
                <li>Sinopsis</li>
                <li>Prolog</li>
                <li>Bagian 1</li>
                <li>Bagian 2</li>
                <li>Bagian 3</li>
                <li>Bagian 4</li>
                <li>Bagian 5</li>
                <li>Bagian 6</li>
            </ul>
            <h2>Synopsis</h2>
            <p style="text-align: center">Coming Soon </p>
            <h2>Prolog</h2>
            <p style="text-align: center">Coming Soon</p>
            <h2>Bagian 1</h2>
            <p style="text-align: center">Coming Soon</p>
        </div>
    </div>

    <!-- Profile -->
    <div class="page" id="profile">
        <div class="profile">
            <img src="Profil.jpg" alt="Your Photo">
            <h2>Septian Ramdoni</h2>
            <p>Username: Yurnosz</p>
            <p>Usia: 17</p>
            <p>Kelamin: Male</p>
            <p>Nomor Telepon: 0895324609215</p>
        </div>
    </div>

    <script>
        function showBook(bookId) {
            // Hide all books
            const pages = document.querySelectorAll('.page');
            pages.forEach(page => page.classList.remove('active'));

            // Show selected book
            const book = document.getElementById(bookId);
            if (book) {
                book.classList.add('active');
            }
        }
    </script>

</body>
</html>
