# Jerry's OCD Test

**Category:** Cryptography  
**Points:** 300  
**Author:** Antigravity  
**Flag:** cryptoSTORM{1two3four5six}  

## Description
Jerry was seen wandering around the **base**ment of the building for over **64** hours. He left behind a single encoded file and a cryptic warning written on the wall:

> "Whatever you decode is messy. Remember: the final flag is **OCD free**. Use your logic to fix it."

## Hints
- **Hint 1 (free):** The encoded file looks like it's using a very common "Base" encoding.
- **Hint 2 (10 points):** If you find something that looks almost like a perfect sequence but has a "messy" mistake at the end, try making the sequence perfect to satisfy the "OCD free" requirement and wrap it in the proper flag format.

## Files / Links
- [encoded_memo.txt](./OCD-Challenge/message.txt)

## Notes for Organiser
The Base64 in `message.txt` decodes to `cryptoSTORM{1two3four6six}`. The user must realize that `6six` follows a `1,2,3,4` pattern but breaks at the end. Following the "OCD free" clue, they must submit the perfect sequence: `cryptoSTORM{1two3four5six}`.
