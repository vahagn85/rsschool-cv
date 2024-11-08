# Vahagn Ulikhanyan

## Contacts

**E-mail:** vahag85yan@gmail.com<br/>
**Telegram:** @vahagnulikh<br/>
**GitHub:** [vahagn85](https://github.com/vahagn85)

## About Me

I am a conscientious person who works hard and pays attention to details. I am flexible, quick to pick up new skills and eager to learn from others. I also have lots of ideas and enthusiasm.

## Skills

- HTML5, CSS3, SASS
- js, React, Next js
- Git/GitHub
- NPM, Webpack
- VS Code, WebStorm
- Adobe Photoshop, Illustrator, XD, Figma

### Code Example

```javascript
export default function promiseAll(iterable) {
  return new Promise((resolve, reject) => {
    const results = new Array(iterable.length);
    let unresolved = iterable.length;

    if (unresolved === 0) {
      resolve(results);
      return;
    }

    iterable.forEach(async (item, index) => {
      try {
        const value = await item;
        results[index] = value;
        unresolved -= 1;

        if (unresolved === 0) {
          resolve(results);
        }
      } catch (err) {
        reject(err);
      }
    });
  });
}
```

## Education

- **University:** YSU - Mathematics and Mechanic
- **Courses**:
  - [FreeCodeCamp](https://www.freecodecamp.org/)
  - [coursera](https://www.coursera.org/)
  - [codecademy](https://www.codecademy.com/)

## Languages

- Armenian - Native
- Russian - Advanced
- English - Intermediate
