# Project-ideas




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


## 4. Names trend explorer

**Problem**   
ბევრს აინტერესებს თუ როგორ იცვლებოდა მისი სახელების რაოდენობა წლების განმავლობაში .   


**Solution**  
ავიღოთ სახელების ბაზა და მოვარგოთ ამ ვიზუალს - https://davidb.tech/project/names-line .  


**Alternatives**      
http://mashasadame.jumpstart.ge/ka . 

**Technical**
D3.js 


## When should we buy,rent place?
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
