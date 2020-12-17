
# Massachusetts Statement of Conditions

# docassemble-statementofconditions

A docassemble extension.

## Author

Jonathan T. Costello, JD Candidate Suffolk University Law School '22, jcostello2@su.suffolk.edu

## Disclaimer 

This is intended for demonstration only. It produces an example document and is for demonstration only. It should not be implemented into existing interviews without refinement detailed below. 

## Watch a demo [here](to-be-added)
Note: This video was made prior to most testing. Some of the pages have more information or instructions on them where users asked for it. The searching mechanism works the same as in this video. 

## Watch a technical explanation [here](https://drive.google.com/file/d/1X6kBxrgeTFffkUJgtmP66jYEPYKIMaSQ/view?usp=sharing)

## Project Biography

**TLDR**
    
My project is a tool to assist potential tenants in completing comprehensive “Statement of Conditions” when signing a rental agreement. The form itself is minimalist and therefor is often overlooked by renters, while abused by landlords who are looking to withhold security deposits. My goal was to create a usable form that could help eliminate this point of tension between tenants and landlord. Ultimately, my ambitious take on the project and limited coding skills were the true point of tension and resulted in a less robust tool than originally envisioned. Ideally, someone with a greater skillset will be able to launch from where I have left off and complete the tool as originally envisioned. 
    
**The Problem**

Scummy landlords, aren’t they the worst? When signing a lease agreement, every tenant is supposed to go through the rental space with the landlord and both are supposed to document and then sign a “Statement of Conditions” form. This form can be used when the tenant eventually moves out of the rental as a benchmark for establishing whether the tenant will recover their security deposit. 
	
Unfortunately, there is an inherent power imbalance between the landlord and renter. Renters are often young, low-income, immigrant, or elderly; while landlords are often wealthy and have made careers out of being property owners/managers. Most every tenant wants to, and believes they will, recover their security deposit when they move out. Most landlords want to keep the security deposit, its money to their bottom line and can be used to market the rental if there isn’t another renter lined up. 

This conflict can arise in many ways during the signing of a lease. But most of the ways can be generally summed up by landlords rushing or pressuring renters to sign incomplete statement of condition forms that do not comprehensively and accurately portray the status of the rental. 

**Key Stakeholders**
Renters, students, elderly, immigrants, landlords, realtors, property management, housing courts

**Intro to the Project**
Please see the Statement of Conditions presentation pptx for a breif summary and introduction to the project


**Research**

My researching of the problem comes largely from personal experience and discussing with industry experts. Prior to law school, I had a length career in real estate development, sales, and rentals. Boston is an especially lucrative real estate rental market with one-bedroom apartments renting for over $2,000/month. Currently, there is not universal solution for this problem. There are some pay-to-play apps that both landlord and renter can sign up for, sign into, and write their own version of events and upload photos. There are also some in-house programs operated by large real estate agencies and property management groups. Subscription based programs are not an effective solution when there is a large economic imbalance between parties. Likewise, real estate agencies and property management groups have a financial incentive to favor landlords. These do not present a fair, open, and equitable solution. I continued my research by reaching out to several realtors still in the industry. Those in Boston reported that they had not heard of any service or platform that offered what I was proposing. One even said their office never used Statement of Condition forms and would only use them upon request. Although my tool would only apply to the state of Massachusetts, I reached out to former professional peers in other states. Those practicing real estate in New York City had heard of the idea of a comprehensive online statement of conditions tool but had never seen it used nor had they heard of it as a free-to-use open-source tool. My real estate peers in Virginia likewise had no knowledge of any opensource statement of conditions tools. Internet research resulted no results either, beyond the subscription-based models. My research concluded that no open-source equitable tool for complete statement of conditions forms current exists. 

**Development**

**Ideation & Prototyping**

Using my industry knowledge and research, I began ideation on who this tool is for and how this tool should function. 

First, who is this tool for? This tool is for renters who may have a future dispute with their landlords over the condition of the rental. The renter needs several key things. First, the renter needs key descriptions of the areas of the rental. Second, (ideally) the renter should have photographs of the rental, both general photographs of each area but also focused photographs of anything that could be considered damage. Third, the renter needs to be informed of their rights protected by the MA Housing Code. Fourth, the renter needs to know how those rights can compel action from the landlord and what timeline the landlord has to restore. My original vision for the tool was that of a machine learning tool that could interpret user text input and correlate it with the MA Housing Code. The tool would then generate a comprehensive Statement of Conditions form that include not simply a statement of the current condition, but also an addendum with supporting photographic proof. On top of that, I set a stretch goal for myself of producing a secondary corresponding document that provided a mix-and-match selection of MA Housing Code violations, based on the user text input, and the timeline to cure to provide the renter ammunition to have any serious Housing Code issues promptly resolved either by the landlords or judicial relief.  

