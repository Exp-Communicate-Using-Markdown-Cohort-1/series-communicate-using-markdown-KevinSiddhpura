# This is a test header for `H1`
## This is a test header for `H2`
###### This is a test header for `H6`

![Image of Yaktocat](https://cdn.discordapp.com/attachments/1041951848107614229/1287776953557848095/OMEN.jpg?ex=66f2c73f&is=66f175bf&hm=68ef62c7edab1df1b6b78be772dd757f4dcf6903166b4a50abfd367ba5f9da5a&)

```ts
function addNumbers(input: string) {
    const numbers = input.split(',').map(n => parseInt(n));
    if (!numbers.length) {
        throw new Error('No numbers provided, make sure the input is a string of numbers separated by commas');
    }

    return numbers.reduce((total, n) => total + n);
}
```

- [x] I want to die
- [x] Sometimes it's like going through hell
- [ ] Life is complete 😃