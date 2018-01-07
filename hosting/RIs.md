
```diff
- under development
```

![go back to table of content](./README.md)

# RIs

### What is this?

A CoE guidance on the use Of RIs. All AWS account owners will be expected to drive cost down and consider RIs as a default starting position.

The guidance will help you to better understand and apply in-house approach.

Three areas are covered

- RIs concept
- How to procure RIs
- Governance expectations

### Intended audience

 Portfolio Devops.

### Who is involved ?

this guidance is developed, updated, validated and sponsored by the following people  

| Who | Role  |
| ------ | ------ |
| Matt | owns the AWS relationship  |
| Abdul | develops, maintains htis guidance and provides support |
| James and Graham| QA project RIs implementations through the TDA and TSG  |
| Projects | Responsible for implementing this guidance. |
| Duncan | Lead Cloud Engineer responsible for ... |



### when should i consider RIs?

- if utilisation is not predicable use Amazon EC2 On Demand   
- for other workloads where you maybe able to predict work load, you should consider  Amazon EC2 reserved instances



### How does it work?

AWS pages describe RIs in details and there is very little point of re-writing readily available text. However, in the interest of speed and assuming that you are comfortable with AWS well architected framework, this section is just a quick reminder of main points

- RIs allow you to make capacity reservations for predictable workloads

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

  - commitment term : either one year or 3 year
  - payment schedule :

      - upfront payment and monthly instalments
      - upfront partial payment  and reminder to be paid by instalments
      - or pay nothing upfront  


            the more you pay upfront the more you save

- if your application workloads requirements change or go away before the end of your  commitment term, you can modify the Instance type to another size in the same family at no extra cost (only applicable to linux)

- if you no longer need your RIs,  you can become a third party seller and sell it on the reserved instance Marketplace


### what do i have to do

- Once you have calculated your compute requirements, get in touch with [to be published] in AWS who will advice you on your optimum RIs options
- Get in touch with CoE for advice and information. At the same time, if you think the advice given here is out of date or incorrect, please either inform the CoE or submit a PR
- Email or book slot with the TSG to validated RIs procurement and to share with others selected
- Build your VPCs
- Prove at the digital assessment session that you have adopted and applied the in-house RIs appraoch
- If your requirements change make sure your off-load what you are not using

### support

Using RIs is not difficult but to speed things up, achieve  internal consistency and insure savings are applied across the board, you are strongly advice make use the following  internal resource

  - CoE direct advice
  - AWS user group forum
  - HO AWS account team
  - Peer advice  

### Governance

All portfolios are expected to secure the following aprovals

- secure TDA and TSG approvals prior to build
-



---

### can I contribute to standards?

- yes. just submit a PR
