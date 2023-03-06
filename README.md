# Tugas-3-Sistem-Kendali
Muhammad Nabil Akbar Musatafa 21/481679/PA/20981

# Penjelasan Kode
Program ini memakai beberapa modul dari paket SymPy seperti simplify, latex, dan parsing.sympy_parser yang digunakan untuk menyederhanakan ekspresi aljabar, mengonversi ekspresi ke dalam format LaTeX, dan menguraikan ekspresi simbolik menjadi ekspresi yang dapat dihitung.

Program ini terdiri dari beberapa fungsi, yaitu:

-	getExpr(raw_expr): untuk mengonversi string ekspresi matematika ke dalam ekspresi simbolik. Fungsi ini mengembalikan ekspresi simbolik yang disederhanakan.
-	determinant(r1c1, r1c2, r2c1, r2c2): untuk menghitung determinan matriks 2x2.
-	printRouthArray(RouthArray): untuk mencetak tabel Routh-Hurwitz dalam bentuk array.
-	exprArrToStrArr(expr_arr): untuk mengonversi array ekspresi simbolik menjadi array string.
-	ToLaTeX(str_arr): untuk mengonversi array string ke dalam format LaTeX.
-	RouthHurwitz(polynomial): untuk menghasilkan tabel Routh-Hurwitz dari polinomial yang diberikan dan mengembalikan array Routh-Hurwitz yang berisi ekspresi simbolik.
-	inputPolynomial(polynomial): untuk menginputkan polinomial dalam bentuk orde tertinggi hingga orde nol, kemudian mencetak polinomial yang diinputkan.
-	defineKvalue(Kvalue,polynomial): untuk menentukan sistem stabil atau tidak dengan memberikan nilai K pada polinomial yang diberikan. Kemudian mencetak hasil dari evaluasi nilai K dan menampilkan apakah sistem stabil atau tidak.