Next, how should this tool function. Generally, I work best when I can spatially visualize something. To do so, I used a combination of yellow legal pads, Sticky Notes, and Lucid Chart to map out my envisions interview. Ultimately, I needed generally cover the entire rental and cover room specific code items that could detrimentally affect the renter. I found this to be tremendously frustrating and time consuming. 
As discussed in class and with Prof. Colarruso, I struggled with mapping the interview flow. I attempted multiple different forms. Originally, I was trying to micro-manage every question and answer into the interview. Trying to work and rework my approach, I ended up with several dozen versions of how the interview could flow. However, after discussing with Professor, he calmed my anxieties and I selected one of the options that best reflected my coding ability matched with my goals. 
Ultimately, I came to a basic form where I envision the renter filling out the info about themselves and the landlord in the car, and then filling out the form as they progress through the rental. There are several key rooms and areas of focus that will be present in every rental: Kitchen, Bathroom, Bedroom, Water, Heat, Electricity, Ventilation, General Safety/Maintenance. This realization created a basic framework of how to approach the interview. 
(For reference, I have included both my Statement of Conditions Intro Pitch ppt, as well as one of my final versions of my interview flow chart)

**User Testing**

For testing I obviously tested the tool myself, however I also had too other individuals test the tool; one a renter and the other a Realtor who works for a property management company. 

They both had similar feedback. They both enjoyed the “Buzzfeed” style of Q&A. They both enjoyed the conversational tone and thought it helped make the tool seem more approachable. Neither were coding experienced but both had some real estate rental knowledge either from the buyer or seller side. 

When testing the project both ran into problems. My “landlord” tester found that when she used the tool, she stumbled into a dead end. She had answered the questions in a different way than I had imagined when writing the code, and therefor she received the blocks of questions in a different order. This resulted in a dead-end where she could not continue further. My “renter” tester found some of the language to be confusing and unapproachable. At one point my renter was confused by a question that seemed to ask for a question as a double-negative, and my renter was confused by several terms of art, from both law and real estate. 

The feedback from the “landlord” resulted in some changes to my code where the user could no longer enter and answer questions about the utilities until they had completed the physical rooms first. The feedback from the “renter” resulted in significant changes in language use and I shifted away from using the formal language I had been trained to use in my real estate careers and into a more conversational, colloquial tone. 


**The Product**
In it's current form the tool is short of its original goal but is functional for use. 

The tool will greatly assist renters and landlords equitably and efficiently resolve disputes over security deposits. The tool will provide an tenants the abilitys to create a comprehensive static image of the condition of the rental at lease, thereby reducing the about of tenant/landlord litigation. This will greatly expedite dispute resolution for attorneys representing tenants by providing a Q&A responses to MA Housing Code Issues, written descriptions, photographs and corresponding codes in one comprehensive document. Additionally, this will likely reduce the volume of cases brought to housing court if the cases can be resolved by comparing the comprehensive report to the current condition. Lastly, cases for unresolved Housing Code violations will be more efficiently resolved in housing court, the plaintiffs will be able to more efficiently submit claims because they will have a timetable for the landlord to cure, and the housing court will be presented with a written description of the violation, photos of the violation, the reference code, and a time table to cure in one pleading. 

The tool presents a much better option for tenants than the current status quo. Currently renters can be pressured, bulled, and mislead into not completing a statement of conditions, or signing an incomplete statement of conditions. This tool allows renters to shield themselves from potentially abusive landlords by relying on the system. By leaning on the system presented by the tool, the user can take their time and thoroughly document the current condition of the unit. 

The future of this tool and the rental market is bright. Real estate has been extremely resistant to technological innovation. Market forces(i.e., Multiple Listing Services are expensive subscription based services), industry resistance(i.e., Realtors do not want to be replaced by iPhones), and technologial illiterancy(i.e., older Realtors are slow to adapt to new technologies) are all factors to why real estate has been slow to grow with technology. This tool can function as a great starting point for modernization. Additionally, this tool is incredibly scalable. The tool would only need to be updated with applicable state codes to be used in every urban population center in the United States. 

**Self-Reflection & Next Steps** 

