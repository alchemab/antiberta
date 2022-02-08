<p align="center">
    <img src="banner.png" alt="blah" /><br>
</p>

<p align = "center">
    <img src="https://img.shields.io/static/v1?label=python&message=3.9&color=blue&style=flat-square"/>
    <a href="https://pytorch.org/"><img src="https://img.shields.io/static/v1?label=pytorch&message=1.9.0&color=blue&style=flat-square"/></a>
    <a href="https://huggingface.co/transformers/"><img src="https://img.shields.io/static/v1?label=huggingface&message=4.7.0&color=yellow&style=flat-square"/></a>
    <a href="https://huggingface.co/docs/datasets/"><img src="https://img.shields.io/static/v1?label=hf-datasets&message=1.11.0&color=yellow&style=flat-square"/></a>
    <a href="https://www.linkedin.com/company/alchemab-therapeutics-ltd/"><img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue"/></a>
    <a href="https://twitter.com/alchemabtx"><img src="https://img.shields.io/twitter/follow/alchemabtx?style=social"/></a>
</p>


# AntiBERTa

This is a repository with Jupyter notebooks describing how we pre-trained the model, and how we apply the model
for fine-tuning.

## FAQs

* _What dataset did you use?_ This is described in our preprint, but briefly, we used a section of the Observed Antibody
  Space (OAS) database (Kovaltsuk et al., 2018) for pre-training, and a snapshot of SAbDab (Dunbar et al., 2014) as of
  26 August, 2021. We've included small snippets of the OAS database that we used for pre-training, and the paratope
  prediction datasets under `assets`.
  
* _Why HuggingFace?_ We felt that the maturity of the library and its straight-forward API were key advantages. Not to
mention it fits really well with cloud compute architectures like AWS.
