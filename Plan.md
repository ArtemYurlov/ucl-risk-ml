# Use of ML for cyber security

## Timing:
- [ ] 8 Oct 2018 - Rough plan
- [ ] 15 Oct 2018 - Outline of work & basic writeup
- [ ] 22 Oct 2018 - Get a *working* idea/model
- [ ] 29 Oct 2018 - Research the background work & formalise the model
- [ ] **2 Nov 2018 - 5 page outline**
- [ ] 5 Nov 2018 - Get some results
- [ ] 12 Nov 2018 - Reflect on the results and make improvements - do most of writeup
- [ ] 19 Nov 2018 - Finalise the model & the results
- [ ] 26 Nov 2018 - Finish writeup
- [ ] **23 Nov 2018 - 10 page draft**
- [ ] 29 Nov 2018 - Final touches
- [ ] **9 Dec 2018 - deadline**


## Rough Plan:
0. Prelude:
   - A CISO (Chief Information Security Officer) is hired to manage the security risk of IT in an enterprise. 
   - In the idealised scenario a CISO and his/her team create requirements for IT security which will in turn be requested from the suppliers (ie Software/Hardware vendors & System integrators), who then would provide the **defendable IT**.
   - However this is not the reality **at all**, largely due to the entire supply side of IT being scale driven -> oligopoly (ie Intel is the only company selling server cpus). The enterprise has very little power to have anything changed in their hardware as there is no incentive for the suppliers to change anything.
   - So the enterprises & CISO has **insufficient market power to enforce any product design changes on the supplier side**. Therefore, they cannot make any security requirements. 
   - Security vendors and Cyber insurers attempt to fill the market gap, however most security products are both trivial to bypass by attacker QA and provide a lot of high privilege attack surface (as they run in root privilege and do have bugs). **So these products are not very useful. Why is there market for this?**
        - Good security products would reduce the risk of Enterprise & CISO
        - Actual security products **look** like they could plausibly reduce the risk of the Enterprise -> Reduce risk for CISO, they are being paid to manage risk.
        - CISO need to make purchasing decisions in a market full of poor products.
        - Biggest risk for CISO is being seen as "having forgotten" a risk 
        - Solution is often **portfolio purchase** (ie buy one of each category), the quality of the products is a secondary issue to CISO, only "look" of the product is important
        -
        - Good security product is the one that's difficult for the attacker to get to do his QA
        - Proliferation of new product categories, since purchasing decisions within each category are based on marketing & manageability (it's rational)
   - Cyber insurance offers to mitigate the cost-of-breach & cost-of-cleanup (cost-of-IR), but they do not insure reputational risk or loss of IP (lack of historical data, distribution of attacks is not static). The current strategies is to underwrite without fully understanding the risk or having the data (is counted as data-acquisition cost)
        - Insurances are unable to tell good/secure products from not
        - They can (in future) offer lower premiums to customers that have secure infrastructure/products, therefore insetivising secure solutions
        - They can also bundle market power to influence Hardware vendors (concentrated demand for better systems)
        - Accumulated risk (many clients being exposed at once) is dangerous to the insurances (they want risks to be independent)
        - Costs can be huge as damage could be non-disinfectable
    - IT grows exponentially - and so does IT risk
    - All code - including security products - need to have tail risks accounted for, so less code = less risk (less bugs, less code, less trusted/privileged code), for example QMail has had no incidents and is still very secure
    - The vast majority of security issues are found in rearly-used features of software
    - 
    - 
1. Introduction:
    - The goal is always to have a secure system at the minimum **cost**
    - In principle it should be more **expensive to hack** into the system than the value of the information stored in the system.
    - Modern methods **trade off the utility** of the system for security (ie utility = how easy it is to operate within the system), so the cost is not just in implementation but in the use of a secure system
    - Lack of organization (eg no updates, no separation of access, etc) will weaken the system
    - As the system grows in size, it is a **disproportionately harder** to keep track of everything and everyone, so it is easy for an attacker to stay unnoticed in the system
        - a lot of data to analyse
    - all hacks need reconnaissance into the company and will need time to execute their attack, early detection is crucial to prevent an attack
    - We can "hedge" the risk of software (eg tight sandbox around risky software)

2. Background work:

3. The model:

4. Results:
5. Conclusion:
6. Discussion:
7. Appendix:

