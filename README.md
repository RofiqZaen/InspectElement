# InspectElementAndroid

1. Buka Chrome
2. Klik titik tiga
3. klik bintang / bookmark, lalu edit
   beri nama InspectElement. Hapus URL lalu isi dengan script di bawah.

javascript:(function () { 
    var script =  document.createElement('script');
    script.src="//cdn.jsdelivr.net/npm/eruda"; 
    document.body.appendChild(script);
    script.onload = function () { 
        eruda.init() 
    } 
})();

4. Klik panah <- di pojok kiri atas
5. Cari / masukan situs yang ingin anda ketahui elemennya.
6. setelah web / situs terbuka, klik di bagian alamat web / situs, kita ketikkan InspectElement, nanti akan muncul saran pencarian kalian klik saja InspectElement yang ada bintang / bookmark seluler. Nanti akan muncul icon di pojok kanan bawah. kalian klik saja nanti kalian akan mengetahui elemen-elemen yang ada di dalam web / situs tersebut.

selesai.

