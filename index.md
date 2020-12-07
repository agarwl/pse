---
title: 'Contrastive Behavioral Similarity Embeddings for Generalization in Reinforcement Learning'
layout: default
---

<style>thead { display: none; }</style>

<p class="cover" align="center"> <img src="assets/behavioral_similarity.png" /> </p>

Reinforcement learning methods trained on few environments rarely learn policies that generalize to unseen environments. To improve generalization, we incorporate the inherent sequential structure in reinforcement learning into the representation learning process. This approach is orthogonal to recent approaches, which rarely exploit this structure explicitly. Specifically, we introduce a theoretically motivated policy similarity metric (PSM) for measuring behavioral similarity between states. PSM assigns high similarity to states for which the optimal policies in those states as well as in future states are similar. We also present a contrastive representation learning procedure to embed any state similarity metric, which we instantiate with PSM to obtain policy similarity embeddings (PSEs). We demonstrate that PSEs improve generalization on diverse benchmarks, including LQR with spurious correlations, a jumping task from pixels, and Distracting DM Control Suite.


Citing
------
To cite this paper, please use the following reference:

    @inproceedings{agarwal2021pse,
      title={Contrastive Behavioral Similarity Embeddings for Generalization in Reinforcement Learning},
      author={Agarwal, Rishabh and C. Machado, Marlos and Samuel Castro, Pablo and G. Bellemare, Marc},
      year={2020}
    }


## Authors

<div style="text-align: left;">
{%- for person in site.data.authors -%}
<div class="person">
  <img src="{{ person.image }}" />
  <a href="{{ person.url | relative_url }}">{{ person.name }}</a><br>
  <span>{{ person.title | replace: '&', '<br>' }}</span>
  <!--span>({{ person.topics }})</span-->
</div>
{%- endfor -%}
</div>


<p style="text-align: left">
For questions, please contact us at:
<a href="mailto:rishabhagarwal@google.com">rishabhagarwal@google.com</a>.
</p>
