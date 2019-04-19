Example Full-Stack Challenge
========================

We're excited that you're interested in performing the coding challenge.
The purpose of this test is to see how you approach problems as well as to evaluate the quality of your code.

# Challenge description
This challenge imagines that we have a social media platform that is under attack from spam. We have implemented a reporting system for users that lets them report spam to the platform, and our spam protection team.  

The challenge is to create a small full stack application for our spam protection team that consists of a server and a web based UI in order to manage reported content.

The UI should look something like:

![Reporting listing](images/wireframe.png)

We provide an example listing response ([data/reports.json](data/reports.json)) that you can use as the basis of your listing. Please fill the appropriate fields in the wireframe, ignore the "Details" link.

Furthermore we need a way to block the content and resolve those reports. The two buttons in the frontend should do a call to your backend service in order to block the content and to resolve the ticket. You are free to make up the blocking as you want, the resolving is defined as a PUT request to an endpoint with this structure /reports/:reportId. An example request for how to update a report is in [data/update_ticket_request.json](data/update_ticket_request.json).

*Blocking* means that the content should no longer be available to users

*Resolving* means that the report is considered "resolved", and it is no longer visible to the spam protection team

# Instructions
- Please don't spend more than 3 hours.
- Choose whatever frameworks you are comfortable with and that lets you achieve a solution in the given time limit. Please nothing too esoteric. We prefer Java, Ruby, Node.js, Python or Elixir.
- Provide the solution source code either as zip or as a link to the code repository

# What we're looking for:
- Code quality
- Technical choices
- Something that can actually run
