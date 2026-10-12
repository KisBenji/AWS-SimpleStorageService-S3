# AWS S3 & CloudFront áttekintés

Amazon S3 (Simple Storage Service)
Skálázható, biztonságos és rendkívül tartós objektumtárhely (object storage) a projekt fájljai (forráskódok, dokumentumok, képek vagy médiafájlok) számára. Megbízható, korlátlanul skálázható és biztonságos alapot nyújt az adatok hosszú távú megőrzésére és központi tárolására. Magas rendelkezésre állással az adatok több független adatközpontban helyezkednek el. Rugalmasság, mert szinte bármilyen méretű és formátumú fájl tárolására alkalmas, korlátlan skálázhatósággal.

Amazon CloudFront (CDN)
Content Delivery Network, amely a világ különböző pontjain található edge locationökön keresztül gyorsítja fel a statikus és dinamikus adatok elérését.

A használatával a világ bármely pontján tartózkodó felhasználók számára villámgyors betöltési időt, alacsony késleltetést és tehermentesített, stabil kiszolgálást biztosítsunk. A tartalmat a végfelhasználóhoz földrajzi elhelyezkedés szerint legközelebbi szerver szolgálja ki. Gyorsítótárral (Caching) tehermentesíti a mögöttes forrásrendszereket a gyakran kért fájlok helyi tárolásával.


### Tartalom
---
1. [S3 - Bucket létrehozása - alap](<./Bucket létrehozása/README.md>)
3. [S3 - Bucket létrehozása - fájl feltöltése](<./Bucket létrehozása -fájl feltöltése/README.md>)
4. [S3 - Verziózás](<./S3 Verziózás/README.md>)
5. [S3 - Statikus weboldal](<./S3 statikus weboldal/README.md>)
6. [S3 fájlok elérése EC2-ről](<./S3 fájlok elérése EC2-ről (IAM role)/README.md>)
7. [IAM role létrehozása](<./IAM role létrehozása/README.md>)
8. [Cloudfront létrehozása](<./Cloudfront létrehozása egy meglévő S3 bucket fölé/README.md>)
