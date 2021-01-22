---
date: 2020-01-10
title: Add Multiple Leads
video_id: Wqr8iL3QE8M
description: Add Multiple Leads
type: Video
sidebar:
  - {id: add-multiple-leads, text: Add Multiple Leads}
  - {id: additional-information, text: Additional Information}
  - {id: schedule-sequence, text: Schedule Sequence}
  - {id: add-multiple-leads, text: Add Multiple Leads}
  - {id: custom-email-subject, text: Custom Email Subject}
  - {id: ways-to-assign-lead, text: Ways to Assign Lead}
  - {id: questions-answered, text: Questions answered}
categories:
  - assigning-leads
# set: getting-started
# set_order: 3
---

Lead can be from various sources and can have different context too. Based on the source and the context of the lead, the Assistant writes short and simple emails to the lead.

## Add Multiple Leads
To add multiple leads, provide an excel sheet in the format specified in sample excel. Each row would represent one lead and the first row is the title row. 

`Intelli Import` is a feature where Assistant will try and read the excel in your existing format, to save you the hassle of converting it to the expected format. 

Once you provide the Lead Source, Context and More information, review the emails written by the assistant and the email sequence. Change the schedule, if required. 

Click on Add Lead. Assistant will start validating each row, and will add the valid leads. Finally Assistant will notify you of the status on email. 

You can look at the status by going to the “Upload History” page.  
Clicking the `valid and invalid counts` will download an excel with the respective leads. Invalid leads file will have the reason too.  
Clicking on the `Added count` will take you the lead list of those leads added from that specific excel file. 

Lead once added can not be deleted. 

## Additional Information
Additional information is intended to provide more context and details to the lead about your company offerings. Assistant will use this information in emails. 

<a name="schedule-sequence"/>
## [Schedule Sequence](#schedule-sequence)
While adding leads,the sequence of emails can be seen in the email preview. These sequence are as per the selected Schedule. 

Default schedule for the Assistant is selected, while you can change the Schedule before adding leads. Change of schedule will also change the email sequence for you to review. 

<a name="custom-email-subject"/>
## [Custom Email Subject](#custom-email-subject)
Assistant will generate the relevant email subject. This can be overwritten too, though we recommend to use the AI generated Subjects. 

You can edit the Subject while adding the leads from the TEC UI. Click the `More button` in the email preview to see the `To, Cc and Subject` fields for you to type your own values. If you are using a custom message in a custom schedule, we recommend to have your Custom subject in the Custom message itself.

Assistant will use the same Subject line for each followup email, so that the all the emails are grouped together for the viewer. If you intend to have different subjects for each followup email then you will have to use custom message and each custom message in the schedule can have different custom subject too. 

Like Subject, the email body can be changed too. We recommend to create a custom message in a custom schedule if you intend to write your own message instead of editing the message at the time of adding leads. One important best practice to follow while creating your own custom message is to have small 5 seconds reading emails on hand-held devices. 

With the intention to keep the emails light, attachments are not possible. While you can add an image to your emails, it is recommended to avoid adding multiple images to keep it small and quick read. 

Note that Assistant will keep the first email in all the followup emails so that the Context is maintained. Even if the lead reads one of the followup emails, the context is there for the lead. 

<a name="ways-to-assign-lead"/>
## [Ways to Assign Lead](#ways-to-assign-lead)
Leads can be added or assigned to the Assistant in multiple ways:
- Add one lead at a time from TEC UI
- Add multiple leads from TEC UI by uploading an excel file
- Copy or Cc your Assistant in the email you are sending to a lead. Have to enable this feature in Edit Assistant
- If you are integrated with CRM, then assign the Lead/Contact from CRM to the Assistant User in CRM

## Questions answered
- Can I add multiple leads ? 
- What are the various different ways of assigning leads to the Assistant ?
- How can I assign a schedule to the lead or leads ?
- How can I change the subject for the emails being sent by the Assistant ?
- Will assistant maintain the first email in the followup emails ? 
- Will all the emails have the same Subjects ? 
- Can I have different Subjects for each email ?  
- Can I write my own message and sequence ? i.e. custom schedule and custom message ?
- Can I add attachment to the email ?
- Can I add image to the email ? 
- Is there a possibility to delete the existing data ?