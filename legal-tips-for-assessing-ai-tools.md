# Legal Checklist for AI Tools

If your legal department is anything like ours, you're constantly responding to requests from the business to use more AI tools. Every team is exploring the value of AI. Developers are using coding agents. Security is implementing AI-driven investigations. Sales and marketing are leveraging AI for conversation insights and competitive research. We've seen a flood of trying and buying new tools, with faster turnaround to adopt than ever before. Even when a business's main focus is not AI, almost every product now offers AI-powered features, and we need to consider how to make sure that our own AI offerings pass these same legal reviews.

When building product, we all know that there are risks associated with using AI, but we feel immense pressure to use it or be left behind. We must balance that risk with a mandate to protect our company's data and intellectual property, as well as the data and intellectual property that we may be holding for our customers.

---

**DISCLAIMER: NOT LEGAL ADVICE**  
Every legal department needs to make their own assessment based on the specific circumstances of their company.

That being said, we believe that our checklist is a sound and reasonable one that most of our peers would agree with.

*So what does legal actually care about?*

In order to protect our (and our customers') data and intellectual property but continue to support the evolving needs of the business, we've aligned on the following requirements for the use of AI tools at Sentry:

- **Limited Data Use Rights:** This means contractual commitments from suppliers that data will only be used to provide the service to us (i.e., data won't be shared with third parties or used to train models without our express consent).
- **In-Product Data Controls:** Tools that use our data to train models should have scalable administrative (not just user-level) controls such as opt-ins to enable training or opt-outs to disable training.
- **Consistent with our Customer Commitments:** Anything that will touch our customers' data must align with our own commitments to customers, including data deletion/retention policies that match our own, data storage location that supports a choice of U.S. or EU data regions and appropriate subprocessor Data Processing Agreements and Business Associate Agreements.
- **Audited Security Controls:** Suppliers must have audited security controls such as SOC 2 Type 2 and ISO 27001.
- **Transparency:** Suppliers are clear about how they are interacting with our data.

---

## Legal Checklist Table

| Principle                              | Controls                                                                                                                                                                                                                                    | Assessment of Supplier |
|----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
| **Limited Data Use Rights**            | - [ ] Supplier's right to use customer data is limited to only providing the service to us  <br>- [ ] Express prohibition on use of our data for model training or product improvement without our consent  <br>- [ ] Express prohibition on sharing output based on our data with third parties without our consent |                       |
| **In-Product Data Controls**           | - [ ] Product includes admin controls to disable model training  <br>- [ ] Product includes admin controls to disable AI features  <br>- [ ] Product includes opt-in controls to use customer data for model training  <br>- [ ] AI features are not on by default and require additional enablement/opt-in |                       |
| **Consistent with Our Customer Commitments** | - [ ] Supplier's data deletion/retention policies align with ours  <br>- [ ] Supplier's data locality commitments align with ours  <br>- [ ] Supplier has DPA  <br>- [ ] Supplier has subprocessor BAA  <br>- [ ] Supplier indemnifies for third party IP infringement claims based on output of generative AI features |                       |
| **Audited Security Controls**          | - [ ] SOC 2 Type 2  <br>- [ ] ISO 27001  <br>- [ ] Annual penetration test  <br>- [ ] Fedramp  <br>- [ ] HIPAA security rule                                                                                                                  |                       |
| **Transparency**                       | - [ ] Supplier publicly documents how our data is used with AI features                                                                                                                                                                      |                       |

