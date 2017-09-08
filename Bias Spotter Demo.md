---
layout: default
---

*This is a demo in development*
As suggested in previous posts, I believe that a fundamental issue with the public consumption of and conflict with the American news media is often the individual's inability to confirm the veracity of an *supposedly* authoritative source. This is to say that people do not have the tools to check whether a person is correct/balanced/(insert commonplace complaint of your choice here) or not in their reporting. This, I think, actually contributes to the phenomenon of confirmation bias. If people had easily accessible tools that would lower the costs of checking information, perhaps the need to resolve to instinctual responses would decrease. This seems natural; most people would regard themselves as the ultimate authority on whether to trust information presented to them, rather than outsource this position to news anchors or political commentators. Of course, perhaps not. However, this page is an initial - due to my remedial coding skills - attempt at developing practical tools as mentioned above. The following exercise aims to improve an individual's understanding of bias in the media. Once people understand what bias is, and are confronted with this, perhaps there can be a push toward creating the avenues to find a more truthful source.

A clear difficulty with this, however, is overcoming existing political alignments and encouraging an individual to recognize failures in their personal perception. This task can really only be voluntary, and it's difficult to create tools which allow for this to occur.

For example, a tool was created a few years back that crowd-sourced opinions on biased reporting. It was a browser add-on which would allow users to highlight instances of biased reporting on various news websites and assign scores to the articles, I believe. Initially, it makes sense - crowd-sourced material from a diverse audience would hopefully result in an evening out of particular biases of users. It was popular for a few months, but failed due to the hijacking of such tools. While democratizing information makes sense in terms of accessibility, that is, on the receiving side, it perhaps devalues the meaning of authority by reducing the ability of trusted sources to identify themselves, on the producing side.

Please reach out with thoughts or with tools such as these already in existence. Again, this is only a rough example, and really offers little to no insight, and is not based in any theory whatsoever; the answer is not verified and random. It is only meant to further Javascript coding skills in the context of this project.

Take a look at [Skeptical Science](https://www.skepticalscience.com/), an excellent example of a fully developed tool which demonstrates how individuals can become their own authoritative source by confirming information heard. While easily accessible, it's likely that many people have not heard of this source.

Click the button when you record an instance of biased reporting.

{% include youtubePlayer.html id="puNQMJmWk7o" %}
<script>
var clicks = 0;
function onClick() {
    clicks += 1;
    document.getElementById("clicks").innerHTML = clicks;
};
</script>
<button type="button" onClick="onClick()">Bias!</button>
<p>This clip has <a id="clicks">0</a> instances of biased reporting.</p>

<script>
function result() {
  if (clicks == 23) {
      alert("Congratulations!");
    } else {
      alert("Sorry! It was 23; read about bias below!");  
    }
  }
</script>

<button onClick="result()">Find out!</button>
