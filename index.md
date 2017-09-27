---
layout: default
description: ''
---

## Introduction

<div style="text-align: justify">
<p>Everyday interactions require a common understanding of language, i.e. for people to communicate effectively, words (for example ‘cat’) should invoke similar beliefs over physical concepts (what cats look like, the sounds they make, how they behave, what their skin feels like etc.). However, how this ‘common understanding’ emerges is still unclear.
One appealing hypothesis is that language is tied to how we interact with the environment. As a result, meaning emerges by ‘grounding’ language in modalities in our environment (images, sounds, actions, etc.).</p>

<p>Recent concurrent works in machine learning have focused on bridging visual and natural language understanding through visually-grounded language learning tasks, e.g. through natural images (Visual Question Answering, Visual Dialog), or through interactions with virtual physical environments. In cognitive science, progress in fMRI enables creating a semantic atlas of the cerebral cortex, or to decode semantic information from visual input. And in psychology, recent studies show that a baby’s most likely first words are based on their visual experience, laying the foundation for a new theory of infant language acquisition and learning.</p>

<p>As the grounding problem requires an interdisciplinary attitude, this workshop aims to gather researchers with broad expertise in various fields -- machine learning, computer vision, natural language, neuroscience, and psychology -- and who are excited about this space of grounding and interactions, and who are willing to share their current work or perspectives on future directions.</p></div>

## Invited Speakers

<table>
    <tr>
        <th>
        <img class='im-speaker-pic' src='images/sanja-fidler-dp.jpg' alt='sanja-fidler'>
        </th>
        <th class='speaker-bio'>
        <b>Sanja Fidler</b> is an Assistant Professor at University of Toronto.
        Her main research interests are 2D and 3D object detection, particularly 
        scalable multi-class detection, object segmentation and image labeling, 
        and (3D) scene understanding.
        She is also interested in the interplay between language and vision.
        <a href='http://www.cs.utoronto.ca/~fidler/'>[Webpage]</a>
        </th>
    </tr>
    <!-- <tr>
        <th>
        <img class='im-speaker-pic' src='images/jack-gallant-dp.jpg' alt='jack-gallant'>
        </th>
        <th class='speaker-bio'>
        <b>Jack L. Gallant</b> is a Professor in the Department of Psychology at
        University of California, Berkeley.
        The focus of research in his laboratory is on understanding the structure
        and function of the visual system.
        <a href='http://psychology.berkeley.edu/people/jack-l-gallant'>[Webpage]</a>
        </th>
    </tr> -->
    <tr>
        <th>
        <img class='im-speaker-pic' src='images/felix-hill-dp.jpg' alt='felix-hill'> 
        </th>
        <th class='speaker-bio'>
        <b>Felix Hill</b> is a Research Scientist at DeepMind.
        He works on models and algorithms for extracting and representing
        semantic knowledge from text and other naturally occurring data.
        <a href='https://www.cl.cam.ac.uk/~fh295/'>[Webpage]</a>
        </th>
    </tr>
    <tr>
        <th>
        <img class='im-speaker-pic' src='images/raymond-mooney-dp.jpg' alt='raymond-mooney'>
        </th>
        <th class='speaker-bio'>
        <b>Raymond J. Mooney</b> is a Professor of Computer Science at The University of Texas at Austin and leads the Machine Learning Research Group within UT Artificial Intelligence Laboratory.
        His current focus is on natural language processing / computational linguistics.
        <a href='https://www.cs.utexas.edu/~mooney/'>[Webpage]</a>
        </th>
    </tr>
    <tr>
        <th>
        <img class='im-speaker-pic' src='images/devi-parikh-dp.jpg' alt='devi-parikh'>
        </th>
        <th class='speaker-bio'>
        <b>Devi Parikh</b> is an Assistant Professor in the School of 
        Interactive Computing at Georgia Tech, and a Research Scientist 
        at Facebook AI Research (FAIR).
        Her research interests include computer vision and AI in general
        and visual recognition problems in particular.
        <a href='https://www.cc.gatech.edu/~parikh/'>[Webpage]</a>
        </th>
    </tr>
    <tr>
        <th>
        <img class='im-speaker-pic' src='images/olivier-pietquin-dp.jpg' alt='olivier-pietquin'>
        </th>
        <th class='speaker-bio'>
        <b>Olivier Pietquin</b> is with DeepMind in London. His research interests
        include spoken dialog systems evaluation, simulation and automatic 
        optimization, machine learning (especially direct and inverse 
        reinforcement learning), speech and signal processing.
        <a href='http://www.lifl.fr/~pietquin/'>[Webpage]</a>
        </th>
    </tr>
    <!-- <tr>
        <th>
        <img class='im-speaker-pic' src='images/linda-smith-dp.jpg' alt='linda-smith'>
        </th>
        <th class='speaker-bio'>
        <b>Linda Smith</b> is a Professor at the Department of Pyschological and
        Brain Sciences at Indiana University Bloomington.
        Her research is on perceptual and cognitive development in infancy and
        young children, the development of visual object recognition, word learning.
        <a href='http://psych.indiana.edu/faculty/smith4.php'>[Webpage]</a>
        </th>
    </tr> -->
