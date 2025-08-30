# Functor Attention: Enforcing Categorical Structure in Transformers

This repository contains the official implementation of our ICTA 2025 paper:

**“Attention Is a Functor: Enforcing Categorical Structure in Transformers”**  
Hyun Kim, Satyam Mishra, Tran Duc Tan, Vishwanath Bijalwan

🧠 In this work, we model each transformer attention head as a *functor* : enforcing identity and composition laws from category theory via a novel differentiable functor loss.

## 🔍 Highlights

- Attention heads treated as **structure-preserving functors**
- Identity and composition constraints imposed via auxiliary loss
- Experiments on **SCAN** and **GeoQuery** show improved compositional generalization
- Minimal change to transformer architecture (~90% training speed retained)



## 📈 Datasets Used

- [SCAN](https://github.com/brendenlake/SCAN)
- [GeoQuery-TableQA](https://huggingface.co/datasets/vaishali/geoQuery-tableQA)

## 📜 Citation

```bibtex
@inproceedings{kim2025attentionfunctor,
  title={Attention Is a Functor: Enforcing Categorical Structure in Transformers},
  author={Kim, Hyun and Mishra, Satyam and Tan, Tran Duc and Bijalwan, Vishwanath},
  booktitle={International Conference on Theory and Applications of Artificial Intelligence (ICTA)},
  year={2025}
}
```