<style type="text/css">
body {background-color:black;color:white;}
a {color:white}
</style>

<center>
  <br>
  2026/06/27 - <b>Information Theory applied to Protocol Specification Design: learnings from maintenance and refining of Stratum V2 Spec</b>
  <br>
</center>
<hr>

During my undergrad years studying Electronics Engineering, I learned about [Claude Shannon](xxx)'s seminal work titled [xxx](yyy). The idea of being able to <b>quantify information </b> fascinated me deeply. I felt Shannon's work was not only extremely elegant, but it also resonated with me on deeply.

That inspired me to briefly pursue some undergrad-level academic research in the field of Biomedical Engineering, hoping that eventually I'd be able to apply these concepts onto mapping the human brain. I worked on some research on biological signal processing, but my interest kinda faded and my professional career ended up going in different directions.

More recently, I watched [3b1b's video titled ](xxx). I've been using Large Language Models (a.k.a. LLMs) to assist my maintanence work on [Stratum V2 Specification](https://github.com/stratum-mining/sv2-spec) for a bit over 2 years now, but up until then I had never been exposed the Information-Theoretical foundations of LLMs. Watching this video made me feel like something clicked deep inside my brain again. It reignited my interest for Information Theory, and also inspired me to write this blogpost.

Perhaps I should make it explicitly clear that <b>I'm not the author of the Sv2 Spec</b>. In fact, I started contributing to the project a few years after the first draft had already been written. I started with naive eyes: "this protocol has a specification, so it's probably written-in-stone, so to speak" was my initial thinking.

Unfortunately, that wasn't true. As my contributions on the Reference Implementation got deeper, I would often find myself in uncomfortable positions such as:
- I couldn't clearly understand how to treat some specific edge case.
- I would have interpretations that would conflict with what other implementers/contributors/maintainers would interpret.
- xxx
- yyy

Now I should also make it explicitly clear that this is not meant to be interpreted as a critique of the authors' work. In fact, the authors hold credentials such as running the [first ever Bitcoin mining pool](xxx) and implementing an innovative system for [xxx betterhash todo](xxx). The original Sv2 Spec draft established solid foundations of the protocol. From it, anyone with some basic understanding of Bitcoin mining can get a good grasp over the authors' original intent.

But yeah, there were rough edges. So the scope of my contributions started expanding from the Reference Implementation into the Spec itself. I spent countless hours drawing diagrams to visualize protocol message flow, gaming out edge cases and re-reading/re-writing the sentences until I knew there was absolutely no room for ambiguity on how the spec should be interpreted.

Here I should also make it explicitly clear that I've never been the <b>sole maintainer</b> of the Sv2 Spec. There's extremely valuable work done from other maintainers as well.

But yeah, I also cannot say my work there is done yet, because every now and then I still stumble upon some rough edges. Which brings me to a very important point:

I do believe that there does exist a <b>Perfect Sv2 Protocol</b> in the realm of ideas, and that it is humanly possible to materialize it into an actual Specification document. And here it's important to emphasize that I'm not using the word "perfect" in a very specific and objective way. Hopefully this concept will be clear by the end of this essay, but while we don't get there, I will clarify that by <b>Perfect Sv2 Protocol</b> I DO NOT mean:
- there's no fundamental trade-offs on the protocol design
- the protocol is superior to alternative approaches on the design space of decentralizing Bitcoin mining

xxx

key concepts:
- Interpretation Entropy
- 

xxx

<hr>

Note: this blogpost was written by a human, but with help from LLM models such as:
- GPT-5.3-Codex
- DeepSeek V4 Pro
- X

LLM help consisted mostly of:
- x
- y
- z

<center>
  <hr>

  <a href="../../index.html">home</a>
  <br>
</center>