# Welcome to _www-clear_ by CodeDay!

## Introduction
CodeDay’s event management backend for volunteers is located within the [**www-clear**](https://github.com/codeday/www-clear) repository. As indicated by the prefix `www-`, this repo has a frontend facing UI:

[![clear.png](https://i.postimg.cc/y6LZqFp3/clear.png)](https://postimg.cc/4nhdVhgX)

At `www-clear`, volunteers are able to mange events, see participant registration, manage ticket pricing, view event status, see a list of sponsors, edit notifications, and view related projects. Engineered with Next.js and React, this repo also incorporates design rules and display requirements defined within `topo`, defined below.

The following mind map illustrates how data flows from `www-clear` through `gql-server` to the `gql-clear` server and back to the user:

[![clear-Mind-Map.png](https://i.postimg.cc/25Qsj7ZY/clear-Mind-Map.png)](https://postimg.cc/XZvHQFL1)

### Contents
- [Getting Started]()
- [Installation]() 
- [Configuration]() 
- [Additional Technical Specs]() 
- [Contribution Guidelines]() 
- [Style Guidelines]() 
- [Additional Documentation]() 

### Getting Started
To get started working with `www-clear`, you will first need to clone the repository to your local machine. Then you will want to follow the [Contribution Guidelines](< link to bullet, not Notion >).

1. Run `nvm install` at the commandline
2. Run `npm yarn` at the commandline
3. Run `run yarn` at the commandline
4. Set environmental variables:
- `clientId: process.env.AUTH0_CLIENT_ID`
- `clientSecret: process.env.AUTH0_CLIENT_SECRET`
- `domain: process.env.AUTH0_DOMAIN`
- `issuer: `https://` + process.env.AUTH0_DOMAIN`
- `employee: process.env.AUTH0_EMPLOYEE_ROLE`
- `admin: process.env.AUTH0_ADMIN_ROLE`
- `manager: process.env.AUTH0_MANAGER_ROLE`
- `volunteer: process.env.AUTH0_VOLUNTEER_ROLE`
- `secret: process.env.GQL_SECRET`
- `accountSecret: process.env.GQL_ACCOUNT_SECRET`
- `audience: process.env.GQL_AUDIENCE`
- `appUrl: process.env.APP_URL`
5. Run `yarn dev` at the commandline

#### Reporting A Bug
< something here >

### Additional Technical Specs
The following specifications will need to be followed for this specific repository < what? >.

### Contribution Guidelines
CodeDay has a dedicated Notion page with more information about adding or changing our open source software. Visit our [Contribution Guidelines](https://www.notion.so/codeday/Contribution-Guidelines-draft-04e4cac2f72744b7b84e1e1a68c55f4e) page to learn more.

### Style Guidelines
The way a page is displayed–the color schemes, content layout, and dimensions–are governed by [_topo_](https://topo.codeday.org/), CodeDay’s design primary design software. Powered by [Chakra UI](https://chakra-ui.com/), `topo` ensures whatever web browser is used will properly display CodeDay’s content to user.

#### Standardized Workflow for Contribtions
As we work with so many volunteers and up-and-coming developers, we have a standardized way to submit pushes, pull requests, merges, and file naming to keep work consistent. Visit our [Formatting Submissions](https://www.notion.so/codeday/Formatting-Submissions-draft-04e4cac2f72744b7b84e1e1a68c55f4e) page to learn more about how to submit your work to CodeDay reviewers.

### Additional Documentation
Check our our [Notion **Fungineering**](https://www.notion.so/codeday/Fungineering-dfc6f9bea0fd43849c9a31bd94a64d17) page for more information.

