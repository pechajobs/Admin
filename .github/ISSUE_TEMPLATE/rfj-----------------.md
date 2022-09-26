---
name: RFJ བོད་ཨིན་ཤན་སྦྱར།
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

# Request for job ལས་ཀའི་སྙན་ཞུ། 
All work on BDRC is done through Requests for Job (RFJs). This has two benefits: The requester has to 1) think about whether the requested work is necessary and 2) describe the requested work in detail. Together with Requests for Comments (RFCs), RFJs ensure that developers only do essential work. They also prevent misunderstandings that lead to abandoning incorrect code and having to change direction midway through a project. Thus RFJs and RFCs lead to less lost time, more productivity, and more successful outcomes.
ནང་བསྟན་དཔེ་ཚོགས་ལྟེ་གནས་ཀྱི་ལས་གཞི་ཚང་མ་ལས་ཀའི་སྙན་ཞུ་(RFJ)གཞིར་བཞག་ནས་བྱེད་དགོས། རྒྱུ་མཚན་ནི་གཅིག་ནས་ལས་གཞི་ངེས་པར་སྒྲུབ་དགོས་མིན་དང་། གཉིས་ནས་ལས་ཀའི་སྐོར་གྱི་གནས་ཚུལ་ཆ་ཚང་ཤེས་ཐུབ། ལས་ཀའི་སྙན་ཞུ་(RFJs)དང་ལས་ཀའི་འཆར་གཞི་(RFCs)འདི་གཉིས་བརྒྱུད་ནས་ལས་ཀ་བྱེད་མཁན་གྱི་ངེས་པར་སྒྲུབ་དགོས་པའི་ལས་ཀ་གང་ཡིན་ཤེས་པ་དང་། མ་ཟད་གོ་ནོར་བྱུང་ནས་ལས་ཀ་འཚམས་འཇོག་བྱེད་པ་སོགས་མི་བྱུང་བར་ཕན་ཐོགས་ཆེན་པོ་ཡོད། བྱས་ཙང་ལས་ཀའི་སྙན་ཞུ་(RFJs)དང་ལས་ཀའི་འཆར་གཞི་(RFCs)གཉིས་ཀྱི་དུས་ཚོད་འཕྲོ་བརླགས་སུ་མི་འགྲོ་བ་དང་ལས་ཀའི་གྲུབ་འབྲས་ཡག་པོ་ཞིག་ཡོང་བར་བྱེད་པ་ཡིན།

The benefit for developers is this. Since the requester and commenter have to come to an agree
Once the owner of the work provides a RFC and the requester and owner agree to the terms and definitions, the owner has the freedom to complete the work in whatever way they want. Since the developer understands the reasoning behind the RFJ, the conceptual framework, and what is to be done, it ensures that any decision they make is well informed.
ལས་ཀ་བྱེད་མཁན་ལ་མཚོན་ན་ཁེ་ཕན་ཧ་ཅང་ཆེན་པོ་ཡོད། རྒྱུ་མཚན་ནི་ལས་གཞི་དེ་ནི་ལས་ཀའི་སྙན་ཞུ་འབུལ་མཁན་དང་ལས་འཆར་བཟོ་མཁན་གཉིས་ཀྱི་མོས་མཐུན་བྱས་པ་ཞིག་ཡིན། སྐབས་འདིར་ལས་འཆར་ལག་བསྟར་བྱེད་མཁན་དང་ལས་ཀའི་སྙན་ཞུ་འབུལ་མཁན་གཉིས་གྱིས་ལས་གཞིའི་ནང་དོན་ཆད་ལྷག་མེད་པར་རྟོགས་པར་བྱས་རྗེས་གཏན་འབེབས་བྱས་པ་དང་། ལས་འཆར་ལག་བསྟར་བྱེད་མཁན་ནས་ལས་ཀའི་གོ་རིམ་དང་དུས་ཡུན་སོགས་ལས་ཀའི་སྙན་ཞུའི་ནང་དོན་ཁག་གསལ་པོ་ཤེས་པས་ལས་ཀ་བྱེད་སྟངས་དང་དུས་ཡུན་སོགས་རང་འདོད་ལྟར་སྒྲུབ་ཆོག

