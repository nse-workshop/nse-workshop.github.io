---
layout: default
permalink: /

speakers:
  - name: Keynote Speaker 1

  - name: Keynote Speaker 2

  - name: Keynote Speaker 3

organizers:
  - name: Christian Medeiros Adriano
    url: https://hpi.de/giese/people/christian-medeiros-adriano.html
    affiliation: Hasso Plattner Institute, University of Potsdam, Germany
    image: assets/img/christian-adriano.jpg

  - name: Sona Ghahremani
    url: https://hpi.de/en/giese/people/sona-ghahremani.html
    affiliation: Hasso Plattner Institute, University of Potsdam, Germany
    image: assets/img/sona.jpg

  - name: Daiki Kimura
    url: https://researcher.watson.ibm.com/researcher/view.php?person=jp-DAIKI
    affiliation: IBM Research - Tokyo <br> <i>(primary contact)</i>
    image: assets/img/Daiki_Kimura.jpg

  - name: Rubén Ruiz-Torrubiano
    url: https://research.imc.ac.at/de/persons/ruben-ruiz-torrubiano
    affiliation: IMC Krems University of Applied Sciences, Austria
    image: assets/img/ruben.png

   

pcs:
  - name: Lucas Sakizloglou
    affiliation: Brandenburg University of Technology, Germany

  - name: Holger Giese
    affiliation: Hasso Plattner Institue, Germany

---

# Workshop Description


 The software engineering community has a strong history on symbolic methods (formal methods, programming languages, etc.) and, more recently, has been quickly adopting machine learning techniques in most of its tasks like automated program repair, program synthesis, code generation & summarization and verification planning.  Many have also taken note of the possibilities of combining the strengths of symbolic and learning techniques, for instance, in the engineering complex software in autonomic, self-adaptive systems, and multi-agents systems as well improving automated methods for bug fixing, code review, and test generation. 
    
We plan to collect experiences, challenges, and solutions involved in combining symbolic methods and machine learning to tackle new and traditional challenges of software engineering task from requirements to analysis & design, coding, testing, and maintenance & evolution. These contributions could be in the form of case studies, proofs-of-concept, new ideas and emerging results, evaluation of tools, controlled experiments with software engineers. e.g., specifying logical rules/constraints or utilizing machine learning recommendations.

Preliminary List of Topics

- Neuro-symbolic methods in automated software engineering tools, e.g., code & test generation, bug fixing, code summarization, code review, etc.
- Neuro-Symbolic agents to support collaboration and decision making in software teams.
- Neuro-Symbolic methods in validation and verification tools.
- Neuro-Symbolic methods for designing safety-mission-critical systems.
- Neuro-Symbolic methods for extracting and maintaining knowledge graphs for software engineering.
- Methods for reasoning about learning from software data.
- Methods for learning while reasoning about software, e.g., automatically & adaptively determine decision thresholds and magnitude of actions for a desired effect of a software tool & technique.
- Methods for applying prior symbolic or probabilistic knowledge to new or improved software tools & methods.


