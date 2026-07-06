# Agentic_AI_preparation_part_2
Part 1: How AI Knows Things

Part 1 ka main goal:
AI ko effectively use karne se pehle ye samajhna zaroori hai ke AI information kahan se laata hai aur kis basis par answer deta hai. Jab ye samajh aa jaye, to AI ki limitations aur strengths dono clear ho jati hain.

Concept 1: Novice vs Power User
Matlab

Zyada tar log AI ko Google Search ki tarah use karte hain: chhota sa question likha, answer liya aur khatam.

Lekin Power Users AI ko ek smart lekin naya colleague samajh kar use karte hain. Wo AI ko sirf question nahi dete, balki usse kaam karne ke liye poora brief dete hain. Isi wajah se unhein zyada accurate aur useful results milte hain.

Important Points
1. Novice User
Chhota prompt deta hai.
Context provide nahi karta.
Generic answer milta hai.

Example (Document):

"Which car should I buy?"

Result:
AI sirf kuch common car models suggest karega.

2. Power User

Power User AI ko sari relevant information deta hai, jaise:

Files
Documents
Quotes
Constraints
Apni requirements

Phir AI se analysis mangta hai.

Example (Document):
Car buy karte waqt insurance quotes, dealer quotes aur cost spreadsheet upload ki gayi. Saath hi commute aur family ki details di gayin. Is basis par AI ne detailed comparison aur recommendation di.

3. Same AI, Different Briefing = Different Answer

Document ka main point ye hai:

AI nahi badalta.
Badalta sirf briefing (context) hai.

Jitni achi briefing hogi, utna hi useful answer milega.

4. AI ko New Colleague ki Tarah Treat Karo

Document AI ko ek:

"Really smart fresh college graduate"

ke jaisa describe karta hai.

Matlab:

Intelligent hai.
Motivated hai.
Lekin tumhare baare mein kuch nahi janta.

Isliye jitni information usse doge, utna acha kaam karega.

Document ke Examples

Document mein ye contrasts diye gaye hain:

Buying a Car: Files upload karo aur trade-offs pucho.
Self Review: Project tracker, documents aur voice notes upload karke draft banao.
Business Idea: "Critique objectively" aur rubric do, sirf "Great idea?" mat pucho.
Blog Post: Seedha article mat likhwao. Pehle outline → critique → bullets → critique → phir final draft.
Summary
Novice sirf question puchta hai.
Power User AI ko complete context aur clear instructions deta hai.
Better prompts ka matlab fancy words nahi, better briefing hai.
AI ko hamesha ek smart but new colleague ki tarah brief karo.

""""Critique objectively""""
Bias ya tareef ki taraf jhukao ke baghair, sirf facts ki bunyaad par analysis karo.
Yani AI ko ye mat bolo:
"Meri idea achi hai na?"
Balki bolo:
"Is idea ko objectively analyze karo."

"""Rubric = Evaluation criteria ya check karne ke points.""""
Document mein business idea ke liye rubric ye tha:
Kya ye real problem solve karta hai?
Kya iski market hai?
Kya iska competitive advantage hai?
AI har point ko alag evaluate karta hai aur score de kar batata hai. Is se sirf tareef nahi, balki honest feedback milta hai.
Ek line mein yaad rakho:
Critique objectively = Bina bias ke facts ke basis par review karo.
Rubric = Wo criteria ya checklist jis ke basis par AI kisi cheez ko evaluate karta hai.

//////////////////////////////////////////////////////
# Concept 2: Pretrained Knowledge

## Concept ka Matlab

AI ne duniya ko dekh kar ya experience karke nahi seekha. Isne internet par mojood text (jaise books, Wikipedia, news articles, research papers, blogs, Reddit aur Quora) ko padh kar knowledge hasil ki hai. 

## Important Points

* AI ka knowledge reading par based hai, personal experience par nahi. 
* Jis topic par internet par zyada information ho, AI uska jawab zyada reliably de sakta hai. 
* Jis topic par internet par kam information ho, AI ka answer kam reliable ho sakta hai. 
* AI private information, knowledge cutoff ke baad ki information aur jo kabhi public internet par publish hi na hui ho, usay nahi jaanta. 
* Typos se AI aam tor par confuse nahi hota. 
* AI internet ki galat ya outdated information bhi seekh sakta hai, isliye important information ko primary source se verify karna chahiye. 

## Example ki Explanation

Document mein ek example diya gaya hai jahan AI se grandmother ke village ke ek regional folk game ke rules puche gaye. AI ne confidently rules bataye, lekin grandmother ne bataya ke woh zyada tar ghalat thay. Wajah ye thi ke us game ke baare mein internet par bohot kam information thi, isliye AI ne milte-julte games ki information ko mila kar answer diya. 

## Summary

AI internet par available text se seekhta hai. Common topics par zyada reliable hota hai, lekin rare, private aur recent information ke liye uske answers ko verify karna zaroori hai. 

**Ab se isi format mein saare concepts dunga — plain text, koi copy box nahi.**

/////////////////////////////////////////
# Concept 3: The 3 Retrieval Modes

## Concept ka Matlab

Jab tum AI se koi question pochte ho, modern AI tools 3 tareeqon mein se kisi ek tareeqe se answer dete hain:

1. **Pretrained Knowledge**
2. **Web Search**
3. **Deep Research**

Har mode ka apna use case, strength aur limitation hoti hai. 

---

## Important Points

* **Pretrained Mode:** Sab se fast hota hai. Common facts aur definitions ke liye best hai, lekin recent ya local information ke liye weak hai. 

* **Web Search:** AI live web pages search karta hai. Current news, recent regulations aur latest information ke liye useful hai.

* **Deep Research:** AI kai sources par research karke detailed report banata hai. Ye multi-dimensional aur in-depth topics ke liye use hota hai, lekin zyada time leta hai. 

* AI aksar khud decide karta hai ke kaunsa mode use karna hai, lekin **tumhare prompt ki wording** us decision ko steer kar sakti hai.

Yani tum apne prompt ke words se AI ko hint dete ho ke kaunsa retrieval mode use karna chahiye.

Document ke examples:

"Latest", "Current", "Today", "Recent" → AI ko Web Search ki taraf guide karte hain.
"Research", "Compare", "Analyze in depth", "Comprehensive report" → AI ko Deep Research ki taraf guide karte hain.

* Agar web search use ho, to AI kabhi kabhi purane ya inaccurate sources bhi use kar sakta hai. Document recommend karta hai ke source types specify karo aur zarurat ho to source ki exact quote bhi mango. 

---

## Example ki Explanation

Document mein 3 examples diye gaye hain:

* **Pretrained:** "Why do cats stare at walls?" — kyun ke ye common knowledge hai. 

* **Web Search:** Latest news ya recent regulation pocho to AI web search use karke current information la sakta hai.

* **Deep Research:** Local water quality ya permits jaisi detailed research ke liye AI kai sources check karke structured report tayar karta hai. 

---

## Summary

AI ke paas 3 retrieval modes hain: **Pretrained, Web Search aur Deep Research.** Kis mode ka use hoga, ye question ki nature aur prompt ki wording par depend karta hai. Har mode ko uske sahi use case ke liye istemal karna chahiye.
