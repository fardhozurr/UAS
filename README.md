# UAS
Tugas UAS 1 Pengenalan Informatika

# Hello Informatics !

## Menjelaskan dan Menginternalisasi Computational Thinking ⭐⭐⭐⭐⭐⭐⭐
Computational Thinking adalah kemampuan untuk memecahkan masalah dengan menggunakan prinsip-prinsip terkait dengan pemrograman komputer. Pemikiran ini melibatkan penggunaan algoritma, logika, dan abstraksi dalam memecahkan berbagai masalah. Dalam konteks ini, algoritma dapat diartikan sebagai langkah-langkah terperinci yang diambil untuk menyelesaikan suatu masalah. Sedangkan logika adalah kemampuan untuk berpikir secara sistematis dan kritis dalam mengevaluasi berbagai kemungkinan solusi. Sementara itu, abstraksi adalah kemampuan untuk menyederhanakan masalah kompleks menjadi komponen-komponen yang lebih kecil dan terkelola. Dengan menggunakan pemikiran komputasional, seseorang dapat mengidentifikasi dan memecahkan masalah dengan lebih efektif dan efisien. Untuk menjelaskan dan menginternalisasi Computational Thinking, ada 4 tahapan yang perlu dilakukan, yaitu:
Decomposition: Memecah masalah yang kompleks menjadi masalah-masalah yang lebih sederhana untuk diselesaikan.
Pattern Recognition: Mengidentifikasi pola atau kesamaan dalam masalah yang diberikan.
Abstraction: Menyederhanakan masalah kompleks menjadi komponen-komponen yang lebih kecil dan terkelola.
Algorithm Design: Merancang algoritma atau langkah-langkah terperinci yang diambil untuk menyelesaikan suatu masalah.


## Menjelaskan Jenis-Jenis Mesin Komputasi ⭐⭐⭐
Jenis-jenis mesin komputasi dapat dibagi menjadi beberapa kategori, antara lain:
a. Komputer pribadi
Personal Computer (PC): Merupakan jenis komputer yang biasanya digunakan untuk keperluan pribadi atau perkantoran. PC terdiri dari beberapa komponen seperti CPU, monitor, keyboard, dan mouse.

b. Server
Server: Merupakan jenis komputer yang digunakan untuk menyimpan data dan aplikasi yang dapat diakses oleh banyak pengguna secara bersamaan. Server biasanya digunakan dalam lingkungan bisnis atau industri.

c. Komputer meja
Desktop: Merupakan jenis komputer yang dirancang untuk digunakan di atas meja. Desktop biasanya memiliki spesifikasi yang lebih tinggi dibandingkan dengan PC.
Laptop: Merupakan jenis komputer yang dirancang untuk digunakan di mana saja. Laptop biasanya lebih ringkas dan portabel dibandingkan dengan desktop.

d.Netbook
Netbook: Merupakan jenis komputer yang dirancang untuk digunakan di mana saja. Netbook biasanya lebih kecil dan lebih ringan dibandingkan dengan laptop.

e.Komputer elektronik digital
Komputer Digital: Merupakan jenis komputer yang menggunakan sinyal digital untuk memproses data.

f.Komputer analog
Komputer Analog: Merupakan jenis komputer yang menggunakan sinyal analog untuk memproses data.

g.Komputer Hybrid: Merupakan jenis komputer yang menggabungkan sinyal digital dan analog untuk memproses data.


## Mengktifkan dan Mencoba Google Colab [v] ⭐⭐⭐⭐⭐

