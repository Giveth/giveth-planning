# DEV Call

[![hackmd-github-sync-badge](https://hackmd.io/Qqhlz_EYQH-J8aXTgeqCWg/badge)](https://hackmd.io/Qqhlz_EYQH-J8aXTgeqCWg)


Sunday 17:00 Berlin // set up as weekly
- Share DEV progress
- GitHub issue cleaning
- Share outlook on next sprint (what issues, projection and time commitment)
- 

## Notes for DEV CALL 11/25/2020


Attending:

Check ins:
Amin, Mateo, Benjamin, Kay, Mateo, Camilo, WIlly, Griff

Using hackMD for Notes and agenda instead of google docs.

Mateo: participating in hackathon
Kay: not much news since wednesday did switch out graphics and names for pages biggest thing on todo list and backend
was very interested in codebase 

Camilo: working with matthew on webflow on fiat flow and project slug no more distractions no more updates
Griff no major updates no distrcations 

Mateo: already downloaded it to computer needs some changes to environment variables. some changes in environment backend to localhost. Mentioned to James that camilo made some changes. Now only need to be a user to make a project. if you comment those lines it will break. it didnt work when they made a PR.

we are having a token when having a user.

better when making changes on repo because of sourcecred. Camilo does a lot of work but not sure it's measured somewhere.


Camilo: who can make a project and that is supposed to be a token. 

Enviornment variables and API keys we have prod for Stripe. Now we can test doing a real donation and receive it in the SDG impact fund bank account. 

Should we use production keys or development keys? even when using prod keys you can make test transactions.

Willy: We got bank account enabled. next day Stripe: your account has been closed because of crowdfunding. Willy is back and fourth with Stripe to be reenalbed. 

Not planning for failure yet!

We have disabled the application. Have no implemented 

Talked to Bryan on Friday about PDF generation, was worried if he made big updates 

Meeting recording: what about using YouTube?

Griff has someone on UpWork to standardize streaming

*Ben will talk to Kay about meeting streaming/recording*

mateo is working on graphql. donate fiat Epic is moved to Review/QA.

need to set up an issue to make the backend points 




## Notes for DEV CALL 11/18/2020

Notes are also on https://docs.google.com/document/d/1EQKAGlxM-xH2hbq3AzE540iaRhF1i84Fnsx-rLf6Ggw/edit?usp=sharing    

#144 donation flow that is almost done after both of those parts are done we should be a qa for the MVP for a basic version. revising all the design after the "my account" is complete and "project details" 
#141 authentication is a complete mess

Kay: 
Amin: create page API in gatsby because its a common functionality that's required. 

* need to figure out authentication flow.
* we should design organization first.
* Marko is the best to figure it out.
* 

Search Algolia: plugin with gastby, really good search 

## Notes for DEV CALL 11/10/2020
* Ben: Organizing dev meetings. Donation executive summary material creation with Dani. Distracted by markets. Intentions listen to updates and take notes.
* Mateo: Excited to have started work on last Friday. Busy with donation flow. Need PDF receipt for fiat donations. Will make issue and ask Marco for design. Donation history is next in line. Intention is to dive fully into things this week.
* Bryan: Working on account page. Intention is to get updated.
* Amin: Pushed tor.us embed. Error when building with Gatsby. Tries to fix.
* Kay: did mostly build stuff set up source cred. maintaining bridges because discord changed some stuff. Still hogging low hanging fruit issues promise to be ready soon. Crazy week. Left some questions in figma for marco and willy and got some responses from Marco some things to decide so will keep adding to questions. Info pages about Giveth which did not change the text. Heavily distracted, intentions are to still follow meeting. 

#31 want to implement search using Minisearch. Assigned to Amin.
#61 Project View Mateo asked Bryan about implementation. Bryan needs to know what to do to generate the slug. Needs to generate projects.  Markup in gastby node file. 
#120 bryan will investgiate
Kay will build front end info pages like About Us and FAQ from Figma. 

Bryan and Amin are generating pages based on Gatsby files. When you want to create a new page. Gasby has templates you can use so without templates using from a slug to rehydrate. 

Mateo forked the previous Impact Graph repository which has all implementation of stripe. Will try and make a pull request and so will Kay. 

Kay: Please don't push anything yet just create a pull request. 

## Notes for DEV CALL 07/10/2020

* Amin: changed Torus wallet to standard wallet. asked user to sign message with private key.  popup will be shown  
* Kay: do we really want search on the FAQ pages. will do the pixel for vector graphics 
* Reoganize ZenHub to correct flow. Bring up ideas in Discord.
* Proposal for work sprints to deliver work. 
* Mateo: needs a lot of changes in the backend, make the screen actually synchronized
* 

## Notes for DEV call 04/10/2020

* Kay: meeting monday. The issue was Epic editing pages. Most links are already up there. Played with wiki 
* Bryan: started project view making more updates to it making some pages generated during deployment. Check latest branches that has fiat credit card
* Mateo: finished most of the stripe payment, only missing a webhook, hoping james would jump in.
* Camilo: 1. Simple flow want to create temporary token 2. Identity of donations now donations are anonymous or require user token 3. Apollo web checking change to apollo express. We should let Camilo and Mateo finish backend.
* Willy: ask James to explain white labeling and organizations. How to create an organization. 


Post MVP, consider migrating from Gatsby to Next.js so front and backend can be bundled together and whitelabeling can be streamlined.



## Notes for DEV call of 01/10/2020
* Amin - closed issues related to node gateway. web socket connections were broken. Andre changed config and fixed it. Will handle buttons this week. Questions about mobile view. was occupied this week, needs help with leaderboard. Adding PAN moved to beta and needs to be tested.
* Andre - Adding tokens in beta server. looking for contract address in forwarding address. Need to test "In Progress" issues so it doesnt break system.
* Hadai - question about 1459 button off center. if button is moved to right, button is not in the center. No progress on issue cleanup task. Will implement #1413 tomorrow finally.
* Griff - closed #1459 and made it part of #1376 #1214 moved to sprint backlog because of low priority. 
* Benjamin - testing adding PAN to Dapp with Amin.

## Notes for DEV  Sprint Call of 28/09/2020
- Amin is going to take ownership of the Topia backend, specifically mapping new features in front end to backend. Next step is connecting the project creation flow to the backend.
- Mateo and Camillo are aiming to finish the 'Donate Fiat' flow this week
- New issue: Replace Tor.Us direct auth integration with Tor.us wallet integration
- New design needs: Show projects their donation address in the project creation flow (maybe the high five screen?) Give 'crypto savvy' projects the ability to 'Edit' their donation address. Give 'crypto noobie' projects a path to learn more about their new donation address and how it works.
- Time zones:
    - Ben: Virginia (GMT -5)
    - Mateo: Columbia (GMT -7)
    - Camillo: Columbia (GMT -7)
    - Bryan: East Africa (GMT +3)
    - Amin: Iran  (GMT+3.3)
    - Kay: Austria (GMT +2)

## Notes for DEV Call of 27/09/2020
- Attending: Kay, Amin, Benjamin (Socretes), Mateo, Willy
- Staging is great again! Login is fixed: staging.giveth.io
- Gatsby handles env variables in a unique way. Kay needs to investigate and will report back.
- Mateo: Made a PR for donation flow earlier in the week. Need access to official account for Stripe Connect. 
- Amin: Amin is back! Will be working on some v2 issues this week
- 

## Notes for DEV Call of 20/09/2020
- We use Stripe Connect Express. Stripe handles KYC. Enables Project bank accounts and accept FIAT donations
- add create_organization mutaion to backend?
- Fiat donations and account management: Organizations might have more than one bank account. Lots of variables to talk about in follow up.
- Camilo created automated stripe customer creation on log-in. Created stripe endpoint that manages communication with stripe and have confirmations, errors about FIAT tranactions.
- Mateo takes care of frontend for Camilo's work
- PRs coming from Mateo for frontend and Camilo for the backend server
---
## Notes for DEV Call of 13/09/2020
- All PRs have been approved and merged!
- Amin, Mateo, Bryan: Please test your changes in prod and ensure they are still working as intended
- There is a bug in staging where users cannot sign in. Need to debug this. A request is being made for the $walletaddress and the response is causing an error.
- Next step: finalize project create flow so that projects are saved after creation. Bryan is working on this along with the High Five success page and the Project View page. (https://github.com/Giveth/giveth-2/pull/103)
- Willy worked with Mateo on donate fiat workflow. working with marko on more mockups. Use stripe to simply donate fiat.
- Mateo has a friend who wants to take on some backend development. He is badass. Wants to help us with stuff like graphql integration with stripe. auto creation of market place i.e.
---
## Notes for DEV Call of 05/09/2020
- Check out the new staging environment! (h/t @geleeroyale) https://staging.giveth.io/
- New process for reviewing and merging PRs: feature-branch -> staging -> master
- Mateo was able to replace some PNGs with SVGs. Some of the SVGs were not rendering properly. Mateo will make a PR to update the images that rendered correctly, and Kay will update the remaining images in the future.
- Mateo will make a PR to update the style of the Project Cards.
- Amin completed image upload functionality on the client side. Projects can upload a photo to IPFS in the project creation flow. *Still needs to be implemented in the project creation flow
*We are using pinata's IPFS service for this. This gives us 1GB of storage for free, after that we should pay
- Marko and Willy had a call. Shared doc from this in chat. Talked about settings. Required: Send funds example (should we just let app.tor.us pop up). Can we get the same private key in our dapp that they get in app.tor.us - torus embed could give us required functionality. (Amin explains drawback: behaviour of torus should be considered in our tx. rewrite functionality that use transactions for embed.)

To-Do
- Amin to create a ticket to move image upload functionality to server side so we're not exposing our pinata/IPFS key.
- Ping Bryan about implementing the pinata image upload functionality in the 
- Project creation flow: Need the 'Confirm' and High Five' page along with the publishing the project to the backend

---
## Notes for DEV Call of 30/08/2020
- Kay reviewed Bryan's contribution, did some issue cleaning, deployed new sourcecred (cred.giveth.io), did start code work on localhost
- Bryan's update: Has a complete branch with Create a Project epic (https://github.com/Giveth/giveth-2/tree/dev/create-project-flow-epic). Kay will review and merge so we can test. Final remaining step is to make the call to GraphQL to save the project and fix any bugs.
- Mateo: Call with Willy, private issues so not much progress this week, James accepted backend PR for FIAT donation flow, help invetigate integration for Paypal or similar, SVG transformation is in progress. Will wait for Bryan's PR for SVG (Kay will ping)
- James: Wants to realize staging with Kay, need to schedule call
- Amin: 
- Willy: Update board

To-Do
- Set up the backend for a staging environment for testing new features (https://github.com/Giveth/giveth-2/issues/88)
- Customize weight configurations in cred.giveth.io; Schedule meeting for Giveth 2 members and Hamad to determine optimal weight config. Propose to DAO before merging.
- 
---
## Notes for DEV Call of 23/08/2020
- Kay is on last stretch of vacation, so assigned issues come next week
- Bryan is making good progress. Needs someone to look through PRs, bug with validation. Will schedule with Kay and Mateo to go through PR. Should be finished by Friday. Awesome!
- Mateo was able to set up project from guides. Solved on frontend and needs help with integration into backend. Needs invite to repo to make PR. Was looking at codebase and has some suggestions. Starting with replacing PNGs with SVGs.
- Amin implemented IPFS image upload. Is done client-side, but should be sent on to backend.

- To-do: Create an issue to replace PNG illlustrations with vector images (SVGs)

### Dev Progress

---
## Notes for DEV Call of 16/08/2020

### Dev Progress
- James worked on the GraphQL server, basically ready for MVP
- Amin looked at image uploader services (will implement IPFS service and push within next days)
- Bryan is almost done with create project flow and will issue PR soon
- Kay implemented sourcecred for GitHub and Discord. We need to work on weighting for it to be useful (see https://cred.giveth.io)
- Matteo will take on the Donation Flow epic
---
## Notes for DEV Call of 26/07/2020

- not much progress on frontend this week, more elements for homepage - still not done
- Amin finishes Tor.us embed integration and opened a new PR for @jamespfarrell to review
- Kay will continue working on frontend, Amin will pick an issue to work on (likely project view filtering)
- Gus takes charge of compiling info to guide contributors and development in general across Giveth and The Commons Stack
- Whitelabel versions will be feature-heavy. Currently two different ones are talked about (Panvala and https://gaiaprotection.com/)
---
## Giveth2 - technical planning

### Frontend Framework

Which framework do we want to build on. Currently we are using Gatsby, but that decision might be too opinionated for our aplication going forward. We are sure we want to build it on React.
- `gatsbyjs` stick with gatsbyjs for now
- ~~`vercel`~~
- ~~`create-react-app`~~ + some library for static rendering like [react-snap](https://github.com/stereobooster/react-snap)

### Tech stack
What is our full software stack? Should include important dependencies as well.
- `tech stack`
  - `Frontend: React-based`
  - `State Management: Apollo Client`
  - `GraphQL server: Apollo, TypeGraphQL`
  - `Blockchain-development: Set of smart contracts? Reuse?`
  - `Blockchain-production: xDAI POA sidechain`
- `services`
  - `Authentication integration and wallet provider: tor.us` (investigate risks of unseein issues with tor.us for complex usescases like managing campaigns and milestones, talk to tor.us)
  - `OAuth provider: google`
  - `blockchain query: infura?, thegraph?` - GraphQL stitching and federation
- `devtools`
  - `storybook ?`

### Data structure and backend(s)
We have multiple pieces of data infrastructure. We should define:
- `data models`
- `db` & `blockchain` -> use database as store for state (postgres ...) -> triggers in database fire off actions to write to blockchain. Makes probably most sense for i.e. campaigns
- `data flow` : User enters data of a project -> we create entry in db -> upload info to ipfs -> return ipfs hash value to user -> user sign transaction with value of ipfs hash

### Deployment
Where is code deployed and hosted
- `code hosting: GitHub`
- `frontend & frontend CI: Netlify`
- `backend: digitalocean?`
- `backend CI: ?`
- `smart contracts`

### Development
How development is structured and organized
- DevFlow: `figma -> storybook -> develop`
- GitFlow: `feature-branch -> develop -> master`
- Project Management: `GitHub issues` & `Zenhub` & `Trello`
- Issue cleaning: `every 2 weeks?`