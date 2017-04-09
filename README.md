# Tugas-2

Web Service - XSD 1154012 - Agien Farhan Saputra - D4TI2A

XML Schema (XSD) merupakan script XML untuk membinding field baik berupa nama, caption, atau value dari field tersebut.

File xml dapat diintegrasikan dengan berbagai project, untuk keperluan praktikum ini kita akan membuat project tidak utuh, hanya membuat file xml dan xsd dengan tools dan plugin eclipse, kemudian memeriksa apakah dokumen tersebut valid, well form.

Langkah-langkanya sebagai berikut :
1.	Klik File > New > Project > Plug-in Project
2.	Beri nama sesuai kebutuhan, disini saya menamakan Tugas 2, lalu klik Next > Finish
3.	Pada Project Explorer, fold: src/Tugas 2. Klik kanan
4.	Pilih New > Other > XML file > Klik Next
5.	Beri nama sesuai kebutuhan, disini saya menamakan p_kayu.xml (jangan lupa pakai .xml) dan klik Finish
6.	Isikan file p_kayu.xml seperti file yang saya upload
7.	Setelah selesai, klik kanan pada file p_kayu.xml dan pilih Create XML definition. (jika tidak muncul “Create XML definition” maka anda harus menginstall plugin Rinzo xml editor. Link Download : https://sourceforge.net/projects/editorxml/files/Rinzo%20XML%20Editor/ )
8.	Beri nama sesuai kebutuhan, disini saya menamakan kayu.xsd (jangan lupa pakai .xsd) dan klik Finish
9.	Setelah itu akan terlihat design schema dari p_kayu.xml
10.	Selanjutnya membuat reference file xsd pada file xml, klik kanan pada kayu.xsd, lalu pilih Generate > XML file
11.	Beri nama sesuai kebutuhan, disini saya menamakan kayu1.xml (jangan lupa pakai .xml) dan klik Next > Finish
12.	Lalu copy link referensi tersebut ke p_kayu.xml
13.	Setelah itu membuat patterns pada atribut email dengan ketentuan @gmail.com
14.	Klik kayu.xsd > Elements > email
15.	Pada struktur email > klik kanan > show properties > pada constraint klik pattern di sebelah kanan > add
16.	Beri nama “.+@gmail.com”
17.	Setelah itu membuat patterns pada atribut satuan dengan ketentuan hanya “batang” yang boleh diisikan
18.	Langkahnya sama dengan nomor 14 – 16, tapi diberi nama “batang”
19.	Setelah itu membuat constraint Min/Max pada jumlah dengan ketentuan minimal 50 dan maximal 1000 pembelian
20.	Pada struktur email > klik kanan > show properties > pada minimum value 50 dan maximal value 1000 > centang inclusive
21.	Selanjutnya tinggal di validate, jika tidak muncul error berarti anda berhasil

