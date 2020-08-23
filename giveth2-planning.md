# DEV Call

Sunday 17:00 Berlin // set up as weekly
- Go through technical planning below
- GitHub issue cleaning



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