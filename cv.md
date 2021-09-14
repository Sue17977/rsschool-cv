# **CV**

### KSENIA ZELENSKA 

## **CONTACTS**
- Location: Lviv
- Phones: 0970335527
- Email: sue.17977@gmail.com
- Skype: ksenia17977

## **SUMMARY**

## **WORKING EXPERIENCE**

#### *Chemist of the quality and control system | "First private brewery": February 2018  - June 2019*

Responsibilities: implementation of physical and chemical quality control of products, filling in technical documentation in the programs Word and Excel. Providing recommendations for improving production technology.

#### *B2B Sales Manager | GP Batteries Company:*

Responsibilities: filling in working documentation in Excel and C1 programs. Expanding the customer base and attracting new customers. Work with the existing customer base and expand the range in the outlet or chain of stores

#### *Sales Manager | JustSchool:*

Responsibilities: sale of English language courses by phone, help with connection to a trial lesson in English, consultation of clients on the terms of cooperation. Work with programs: amoCRM, Binotel, Oki-Toki, Teamviewer, Slack

#### *DTP specialist:*

Responsibilities: Professional formatting of the document, recreation of scanned documents, formatting after/before translation, editing documents, creating new brochures/magazines/books. Also I worked on the design of translated texts and formatting with Figma(for various applications and sites.)

## **TECH SKILLS:**
- HTML5, CSS, JS,  
- Microsoft Word
- Microsoft Power Point
- Microsoft Excel
- Adobe Illustrator
- Adobe InDesign
- Adobe Photoshop
- OCR Tools (Omni Page & ABBYY Fine Reader)
- Figma

## **SOFT SKILLS:** 
- Team player
- Self-direction
- Ability to communicate effectively
- Patience
- Attention to detail
- Critical thinking
- Adaptability

## **CODE EXAMPLES**
```
function revrot(str, sz) 
{
   ln = str.length;
   if(sz < 1 || !str || sz > ln) return "";

   const test = s => Array.prototype.reduce.call(s, (acc, val) => acc + Number(val) ** 3, 0) % 2 === 0;
   const reverse = s => s.split("").reverse().join("");
   const rotate = s => s.slice(1) + s.slice(0, 1);

   let arr = [];
   for(let i = 0; i < ln; i += sz) arr.push(i+sz <= ln ? str.slice(i, i+sz) : "")
   return arr.map(x => test(x) ? reverse(x) : rotate(x)).join("");
}

function myLanguages(results) {
     return Object.keys(results).filter(v=>results[v]>=60).sort((a,b)=>results[b]-results[a])
}

function tickets(peopleInLine){
let [c25,c50,c100] = [0,0,0];
  for(let v of peopleInLine) {
    if(v===25) c25++;
    if(v===50) {c50++; c25--;}
    if(v===100) {c25--; c50>0?c50--:c25-=2;}
    if(c25<0||c50<0) return 'NO'
  }
  return 'YES'
}

function revrot(str, sz) {
   ln = str.length;
   if(sz < 1 || !str || sz > ln) return "";

   const test = s => Array.prototype.reduce.call(s, (acc, val) => acc + Number(val) ** 3, 0) % 2 === 0;
   const reverse = s => s.split("").reverse().join("");
   const rotate = s => s.slice(1) + s.slice(0, 1);

   let arr = [];
   for(let i = 0; i < ln; i += sz) arr.push(i+sz <= ln ? str.slice(i, i+sz) : "")
   return arr.map(x => test(x) ? reverse(x) : rotate(x)).join("");
}
```

## **EDUCATION AND TRAININGS**
- Lokhvytsia College of Poltava Agrarian Academy, Chemist - Technologist, 2016
- Lviv Polytechnic, specialty - Public administration, 2018 
- Training course on the basics of programming, Logos it academy, 2020

## **FOREIGN LANGUAGES**
English – B1
