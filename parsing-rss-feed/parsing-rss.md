## Final Project - 2
### Bryan Pratama Putra 1202190037

Menghubungkan database dengan mengubah .env


<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/connect_db.png" width="" height="350">


<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/localhost.png" width="" height="350">

Membuat rss table dan news table
```
php artisan make:migration create_rss_table
php artisan make:migration create_news_table
```

![](Assets/rss_table.png)

Tambahkan name dan url pada rss table

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/add_name_url.png" width="" height="350">

Tambahkan title,img_url,description,source_url,dan rss_id pada news_table

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/add_title_imgurl_desc_etc.png" width="" height="350">

Membuat model Rss dan News

```
php artisan make:model Rss --seed --controller
php artisan make:model News --controller

```
![](Assets/model_seed_controller.png)


Melakukan Route di web.php

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/route.png" width="" height="350">

![](Assets/news_link.png)


```
php artisan migrate

```
Edit file NewsController.php

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/news_controller.png" width="" height="350">

```
php artisan migrate:refresh
php artisan migrate --seed
```

RSS 1

![](Assets/rss_1.png)
<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/output_rss1.png" width="" height="350">

RSS 2

![](Assets/rss_2.png)
<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/output_rss2.png" width="" height="350">

RSS 3

![](Assets/rss_3.png)
<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/parsing-rss-feed/Assets/output_rss3.png" width="" height="350">
