# petstore_api_testing
Swagger UI
https://petstore.swagger.io/

Case1: Delete all pets and Get petId 103 - fail 404
Oluşturulan bütün pet dataları silinir.
petId 103 read işlemi yapıldığında 404 "pet not found" response code'u alınır.

Case2: Get petId 102 - pass 200
7 adet pet datası create edilir.
petId 102 read işlemi yapıldığında 200 "response is ok" response code'u alınır.

Case3: Get petId 1010 - fail 404
7 adet pet datası create edilir.
petId 1010 read işlemi yapıldığında 404 "pet not found" response code'u alınır.

Case4: Get order by petId 3 - pass 200
7 adet pet datası create edilir. (pet shope order)
order by petId 3 read işlemi yapıldığında 200 "response is ok" response code'u alınır.

Case5: Get order by petId 36515 - fail 404
7 adet pet datası create edilir. (pet shope order)
order by petId 36515 read işlemi yapıldığında 404 "pet not found" response code'u alınır.

Case6: Update user
3 adet user datası create edilir.
Userlardan bir tanesinin username'i update edilir.
