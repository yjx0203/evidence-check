# Evidence Check

**README prose word count:** 264

Evidence Check is a browser prototype for checking whether a cited passage supports a simulated AI claim about convolution output size.

## Project status

- Implemented: case selection, claim and passage display, source details, judgment submission, worked feedback and revision.
- Simulated: two preset AI claims linked to one teaching note written for this demonstration. Both reference judgments and explanations are prewritten.
- Planned: live retrieval and model-generated claims for a larger collection of course material.

## Technology and setup

The prototype uses HTML, CSS and vanilla JavaScript in [evidence-check.html](evidence-check.html). It uses no runtime model, dependencies or API key.

Download the HTML file and open it in a browser. In each case, compare the claim and passage, choose a judgment and select **Check my judgment**. Select **Change my judgment** to revisit your choice.

## Development record

1. Scoped the Assignment 1 proposal to two claims that share one passage. This makes the difference between supported and unsupported wording easy to inspect.
2. Built the side-by-side view, submit-to-reveal feedback and revision control. Checked both stored verdicts, the calculations and the script’s reset and resubmission behaviour.
3. Opened the prototype in Microsoft Edge on Windows, submitted both judgments and captured the screens before and after submission. Both cases showed the intended worked explanations.

## AI assistance

I used ChatGPT (Codex) to help scope the prototype, draft the HTML, CSS and JavaScript, and prepare the report and README. I opened the prototype in Edge, selected and submitted both judgments, and captured the interaction states. I compared the displayed feedback with the formula.

## Additional files

The course report is submitted separately and contains the system diagram and storyboards. The HTML file contains everything needed to replay the prototype.
