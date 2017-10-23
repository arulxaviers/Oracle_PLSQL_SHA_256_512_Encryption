# SHA256 & SHA512 Encryption
# Oracle PL/SQL World

Run the below two Files in Respective Oracle Schema.

SQL> 1_SHA_FUCTION.SQL

SQL>2_SHA_JAVA_CLASS.SQL

--In 256 Encryption will get 64 Character Length String

SQL> SELECT LOWER(SHA('Oracle PL/SQL World',256)) FROM DUAL; 1f2f1fd5ab78cf15bd3cdf330d6ab79ba60cc797fb4875e5267f90daa10157aa

--In 512 Encryption will get 128 Character Length String

SQL> SELECT LOWER(SHA('Oracle PL/SQL World',512)) FROM DUAL; 478811ecf93ae1564ad0775c20aa0f1b5de5992306974a9339b25794de32a000d058136c481229c38f3ee9e6775426a3b54ff1daf495d3b7f2b6e571595ca888
