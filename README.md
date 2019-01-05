# Project Ideas List

[Home Aggregator](#1-home-aggregator)

[Vacancies Aggregator](#2-vacancies-aggregator)

[Instant Data Explorer](#3-instant-data-explorer)

[Names Trend Explorer](#4-names-trend-explorer)

[When should we buy & rent place](#5-when-should-we-buyrent-place)

[From which region are you](#6-from-which-region-are-you)

[Loan Manager](#6-loan-manager)

# Notice
### მოცემული იდეები შეუძლია გამოიყენოს ნებისმიერმა ადამიანმა, როგორც თავად სურს (MIT LICENSE)



# Idea's details

## 1. Home aggregator:

**Problem**  
სასურველი ბინის(გირა,ქირა,ყიდვა) ძებნაში დღეებს ვხარჯავთ ხოლმე, და სხვადასხვა ვებ-გვერდებზე ვცდილობთ შედეგების ნახვას

**Solution**   
ერთიანი API-ს მომზადება, რომელშიც მომხმარებლები სასურველი კონფიგურაციის ბინებს აარჩევენ (გამოიწერენ) და როგორც კი სისტემა ნახავს რომ რომელიმე ვებ-გვერდზე შესაბამისი კონფიგურაციის ბინა დაიდო,   ეგრევე შეატყობინებს მომხმარებელს 

**Alternatives**  
რამდენიმე ვებ-გვერდს თვითონ აქვს გამოწერის ფუნქცია და მოგდის შესაბამისი ბინები (ფასიანია რამდენიმე)

**Technical**
* Scraping
* Chatbot Integration

**Revenue**
* ფასიანი Subcribe მომხმარებლების მხრიდან (სავარაუდოდ უძრავი ქონების ბროკერები დაინტერესდებიან ძირითადად)
* მონაცემების გაქირავება დაინტერესებული მხარეებისთვის (როგორი ტიპის  ბინებზეა მოთხოვნა, და ასევე საშუალება რომ პირდაპირ შესთავაზოს მომხმარებელს ის პროდუქტი, რაც მას აინტერესებს )


## 2. Vacancies aggregator:

**Problem**  
სასურველი ვაკანსიის(ხელფასი,მოთხოვნები) ძებნაში დღეებს ვხარჯავთ ხოლმე, და სხვადასხვა ვებ-გვერდებზე ვცდილობთ შედეგების ნახვას

**Solution**   
ერთიანი API-ს მომზადება, რომელშიც მომხმარებლები სასურველი კონფიგურაციის ვაკანსიებს აარჩევენ (გამოიწერენ) და როგორც კი სისტემა ნახავს რომ რომელიმე ვებ-გვერდზე შესაბამისი კონფიგურაციის ვაკანსია დაიდო, ეგრევე შეატყობინებს მომხმარებელს 

**Alternatives**  
რამდენიმე ვებ-გვერდს თვითონ აქვს გამოწერის ფუნქცია  (თუმცა დასაზუსტებელია, ხელფასის და დარგის შეზღუდვა თუ შეგიძლია)

**Technical**
* Scraping
* Chatbot Integration

**Revenue**
* ფასიანი Subcribe მომხმარებლების მხრიდან (ცოტა ირონიულია რომ ფული იმან იხადოს ვინც დაუსაქმებელია, მაგრამ რომ დაფიქრდე, უნდა იხადოს, რადგან მცირე ფასად კარგ ინფორმაციას იღებს)
* მონაცემების გაქირავება დაინტერესებული მხარეებისთვის (როგორი ტიპის  ვაკანსიებზეა მოთხოვნა, და ასევე საშუალება რომ პირდაპირ შესთავაზოს მომხმარებელს ის პროდუქტი, რაც მას აინტერესებს, სავარაუდოდ რეკრუიტერებს დააინტერესებთ )

## 3. Instant Data Explorer

**Problem**  
საკმაოდ ხშირად გვაქვს მონაცემები სხვადასხვა ფორმით (json,tsv,csv,excell, google spreadsheet) , სხვადასხვა ლოკაციაზე (online, local ) და გვინდა სწრაფი insight-ების ნახვა

**Solution**  
შევქმნათ ვებ-გვერდი რომელიც წამოიღებს მონაცემებს მითითებული url-დან, ან drag & drop-ით ავტვირთავთ და dc.js-ის დახმარებით Bar Chart-ებს ააგებს თითოეული სვეტისთვის. 

უნდა გვქონდეს შესაძლებლობა მივუთითოთ დამაჯგუდებელი სვეტი და დაჯგუფების ტიპი (Avg,Sum) და აგრეთვე რომელი სვეტები უნდა დაიკიდოს 

**Alternatives**  
Tableau -  მაგრამ ძაან მოუხეშავია, ინსტალაცია ჭირდება, რაღაც დონეზე ცოდნაც გჭირდება

**Technical**
* Website

**Revenue**
* რეკლამები & რეფერალები


## 4. Names trend explorer

**Problem**   
ბევრს აინტერესებს თუ როგორ იცვლებოდა მისი სახელების რაოდენობა წლების განმავლობაში .   


**Solution**  
ავიღოთ სახელების ბაზა და მოვარგოთ ამ ვიზუალს - https://davidb.tech/project/names-line .  


**Alternatives**      
http://mashasadame.jumpstart.ge/ka . 

**Technical**
D3.js 

**Revenue**
* რეკლამები & რეფერალები


## 5. When should we buy,rent place?
**Problem**

ხშირად გვაინტერესებს თუ როდის არის საუკეთესო დრო ბინის საყიდლად & დასაქირავებლად & დასაგირავებლად

**Solution**

ინტერაქტიული ბლოგ პოსტი რომელიც შესაბამისი პარამეტრების საფუძველზე (კვადრატულობა, სართული , სტატუსი და ა.შ. ) გვაჩვენებს თუ როდის არის უმჯობესი ბინის შეძენა, ქირაობა ან გირაობა

**Alternatives**

\_(ツ)_/¯

**Technical**
* Scraping for data
* T-sne for substracting anomalies
* D3.js for visualuzations
* Observablehq for interactivity

**Revenue**
* რეკლამები & რეფერალები 


## 6. From which region are you
**Problem**

ბევრს აინტერესებს გვარის საფუძველზე საიდან არიან წარმოშობით

**Solution**

ინტერაქტიული საქართველოს რუკა 3D ბარებით და ტულტიპით, რომელიც გიჩვენებს რომელი რეგიონიდან და რამდენი შენი გვარის წარმომადგენელი ცხოვრობს
გარდა ამისა აგრეგაციებით შეიძლება იმის თქმ, რამდენი % იმერელია, რამდენი % თბილისელი, მეგრელი და ა.შ.


**Alternatives**      
http://mashasadame.jumpstart.ge/ka 

**Technical**

მონაცემების დაპატარავება, რომ კლიენტის მხარეს გადაიწეროს პირდაპირ

**Revenue**
* რეკლამები & რეფერალები



## 6. Loan Manager
**Problem**

ხშირად ვსესხულობთ ან ჩვენ თვითონ გავასესხებთ ხოლმე ფულს, ზოგს ნაწილს ვუბრუნებთ ან ნაწილს გვიბრუნებენ. ზოგს საერთოდ არ ვუბრუნებთ ან საერთოდ არ გვიბრუნებენ , მისი მენეჯმენტი/აღრიცხვა საკმაოდ რთულია და ძირითადად არ ხდება ხოლმე

**Solution**

ინტერაქტიური ვებსაიტი, ან ბლოგპოსტი, სადაც შენი სესხების შესახებ ფაილის მონაცემებს მიუთითებ და თვითონ გადაითვლის საჭირო სტატისტიკას

* ვის რა ვალი აქვს
* როდის რა სიტუაცია იყო (დროის სლაიდერი)
* ვინ როდის რა გაგისტუმრა
* ჯამური სესხი  
* სიმულაცია რა თანხა გვექნებოდა, რომ ეს თანხა დეპოზიტის სახით გვქონოდა ბანკში
* უმარტივესი ოპერაციები, ქართულ რეალობაზე მორგებული, მაგრამ შესაძლებლობა რომ უცხოურზეც იმუშაოს


**Alternatives**      
სამწუხაროდ, მარტივი რომ ყოფილიყო ვერაფერი ვიპოვე

**Technical**
* Observable backend

**Revenue**
* რეკლამები & რეფერალები





