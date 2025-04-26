# Easy - Cryptography - Hashcrack

## What I Learned

Understanding the character length of different hash types:
- MD5 = 32 characters
- SHA1 = 40 characters
- SHA256 = 64 characters

## Tools Used
- Hash Identifier: https://hashes.com/en/tools/hash_identifier
- MD5 Decoder: https://www.dcode.fr

## Step-by-Step Solution

### Step 1: Identify the Hash Type
Given a hashed string, I needed to determine its type.

![Hash to be identified](res/image.png)

### Step 2: Use Hash Identifier Tool
Using the hash identifier tool, I found that this is an MD5 hash.

![Hash identification result](res/image-1.png)

### Step 3: Decode the Hash
I used an online MD5 decoder to get the actual string.

![MD5 decoding result](res/image-2.png)

### Step 4: Repeat for Additional Hashes
Given another hashed string, I performed the same steps to identify and decode it.

![Second hash to decode](res/image-3.png)
![Hash identification for second hash](res/image-4.png)
![Decoding result for second hash](res/image-6.png)

### Step 5: Submit the Answer
After inputting the correct decoded string, the flag was printed out.

![Flag revealed](res/image-5.png)
