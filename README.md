# Determine if a sentence is a pangram.

Determine if a sentence is a pangram. A pangram (Greek: παν γράμμα, pan gramma, "every letter") is a sentence using every letter of the alphabet at least once. The best known English pangram is "The quick brown fox jumps over the lazy dog."

The alphabet used is ASCII, and case insensitive, from 'a' to 'z' inclusively.

- sentence empty
  ""
  false

- pangram with only lower case
  the quick brown fox jumps over the lazy dog
  true

- missing character 'x'
  a quick movement of the enemy will jeopardize five gunboats
  false

- another missing character 'x'
  the quick brown fish jumps over the lazy dog
  false

- pangram with underscores
  the_quick_brown_fox_jumps_over_the_lazy_dog
  true

- pangram with numbers
  the 1 quick brown fox jumps over the 2 lazy dogs
  true

- missing letters replaced by numbers
  7h3 qu1ck brown fox jumps ov3r 7h3 lazy dog
  false

- pangram with mixed case and punctuation
  "Five quacking Zephyrs jolt my wax bed."
  true

- pangram with non ascii characters
  Victor jagt zwölf Boxkämpfer quer über den großen Sylter Deich.
  true
