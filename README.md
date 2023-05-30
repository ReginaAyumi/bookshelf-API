# bookshelf-API
Dicoding Submission - Belajar Membuat Aplikasi Back-End untuk Pemula
Pengujian dilakukan menggunakan Postman

# Kriteria
1. Aplikasi menggunakan port 9000
2. Aplikasi dijalankan dengan perintah npm run start.
3. API dapat menyimpan buku
Method : POST
URL : /books
4. API dapat menampilkan seluruh buku
Method : GET
URL: /books
5. API dapat menampilkan detail buku
Method : GET
URL: /books/{bookId}
6. API dapat mengubah data buku
Method : PUT
URL : /books/{bookId}
7. API dapat menghapus buku
Method : DELETE
URL: /books/{bookId}
8. Menambahkan fitur query parameters pada route GET /books (Mendapatkan seluruh buku).
- ?name : Tampilkan seluruh buku yang mengandung nama berdasarkan nilai yang diberikan pada query ini. Contoh /books?name=”dicoding”, maka akan menampilkan daftar buku yang mengandung nama “dicoding” secara non-case sensitive  (tidak peduli besar dan kecil huruf).
- ?reading : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sedang tidak dibaca (reading: false). Bila 1, maka tampilkan buku yang sedang dibaca (reading: true). Selain itu, tampilkan buku baik sedang dibaca atau tidak.
- ?finished : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sudah belum selesai dibaca (finished: false). Bila 1, maka tampilkan buku yang sudah selesai dibaca (finished: true). Selain itu, tampilkan buku baik yang sudah selesai atau belum dibaca.
9. Menggunakan ESLint 
10. Server dapat mengembalikan respons dengan status code 200, 400, dan 404

# Dokumentasi
![image](https://github.com/ReginaAyumi/bookshelf-API/assets/90667044/9b36e5ce-6248-4610-a25f-a534fa3f2c4f)

