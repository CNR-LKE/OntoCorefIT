# OntoCorefIT

**OntoCorefIT** is an Italian dataset for **coreference resolution**, developed by the **Language and Knowledge Engineering (LKE)** research group at **ICAR-CNR**, the Institute for High Performance Computing and Networking of the National Research Council of Italy.

The dataset was created to support research on coreference resolution for the Italian language and to contribute to the availability of annotated resources for Natural Language Processing beyond English.

## About OntoCorefIT

Coreference resolution aims to identify expressions in a text that refer to the same real-world entity. Despite its importance for natural language understanding, the task has historically received less attention than other NLP problems, particularly for languages other than English.

OntoCorefIT was developed to help address the limited availability of resources for **Italian coreference resolution**.

The dataset originates from **OntoNotes**[^1] and was produced through a methodology designed to translate and refine English utterances while:

- preserving coreference relations and mentions;
- generating utterances consistent with Italian grammar;
- addressing language-specific linguistic phenomena;
- accounting for the characteristics of an inflectional and morphologically rich language such as Italian.

The resulting dataset was also used to train and evaluate neural coreference resolution models.

## Research Context

The creation of OntoCorefIT is motivated by the need for high-quality linguistic resources that can facilitate the development and evaluation of coreference resolution systems for languages other than English.

The methodology proposed for its construction combines automated translation and language-specific refinement in order to transfer information from an existing annotated resource while preserving the linguistic structures required by the coreference resolution task.

Although the methodology was developed and evaluated for the English-to-Italian setting, its general principles were conceived with potential adaptation to other languages in mind, provided that the appropriate language-dependent rules and linguistic phenomena are considered.

## Using OntoCorefIT

We are grateful to everyone who visits this repository to **explore, evaluate, or use OntoCorefIT**.

If you use the dataset in your research, experiments, teaching activities, or other projects, we would be very pleased to hear about your experience. Feedback from the community can help us better understand how OntoCorefIT is being used and can contribute to future research and development.

We therefore kindly invite you to **contact the LKE research group at ICAR-CNR** to share your experience, results, observations, or possible collaborations.

When possible, please also **cite the scientific publications associated with OntoCorefIT**, listed below.

```bibtex
@article{minutolo2022multi,
  title={A multi-level methodology for the automated translation of a coreference resolution dataset: an application to the Italian language},
  author={Minutolo, Aniello and Guarasci, Raffaele and Damiano, Emanuele and De Pietro, Giuseppe and Fujita, Hamido and Esposito, Massimo},
  journal={Neural Computing and Applications},
  pages={1--26},
  year={2022},
  publisher={Springer}
}

@article{guarasci2021electra,
  title={ELECTRA for Neural Coreference Resolution in Italian},
  author={Guarasci, Raffaele and Minutolo, Aniello and Damiano, Emanuele and De Pietro, Giuseppe and Fujita, Hamido and Esposito, Massimo},
  journal={IEEE Access},
  volume={9},
  pages={115643--115654},
  year={2021},
  publisher={IEEE}
}
```

## About LKE

The LKE group conducts research in Natural Language Processing, language and knowledge technologies, and related areas, developing methodologies and intelligent systems for the representation, extraction, processing, and exploitation of linguistic and semantic information.

For information about the research group, projects, publications, and collaborations, please visit the official LKE webpage:

**https://www.icar.cnr.it/en/gruppi-di-ricerca/language-and-knowledge-engineering/**

## Acknowledgments

Thank you for your interest in **OntoCorefIT**.

We sincerely appreciate researchers, developers, students, and practitioners who take the time to evaluate and use this resource. We hope that making OntoCorefIT available to the community can support further research on Italian coreference resolution and encourage the development of NLP resources and methods for languages other than English.

If OntoCorefIT contributes to your work, we would be glad to learn about your experience. Please feel free to get in touch with the **LKE research group** and, whenever possible, cite the publications associated with the dataset.

[^1]: E. Hovy, M. Marcus, M. Palmer, L. Ramshaw, and R. Weischedel, *OntoNotes: The 90% Solution*, Proceedings of the Human Language Technology Conference of the NAACL, Companion Volume: Short Papers, pp. 57–60, 2006.