</table>

## Important Dates

3rd November 2017: Submission deadline

10th November 2017: Acceptance notification

8th December 2017: Workshop

## Submission Details

We invite you to submit papers related to the following topics:
- language acquisition or learning through interactions
- visual captioning, dialog, and question-answering
- reasoning in language and vision
- visual synthesis from language
- transfer learning in language and vision tasks
- navigation in virtual worlds with natural-language instructions
- machine translation with visual cues
- novel tasks that combine language, vision and actions
- understanding and modeling the relationship between language and vision in humans
- semantic systems and modeling of natural language and visual stimuli representations in the human brain

<!-- We accept research papers on a multimodal grounding problem from various disciplines: machine learning, computer vision, natural language processing, neuroscience, cognitive science, and psychology. -->

Submissions should be up to 4 pages excluding references, acknowledgements, and supplementary material, and should be in the <a href='https://nips.cc/Conferences/2017/PaperInformation/StyleFiles'>NIPS format</a>. We also welcome published papers that are within the scope of the workshop (without re-formatting).

Accepted papers will be presented during 2 poster sessions, and up to 5 will be invited to deliver short talks. Accepted papers will be made publicly available as non-archival reports, allowing future submissions to archival conferences or journals.

Please submit your paper to the following address: nips2017vigil@gmail.com

## Detailed Description

<div style="text-align: justify">
<p>Statistical language models learned from text-only corpuses form the dominant paradigm in modern natural language understanding. Many popular models of this type (including GloVe and word2vec) are distributional, i.e. the "meaning" of words is based only on their co-occurence patterns with other words in similar context. While effective for many applications, these text-only distributional approaches suffer from limited semantics as they miss the interactive environment in which communication often takes place, i.e., its symbols are not grounded. This limitation was first highlighted with the symbol grounding problem: "meaningless symbols (i.e. words) cannot be grounded in anything but other meaningless symbols" [16].</p>

<p>Humans, on the other hand, acquire and learn language by communicating about and interacting with the visual environment. This behavior provides the necessary grounding of physical concepts in words. To this end, several recent works study grounded language-learning tasks, e.g. grounding in natural images (ReferIt [1], GuessWhat?! [2], Visual Question Answering [3,4], Visual Dialog [5], Captioning [6]) or grounding in a physically-simulated environment (DeepMind Lab [7], Baidu XWorld [8], OpenAI Universe [9]). We believe this line of research is more suited for human-machine collaboration than unimodal approaches that ignore the grounding aspect.</p>

<p>From a modeling perspective, deep learning approaches are promising for grounding because they are capable of learning high-level semantics from low-level sensory data in both computer vision and language. Subsequently, deep learning turns out to be an efficient tool for fusing different modalities into a single representation [3,4]. In addition, as grounded language acquisition requires to interact with an external environment, reinforcement learning provides an elegant framework to cover the planning aspect of visually grounded dialogue as well as other goal-oriented tasks. There has been some recent effort on combining deep learning and reinforcement learning approaches in various grounding scenarios [10,11,12].</p>

<p>Research in understanding human behavior provides yet another perspective in building models capable of grounded language-learning. In cognitive science, recent progress in fMRI enables us to create a semantic atlas of the cerebral cortex [13] or to learn to decode semantic information from visual input [14]. In one study, psychologists followed blind children and show that they are not linguistically deficient. Despite the lack of visual stimuli, blind children manage to use visual concepts such as colors or visual verbs ("see" or "look") [15] and circumvent their visual impairment through unique strategies [17].</p>

<p>This workshop aims to gather people from backgrounds in machine learning, computer vision, natural language, neuroscience, and psychology, who are excited about this space of grounding and interaction, and are willing to share ideas from their work and perspectives on future directions.</p>
</div>

## Organizers