ALL FIELDS ARE REQUIRED འོག་གི་དོན་ཚན་རེ་རེ་བཞིན་ཆད་ལྷག་མེད་པར་འགེངས་དགོས།

## Preliminary Questions དྲི་བ་ཁག
Check Yes or No ཡོད་མེད་གཉིས་ལས་གང་རུང་གཅིག་འདེམས།

1. Is this proposed work really necessary?
ལས་ཀ་འདི་གལ་ཆེན་པོ་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

2. Is it more important than other work we could be doing? 
ང་ཚོས་ལས་བཞིན་པའི་ལས་ཀ་གཞན་པ་ལས་གལ་ཆེ་བ་རེད་པས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

 3. Will it take more than four hours? 
ལས་འཆར་འདི་ལས་ཚར་བར་ཆུ་ཚོད་བཞི་ལས་མང་བ་དགོས་ཀྱི་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

4. Does it focus on a single part of the system?
གནད་དོན་གཅིག་གིས་སྐོར་ལ་བྱེད་ཡ་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

5. If it consists of several small tasks bundled together, do all the tasks focus on a single part of the system? 
གལ་སྲིད་ལས་འཆར་འདི་ལས་གཞི་ཆུང་བ་འགའ་ལས་མཉམ་དུ་གྲུབ་པ་ཡིན་ན། ལས་གཞི་ཆུང་བ་ཚང་མ་གནད་དོན་གཅིག་སྐོར་ལ་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

6. Does this request either build something new or extend something that already exists but not mix the two? 
ལས་འཆར་འདི་ལས་རིམ་ཁག་གསར་གཏོད་བྱེད་དགོས་པའམ་ཡང་ན་སྔར་ཡོད་སྟེང་ལ་ཁ་གསབ་བྱེད་དགོས་པ་ལས་གཉིས་ཀ་མཉམ་བསྲེས་བྱས་པ་ཞིག་མ་རེད་བ།
- [ ] Yes རེད།
- [ ] No མ་རེད།

7. Would this work contribute to the mission of BDRC? 
ནང་བསྟན་དཔེ་ཚོགས་ལྟེ་གནས་ཀྱི་དམིགས་ཡུལ་དང་མཐུན་པ་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

8. Could it be done without having a negative effect on other parts of BDRC? 
ནང་བསྟན་དཔེ་ཚོགས་ལྟེ་གནས་ཀྱི་ལས་གཞི་གཞན་པ་གནོད་སྐྱོན་མ་ཐེབས་པར་བྱེད་ཐུབ་པ་ཞིག་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

9. Does it provide more business value than alternative solutions? 
ཐབས་ལམ་གཞན་ལས་རིན་ཐང་ཆེ་བ་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

10. Does it take less effort than alternative solutions? 
ཐབས་ལམ་གཞན་ལས་བྱེད་བདེ་པོ་དང་ལས་སླ་པོ་རེད་འདུག་གས།
- [ ] Yes རེད།
- [ ] No མ་རེད།

If you checked “yes” for all answers, continue to the main section. 
གལ་སྲིད་གོང་གི་དྲི་བའི་ལན་ཚང་མ་"རེད"ཡིན་ན་མུ་མཐུད་དུ་འོག་གི་སྡེ་ཚན་ཁག་ལྟ་རོགས་གནང་།

## 1. Summary སྙིང་བསྡུས།
Provide an overview of what is being introduced, added, changed, or deleted.  
ནང་དོན་་གསར་བ་ཁ་གསབ། བརྗེ་འགྱུར།  སུབ་པ་སོགས་གང་བྱས་ཡོད་མེད་སྐོར་ཀྱི་སྙིང་དོན་མཁོ་སྤྲོད་བྱེད་རོགས།

