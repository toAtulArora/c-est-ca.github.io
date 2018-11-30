---
layout: persp
title: "Large Number"
categories: perspective
author: "Atul Singh Arora and Bharti Yadav"
meta: "Perspective"
---

What is the largest number you can think of? We may start with one, two, three and so on. We may be tempted to say that perhaps a billion billion? But then there's always a billion billion plus one. It is not too hard to see that regardless of which number we claim is the largest, we can always add one to it and make it even larger. So there doesn't exist any *largest* number. The question is ill-posed. 

पार्थ — सबसे बड़ा अंक क्या है, माधव?  
माधव — हम एक, दो, तीन से सोचना शुरु कर सकते है। इस हिसाब से हम सोच सकते है शायद करोड़ करोड़?  
पार्थ — हे माधव, परंतु हम हमेशा करोड़ करोड़ में एक जोड़ सकते हैं। तो इस तर्क के अनुसार किसी भी सोची गई सबसे बड़ी संख्या में हम एक जोड़कर उससे भी बड़ी संख्या बना सकते हैं। तो मेरा प्रश्न गलत है क्या?

Alright, fair enough, but let us anyway denote by $$N_0​$$ the number of numbers. Yes, we just agreed upon the fact that this can't be a number, at least not in the sense we are familiar with, but can we still ask the following: Is there a number which is even larger than this? To do this, we need to come up with a way of thinking about how to compare this strange number $$N_0​$$ with other numbers of its type.

माधव — नहीं पार्थ! मान लो कि सारे अंकों को हमने एक टोकरे में डाल दिया। टोकरे में रखी चीज़ों की संख्या को *अ*  से संबोधित करते हैं। तुम्हारे तर्क के अनुसार यह तो तय है कि *अ*  एक साधारण संख्या नहीं हो सकती। लेकिन क्या कोई ऐसी संख्या है जो *अ*  से भी बड़ी हो?  
पार्थ — पर हे माधव, मेरे छोटे नैन इन विशाल एवं विचित्र अंकों की तुलना कैसे करेंगे?  

Let us first try to understand how $$N_0$$ plus one can possibly stay $$N_0$$ otherwise its title of being the largest number would already be in jeopardy. Consider a hotel with infinite (or in our notation $$N_0$$) floors. Let each floor be completely occupied by guests. Imagine that it is a grand luxury hotel and that each floor has just one guest. So now the number of guests equals the number of floors. Alright. Imagine a new guest arrives. The Hotel is completely full. And yet, we can accommodate the new guest. How? Well, we move each guest at a given floor to the floor above. This way the ground floor becomes available while all the previous guests are still inside the hotel! Once the new guest takes her place in the ground floor we have again reached the configuration where there're infinite floors and each floor has one guest. This number earlier was $$N_0$$ and now it must be $$N_0$$ plus one. But since the configuration of the hotels is the same, we are forced to conclude that $$N_0$$ must be the same as $$N_0$$ plus one. Insane right? So what's going on here? Well, this is the reason why infinities are hard to deal with. Adding (or subtracting) finite numbers to (or from) $$N_0$$ will leave $$N_0$$ unchanged. Take a moment to appreciate what just happened. When you're convinced read on to realise that the crazy has just begun.

माधव — प्रिय पार्थ, तुम्हारा संदेह ही तुम्हे उत्तर तक पहुंचाएगा। तुम्हारे प्रश्न का उत्तर प्रश्न से ही मिलेगा। बताओ ऐसा कैसे हो सकता है कि *अ*  जमा एक *अ*  के ही बराबर हो?   
पार्थ —  यह तो एक कठिन प्रश्न है। मैं अपने भवन की उपमा लेकर सोचना शुरु कर सकता हूं। यदि मेरे भवन की ऊँचाई अनन्त है, और उसकी हर एक मंज़िल पर एक मेहमान है तो मेहमानों की संख्या को मैं एक अंक से संबोधित कर सकता हूं। इस प्रकार, मेरे भवन में रहने वाले मेहमानों की संख्या *अ*  के बराबर हो जाएगी। अब सवाल यह है कि यदि एक नया मेहमान आए तो उसको कहाँ ठहराएंगे? इससे मेहमानों की गिनती प्रभावित नहीं होगी?   
माधव — अति उत्तम पार्थ। पुराने सभी मेहमानों के रहते हुए, नए मेहमान को स्थान देने के लिए हर एक पुराने मेहमान को उनकी वर्तमान मंज़िल से एक ऊपर वाली मंज़िल पर भिजवादें। इस प्रकार पुराने मेहमानों को प्रभावित बिना किए नए मेहमान के लिए तल मंज़िल खाली हो जाएगी।    
पार्थ — परंतु फिर तो भवन दोबारा अपनी पुरानी स्थिती में ही पहुंच गया क्योंकि हर मंज़िल पर एक मेहमान है। इसका अर्थ तो यह हुआ कि यद्यपि हमने अ में एक जोड़ा, परिणाम तो अ ही रहा! आप धन्य हैं माधव!   
(पांच मिनट के विस्मय के बाद)    
परन्तु माधव, इससे मेरे प्रश्न का उत्तर तो मिला नहीं, मैं ऐसे अंकों की तुलना कैसे कर सकता हूँ? 

