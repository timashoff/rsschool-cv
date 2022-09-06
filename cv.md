# Roman Timashev


## Contacts:
- **Saint Petersburg**  ✈️  **Bishkek, Kyrgyzstan** 
- +996 702 234 087
- timashoff@gmail.com
- [**GitHub**](https://github.com/timashoff)
- [**Twitter**](https://twitter.com/timashoff)
- [**Telegram**](https://t.me/timashoff)


## About me
Passionate about React.js and eager to learn Node.js    
I know how to make decisions and take responsibility for them   
Aiming to become a senior Full Stack developer and probably lead the team.    


## Skills 
- HTML
- CSS 
- JS
- Git
- React


## Code example:
Codewars Kata **Partition On**:

Description:
>_Write a function which partitions a list of items based on a given predicate.
After the partition function is run, the list should be of the form [ F, F, F, T, T, T ] where the Fs (resp. Ts) are items for which the predicate function returned false (resp. true).
NOTE: the partitioning should be stable; in other words: the ordering of the Fs (resp. Ts) should be preserved relative to each other.
For convenience and utility, the partition function should return the boundary index. In other words: the index of the first T value in items._

Code:
```javascript
function partitionOn(pred, items) {
  const [firstArray, secondArray] = items.reduce((acc, item) => {
    pred(item)? acc[1].push(item) : acc[0].push(item)
    return acc
  }, [[], []])

  items.splice(0, items.length, ...firstArray, ...secondArray)
  return firstArray.length
}
```


## Work experience 
Past entrepreneurial activity not related to the IT-industry


## Education
1. [**Learning How to Learn**](https://www.coursera.org/learn/learning-how-to-learn) on Coursera
1. [**The Modern JavaScript Tutorial**](https://javascript.info) by Ilya Kantor
1. [**HTML Academy**](https://htmlacademy.ru/profile/timashoff) workshop
2. [**React by Bogdan Stashchuk**](https://www.udemy.com/certificate/UC-3cdac213-c6a9-4234-9846-4f9743c3f63a/) on Udemy
3. [**JavaScript/Front-end 2022Q3**](https://rs.school/js/) RS school ( _in progress..._ )


## Language
**Russian**  -  Native   
**English**  -  CEFR A2+[^1] 

[^1]: I had language practice for a year when I lived in Hong Kong
