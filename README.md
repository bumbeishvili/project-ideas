# Project Ideas List

1. [Home Aggregator](#1-home-aggregator)

1. [Vacancies Aggregator](#2-vacancies-aggregator)

1. [Instant Data Explorer](#3-instant-data-explorer)

1. [Names Trend Explorer](#4-names-trend-explorer)

1. [When should we buy & rent place](#5-when-should-we-buyrent-place)

1. [From which region are you](#6-from-which-region-are-you)

1. [Loan Manager](#6-loan-manager)

1. [Cheaper currency exchanger](#7-cheaper-currency-exchanger) 

1. [Better js group by](#8-group-by)

1. [Which animal do I look like?](#9-which-animal-do-i-look-like)

1. [Dunstan Baby Language Detection](#10-dunstan-baby-language-detection)

1. [CarBNB]

1. [Parkin spaces](#12-parking-spaces)



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




## 7. Cheaper currency exchanger
**Problem**

ძირითადად ანგარიში თანხას ინტერნეტ ბანკში ვინახავთ ხოლმე და ხშირად არის სიტუაციები როცა ვალუტის გადაცვლა გვჭირდება. თუმცა ბანკები ბლუმბერგის კურსისგან განსხვავებულ ძალიან დიდ კურსით გვთავაზობენ ხოლმე კონვერტაციას. 
ვალუტის გადამცვლელ პუნქტები კი გვთავაზობენ უფრო შეღავათიან ფასებში, თუმცა დიდი დროითი დანახარჯი ახლავს და ასევე რისკია ნაღდი ფულის ტარება

**Solution**

სისტემა, რომელიც საშუალებას მისცემს ორ ადამიანს რომ ერთმანეთში შეათანხმოს თანხა და კურსი რითაც გადაცვლიან ვალუტას. შეთანხმების შემდეგ, ამ ადამიანებმა უნდა გადმორიცხონ შესაბამისი თანხები პლატფორმის ანგარიშზე და როცა სისტემა ნახავს რომ ორივე ადამიანმა გადმორიცხა, შემდეგ მოახდენს სხვა ვალუტის გადარიცხვას ამ ადამიანების ანგარიშზე


**Alternatives**      
არ აქვს ალტერნატივა

**Technical**
* ვებ აპლიკაცია რომელიც ორი ადამიანის ინტერაქციის მენეჯმენტს გააკეთებს 
* ავტომატური გადარიცხვის მოდული რომელიც თანხას გადაურიცხავს ამ ადამიანებს, ასევე ბალანსი რომ უჩანდეთ
* ნდობის მოპოვება 

**Revenue**
* ბანკებს თუ აქვთ 3 თეთრის განსხვავებული კურსი, ვალუტის გადამცვლელ პუნქტებს თუ აქვთ 0.6 თეთრით განსხვავებული კურსი. ჩვენ გვექნება 0.2 თეთრის განსხვავებული კურსი (რაც 1000 ლარზე 2 ლარს, ხოლო მილიონ ლარზე 2000 ლარის შემოსავალს მოგვცემს)



## 8. Group by
**Problem**

ჯავასკრიპტის გარემოში მუშაობისას ხშირად გვჭირდება კოლექციებზე სხვადასხვა სახის დაგრუპვა

**Solution**

მოდული რომელიც ამ პრობლემას გადაჭრის  - https://beta.observablehq.com/@bumbeishvili/group


**Alternatives**      
lodash, d3-group, d3-nest

**Technical**
* npm-ში პაბლიში და მაგალითები

**Revenue**
* Nah





## 9. Which animal do I look like
**Problem**

ხშირად , just for fun ადამიანებს აინტერესებთ, თავად ან სხვები რომელ ცხოველს ჰგავენ

**Solution**

სისტემა, რომელიც დასკრაპავს ფოტოებს (animal laughing უეჭველი tag) და ML-ის საშუალებით ატვირთული ფოტოებიდან, ყველაზე დაახლოებულ ფოტოს შეურჩევს


**Alternatives**      
AnimalCam მგონი, არ გამიტესტავს უბრალოდ

**Technical**
* სკრეპინგი და ლაბელები
* ML სურათების დატრენინგევა
* ML შეფასება ატვირთული ფოტოსი

**Revenue**
* Ads & Referrals

## 10. Dunstan Baby Language Detection
**Problem**

0-3 თვემდე ასაკის ბავშვების ერთადერთი კომუნიკაციის წყაროა ტირილი, თუმცა იმის გამო რომ რამდენიმე მიზეზი შეიძლება იყოს ამ ტირილის, რთულია იმის გაგება რა უნდა ბავშვს სინამდვილეში

**Solution**

Dunstan Baby Language-ის მიხედვით და machine learning-ის გამოყენებით, ბავშვის ტირილის მოსმენა და და იმის დადგენა თუ რა შეიძლება უნდოდეს ბავშვს (ძილი, ჭამა, მარტოსულია, რაღაც ტკივა და ა.შ. )


**Alternatives**      
ვერ ვიპოვე ვერაფერი, მხოლოდ წიგნები და ვიდეო გაკვეთილები

**Technical**

* ბავშვების ტირილები და-label-ება
* ML-ით ხმების კლასიფიკაცია
* მიკროფონზე მოსმენისას აპლიკაცია გეტყვის თუ რა უნდა ბავშვს დიდი ალბათობით


**Revenue**
* Paid membership or paid application


# 11 AIRBnb but for cars


# 12 Parking Spaces
**Problem**

თბილისში თითქმის ყველგან არის პარკინგის პრობლემა და რთულია როცა სადმე ხარ გასული მანქანის დასაყენებელი ადგილი მოძებნო

**Solution**

ამავე დროს ძალიან ბევრ ადგილას არის კერძო პარკინგი რომელიც ხშირად არის თავისუფალი. იგულისხმება კორპუსებში არსებული პარკინგები, რომელიც ვიღაცას ეკუთვნის. შესაძლებელია რომ ისე გაკეთდეს, ამ ადამიანებს ჰქონდეს ცენტრალიზებული პარკინგის გაქირავების და დაქირავების შესაძლებლობა. ვისაც საპარკინგე ადგილი ეკუთვნის,მაგრამ მოცემულ მომენტში არ ჭირდება, გააქირავოს მათზე ვისაც არ აქვს საპარკინგე ადგილი მაგრამ მოცემულ მომენტში სჭირდება.



**Alternatives**      
საქართველოში არ გამიგია მსგავსი რამე, უცხოეთში წესით უნდა მოფიქრებოდა ვინმეს აქამდე

**Technical**
* აპლიკაცია რომელიც მენეჯმენტს გაუწევს ამ სერვისს
* სავარაუდოდ ელექტრონული მოწყობილობა იქნება საჭირო რომელიც ამ აპლიკაციებს დაუკავშირდება და გახსნის ან დახურავს საპარკინგე სივრცეს. 


**Revenue**
* წილი ყოველი გაქირავებული ადგილიდან

