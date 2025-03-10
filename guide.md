# Glean product writing style guide

These guidelines apply to text in U.S. English, our source language for writing in-product content. Defer to component-level style guidance when needed, and keep in mind that in-product language is internationalized according to specific locale standards and style.

## Active and passive voice
Use active voice in most cases, and use passive voice sparingly.

* With **active voice**, sentences are simpler, shorter, clearer, and more conversational
* With **passive voice**, you can soften and provide distance in select situations (e.g., notifications of a disabled account).

### Active voice
In an active sentence, it’s clear who’s doing what. The actor is the subject, and the subject of the sentence is doing something. 

✅ Cindy Chang resolved your comment

🚫 Your comment was resolved by Cindy Chang

### Passive voice
At times, active voice can come across too harshly. In these cases, use passive voice. This separates the actor from the action enough to soften a sentence. In a passive sentence, action is being taken upon the subject.

✅ Your payment has been declined

🚫 We declined your payment

## Contractions
Use contractions to sound more conversational and natural.

### Common contractions
Use commonly understood contractions to keep sentences from feeling rigid, robotic, or overly formal.

Some common contractions:

* What's
* We'll
* You'll
* You'reYou've
* We're
* They're
* Doesn't
* Didn't
* Isn't
* Aren't
* Can't

### ✅ Do:
* If you can't
* You aren't connected
* This app isn't available

### 🚫 Don't:
* If you cannot
* You are not connected
* This app is not available

### Contraction considerations
* Avoid contracting nouns with _is_, _does_, _has_, or _was_. This might make it look like the noun is possessive.
* Don’t use uncommon or old-fashioned contractions (e.g., _would’ve_ or _tweren't_).
* Don’t use colloquial and regional contractions (e.g., _ain't_, _y'all_, _yinz_).
* Be mindful of how many contractions you use in a sentence. Too many contractions can make things difficult to read.
* Avoid using contractions when dealing with legal concerns, payment processing, and account security. Casual isn’t always the best style when handling sensitive information.

### ✅ Do:
* Your account has been disabled
* Your document is ready to view

### 🚫 Don't:
* Y’alls account has been disabled
* Your document’s ready to view

## Pronouns
### Second person
Most of the time, use _second person_ (_you, your, you're_) to address users and services

### ✅ Do:
* You can switch to company knowledge mode at any time
* Your agents
  
### 🚫 Don't:
* I can switch to company knowledge mode at any time
* My agents

### First person singular, referring to the user
Use _first person singular_ (_me, I, my_) only in these situations:
* When we're presenting options for the user to select to respond directly
* When there are legal requirements to use first person to ask for consent (e.g. "I agree to these terms and conditions")

### ✅ Do:
* I agree to these terms of service
  
### 🚫 Don't:
* You agree to these terms of service

### First person plural, referring to Glean
The only time that Glean would refer to itself (ourself?) in first person (_me, I, my) is in chat experiences, where Assistant refers to itself to help the conversation flow more smoothly or naturally. Although we don't want to personify Asisstant too much, this helps frame the conversation mechanics and reinforces that it's a helpful robot.

### ✅ Do:
* Assistant: Would you like me to create a Google Doc for you?
  
### 🚫 Don't:
* Shall the assistant create a Google Doc doc for you?

### First person plural
Use _first person plural_ (_we, us_) sparingly, when it's appropriate to refer to the humans of Glean, the company, in situations like these: 
* Requesting feedback ("Help us improve this feature")
* Critial errors or mistakes where we may need the user's empathy ("We're sorry for the inconvenience")
* Celebratory or launch moments when we, as a team, are proud of a launch ("We're excited to show you what we've been working on...")

### Singular they
Except in high-confidence, highly personalized contexts, Glean doesn't need to know or assume the gender of our users. When we refer to users — unless specifically directed to use their pronoun — we use the singular "they".

We avoid the clunky "he/she" of male/female-inclusive references. Those are awkward and halting, and excludes folks outside of bindary gender identicfication.
