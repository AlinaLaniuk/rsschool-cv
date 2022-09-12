# Alina Laniuk

***

## Contacts

***

+ **Location**: Vilnius, Lithuania
+ **Phone**: +37060903937
+ **Email**: alinavoronina16@gmail.com
+ **GitHub**: AlinaLaniuk

***

## About me

***
I have 3 years of experience in journalism.

I have more than 2 years of experience in marketing.

I haven't experience on a real project in front-end yet. But I'm really want to get it.

My code is really bad now (also like my English). But I have a very important achievement: I`ve done this course already and it was the hardest learning in my life.

I'm sure that I can walk through all difficulties at learning way and in the future I will become a highly competent IT professional.

I'm strongly sure in my success because of my personal qualities:

+ *Self-motivated.* I really love programming and see good
opportunities in this area for personal growth.
+ *Hardworking.* I set ambitious goals and achieve them with hard work.
+ *Flexible.* The best demonstration of my ability to successfully adapt to change is my career way. I have a good experiense in two different area.

So my immediate goal at front-end way is graduate Rsschool successfully and became a Junior Software engiheer.
***

## Skills

***
| Skills |  HTML |  CSS  |   JS  |   TS  |  Git  | Webpack |
|:------:|:-----:|:-----:|:-----:|:-----:|:-----:|---------|
|  Level | Basic | Basic | Basic | Basic | Basic | Basic   |
***

## Code example

***

```TS
async getWordsInfo(group: number, page: number) {
    const userInfo = getAutentificationInfo();
    const wordsInfoForNotAutorizated = await (await fetch(`${API_URL}words?group=${group}&page=${page}`)).json();
    if (userInfo && isAuthorized && group === 6) {
      const wordsInfoForMyWordPage = await agregationAPI.getAllAgregations({ wordsPerPage: '4500', filter: JSON.stringify({ $and: [{ 'userWord.difficulty': 'hard', 'userWord.optional.isLearned': false }] }) });
      return wordsInfoForMyWordPage;
    }
    if (userInfo && isAuthorized) {
      const wordsInfoForAutorizated = await agregationAPI.getAllAgregations({ group: `${group}`, page: `${page}`, wordsPerPage: '20' });
      return wordsInfoForAutorizated;
    }
    return wordsInfoForNotAutorizated;
  }
```

## Experience

***
Haven't yet on a real project.
***

## Education

***

+ **University**: Belarusian National Technical University, marketing; Belarusian State University, journalism.
+ **Courses**: HTML Academy, RS2022Q1.

***

## Languages

***
Russian - native speaker.

English - B1.
