
```diff
- under development
```

![go back to table of content](./README.md)

# Reserved Instances (RIs )

```diff
- Disclaimer: views, thoughts, and opinions expressed in the text belong solely to the author, and not necessarily to the author's employer. 
```

### What is this?

A Home Office Centre OF Excellence (CoE) guidance on the use Of AWS RIs. All AWS account owners will be expected to drive cost down and consider RIs as a default starting position.

The guidance will help you to understand and apply in-house approach.

Three areas are covered

- RIs concept.
- How to procure RIs.
- Governance expectations.

### Intended audience

 Portfolio DevOps.

### Who is involved?

this guidance is developed, updated, validated and sponsored by the following people  

| Who | Role  |
| ------ | ------ |
| Matt | owns the AWS relationship  |
| Abdul | develops, maintains this guidance and provides support |
| James and Graham| QA project RIs implementations through the TDA and TSG  |
| Projects | Responsible for implementing this guidance. |
| Duncan | Lead Cloud Engineer |



### when should I consider RIs?

- if utilisation is not predictable, use Amazon EC2 On-Demand   
- for other workloads where you can predict workloads, you should consider  Amazon EC2 reserved instances.



### How does it work?

AWS pages describe RIs in details (see this https://aws.amazon.com/ec2/pricing/reserved-instances/), and there is no point of re-writing readily available text. However, in the interest of speed and assuming that you are comfortable with AWS well-architected framework, this section is just a quick reminder of main points

- RIs allow you to make capacity reservations for predictable workloads

- RIs are a billing concept that allows you to receive discounts on On-Demand cost if your instance matches certain conditions 

- RIs pricing is calculated using three key variables

    - the Instance attributes
    - term commitment and
    - payment options that you select


- instance attributes that determine pricing include

  - instance type
  - availability zone  and
  - tenancy
  - platform


- Example

   - instance type = M3 X large
   - availabilities = us-east-1
   - tenancy = default
   - platform  = linux



- AWS will automatically give you  the discounted reserved instance rate anytime that you're running instance with RI attributes

-  RIs pricing is  that determined by

  - commitment term: either one or 3 year
  - payment schedule :
      - upfront payment and monthly installments
      - upfront partial payment  and reminder to be paid by installments
      - or pay nothing upfront  


            the more you pay upfront, the more you save

- RIs pricing list can be found here https://aws.amazon.com/ec2/pricing/reserved-instances/pricing/

- if your application workloads requirements change or go away before the end of your  commitment term, you can modify the Instance type to another size in the same family at no extra cost (only applicable to linux)

- if you no longer need your RIs,  you can become a third party seller and sell it on the reserved instance Marketplace

### As a DevOp, what is expected of me?

- Once you have calculated your compute requirements, get in touch with [to be published] in AWS who will advise you on your optimum RIs options. Make sure you select the right type of RI depending on your application type/load). In most cases, you are likely to use standard RIs and not Convertible or Scheduled. 
- Contact CoE for advice and information. At the same time, if you think the guidance given here is out of date or incorrect, please either inform the CoE or submit a PR
- Email or book slot with the TSG and I&P TDAs to validated RIs procurement approach and to share lessons learned 
- Build your VPCs
- Prove at the digital assessment sessions that you have adopted and applied the in-house RIs approach
- If your requirements change, make sure you off-load what you are not using

### How do I know that this guidance is sound?


- Guidance is based on the practical IPT implementation 
- Home Office AWS account team validated the content 
- CoE working with CDP applied the advice given and founded it  ...

```diff
- all of the above is current/future work 
```
### Billing  and commercials  and RIs

```diff
- This section is under development. it will detail how internal billing works. 
```
### support

Applying RIs is not difficult but to speed things up, achieve internal consistency and ensure savings are applied across the board, you are strongly advised to make use the following  internal resource.

  - CoE direct advice
  - AWS user group forum
  - HO AWS account team
  - Peer advice  

### Governance

All portfolios are expected to secure the following approvals

- TDA and TSG approvals before build
-  Matt's RIs management monthly sign-off
-  Digital assessment value for money test


---

### can I contribute to standards?
- yes. just submit a PR
