# GDS README template

This is a template to follow when you write a README for your GDS GitHub repository. Refer to the [GDS Way guidance on writing READMEs](#link) for more information.

## Title your README clearly
Give the user a clear sign they’re looking at the right thing. For example, `GOV.UK webchat prototype` not `chatbot-v1`.

## Introduce the project 
Use the start of your README to describe your project and what it does. Focus on what your project provides to users or other developers. You can also explain how your project links to other things. 

For example:

```
whitehall is a Ruby on Rails app built on a MySQL database. It’s deployed in 2 modes: 
'admin' for publishers to create and manage content
'frontend' for rendering some content under https://www.gov.uk/government and https://www.gov.uk/world
```

Include any limitations up front so the user can evaluate whether the project meets all their needs. This includes any version information. 

You can also add a table of contents to the start of your README to help users jump to the information they need. 

## Share examples
If applicable, consider adding screenshots or links to live examples of your project so users can see how other people use your project. The [GOV.UK Rummager README](https://github.com/alphagov/rummager) provides a screenshot of the public search API using the project. 

## Explain any prerequisites
If applicable, list the items a user needs to be able to use your project, such as a certain version of a programming language. It can be useful to link to documentation on how to install these items. This could be under a heading such as `Before you start`.

If your project depends on other systems or projects, you should list these technical dependencies. For example:

```
- [alphagov/other-repo]() - provides some downstream service
- [redis]() - provides a backing service for work queues
```

## Explain how to get started
Next tell the user how to get started with your project. This is often a numbered list on how to install the project and run it locally. List one action per step.

Follow each step with example code if possible as some users will want to copy and paste directly from your README. 

For example:

```
1. Install middleman.

`gem install middleman`
```

These instructions should help your users get to “hello world” or be able to run the project locally. If you want to provide more advanced documentation, you could:

- add a configuration section to help the user amend the project for their own use 
- speak to a technical writer about publishing separate documentation 

## Help users configure and deploy the project for their needs
If applicable, include a link to any editable project configuration files. You should do this shortly after the ‘getting started’ guidance. You could also:

- list any environment variables available in a table
- link to more detailed configuration documentation in a different file 

Describe how to deploy the project if applicable. 

## Explain how to test the project
Add information on how users can check they can run the project successfully. For example, instructions for how to run a test suite. 

This can be a useful place to list error messages and suggested fixes.

## Share additional information
This is a good place to link to additional or related information if it’s available such as API documentation or a separate documentation website. 

## Show users where to get support
Let the user know where they can go for help using the project. This could be a support email address, community forum, or issue tracker attached to the repository. 

## Explain how users can contribute
Let users know they can contribute. Consider adding a contribution file (often named `CONTRIBUTING.md`) with more detail, or state how to contribute in the README. The [GOV.UK Frontend repository](https://github.com/alphagov/govuk-frontend) has a shared [contribution file](https://github.com/alphagov/govuk-frontend/blob/master/CONTRIBUTING.md) explaining the:
- style conventions that GOV.UK Frontend follows 
- [alphagov practice for pull requests](https://github.com/alphagov/styleguides/blob/master/pull-requests.md) 
The GOV.UK Frontend repository also has a [`CODE_OF_CONDUCT.md`](https://github.com/alphagov/govuk-frontend/blob/master/CODE_OF_CONDUCT.md) file linking to expected communication and behaviour standards expected of alphagov contributors. All open repositories should link to this code of conduct.

You can also credit individual contributors or link to other repositories that inspired your project. 

## Link to the licence file(s)
All open repositories [must have a copyright licence](https://gds-way.cloudapps.digital/manuals/licensing.html#copyright-notice). Under a `licence` heading specify the license(s) you’re using and link to the licence file(s). There are 2 possible licenses to use.

Use the [MIT License](https://opensource.org/licenses/MIT) if your repository contains software code. This license also covers documentation in the repository about that code.

Use ©Crown copyright and the [Open Government Licence (OGL)](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3) if documentation is displayed to users using the software code in your repository. An example of this is technical documentation.
