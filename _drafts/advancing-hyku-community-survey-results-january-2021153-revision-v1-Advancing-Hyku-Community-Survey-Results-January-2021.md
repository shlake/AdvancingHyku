---
id: 170
title: 'Advancing Hyku Community Survey Results, January 2021'
date: '2020-12-14T15:20:34+00:00'
author: 'Ellen Ramsey'
layout: revision
guid: 'https://advancinghyku.io/2020/12/14/153-revision-v1/'
permalink: '/?p=170'
---

Results of the [survey](https://advancinghyku.io/2020/11/05/advancing-hyku-at-samvera-connect-2020-your-vote-matters/) we conducted last month across current and prospective members of the Samvera Community are in!

#### Top level takeaways:

As was our hope, we received confirmation that community contributions of features on our requirements list will allow the Advancing Hyku project jump ahead to other development, and limit creating duplicate implementations of already existing features across different community projects contributing back to the same core code. We also sought out responses from non-Hyrax/Hyku repository (e.g. Bepress DC users) indicating what is essential for them to continue interest in Hyku and remain engaged as potential future Samvera-Hyku adopters.

#### Adjustments we have already made:

1. OAI-PMH moved earlier in our roadmap due to strong support for this feature from survey respondents. Much of its functionality is already in the next release of Hyrax, so easier metadata interoperability across repositories (both institutional and external) is close at hand.
2. Respondents told us user experiences with viewing content via browser is more important than uploading and downloading files (Feature #20), so we are moving the file interaction work later in our roadmap. Examples given of respondent viewing priorities are as follows; viewing file in browser option and use Universal view for PDFs, full text search and indexing, filtering by date.

#### Findings impacting future work:

3. We have written in a [previous post about metrics and analytics](https://advancinghyku.io/2020/09/18/project-update-september-2020/) that getting clarity on those across community projects is a continual need. Applying survey results about work going on in our project and others looks like:
    - Current metrics in the Advancing Hyku test repository (we call it “Butterscotch” since it is a little more built out than just a “plain vanilla” sandbox) are what come out of the box with Hyrax 2.
    - The Oregon Digital Hyrax Analytics project has stats reporting mailer (Feature #16) and also more advanced repository analytics (Feature #17) on their roadmap. The lightweight repository-wide statistics are sufficient for Advancing Hyku’s requirements, so we will leave development of more complete aggregate repository statistics to our collaborators in Oregon.
4. Multiple work types progress is happening in the community: Since both we and Hyku for Consortia have nearly this exact feature on both our roadmaps, we will coordinate (or at least flip a coin).
5. Even though the intention of Hyku is that is be ready for common repository use scenarios without a lot of configuration, survey responses confirmed that Many features that are specific to repository type (IR vs collections) so at least some features should be able to be toggled on or off during configuration, for example:
    - Title availability checker (only for self-deposit repos)
    - Cross-tenant search (only for multi-tenant implementations)
6. Further, not every implementation will need to be multi-tenant. Heavy emphasis in the Samvera-Hyku community of late on multi-tenancy has obscured need for easy implementation for single tenant instances, our survey re-surfaced the continued need by potential adopters for easy setup of a hosted basic repository for a single institution.

Please [see the list of features](https://docs.google.com/document/d/1efJN_K0zmjeeHyzuojeV5fb05pJdd5-qcmNyVCfAYeM/edit?usp=sharing) covered in the survey including relevant user stories. Here is a visualization of all results, ordered by priority:

<div class="wp-block-image"><figure class="aligncenter size-large">![](https://advancinghyku.io//srv/htdocs/wp-content/uploads/2020/12/AH-feature-prioritization-survey-results-Dec2020-1024x417.png)<figcaption>Advancing Hyku feature prioritization survey results, December 2020</figcaption></figure></div>As always, questions, input, and offers of help [welcome and encouraged](https://advancinghyku.io/contact/).

-Ilkay Holt and Ellen Ramsey for Advancing Hyku