# RGB-Clock_UTS_KGV_Wiyata

## RGB Clock

Untuk menjalankan program ini terdapat beberapa konfigurasi yang harus dilakukan:

1. Gunakan <em>command</em> <strong>git clone https://github.com/FrederickGodiva/RGB-Clock_UTS_KGV_Wiyata.git</strong> untuk menduplikasi semua file yang ada di repository ini ke local device Anda.

2. Pastikan bahwa Anda sudah memasukkan <strong>GLFW</strong> dan <strong>GLEW</strong> ke dalam folder <em><strong>Dependencies</em></strong>

3. Klik kanan pada Solution dan pilih <em>Properties</em>.<br>
   a. Pada menu <strong>Configuration Properties</strong>, submenu <em>VC++ Directories<em>, tambahkan <strong>$(SolutionDir)Dependencies\GLFW\include</strong> dan <strong>$(SolutionDir)Dependencies\GLEW\include</strong> pada bagian <em>Include Directories</em><br>
   b. Tambahkan juga <strong>$(SolutionDir)Dependencies\GLFW\lib</strong> dan <strong>$(SolutionDir)Dependencies\GLEW\lib</strong> pada bagian <em>Library Directories</em><br>
   c. Pada menu <strong>C/C++</strong>, submenu <em>Preprocessor</em>, tambahkan <strong>GLEW_STATIC</strong> pada <em>Preprocessor Definitions</em><br>
   d. Pada menu <strong>Linker</strong>, submenu <em>Input</em>, tambahkan <strong>glfw3.lib; opengl32.lib; glew32s.lib</strong> pada <em>Additional Dependencies</em><br>
   e. Pastikan bahwa <strong>Platform</strong> sudah menggunakan <strong><em>x64</em></strong>