<table class='organizer-pics-four'>
    <tr>
        <td>
        <img class='im-speaker-pic' src='images/florian-strub-dp.jpeg' alt='florian'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/harm-devries-dp.jpg' alt='harm'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/abhishek-das-dp.jpg' alt='abhishek'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/satwik-kottur-dp.jpg' alt='satwik'>
        </td>
    </tr>
    <tr>
        <td><a href='http://www.florian-strub.com'>Florian Strub</a> <br> University of Lille, Inria </td>

        <td><a href='http://www-etud.iro.umontreal.ca/~devries/'>Harm de Vries</a> <br>
        University of Montreal </td>

        <td><a href='https://abhishekdas.com'>Abhishek Das</a> <br>
        Georgia Tech </td>

        <td> <a href='https://satwikkottur.github.io/'>Satwik Kottur</a> <br>
        Carnegie Mellon</td>
    </tr>
    <tr>
        <td>
        <img class='im-speaker-pic' src='images/stefan-lee-dp.png' alt='stefan'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/mateusz-malinowski-dp.jpeg' alt='mateusz'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/olivier-pietquin-dp.jpg' alt='olivier'>
        </td>

        <td></td>
    </tr>
    <tr>
        <td><a href='https://www.cc.gatech.edu/~slee3191'>Stefan Lee</a> <br>
        Georgia Tech </td>

        <td><a href='http://www.mateuszmalinowski.com'>Mateusz Malinowski</a> <br>
        DeepMind</td>

        <td><a href='http://www.lifl.fr/~pietquin/'>Olivier Pietquin</a> <br>
        DeepMind</td>

        <td></td>
    </tr>
    <tr>
        <td>
        <img class='im-speaker-pic' src='images/devi-parikh-dp.jpg' alt='devi'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/dhruv-batra-dp.jpg' alt='dhruv'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/aaron-courville-dp.jpg' alt='aaron'>
        </td>
        <td>
        <img class='im-speaker-pic' src='images/jeremie-mary-dp.jpg' alt='jeremie'>
        </td>
    </tr>
    <tr>
        <td><a href='http://www.cc.gatech.edu/~parikh/'>Devi Parikh</a><br>
        Georgia Tech &amp; Facebook AI Research</td>

        <td><a href='http://www.cc.gatech.edu/~dbatra/'>Dhruv Batra</a> <br>
        Georgia Tech &amp; Facebook AI Research</td>

        <td><a href='https://mila.quebec/en/person/aaron-courville/'>Aaron Courville</a> <br>
        University of Montreal<br>&nbsp;</td>

        <td><a href='http://www.grappa.univ-lille3.fr/~mary/'>Jeremie Mary</a> <br>
        Criteo<br>&nbsp;</td>
    </tr>
</table>

## Sponsors

<div id="sponsors" style="text-align:center;">
    <p><a href="https://research.fb.com/">
    <img class="fblogo" border="0" style="display: inline-block; margin-left: auto; margin-right: auto; height: 30px;" src="https://research.fb.com/wp-content/themes/fb-research/images/branding/fb-research-logo-2x.png"/></a></p>
    <p><a href="https://deepmind.com/">
    <img class="fblogo" border="0" style="display: inline-block; margin-left: auto; margin-right: auto; height: 45px;" src="https://deepmind.com/static/v0.0.0/images/deepmind_logo.png"/></a></p>
</div>

we would also like to acknowledge the following institutions that supported us:
- CHIST-ERA project "Interactive Grounded Language Understanding" [IGLU](https://iglu-chistera.github.io/)


## References
<div>
    <ol>
        <li>Kazemzadeh, Sahar, et al. "ReferIt Game: Referring to Objects in Photographs of Natural Scenes". EMNLP. 2014.</li>
        <li>de Vries, Harm, et al. "GuessWhat?! Visual Object Discovery through Multi-modal Dialogue". CVPR. 2017.</li>
        <li>
            Antol, Stanislaw, et al. "VQA: Visual Question Answering". ICCV. 2015.
        </li>
        <li>
            Malinowski, Mateusz, et al. "Ask Your Neurons: A Neural-based Approach to Answering Questions about Images". ICCV. 2015.
        </li>
        <li>
            Das, Abhishek, et al. "Visual Dialog". CVPR. 2017.
        </li>
        <li>
            Rohrbach, Anna, et. al. "Generating Descriptions with Grounded and Co-Referenced People". CVPR. 2017.
        </li>
        <li>
            Beattie, Charles, et. al. <a href="https://deepmind.com/blog/open-sourcing-deepmind-lab/">"DeepMind Lab".</a> 2016.
        </li>
        <li>
            Yu, Haonan, et al. "A Deep Compositional Framework for Human-like Language Acquisition in Virtual Environment". arXiv preprint arXiv:1703.09831. 2017.
        </li>
        <li>
            OpenAI. <a href="https://universe.openai.com/">"Universe".</a> 2016. 
        </li>
        <li>
            Strub, Florian, et al. "End-to-end Optimization of Goal-driven and Visually Grounded Dialogue Systems". IJCAI. 2017.
        </li>
        <li>
            Das, Abhishek, et al. "Learning Cooperative Visual Dialog Agents with Deep Reinforcement Learning". ICCV. 2017.
        </li>
        <li>
            Hermann, Karl Moritz, et al. "Grounded Language Learning in a Simulated 3D World". arXiv preprint arXiv:1706.06551. 2017.
        </li>
        <li>
            Huth, Alexander G., et al. "Natural Speech Reveals the Semantic Maps that Tile Human Cerebral Cortex". Nature 532.7600 (2016): 453-458. 2016.
        </li>
        <li>
            Huth, Alexander G., et al. "Decoding the Semantic Content of Natural Movies from Human Brain Activity". Frontiers in systems neuroscience 10. 2016.
        </li>
        <li>
            Landau, Barbara, et al. "Language and Experience: Evidence from the Blind Child". Vol. 8. Harvard University Press. 2009.
        </li>
        <li>
            Harnad, Stevan. "The Symbol Grounding Problem". Physica D. 1990.
        </li>
        <li>
            Perez-Pereira et al. "Language Development and Social Interaction in Blind Children". Psychology Press. 2013.
        </li>
    </ol>
</div>


