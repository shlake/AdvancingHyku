---
id: 234
title: 'On the way to the community-owned infrastructures: Code contributions'
date: '2021-07-20T16:24:40+00:00'
author: 'Advancing Hyku'
layout: post
guid: 'https://advancinghyku.io/?p=234'
permalink: /2021/07/20/code-contributions/
spacious_page_layout:
    - default_layout
categories:
    - Blog
    - Update
tags:
    - 'code contributions'
    - Codebase
    - 'community ownership'
---

Community ownership<sup>1</sup> over infrastructure is about who controls and maintains the building blocks of the environment for the given technology. This blog post will not examine this term extensively but will look into it in terms of Advancing Hyku’s approach to our stated project deliverables.

True to our project goals, the Advancing Hyku project has been introducing new features to the Samvera’s Hyku platform, with the community and for the community, where others can build upon and create or improve their own infrastructure. One of the main objectives of the Advancing Hyku project, funded by [Arcadia](https://www.arcadiafund.org.uk) which provides visibility and strong support for related and complementary open infrastructure projects currently active or proposed, is to contribute the code we develop back to the Hyku/Hyrax codebase<sup>2</sup>. Therefore, the project team highly values community contributions at all levels to strengthen the implementation process of current and future Hyku adopters.

Advancing Hyku developers continuously work with the Samvera community to develop code either new or as an improvement to existing Hyku and Hyrax software platforms. In an [earlier post](https://advancinghyku.io/2020/09/18/project-update-september-2020/) we have listed some of these contributions. Since then, in February 2021, Advancing Hyku developers teamed up with the community for the release of [Hyku 3.0](https://samvera.org/2021/02/17/hyku-3-0-release-includes-new-customization-features/) and contributed to the features such as [embargo and lease options](https://github.com/samvera/hyku/pull/1648).

One of the key commitments over the past year was the work on the DOI plugin to push the code developed for Hyku version 1 to the core Hyrax codebase, then upgrade it to Hyku 3.0. This plugin includes DOI minting and fetching metadata by using DOIs. The work is ongoing at the moment and the relevant development work can be followed on github for [Hyrax](https://github.com/samvera-labs/hyrax-doi). Advancing Hyku developers were also involved in many improvements around DOIs on the DataCite github including [reading crossref DOIs](https://github.com/datacite/bolognese/pull/115), [fixing validation of funder](https://github.com/datacite/bolognese/pull/114) DOIs and [loosening the restriction on dependency versions](https://github.com/datacite/bolognese/pull/102).

More specifically for Hyku gems and plugins, the list of community contributions which Advancing Hyku developers, specifically Chris Colvard from Ubiquity Press up until July 2021, have been working together with the community developers are as follows. Our hope is that this list will help other developers to identify work already in the community codebase, enable them to implement and adopt these features in their repositories, and/or build upon existing work to make contributions back to the community codebase.

- Per-tenant configuration – [pull request 1](https://github.com/samvera/hyku/pull/1713) (unmerged) and [2](https://github.com/samvera/hyku/pull/170)
- Fix issue with creating superadmin user- [pull request ](https://github.com/samvera/hyku/pull/1712)
- Remove honeybadger dependency – [pull request ](https://github.com/samvera/hyku/pull/1669)
- Fix automated tests – [pull request](https://github.com/samvera/hyku/pull/1666)
- Improve UI for a11y – [pull request](https://github.com/samvera/hyku/pull/1665)
- Fix bug when no available work types are enabled – [pull request ](https://github.com/samvera/hyku/pull/1661)
- Upgrading version of blacklight\_oai\_provider to fix security issue and allow dynamic configuration – [pull request ](https://github.com/samvera/hyku/pull/1660)
- Upgrade to latest Hyrax 2.x – [pull request 1](https://github.com/samvera/hyku/pull/1709) and [2](https://github.com/samvera/hyku/pull/1657)
- Autorun lease/embargo expiration background jobs – [pull request](https://github.com/samvera/hyku/pull/1648)
- Maintenance – [pull request ](https://github.com/samvera/hyku/pull/1647)
- Allow overriding of presenter by plugins – [pull request 1](https://github.com/samvera/hyku/pull/1659) and[ 2](https://github.com/samvera/hyku/pull/1646)
- Development environment fix – [pull request](https://github.com/samvera/hyku/pull/1645)
- Fix issue with tenant switching – [pull request ](https://github.com/samvera/hyku/pull/1644)
- Make hyku tests runnable in plugins – [pull request](https://github.com/samvera/hyku/pull/1635)

The Advancing Hyku team is currently working on a Google analytics plugin and ORCID integration in Hyku 3. The Google analytics plugin is part of the metrics work package in the project and it has already been implemented in the local instance hosted by Ubiquity Press (UP). Next, UP will share the analytics code back to the community for adoption in Hyku 3. The author ID integration via ORCID work is part of the author profile services work package in the Advancing Hyku. With this feature, authors registered in repositories will be able to populate outputs from their institutional repository to their public ORCID profile and vice versa. This work is slated to be completed by UP by October 2021.

We share the status of Advancing Hyku features developed via the community’s shared, open [Hyku Roadmap](https://github.com/samvera/hyku/projects/1) on Samvera/ Hyku github where you can also see other project updates within the Hyku repository community.

For knowledge sharing purposes and creating synergies among the partners and other stakeholders, the Advancing Hyku team also initiated a regular, monthly developer-focused Hyku Tech Call, with the first call on July 15, 2021. The call’s aim is to work closely with other developers, share experiences and stay informed about ongoing work within the community. To join the Hyku Tech Call, contact Bertie Wooles via the Samvera Slack channel or bertie.wooles at ubiqitypress dot com.

The Advancing Hyku project is committed to practices that support community ownership over repository infrastructures together with the Samvera Community.

<sup>\[1\]</sup>*For those who would like to read further about community-owned infrastructures, there are a number of good readings, reports about the future of digital infrastructure, and active civil society organizations in the scholarly communication landscape. Here are some useful sites: [1](https://sparcopen.org/our-work/community-owned-infrastructure/), [2](https://infrastructure.sparcopen.org), [3](https://investinopen.org/about/), [4](https://www.coar-repositories.org/news-updates/), [5](https://www.arcadiafund.org.uk/promoting-open-access)*

<sup>\[2\] </sup>*Codebase: Hyku codebase allows for institutions with smaller technical resource pools to get a repository up and running quickly and maintain it efficiently; Hyrax codebase allows for institutions with more significant development resources to customise repository functionality for specific institutional requirements.*