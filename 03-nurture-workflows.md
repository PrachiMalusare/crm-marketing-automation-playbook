# Automated Nurture Workflows

## Workflow design template

For each workflow define: business goal, entry criteria, exclusions, sequence, owner, exit condition, re-enrollment rule, error alert, and success metric.

## Workflow A: New inbound lead

**Entry:** Valid form submission with consent and no active opportunity.

1. Send the promised resource immediately.
2. Create/update the CRM record and preserve source fields.
3. Enrich and score the lead.
4. Day 2: send a pain-point educational email.
5. Day 5: send a relevant use case.
6. Day 9: invite the lead to a consultation or demo.
7. Exit when the contact requests a demo, replies, unsubscribes, becomes an opportunity, or completes the sequence.

## Workflow B: High-intent MQL

**Entry:** Score reaches threshold plus required fit condition.

1. Set lifecycle stage to MQL.
2. Assign owner by territory/product/round-robin rule.
3. Create a time-bound follow-up task.
4. Notify the owner with source, use case, score reasons, and recent activity.
5. Send a personal acknowledgement from the assigned representative.
6. Escalate if no action is recorded within the SLA.
7. Branch to accepted, recycle, or disqualified outcome.

## Workflow C: Re-engagement

**Entry:** Previously engaged lead with no meaningful activity for 45 days.

1. Send one concise value-led update.
2. Offer preference selection or a useful new resource.
3. Send a final check-in only if engagement occurs.
4. Suppress from active nurture after no response; retain only as policy permits.

## Quality controls

- Never enroll unsubscribed, bounced, restricted, or active-customer records accidentally.
- Apply frequency caps across workflows.
- Test every branch with sample records before activation.
- Use plain-language emails with one primary call to action.
- Monitor delivery, replies, conversions, complaints, and workflow errors.

