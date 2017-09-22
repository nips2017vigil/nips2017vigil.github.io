---
layout: default
---

## Introduction
<div style="text-align: justify">
<p>Among the most important aspects of many multimodal tasks -- such as Visual Dialogue, Physical Interactions, or Visual Question Answering -- is the grounding problem that seeks the "meaning" by connecting meaningless symbols with meaningless symbols in another domain.</p>

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
        <b>Felix Hill</b> is a Research Scientist at Google DeepMind.
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
        <b>Olivier Pietquin</b> is with Google DeepMind in London. His research interests
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
        <td><a>Florian Strub</a> <br> University of Lille, Inria </td>

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

## References
<div>
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
            Beattie, Charles, et. al. <a href="https://deepmind.com/blog/open-sourcing-deepmind-lab/">"DeepMind Lab."</a> 2016.
        </li>
        <li>
            Yu, Haonan, et al. "A Deep Compositional Framework for Human-like Language Acquisition in Virtual Environment." arXiv preprint arXiv:1703.09831. 2017.
        </li>
        <li>
            OpenAI. <a href="https://universe.openai.com/">"Universe."</a> 2016. 
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