We now return to the question of comparing numbers like $$N_0$$. It will be useful to think of these numbers as describing the number of constituents making up some object. For concreteness, consider the set of odd numbers $$1,3,5,7\dots$$ and let $$N'_0$$ denote the number of elements in this set similar to how $$N_0$$ was the number of elements in the set $$1,2,3\dots $$. One way of comparing the two numbers could be to compare the sizes of the associated sets. If we can show that for each element in the first set there is exactly one element in the other set then we can say without any doubt that the sets are of equal size and thereby conclude that the numbers associated are equal. Else whichever set has more elements, we can declare the associated number to be larger. Reasonable? Now it is evident that we removed half the elements from the set $$1,2,3,4\dots$$ to obtain $$1,3,5,7\dots$$ so the number $$N_0$$  should be greater than $$N'_0$$. Right? Sure? What if we map $$1\to 1$$, $$2\to 3$$, $$3\to 5$$, $$4\to 7$$ and in general $$n\to 2n-1$$? We have obtained a one to one map between the elements of the first set and the elements of the second set. Thus by our accepted definition the two sets have the same size even though we created the second set by removing half the elements from the first! You were warned, infinities are crazy. We have thus reached the conclusion that $$N_0=N'_0$$. By a similar argument one can show that the set $$ \dots, -3,-2,-1,0,1,2,3,\dots $$ is just as large as the set $$1,2,3\dots$$ .  The foolhardy among us still dare to ask if there can be a number larger than $$N_0$$? Answer: Yes! The number of points in a line segment. If you can prove this independently, you're a mathematician of the first class. The rest of us mortals can consider reading the second part of this article.

माधव — प्रिय पार्थ, अब मैं तुम्हारे ही तर्क का प्रयोग करता हूं। तुमने *अ*  पर चर्चा करने के लिए मेहमानों की संख्या का सहारा लिया था। मौलिक रूप से तुमने सोचा कि एक समूह में कितने सदस्य हैं। स्पष्टता के लिए विषम संख्याओं के समूह $$\{1,3,5,7\dots\}$$ पर ध्यान देते हैं और इस समूह के नाप को *आ*  से संबोधित करते हैं। यह ठीक वैसे ही है जिस प्रकार तुमने मौलिक रूप से $$\{1,2,3\dots \}$$ के नाप को *अ*  से संबोधित किया था। तो अब तुम्हारे अनुसार, इन समूहों की भाषा में, *अ*  और *आ*  जैसे अंकों की तुलना कैसे हो सकती है?
(इसके बाद माधव पार्थ को अपनी दृष्टि देते हैं)   
पार्थ — माधव, एक सरल तरीका तो यह हो सकता है कि हम एक नियम स्थापित करें जिससे हम हर पहले समूह के सदस्य को दूसरे समूह के ठीक एक सदस्य से जोड़ें। हम निश्चित करते हैं कि हर सदस्य का प्रयोग अधिकतम एक बार हो। यदि हमें ऐसा नियम मिल जाता है और दूसरे समूह का कोई सदस्य शेष नहीं रहता तो हम पक्का यह कह सकते हैं कि दोनो समूहों का नाप एक है। इसका अर्थ यह है कि दोनों संथ्याएँ जो इन समूहों से संबंधित थीं, वे बराबर हैं।   
माधव — अति श्रेष्ट वत्स! लेकिन हमारे उदाहरण में तो यह स्पष्ट है कि $$\{ 1,3,5,7 \dots \}$$ से $$\{ 1,2,3 \dots  \}$$ छोटा है क्योंकि दूसरे समूह से आधे अंकों को तो निकाल दिया पहला समूह बनाने के लिए। सहमत?    
पार्थ — आवश्य माधव, यह तो प्रत्यक्ष है।   
माधव — (प्रेम से हँसते हुए) तो प्रिय पार्थ यह बताओ कि यदि मेरा नियम है *क*  को *2क — 1* पर भेजना, जैसे $$1\to 1,$$ $$2\to 3,$$ $$3\to 5,$$ $$4\to 7, \dots $$ तो तुम्हारे तर्क के अनुसार तो दोनो समूह $$\{ 1, 2 ,3 \dots \}$$ एवं $$\{ 1,3,5,7 \dots  \}$$ का नाप एक नहीं हो गया?  क्योंकि पहले समूह के हर एक सदस्य के साथ दूसरे समूह का ठीक एक सदस्य संबंधित हो गया।    
पार्थ — विचित्र, माधव! तो आधे अंक निकालने के बाद भी समूह का नाप नहीं बदला।?   
(पांच मिनट विस्मयविभूत होने के बाद)   
तो मतलब *अ*  और *आ*  बराबर हैं! वाह माधव, मैं धन्य हुआ।   
पर हे माधव अब तो मैं तुलना करने की विधि सीख गया हूं। अब मुझे ऐसी संख्या बताएं जो *अ*  से भी बड़ी हो।    
माधव — एक रेखा खंड में उपस्थित बिंदुओं की संख्या।  
इस कथन को सिद्ध करने के लिए कठोर तपस्या की आवश्यकता होगी वत्स। है साहस?   
(आगे जानने के लिए अगला अध्याय पढ़ें)

 