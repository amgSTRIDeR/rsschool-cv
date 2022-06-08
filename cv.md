# Ovchinnikov Aleksei
![it's me](./assets/img/my-photo.jpg)
## Junior Frontend Developer
*********
## Contact information:
* **Phone:** *+995551176596*
* **Email:** *amgstrider@gmail.com*
* **Telegram:** *@amgSTRIDeR*
* **Discord:** STRIDeR(@amgSTRIDER) *STRIDeR#1707* 
* [Linkedln](https://www.linkedin.com/in/aleksei-ovchinnikov)

## About me

I have worked at hydro-electric power station more than for ten years as an Engineer. 
I have experience working with subordinates in stressful situations and situations requiring quick decisions, also I have good communication skills, rational thinking.

I decided to change my profession to a front-end developer, I'm ready for constant learning, advanced training, relocate. My current location is Georgia.

## Skills

+ **HTML** 
+ **CSS** 
+ **JS** - basic level
+ **Git**

## Code example

**Range Extraction** - A format for expressing an ordered list of integers is to use a comma separated list of either

* individual integers
* or a range of integers denoted by the starting integer separated from the end integer in the range by a dash, '-'. The range includes all integers in the interval including both endpoints. It is not considered a range unless it spans at least 3 numbers. For example "12,13,15-17"


Complete the solution so that it takes a list of integers in increasing order and returns a correctly formatted string in the range format.

```
function solution(list){
let answer = [];
  
  for (let i = 0; i < list.length; i++) {

      let k = i;

      while((((list[i] - list[i + 1]) === -1))) {
        i++;
      }
      
      if (k === i) {
        answer = answer + ',' + list[k];
      } else if (Math.abs(i - k) > 1) {
      answer = answer + ',' + list[k] + '-' + list[i];
      } else {
        answer = answer + ',' + list[k] + ',' + list[i];
      }
    }
    
  answer = answer.substring(1);
  return answer; 
}
```
## Work experience
[HTML, CSS work example](http://x96706sv.beget.tech/)

## Education 
* **Engineer on specialization - Hydro Power Stations** - *Siberian Federal University* (2010)
* **Frontend developer** - *Netology* (In progress)

## Languages

* **Russian** - native
* **English** - upper intermediate (IELTS - 8.5 8.0 6.5 6.5)
