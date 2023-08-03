# Project_Analisis_Data_COVID19_di_Dunia_ASEAN

## Pendahuluan

Covid19 adalah pandemi yang sudah mewabah ke seluruh dunia. Sebagian besar negara-negara di dunia sudah terjangkit. Penanganan tiap-tiap negara pun berbeda, sesuai dengan kebijakan pemerintah. 

Hal ini mengakibatkan perbedaan trend kenaikan atau penurunan kasus covid berbeda-beda tiap negara.
Pada kasus kali ini, kita akan mencoba menggali data covid19 dari salah satu open api yang tersedia yaitu https://covid19-api.org/.

## Visualisasi Negara dengan Fatality Ratio Tertinggi di Bulan Agustus 2020

Untuk memvisualisasikan negara-negara dengan kasus fatality rate tertinggi akibat covid-19 ini dapat dilakukan dengan menggunakan bar chart, tepatnya horizontal bar chart.  

Dengan memilih kolom fatality_ratio pada data frame df_top_20_fatality_rate_on_august terapkanlah method-method berikut secara chaining mulai dari pengurutan dengan .sort_values, plot dengan .plot menggunakan keyword argument kind="barh".

![alt text](https://github.com/muhammadrafi18/Project_Analisis_Data_COVID19_di_Dunia_ASEAN/blob/main/Slide1.JPG?raw=true)

## Visualisasi Kasus COVID-19 di ASEAN

Untuk visualisasi kali ini menggunakan seaborn lineplot untuk menampilkan perbandingan kasus di lima negara ASEAN mulai per 1 Maret 2020. 

Menggunakan keyword argument data yaitu df_covid_denormalized_asean_march_onward, x yaitu index data frame df_covid_denormalized_asean_march_onward, y yaitu kolom confirmed_cases, dan hue yaitu kolom country_name.

![alt text](https://github.com/muhammadrafi18/Project_Analisis_Data_COVID19_di_Dunia_ASEAN/blob/main/Slide2.JPG?raw=true)
