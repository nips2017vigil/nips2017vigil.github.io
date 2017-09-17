---
layout: default
---

## Introduction

Statistical language models learned from text-only corpuses form the dominant paradigm in modern natural language understanding. Many popular models of this type (including GloVe and word2vec) are distributional, i.e. the "meaning" of words is based only on their co-occurence patterns with other words in similar context. While effective for many applications, these text-only distributional approaches suffer from limited semantics as they miss the interactive environment in which communication often takes place, i.e., its symbols are not grounded. This limitation was first highlighted with the symbol grounding problem: "meaningless symbols (i.e. words) cannot be grounded in anything but other meaningless symbols" [16].

Humans, on the other hand, acquire and learn language by communicating about and interacting with the visual environment. This behavior provides the necessary grounding of physical concepts in words. To this end, several recent works study grounded language-learning tasks, e.g. grounding in natural images (ReferIt [1], GuessWhat?! [2], Visual Question Answering [3,4], Visual Dialog [5], Captioning [6]) or grounding in a physically-simulated environment (DeepMind Lab [7], Baidu XWorld [8], OpenAI Universe [9]). We believe this line of research is more suited for human-machine collaboration than unimodal approaches that ignore the grounding aspect.

From a modeling perspective, deep learning approaches are promising for grounding because they are capable of learning high-level semantics from low-level sensory data in both computer vision and language. Subsequently, deep learning turns out to be an efficient tool for fusing different modalities into a single representation [3,4]. In addition, as grounded language acquisition requires to interact with an external environment, reinforcement learning provides an elegant framework to cover the planning aspect of visually grounded dialogue as well as other goal-oriented tasks. There has been some recent effort on combining deep learning and reinforcement learning approaches in various grounding scenarios [10,11,12]. 

Research in understanding human behavior provides yet another perspective in building models capable of grounded language-learning. In cognitive science, recent progress in fMRI enables us to create a semantic atlas of the cerebral cortex [13] or to learn to decode semantic information from visual input [14]. In one study, psychologists followed blind children and show that they are not linguistically deficient. Despite the lack of visual stimuli, blind children manage to use visual concepts such as colors or visual verbs ("see" or "look") [15] and circumvent their visual impairment through unique strategies [17].

This workshop aims to gather people from backgrounds in machine learning, computer vision, language, neuroscience and psychology, who are excited about this space of grounding and interaction, and are willing to share ideas from their work and perspectives on future directions.

<div class="small">
    <ol>
        <li>Kazemzadeh, Sahar, et al. "ReferIt Game: Referring to Objects in Photographs of Natural Scenes." EMNLP. 2014.</li>
        <li>de Vries, Harm, et al. "GuessWhat?! Visual object discovery through multi-modal dialogue." CVPR. 2017.</li>
        <li>
            Antol, Stanislaw, et al. "VQA: Visual question answering." ICCV. 2015.
        </li>
        <li>
            Malinowski, Mateusz, et al. "Ask Your Neurons: A Neural-based Approach to Answering Questions about Images." ICCV. 2015.
        </li>
        <li>
            Das, Abhishek, et al. "Visual Dialog." CVPR. 2017.
        </li>
        <li>
            Rohrbach, Anna, et. al. "Generating Descriptions with Grounded and Co-Referenced People." CVPR. 2017.
        </li>
        <li>
            "DeepMind Lab. <a href="https://deepmind.com/blog/open-sourcing-deepmind-lab/">https://deepmind.com/blog/open-sourcing-deepmind-lab/</a>
        </li>
        <li>
            Yu, Haonan, et al. "A Deep Compositional Framework for Human-like Language Acquisition in Virtual Environment." arXiv preprint arXiv:1703.09831. 2017.
        </li>
        <li>
            "OpenAI Universe." https://universe.openai.com/
        </li>
        <li>
            Strub, Florian, et al. "End-to-end optimization of goal-driven and visually grounded dialogue systems." IJCAI. 2017.
        </li>
        <li>
            Das, Abhishek, et al. "Learning Cooperative Visual Dialog Agents with Deep Reinforcement Learning." ICCV. 2017.
        </li>
        <li>
            Hermann, Karl Moritz, et al. "Grounded Language Learning in a Simulated 3D World." arXiv preprint arXiv:1706.06551. 2017.
        </li>
        <li>
            Huth, Alexander G., et al. "Natural speech reveals the semantic maps that tile human cerebral cortex." Nature 532.7600 (2016): 453-458.
        </li>
        <li>
            Huth, Alexander G., et al. "Decoding the semantic content of natural movies from human brain activity." Frontiers in systems neuroscience 10 (2016).
        </li>
        <li>
            Landau, Barbara, et al. Language and experience: Evidence from the blind child. Vol. 8. Harvard University Press, 2009.
        </li>
        <li>
            Harnad, Stevan. The symbol grounding problem. 1999.
        </li>
        <li>
            Perez-Pereira et al. Language development and social interaction in blind children. Psychology Press, 2013.
        </li>
    </ol>
</div>

## Invited Speakers

(To be announced)

## Important Dates

3rd November 2017: Submission deadline

10th November 2017: Acceptance notification

## Organizers

Florian Strub, University of Lille, Inria

[Harm de Vries](http://www-etud.iro.umontreal.ca/~devries/), University of Montreal

[Abhishek Das](https://abhishekdas.com), Georgia Tech

[Satwik Kottur](https://satwikkottur.github.io/), Carnegie Mellon University

[Stefan Lee](https://www.cc.gatech.edu/~slee3191), Georgia Tech

[Mateusz Malinowski](https://www.mateuszmalinowski.com), Google DeepMind

[Olivier Pietquin](http://www.lifl.fr/~pietquin/), Google DeepMind

[Devi Parikh](http://www.cc.gatech.edu/~parikh/), Georgia Tech &amp; Facebook AI Research

[Dhruv Batra](http://www.cc.gatech.edu/~dbatra/), Georgia Tech &amp; Facebook AI Research

[Aaron Courville](https://mila.quebec/en/person/aaron-courville/), University of Montreal

[Jeremie Mary](http://www.grappa.univ-lille3.fr/~mary/), Criteo
