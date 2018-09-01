# KickStarter-NLP-Analysis
## Introduction:

> Kickstarter is an American public-benefit corporation[2] based in Brooklyn, New York, that maintains a global crowdfunding platform focused on creativity and merchandising.[3] The company's stated mission is to "help bring creative projects to life".[4] Kickstarter has reportedly received more than $1.9 billion in pledges from 9.4 million backers to fund 257,000 creative projects, such as films, music, stage shows, comics, journalism, video games, technology and food-related projects.[5]
People who back Kickstarter projects are offered tangible rewards or experiences in exchange for their pledges.[6] This model traces its roots to subscription model of arts patronage, where artists would go directly to their audiences to fund their work.[7][Wikipedia](https://en.wikipedia.org/wiki/Kickstarter)

So, with the help of the crawlers of [webrobots](https://webrobots.io/kickstarter-datasets/), we got all the data from the run along 2017 kickstater projects and keep just those written in english and finished either as "successful" or "failed", and two columns:

- the one with the blurb or short description of the project [text]
- the one with the final state: "successful" if the project got the money goal in time or "failed" if don't [factor]

