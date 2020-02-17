# vowels
function vowels(str) {

    const vowels = "aeiou".split("");
    let count = 0;

    for (let i = 0; i < str.length; i++) {
        const char = str[i].toLowerCase();

        for (let j = 0; j < vowels.length; j++) {
            const vowel = vowels[j];
            if (char === vowel) {
                count++;
            }
        }
    }
    return count;

}