Reflecting on the term, I realize I have learned a tremendous amount this semester. I knew nothing about coding coming into this year, and now I have a rudimentary understanding of how much of it works and a *very* basic understanding of how to build some simple tools. Reflecting on my project, it is clear to me that 1) I was far too ambitious in my original goal for the project, and 2) there are several problems that may immerge in real world practice. 

Originally, I envisioned a machine learning tool that could interpret user text input and correlate that with the MA Housing Code and then generate a comprehensive Statement of Conditions form that include not simply a statement of the current condition, but also an addendum with supporting photographic proof. On top of that, I set a stretch goal for myself of producing a secondary corresponding document that provided a mix-and-match selection of MA Housing Code violations, based on the user text input, and the timeline to cure to provide the renter ammunition to have any serious Housing Code issues promptly resolved either by the landlords or judicial relief.  It became clear to me through prototyping and development that my vision of the tool greatly exceeded my skill as a novice, beginner, neophyte, amateur, introductory coder. The smart, elegant and egalitarian tool I envisioned was replaced by a far simpler, far clunkier tool that was within my skill range. Although functional, the tool is far from my original, far too ambitious, vision. 

The first problem and second problem are tied together: language. More than 15% of Massachusetts residents are not born in the United States and many are not native English speakers. This form could be too complex for someone who does not natively speak English. I tried to use a conversational tone and implemented colloquialisms to make the assessment of property damage and seeing if the landlord is compliant with MA Housing Code a more approachable and, dare I say, fun experience. The colloquialisms may completely derail someone with limited English proficiency. Ideally, I would like to see the form have translated versions to assist the Spanish, Portuguese and Chinese native speaking populations. 

The second issue is structural vocabulary. There are many building, construction, and engineering terms that have made their way into the MA Housing Code. I tried to reduce as many terms as possible to layman terms, but sometimes it is unavoidable. 

The third issue, I weigh against the second issue: complexity. I worry that this tool can become overly complex and cumbersome in the attempt for comprehensive coverage. With the rigid structure, I worry that it is too long and complex for some users to begin to approach. After their third questions about whether their landlord has provided proper water pressure, I’m sure many would give up and just sign a blank statement of conditions form. 

**Next Steps**

Ultimately, I would like to see several things implemented once someone new takes the reigns of this project. 

First, I would love to see how a more veteran and experienced coder tackles the issue of complexity. I attempted to use some logic and make Docassemble’s “brain” do the work for me. But more often than not, I would find that when I tried to get clever, I would break other parts of the logic and have to revert to ham-fistedly punching through yesnoradio or fill-in the blank questions. 

Secondly, in the interview I made a “general living space” and “other room” question sets. These are not nearly detailed enough to be effective and likely wouldn’t holdup under scrutiny if there was a legal conflict. I would like to see my successor create the open ended room answer that I attempted, where the user can name a room (e.g., Den, mancave, command deck), the appropriate questions are generated, and then (where I failed), the open-ended question can repopulated indefinitely with new naming options for the user if there are more rooms. 

Third, I had originally planned to include both the Statement of Conditions document coupled with a supplement document that has a timetable detailing the timeline placed upon the landlord for repairs. This was a stretch goal I had set for myself and between my over extended scheduled and limited coding skill, I was unable to complete the addendum document. 

Fourth, as discussed above, I would love to see the tool translated to be used by those who are not native English speakers. A large portion of the rental community are immigrants and it would most benefit them if they could read the tool in their native language and then respond, and have their responses translated to English for populating the form. I envision two forms being created, one in their native language and an identical form in English and both forms would be signed, dated and shared. 

Lastly, my coding skill limited my ability to use machine learning to my advantage. The most approachable way for this form to be mass utilized is through machine learning. The yesno, checkbox question format is very limiting and rigid. Ideally, I see the form transforming into to a simple “tell me what you see” text boxes for each room or area of focus with guiding instructions leading the renter to detail items that are listed in the Housing Code. Then through Machine Learning, the tool will be able to identify the key words and phrases corresponding to the Housing Code and then identify, based off the renter’s description, whether or not the unit and landlord are compliant. These responses are then compiled and correlated with the Housing Code for the statement of conditions.  

**Concluding Notes**

Although I am still very new to coding, and still feel intimidated by more experienced coders and complex concepts, I am very thankful for this class. This has been a tremendous learning experience. I got my first taste of basic coding and have learned a few very useful skills for my future as a law student and lawyer. I would like to thank Prof. Colarruso for everything he has done for our class through such a difficult semester and thank him for being a great guide through the looking glass into a whole new way of thinking and whole new world of coding. 
