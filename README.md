# Discussion leader assignment for Comp 417/517

In this assignment you will lead discussions and be
responsible for the following three elements:

1. Fill out paper review form
2. Short presentation highlighting key moves and
   contributions of the paper 
3. Facilitating discussion. 
 
## Review Form (25%)

Fill out and commit by midnight the night before: 

[Standard Review Form](./review.md)

Note for most of these sections, concision is preferred.
Provide 1-2 sentences if possible, of course go over if you
need.

## Presentation (25%)

The goal of leading the presentation is to format your
understanding of the paper from the perspective of a
critical reader. It is more an exercise to capture that
you've extracted the critical elements from the paper, as
well as a quick refresher to the class. 

The following slides are expected:

1. Title Page
2. Problem and Motivation
3. Why isn't it solved?
4. The key hypothesis of this paper?
5. The methods used to achieve it (how)?
6. The evaluation results
7. Key takeaways

The presentation should take between 5-12 minutes.

**Presentation: https://docs.google.com/presentation/d/1rqkd_GjiU5JAsozomKO6H0U8f70Wo0y9neEbNwB6nYg/edit?usp=sharing**

## Discussion Leading (25%)

Develop 5-7 questions after reviewing the online discussion
and lead an initial 15 minute small group and a larger 15
minute discussion.

- Do you think the problem and criteria for performance were properly defined?
- What did you think the level of isolation for VServer? Should each VM include more features or less?
- Why did Xen perform so horribly in I/O. Did this have to do with hypervisors in general or Xen’s specific implementation?
- Did this paper commit any benchmarking crimes?
- Specifically, were the techniques used to benchmark scalability appropriate?
- What areas of improvement do you see for the containerization approach?
- Is containerization only useful for OS virtualization or are there any adjacent areas where this paper could have an impact?
- Split the class in half. Each think of three systems where Xen is better and three where Server is better respectively.  Now argue against one of the other teams scenarios.

## Discussion Debrief (25%)

Answer the following questions: 

1. What new insights came out of the discussion?

I think the insights were exploring and brainstorming the practical use cases for these technologies.

2. Was there disagreement? Why?

We argued ab whether hypervisors could virtualize hardware arch for a while, but nobody really new the answer. Other than that, we mostly agreed as a unit.

3. What was the consensus about the work?

In general we decided that hypervisors were better for vulnerable apps, multikernel, customization, and portability. Containers were way better for efficiency.

4. Follow Up Questions for Nathan

- Where the Xen I/O deficiencies due to the benchmarking techniques, the specifics of Xen's implementation, or general hypervisor design?
- Hypervisors can run different kernels easily, but can they also virtualize different architectures (ie. simulate ARM on an x86 hardware and vice versa)?