{: #cfp }

# Call for Papers

We welcome two types of original research papers: full papers (max. 6 pages) and short papers (max. 4 pages, in both cases not including references or supplementary materials) which is formatted according to the ICSE 2025 guidelines. 

Please submit your paper here: [HotCRP](https://icse2025-workshops.hotcrp.com/)

We also welcome extended abstracts of up to **2 pages** (not including references) that describe open problems and challenges in the area of Neuro-Symbolic methods applied to Software Engineering.

Accepted papers and extended abstracts will be presented as in a short-pitch (3 min) session.

There will be a reflection session at the end of the workshop to facilitate discussions among attendees.

Workshop papers will be published by IEEE.

**Summary:**

- **Length: 4-6 pages (research paper), or 2 pages (extended abstract)**
- **Two types of presentations: full presentations and short pitches**
- **Submission site: [HotCRP](https://icse2025-workshops.hotcrp.com/)**

{: #dates }

# Important Dates

- Submission deadline: **November 11th 2024 (AOE)**
- Acceptance notification: **December 1st, 2023 (AOE)**
- Camera ready for accepted submissions: **Feb 5th, 2025 (AOE)**
- Workshop date: **April 28, 2025**

{: #papers }

# Accepted papers

#### Research papers

- Authors Paper 1, "Title of Paper 1".
- Authors Paper 2, "Title of Paper 2".
- Authors Paper 3, "Title of Paper 3".
- Authors Paper 4, "Title of Paper 4".
- Authors Paper 5, "Title of Paper 5".


#### Short papers and extended abstract

- Authors Short Paper 1, "Title of Short Paper 1".

{: #schedule }

# Schedule

| Time  | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Agenda&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |                                                                                                                                             |
| ----- | ------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------ |
| 8:50  | Opening                                                                                                | The organizers                                                                                                                            |
| 9:00  | Invited talk                                                                                           | Keynote Speaker 1, "Keynote on Neuro-Symbolic AI for Software Engineering"                                      |
| 10:00 | Paper presentation                                                                                      | Presentation Paper 1                                                                         |
| 10:30 | Coffee break                                                                                           |                                                                                                                                             |
| 11:00 | Invited talk                                                                                           | Keynote Speaker 2, "Another Invited Talk on Neuro-Symbolic Methods"                                                                                            |
| 12:00 | Paper presentation                                                                                       | Presentation Paper 2                                                   |
| 12:30 | Lunch break                                                                                            |                                                                                                                                             |
| 14:00 | Invited talk                                                                                           | Keynote Speaker 3, "The Last Invited Talk on Neuro-Symbolic AI"                                                                                       |
| 15:00 | Paper presentation                                                                                      | Presentation Paper 3                                                     |
| 15:30 | Coffee break                                                                                           |                                                                                                                                             |
| 16:00 | Contributed talk                                                                                       | Presentation Paper 4 |
| 16:30 | Contributed talk                                                                                       | Presentation Paper 5        |
| 16:45 | Contributed talk                                                                                       | Presentation Paper 6                                                                  |
| 17:00 | Reflection block (open end)                                                                                                 | All participants                                                                                                                       |

{: #invited }

# Invited Talks

<div class="row justify-content-center">
  {% for p in page.speakers %}
  <div class="col-lg-3 text-center">
    <div class="member-box">
      <div class="member-image">
        <a href="{{ p.url }}">
        <img alt="{{ p.name }}" class="img-fluid mb-2" style="height: 180px;" src="{{ p.image }}" />
        </a>
      </div>
      <div class="member-meta">
        <a href="{{ p.url }}">{{ p.name }}</a><br>
        {{ p.affiliation }}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="text-center"> * in alphabetical order</div>

{: #organizers }

# Organizers

<div class="row justify-content-center">
  {% for p in page.organizers %}
  <div class="col-lg-3 text-center">
    <div class="member-box">
      <div class="member-image">
        <a href="{{ p.url }}">
        <img alt="{{ p.name }}" class="img-fluid mb-2" style="height: 180px;" src="{{ p.image }}" />
        </a>
      </div>
      <div class="member-meta">
        <a href="{{ p.url }}">{{ p.name }}</a><br>
        {{ p.affiliation }}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="text-center"> * in alphabetical order</div>

{: #pcs }

# Program Committee

{% for p in page.pcs %}

- {{p.name}} ({{p.affiliation}})
  {% endfor %}

<div class="text-center"> * in alphabetical order</div>

### Reference

- Anderson, G., Verma, A., Dillig, I., and Chaudhuri, S., "Neurosymbolic reinforcement learning with formally verified exploration", NeurIPS 2020.
- Chaudhury, S., Sen, P., Ono, M., Kimura, D., Tatsubori, M., and Munawar, A., "Neuro-symbolic approaches for text-based policy learning", EMNLP 2021.
- Dong, H., Mao, J., Lin, T., Wang, C., Li, L., and Zhou, D., "Neural logic machines", ICLR 2019.
- Kimura, D., Ono, M., Chaudhury, S., Kohita, R., Wachi, A., Agravante, D. J., Tatsubori, M., Munawar, A., and Gray, A., "Neuro-symbolic reinforcement learning with first-order logic", EMNLP 2021.
- Mnih, V., Kavukcuoglu, K., Silver, D., Rusu, A. A., Veness, J., Bellemare, M. G., Graves, A., Riedmiller, M. A., Fidjeland, A., Ostrovski, G., Petersen, S., Beattie, C., Sadik, A., Antonoglou, I., King, H., Kumaran, D., Wierstra, D., Legg, S., and Hassabis, D., "Human-level control through deep reinforcement learning", Nature 2015.
- Narasimhan, K., Kulkarni, T. D., and Barzilay, R., "Language understanding for text-based games using deep reinforcement learning", EMNLP 2015.
- Riegel, R., Gray, A. G., Luus, F. P. S., Khan, N., Makondo, N., Akhalwaya, I. Y., Qian, H., Fagin, R., Barahona, F., Sharma, U., Ikbal, S., Karanam, H., Neelam, S., Likhyani, A., and Srivastava, S. K., "Logical neural networks", arXiv 2020.
- Yuan, X., Côté, M., Sordoni, A., Laroche, R., des Combes, R. T., Hausknecht, M. J., and Trischler, A., "Counting to explore and generalize in text-based games", arXiv 2018.
