- 👋 Hi, We are @metaasdigitalindonesia

<!---
metaas/metaas is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
cara jalankan coding di local :
1. tidak perlu install laragon / xampp
2. buka visual studio code 
3. ambil git dari Github
	https://github.com/metaas/metaas.id.git
4. update versi php (sesuaikan dgn versi php di server) di environment variable
5. copy .env.example ke .env
6. open Terminal di VSCode
7. masuk ke folder coding hasil checkout
	C:\2. METAAS\METAAS SOURCECODE\Git Production Server\metaas.co.id\laravel_43784a
8. jalankan 
	composer update
9. jalankan
	php artisan key:generate
10. utk running di local jalankan
	php artisan serve
11. buka di browser sesuai server running
	http://127.0.0.1:8000