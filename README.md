# A/B_Testing

**1. Project Objectives & Overview**

**1.1. Business Problem**

The Library of Montana State University has a website that students use to find books and articles. This is what the homepage looks like:

<img width="749" alt="Screenshot 2023-04-20 at 16 03 15" src="https://user-images.githubusercontent.com/120720780/233407298-dc314f9a-38c0-4c5d-8f35-387cc6d241ce.png">

Below the library picture, there is a search bar and three big items: “Find”, “Request” and “Interact”. All three of them contain access to important information and services that the library prides itself in offering. However, the Website Analytics show that the “Interact” button has, ironically, almost no interactions:

<img width="744" alt="Screenshot 2023-04-20 at 16 03 58" src="https://user-images.githubusercontent.com/120720780/233407499-c41369f6-cd82-476a-9e17-c3612d5dd279.png">

During the sample period from April 3, 2013 – April 10, 2013, which included 10,819 visits to the library homepage, there was a large disparity among the three main content categories. The click-through rate for Find was 35%, Request was 6%, and Interact was 2%. This observation prompted a question: “Why are Interact clicks so low?” At this time, the content beneath Interact included links to Reference Services, Instruction Services, Subject Liaisons, Writing Center, About, Staff Directory, Library FAQ, Give to the Library, and Floor Maps. The library’s web committee surmised that introducing this category with the abstract term “Interact” added difficulty and confusion for users trying to navigate into the library website homepage. Four different category titles were then proposed as variations to be tested: Connect, Learn, Help, and Services.

**1.2 User Research** 

The team had conversations with a few students received this feedback:

Sophomore student:
- “I didn’t know that ‘About’ was under Interact.'”
- “Learn doesn’t work.”
- “Connect is too vague and too close to Interact.”
- “Services is more accurate. Help is stronger.”
- “Floor maps seem odd here.”
- In order of preferences of the choices, this student responded: Help, Services, Interact, Connect, Learn

Junior student:
- “I am not a native English speaker, so I look for strong words. I look for help, so Help is the best, then Services too.”

Senior student:
- “I’ve never felt the need to click on Interact. What am I interacting with? I guess the library?”
- “I never knew floor maps were there, but I have wondered before where certain rooms were.”
- “Help makes sense. When I’m in the library, and I think I need help, it would at least get me to click there to find out what sort of help there is.”
- “Services also works.”
- “Learn doesn’t really work. I just think, What am I learning? I think of reading a book or something.”
- “Connect is better than Interact, but neither are very good.”
- In order of preferences of the choices, this student responded: Help, Services, Connect, Interact, Learn

**1.3 A/B Test**

After the interviews with the users and some brainstorming, the website team settled on 4 different new versions to test against the original “Interact” button:
- Connect
- Learn
- Help
- Services

The hypotheses to be tested in the experiment are the following:
- Null Hypothesis: all versions have the same CTR.
- Alternative Hypothesis: there is a difference in the CTR for the different versions.

**2. Results**

**2.1. Questions**

**Would you include all suggested variants in the experiment (Connect, Learn, Help, Services)?**

No: Test Help and Services
**Remove Learn** as it was a common theme that students didn't like it: “Learn doesn’t work.”, “Learn doesn’t really work. I just think, What am I learning? I think of reading a book or something.” For softmore and senior students it was the last choice in order of preference. The junior student only liked help and service.
**Remove Connect** as it was another common theme students didn't like: “Connect is too vague and too close to Interact.”, “Connect is better than Interact, but neither are very good.” For softmore and senior students it was low in there order of preference. Again the junior student only liked help and service.

**What is the “business value” that performing this experiment would add within the broader strategy of the University?**

Unsure on the broader strategy of the university. But some ideas below:

Enhance the students experience:
- They will more easily be able to access what they might need
- They might find new resourses that will help them througout there time at university. E.g. “I never knew floor maps were there, but I have wondered before where certain rooms were.”
- Accessing these resources could improve the grades
- Students could have an easier time which could improve there overall experiance and views on the university - could increase interest with new students
- Potenitally reduce the amount of questions the libarian gets freeing there time

**Which main metric would you choose to measure the success of a variant and perform the experiment on?**

Click Through Rate - (Number of Clicks / Total Visits)*100

**How would you define the null and the alternative hypotheses?**

Null Hypothesis ( 𝐻0 ): click rate(version Interact) = click rate(version Help) = click rate(version Services)

Alternative Hypothesis ( 𝐻𝐴 ): at least one of the versions has a significantly better or worse click rate than the others

**What threshold for statistical significance would you set?**

alpha = 0.1

**2.2. Conclusion**

Since the p-value is smaller larger than alpha, we reject the Null Hypothesis.

![Screenshot 2023-04-20 at 16 15 45](https://user-images.githubusercontent.com/120720780/233410727-f901039b-a757-43a6-85cf-473fc5927e70.png)

**Connect** and **Services** have the strongest click through rate at **3.3%**

Combining this result with the user research stating more negetive views towards Connect: "“Connect is too vague and too close to Interact.” and “Connect is better than Interact, but neither are very good.”.

Also the order of preferences; softmore student Help, Services, Interact, Connect, Learn and
- Softmore Student: Help, Services, Interact, Connect, Learn
- Senior Student: Help, Services, Connect, Interact, Learn
- Also the junior student stated “I look for help, so Help is the best, then Services too.” so services being preferred.

In conclusion the word show be updated to **SERVICES**