## 2. Justification རྒྱུ་མཚན།
### Motivation ཀུན་སློང་།
Why are you making this RFJ? 
ལས་ཀའི་སྙན་ཞུ་འདི་བཟོ་དགོས་དོན་གང་ཡིན་ནམ། 

### Differentiation ཁྱད་པར།
How is your proposed work different from what we already have?
ལས་གཞི་འདི་སྔར་ཡོད་ཀྱི་ལས་འཆར་གཉིས་ཀྱི་བར་ལ་ཁྱད་པར་ག་རེ་ཡོད།

### Drawbacks ཞན་ཆ།
What are the drawbacks of this work, if any?
ལས་འཆར་འདི་ལ་སྐྱོན་ཆ་འདྲ་ཨེ་ཡོད་དམ།

### Alternatives ཐབས་ལམ་གཞན།
What are some alternatives and why shouldn’t we use them instead?
ཐབས་ལམ་གཞན་པ་འདྲ་ཡོད་དམ། ཡོད་ན་ག་རེ་བྱས་ནས་བེད་སྤྱོད་བྱེད་ཀྱི་མེད།

## 3. Description འགྲེལ་བཤད།
### Summary སྙིང་བསྡུས།
Paste your answer from above གོང་ནས་བཤུས་ཏེ་འཇོག་རོགས།

### Owner བདག་པོ།
Who is the owner of this request?
ལས་ཀའི་སྙན་ཞུ་རྒྱག་མཁན་སུ་རེད།

### Type རིགས།
Is this a new request or an extension request?
ལས་ཀའི་སྙན་ཞུ་འདི་གསར་པ་རེད་དམ་ཡང་ན་སྔར་ཡོད་སྟེང་ཁ་སྣོན་བྱས་པ་ཞིག་རེད་དམ།

### Key definitions དོན་གནད་གཙོ་བོ་ཁག
Define any new or important concepts in the summary or conceptual design section.
ལས་ཀའི་སྙན་ཞུ་དང་འབྲེལ་བའི་གཞུང་ལུགས་སམ་རྣམ་བཞག་སོགས་དོན་གནད་ཁག་འབྲི་རོགས་གནང་།

### Conceptual design ལས་ཀའི་སྙིང་དོན་རི་མོ།
Provide a detailed, well-structured conceptual outline of the contents of this work.
ལས་ཀའི་སྙིང་དོན་ཁག་མཚོན་པའི་རི་མོ་སྟབས་བདེ་ཞིག་འབྲི་རོགས།

### Results གྲུབ་འབྲས།
What will the results of this RFJ be for users?
ལས་འཆར་འདིའི་བརྒྱུད་ནས་སྤྱོད་པ་པོ་རྣམས་ལ་ཕན་ཐོགས་ག་རེ་ཡོད་རེད།

### New data གནས་ཚུལ་ལམ་དངོས་རིག་གསར་བ།
Describe any new data artifacts that will result from this work.
ལས་གཞི་འདི་ལ་བརྟེན་ནས་གནས་ཚུལ་ལམ་དངོས་རིག་གསར་བ་ག་རེ་བྱུང་གི་ཡོད་མེད་ཀྱི་སྐོར་ལ་བྲིས།

### Sample messages འཕྲིན་ཐུང་ངམ་བརྡ་ལན་དཔེ་མཚོན།
Provide sample messages for any new messages the system will display as a result of this work.
ལས་གཞི་འདི་ལ་བརྟེན་ནས་བྱུང་བའི་འཕྲིན་ཐུང་ངམ་བརྡ་ལན་གསར་པའི་དཔེ་མཚོན་འདིར་འགོད་རོགས།

### Adoption window དུས་ཡུན།
When do you expect this work to be finished? 
ལས་འཆར་འདི་ག་དུས་ཚར་དུ་འཇུག་རྩིས་ཡོད།