Saya sudah mengaktifkan google colab dan melakukan percobaan tentang bagaimana memperkenalkan diri dengan sejumlah identitas. Berikut link percobaan perkenalan yang dibuat di akun google colab :
[https://colab.research.google.com/drive/1BeLoZJW5sb2XTgIcEmgQbgYCilMBj73J?usp=sharing](https://colab.research.google.com/drive/1BeLoZJW5sb2XTgIcEmgQbgYCilMBj73J?usp=sharing)

## Mencoba Console Sistem Operasi
### Windows CMD [v] ⭐⭐⭐⭐
Referensi [1](https://www.stationx.net/windows-command-line-cheat-sheet/)

1. append = c:\docs;c:\letters edit myfile.txt
2. arp = -s 220.0.0.161 00-50-04-62-F7-23
3. assoc = .txt
4. at = /delete /yes
5. attrib = -R example.txt
6. bcdedit = /command <argument>
7. bootsect = /nt52 E:
8. break = off
9. cacls = [file name] [sub-command]
10. call = second.bat
11. chdir = ..
12. chkdsk = d: /r
13. chkntfs = /d
14. cipher = /c myfile.txt
15. clip = readme.txt
16. clip  = cls
17. cmdkey = /list
18. color = <b><f>
19. comp = file1.txt file2.txt /n=10 /a
20. compact = file.txt /c 


### Linux Terminal Menggunakan Google Colab [v] ⭐⭐⭐⭐

Saya telah mencoba Terminal Linux dengan menggunakan google colab. Berikut adalah link terminal linux dengan membuat contoh seperti surat terbuka untuk ibu : https://colab.research.google.com/drive/1QFC_MzULq4eDcQan-CmOsniW-O1bR6Oq?usp=sharing

## Membuat Algoritma Dalam Bentuk Flow Chart [v] ⭐⭐⭐⭐⭐







![flowchart drawio](https://github.com/fardhozurr/UAS/assets/149001449/401c100b-1a59-476a-8a3f-558dae0b9343)




 


## Mencoba Scratch Bahasa Indonesia [v] ⭐⭐⭐⭐⭐⭐⭐

Referensi [1](https://scratch.mit.edu/)


## Mencoba Algoritma Bubble Sort Menggunakan Java [v] ⭐⭐⭐
public class BubbleSortExample {
    static void bubbleSort(int[] arr) {
        int n = arr.length;
        int temp = 0;
        for(int i=0; i < n; i++) {
            for(int j=1; j < (n-i); j++) {
                if(arr[j-1] > arr[j]) {
                    //swap elements
                    temp = arr[j-1];
                    arr[j-1] = arr[j];
                    arr[j] = temp;
                }
            }
        }
    }
     public static void main(String[] args) {
        int arr[] ={3,60,35,2,45,320,5};
        System.out.println("Array Before Bubble Sort");
        for(int i=0; i < arr.length; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();

        bubbleSort(arr);//sorting array elements using bubble sort

        System.out.println("Array After Bubble Sort");
        for(int i=0; i < arr.length; i++) {
            System.out.print(arr[i] + " ");
        }
    }
}

## Mencoba dan Mendemonstrasikan Penggunakan IDE ⭐⭐

## Mendaftar, Mengeksplorasi, dan Mendemonstrasikan Penggunaan HackerRank [v] ⭐⭐⭐⭐⭐

Saya telah mendaftar dan mengeksplorasi Penggunaan HackerRank. Berikut link profil akun HckerRank yang saya buat dan Bukti Ekssplorasi tentang Java (Loops) dari akun yang saya baut: https://www.hackerrank.com/profile/koushikizurro1
![image](https://github.com/fardhozurr/UAS/assets/149001449/b0ee7be2-6608-4b03-ac08-ef9ad4068450)


## Mendemonstrasikan Pembuatan Aplikasi / Game Pada Platform : Mobile / Desktop / Web Browser ⭐⭐⭐⭐⭐

Link YouTubw :

## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐

Referensi installer [PostgreSQL](https://www.postgresql.org/download/windows/)
Referensi tambahan [1](https://db-engines.com/en/ranking)

## Mencoba Eksplorasi dan Query Database Menggunakan Database Explorer (Dbeaver / dsb.) [v] ⭐⭐⭐

Referensi installer [Dbeaver](https://dbeaver.io/download/)
Referensi [1](https://www.w3schools.com/postgresql/postgresql_create_table.php)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐
- Dokumen HyperText Markup Language (HTML) ada untuk memudahkan pertukaran informasi berbasis Hypertext.
- Web Browser seperti Firefox, Chrome, Opera, ada untuk membuka dan mempresentasikan dokumen HTML
- Dokumen HTML ini bisa bersumber dari web server yang kita ingin datanya (Tokopedia, Wikipedia, Detik.com, dsb.) atau bisa juga dukumen HTML yang kita buat sendiri

  Halo, ini adalah Fardho Zurrahman. Saya dapat membantu Anda mempelajari tentang penggunaan web browser untuk mengakses halaman web HTML.
Web browser adalah program yang memungkinkan Anda untuk melihat konten web di internet. HTML adalah bahasa yang digunakan untuk membuat dan mendesain halaman web. Untuk mengakses dokumen HTML di browser, Anda perlu mengetahui alamat URL (Uniform Resource Locator) dari halaman web yang ingin Anda lihat. URL adalah teks yang menunjukkan lokasi sumber web, seperti https://www.bing.com/.
Ada banyak cara untuk mengakses dokumen HTML di browser, yaitu:
Mengetikkan URL di bilah alamat browser dan menekan Enter. Ini akan memuat halaman web yang sesuai dengan URL tersebut.
Mengklik tautan yang mengarah ke dokumen HTML di halaman web lain. Ini akan membuka halaman web baru di tab atau jendela browser Anda.
Membuka dokumen HTML yang tersimpan di komputer Anda dengan menggunakan menu Buka Dengan atau menyeret dan menjatuhkan file ke browser. Ini akan menampilkan halaman web yang dibuat oleh dokumen HTML tersebut.
Anda dapat menggunakan browser web apa pun untuk mengakses dokumen HTML, seperti Google Chrome, Firefox, Safari, atau Edge. Browser web berbeda dalam hal fitur, kecepatan, dan keamanan, tetapi semuanya dapat menafsirkan dan menampilkan HTML dengan cara yang sama.
Jika Anda ingin belajar lebih lanjut tentang HTML dan cara membuat halaman web Anda sendiri, Anda dapat mengunjungi situs web seperti W3Schools atau GeeksforGeeks, yang menawarkan tutorial, editor, dan contoh HTML online. Anda juga dapat menggunakan alat seperti W3School Spaces untuk membuat, menguji, dan menerbitkan situs web Anda sendiri dengan mudah.
Semoga ini membantu. 

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐

Referensi: [1](https://www.startertutorials.com/ajwt/uniform-resource-locator.html)

Uniform Resource Locator (URL) adalah alamat situs web di internet yang menunjukkan lokasi sumber daya serta protokol yang digunakan untuk mengaksesnya. URL terdiri dari beberapa komponen, yaitu:

Protokol: Protokol yang digunakan untuk mengakses sumber daya, seperti HTTP, HTTPS, FTP, dan lain-lain .
Nama domain: Lokasi server yang menyediakan sumber daya, dapat berupa alamat IP atau nama domain .
Path: Lokasi sumber daya dalam struktur direktori server.
Port: Nomor port di server (opsional).
Pengidentifikasi fragmen: Pengidentifikasi fragmen (opsional).
Sebagai contoh, URL berikut ini menjelaskan komponen-komponen URL: https://www.example.com:8080/path/to/resource?param=value#fragment

Protokol: https
Nama domain: www.example.com
Port: 8080
Path: /path/to/resource
Query string: param=value
Pengidentifikasi fragmen: fragment


## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐

Referensi terkait: [1](https://en.wikipedia.org/wiki/Country_code_top-level_domain) [2](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐

Referensi tutorial 
- Isi konten halaman web : [HTML](https://www.w3schools.com/html/)
- Styling halaman web : [CSS](https://www.w3schools.com/css/)
- Interaktivitas halaman web : [JavaScript](https://www.w3schools.com/js/)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐

Referensi []

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐
 Done!


## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐


## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐

## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐
Saya telah mencoba menggunakan penggunaan developer tools pada web browser di chrome. Saya bisa  menggunakan fitur Developer Tools dan  memeriksa elemen HTML, mengecek CSS, memantau jaringan, dan lain-lain. Berikut tangkapan layar ketika saya mencoba developer tools.



![ssss](https://github.com/fardhozurr/UAS/assets/149001449/928666f8-9e02-4f16-9807-fa474e69d439)




## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐
Saat ini banyak perusahaan berbasis digital seperti Gojek, Tokopedia, Instagram, Telkom memanfaatkan Cloud Service karena memudahkan untuk mulai pembangunan dan analisis menggunakan infrastruktur digital yang dapat berkembang secara dinamis dengan tarif yang sangat teliti.

Referensi cloud service: [Amazon Web Service](https://aws.amazon.com/) [Microsoft Azure](https://azure.microsoft.com) [Google Cloud Platform](https://cloud.google.com) 

## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐
Saya telah membuat akun dan mencoba penggunaan sistem manajemen konten sebagaiamana yang tertera di link berikut.
https://fardhoo.wordpress.com/2023/11/29/penting-menjaga-kesehatan-tubuh/
https://fardhoo.wordpress.com/2023/12/25/kisah-sahabat-nabi-yang-buruk-rupa-namun-jadi-rebutan-bidadari/

## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐
Saya sapat menggunakan tag HTML seperti <img>, <audio>, dan <video> untuk menampilkan gambar, audio. Saya juga mampu menggunakan Content Management System (CMS) seperti WordPress, yang memungkinkan saya untuk mengelola konten multimedia dengan mudah. saya dapat mengunggah gambar, audio, dan video ke CMS Anda dan menambahkannya ke halaman web Anda dengan mudah. Ada banyak aplikasi yang memungkinkan Anda untuk mengakses konten multimedia. Misalnya, Anda dapat menggunakan aplikasi seperti VLC Media Player untuk memutar video dan audio, atau aplikasi seperti Adobe Photoshop untuk mengedit gambar. Berikut contoh salah satu bahwa saya dapat menggunakan aplikasi mengedit gambar menggunakan Adobe Photoshop.

![WhatsApp Image 2023-12-25 at 01 14 32](https://github.com/fardhozurr/UAS/assets/149001449/43f09cd0-30fd-4926-8f18-beabc1a2e30e)



## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐
Saya telah mencoba dan mampu menguasai bagaimana mengedit konten multimedia yang terdiri dari image, audio, dan video. Salah satu apliksi yang saya kuasai dan digunakan dalam mengedit konten tersebut yaitu Canva, Pisc Art, Capcut dll.Berikut link dari salah satu contoh bahwa saya telah mencoba mengedit sebuah video.
https://youtu.be/K66E6HhAAqk?si=em72k9-KC42twjBw


## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐


## Mencoba pemprosesan konten multimedia (image, audio) menggunakan google colab [v] ⭐⭐⭐


## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐

## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐

import org.jfree.chart.ChartFactory;
import org.jfree.chart.ChartPanel;
import org.jfree.chart.JFreeChart;
import org.jfree.chart.plot.PlotOrientation;
import org.jfree.data.category.DefaultCategoryDataset;
import javax.swing.JFrame;

public class BarChartExample {
    public static void main(String[] args) {
        
        DefaultCategoryDataset dataset = new DefaultCategoryDataset();
        dataset.addValue(50, "Category 1", "Series 1");
        dataset.addValue(60, "Category 1", "Series 2");
        dataset.addValue(40, "Category 2", "Series 1");
        dataset.addValue(70, "Category 2", "Series 2");

        JFreeChart barChart = ChartFactory.createBarChart(
                "Contoh Grafik Batang",
                "Kategori",
                "Jumlah",
                dataset,
                PlotOrientation.VERTICAL,
                true, true, false);
                ChartPanel chartPanel = new ChartPanel(barChart);
        chartPanel.setPreferredSize(new java.awt.Dimension(500, 270));
        JFrame frame = new JFrame("Bar Chart");
        frame.setContentPane(chartPanel);
        frame.pack();
        frame.setVisible(true);
    }
}

## Mencoba Data Visualization Dengan Code [v] ⭐⭐

import org.jfree.chart.ChartFactory;
import org.jfree.chart.ChartPanel;
import org.jfree.chart.JFreeChart;
import org.jfree.chart.plot.PlotOrientation;
import org.jfree.data.category.DefaultCategoryDataset;
import javax.swing.JFrame;

public class BarChartExample {
    public static void main(String[] args) {
     
        DefaultCategoryDataset dataset = new DefaultCategoryDataset();
        dataset.addValue(50, "Category 1", "Series 1");
        dataset.addValue(60, "Category 1", "Series 2");
        dataset.addValue(40, "Category 2", "Series 1");
        dataset.addValue(70, "Category 2", "Series 2");

        JFreeChart barChart = ChartFactory.createBarChart(
                "Contoh Grafik Batang",
                "Kategori",
                "Jumlah",
                dataset,
                PlotOrientation.VERTICAL,
                true, true, false);
                ChartPanel chartPanel = new ChartPanel(barChart);
        chartPanel.setPreferredSize(new java.awt.Dimension(500, 270));
        JFrame frame = new JFrame("Bar Chart");
        frame.setContentPane(chartPanel);
        frame.pack();
        frame.setVisible(true);
    }
}

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐
Saya telah mendaftar dan mengeksplorasi HuggingFace tentang Magic Animate yang mana terdapat berbagai referensi gambar dan banyak motion sequence. Berikut link profil HuggingFace saya dan tangkapan layar tentang eksplorasi dari Hugging Face yang saya lakukan.
https://huggingface.co/fardhozurr



![sslg](https://github.com/fardhozurr/UAS/assets/149001449/d4ab15e7-c301-421c-8c33-51d9b8172fdc)



## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐
Saya telah mendaftar dan melakukan eksplorasi tentang Jerawat, jenis-jenis jerawat di kulit manusia dan beberapa gamber jenis jerawat tersebut di Kaggle. Berikut adalah link profil akun Kaggle saya dan tangkapan layar tentang eksplorasi Acne pada Kaggle.
https://www.kaggle.com/fardhozurrahman



![SSWOI](https://github.com/fardhozurr/UAS/assets/149001449/277132dc-a65f-44d8-8388-ccbda4fe06c0)





## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐
Saya telah mendownload mqtt dan melakukan operasi bersama panduan pak insan di kelas.


## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐


## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐


## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐

 Jurnal adalah publikasi ilmiah yang memuat artikel-artikel hasil penelitian yang telah selesai dilaksanakan dan telah memperoleh hasil. Artikel dipublikasikan sesuai periode tertentu oleh jurnal. Ada jurnal yang mempublikasikan artikel per 6 bulan, per 3 bulan atau bahkan ada per 1 bulan.

Conference adalah wadah bertemunya para peneliti/akademisi/praktisi untuk menyampaikan penelitiannya yang sedang berjalan ke sesama peneliti dalam bidang yang sama (dalam bentuk manuskrip) dengan tujuan untuk mendapat masukan dari peserta lainnya, agar ada perbaikan dari penelitiannya. Manuskrip yang dipresentasikan dalam conference juga mesti melewati proses review.

Artikel adalah karya tulis ilmiah yang telah dinyatakan diterima dan dipublikasikan pada suatu jurnal atau prosiding. Artikel yang dimuat pada prosiding merupakan artikel dari penelitian yang sedang berjalan, sehingga hasilnya bisa berupa hipotesis, dan belum teruji. Oleh karena itu, artikel yang berasal dari prosiding sangat jarang digunakan sebagai rujukan utama dalam sebuah penelitian. Sedangkan artikel yang dipublikasikan pada jurnal telah memperoleh hasil yang terukur dan metodenya jelas.

Grade jurnal adalah sistem penilaian kualitas jurnal ilmiah yang biasanya digunakan oleh lembaga-lembaga akademik atau pemerintah. Sistem penilaian ini bertujuan untuk menilai kualitas jurnal ilmiah berdasarkan kriteria tertentu seperti kualitas artikel, tingkat keberhasilan dalam proses review, dan dampak dari artikel tersebut terhadap perkembangan ilmu pengetahuan


## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐

Repository terekognisi internasional adalah tempat penyimpanan artikel jurnal atau conference yang telah diakui secara internasional. Artikel jurnal adalah karya ilmiah yang dipublikasikan dalam jurnal ilmiah, sedangkan artikel conference adalah karya ilmiah yang dipublikasikan dalam prosiding conference. Kedua jenis artikel ini biasanya diakui secara internasional dan dapat diakses melalui berbagai repository online.Beberapa contoh repository terekognisi internasional yang dapat Anda gunakan untuk mencari artikel jurnal atau conference antara lain:
1. Google Cendekia
Google Scholar: Google Scholar adalah mesin pencari khusus untuk artikel jurnal dan conference 
2. Scopus
Scopus: Scopus adalah database artikel jurnal dan conference yang diakui secara internasional 
3. Web of Science: Web of Science adalah database artikel jurnal dan conference yang diakui secara internasional 
4. Directory of Open Access Journals (DOAJ): DOAJ adalah direktori artikel jurnal open access yang diakui secara internasional
5. ResearchGate
ResearchGate: ResearchGate adalah jaringan sosial akademik yang memungkinkan para peneliti untuk berbagi artikel jurnal dan conference 

## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐
Saya telah menonton tentang Video Presentasi Tugas Akhir Jurusan Informatika yaitu tentang bagaimana menyusun power point saat akan melaksanakan tugas akhir. Berikut adalah link video yang sudah ditonton 
https://youtu.be/z2j2wgFE6JI?si=MimVLNhx6cbHOPm_

## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐
Profesi terkait di informatika sangatlah banyak, Namun secara garis besar dapat ditarik menjadi beberapa bagian:
1. Software engineer: Merupakan pekerjaan yang mengaplikasikan prinsip-prinsip pengelolaan dan optimalisasi software. Pekerjaan ini seperti analisis teknik informatika dan matematika dalam desain, development, maintenance, hingga testing software komputer atau device lain 
2. IT consultant: Bertugas untuk menerapkan strategi teknologi informasi dalam perencanaan, pelaksanaan, hingga evaluasi di sebuah perusahaan. Seorang IT consultant harus memiliki kemampuan analisis yang kuat untuk memahami masalah klien dan membuat solusi yang efektif 
3. Web developer: Para pakar yang memiliki spesialisasi dalam bidang pengembangan aplikasi world wide web, atau aplikasi yang dibangun pada HTTP dari sebuah web server 
4. Data analyst: Bertanggung jawab untuk mengumpulkan, menganalisis, dan memperoleh informasi dari data yang ada 
5. Network engineer: Bertanggung jawab untuk merancang, mengimplementasikan, dan memelihara jaringan komputer 
6. Database administrator: Bertanggung jawab untuk merancang, mengimplementasikan, dan memelihara database 
7. UI/UX designer: Bertanggung jawab untuk merancang antarmuka pengguna dan pengalaman pengguna yang baik 
8. Game developer: Bertanggung jawab untuk merancang, mengembangkan, dan memelihara video game

   Adapun aplikasi yang sekarang saya minati adalah IT consultant, Data analyst, UI/UX designer,  Game developer.

## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐
Berikut Link belajar bahasa inggris :
https://drive.google.com/file/d/1tzJRfHCe6v_G3C-mzT9dKR0fJvzLGe3t/view?usp=sharing

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 

## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐
Saya menemukan sejumlah lowongan kerja information technology yang bersumber dari 
https://id.indeed.com/q-teknik-informatika-lowongan.html?vjk=15800b0d231a8761
yaitu : 
BCA Syariah IT Development Program
IT Staff
UI/UX Engineer
Programmer
IT Supervisor
Software Engineer
Admin Marketplace
Network Engineer
etc.

## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐
Saya menemukan berbagai macam pekerjaan freelancher ti yang bersumber dari
https://id.indeed.com/lowongan-kerja-Freelance?vjk=fbb9b2f16aabd9f0
yaitu:
English Translator
Admin Project Freelance
Freelance Branding specialist
Freelancer Graphic Designer
Freelance Web Designer
Script Writer Freelancer
Sales Freelancer
Freelance Model
Frelance Photographer
etc.

## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐
Topik yang diminati = Roadmap to becoming a Game Developer in 2023

## Eksplorasi Top Github Project yang Diminati ⭐⭐
Berikut tentang github project yang diminati :
Rust implementation of Namada, a Proof-of-Stake L1 for interchain asset-agnostic privacy

## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐
Saya telah membuat akun Linkedin dan memfollow beberapa akun inspiratif. Berikut link profil akun saya :
https://www.linkedin.com/in/zurrahman-1-204bb42a4?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

## Membangun Profil Github Page ⭐⭐⭐⭐⭐

Link Github Profil : https://github.com/fardhozurr

## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐
Saya telah mengikuti Event GDSC. Tetapi saya tidak memiliki discord yang mana membuat saya tidak bisa mengikuti kegiatan yang sering diadakan melalui GDSC tersebut.

## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐

   
  

