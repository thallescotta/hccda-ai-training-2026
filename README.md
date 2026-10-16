# HCCDA – Artificial Intelligence (Huawei) – Notas de treinamento

Anotações e exercícios do treinamento **HCCDA – Artificial Intelligence**, da Huawei, realizado online em outubro de 2026.

## 📓 Notebook

**[Ver o notebook](https://github.com/thallescotta/hccda-ai-training-2026/blob/main/HCCDA_artificial_intelligence_training_tutorial_2026_Huawei_CLAROBR.ipynb)**

Conteúdo praticado no notebook:

- Criação de arrays NumPy (1D, 2D e 3D)
- `ndim`, `shape` e `size`
- `arange`, `linspace` e `logspace`
- Indexação e fatiamento
- `np.all`, `np.any` e `np.where`
- `np.newaxis` e broadcasting (resposta do quiz com exemplo)

## 📅 Sobre o treinamento

| Item | Detalhe |
|---|---|
| Curso | HCCDA – Artificial Intelligence |
| Datas | 13, 14 e 15/10/2026 (terça a quinta) |
| Horário | 14h às 17h (horário de Brasília, UTC-3) |
| Carga | 3 encontros de 3 horas, 9 horas no total |
| Formato | Videoconferência pelo Huawei WeMeeting |
| Ambiente de prática | Huawei Cloud ModelArts (notebook com arquivos montados em um bucket OBS) |

## 🗓️ Como foi o treinamento

O treinamento aconteceu em três tardes seguidas, em reunião online, com exercícios práticos feitos em um notebook Jupyter no ModelArts. As práticas deste repositório usam a biblioteca NumPy. A última parte do treinamento foi um laboratório da plataforma de educação da Huawei Cloud (veja os links abaixo).

<!-- Opcional: adicione aqui suas impressões, o que aprendeu em cada dia e o que achou mais difícil. -->

## 🎓 Certificação

O treinamento está ligado à certificação **HCCDA – Artificial Intelligence**, cuja página fica no portal de educação da Huawei Cloud:

- [Página da certificação](https://edu.huaweicloud.com/intl/en-us/certification/65326da509554551b3dae8b9fcebfdbe)

<!-- Opcional: adicione o status (por exemplo, exame agendado ou aprovado) e a data. -->

## 🏆 Campanha de Certificação Huawei na Claro

Campanha de Certificação Huawei na Claro, com premiações para os colaboradores que conquistarem suas certificações e atenderem aos critérios da campanha.

![Campanha de Certificação Huawei na Claro](Campanha%20de%20Certifica%C3%A7%C3%A3o%20Huawei%20na%20Claro.jpg)

Caso sobrem prêmios do Grupo 2, eles serão concedidos aos primeiros colaboradores que conquistarem sua primeira certificação Huawei. Para fins de classificação, será considerada a data em que cada colaborador obteve a certificação.


**Data de fechamento da campanha: 30/11/2026.**

## 🔗 Links usados no notebook

| Link | O que é |
|---|---|
| [Laboratório (experiment 2028)](https://edu.huaweicloud.com/intl/en-us/lab/experiment-detail_2028) | Página pública do laboratório de NumPy da plataforma de educação da Huawei Cloud. O notebook usa esse endereço para exibir a tela do lab. |
| [Página da certificação](https://edu.huaweicloud.com/intl/en-us/certification/65326da509554551b3dae8b9fcebfdbe) | Página da certificação no mesmo portal, a que o notebook tentou exibir em iframe. O site bloqueia essa exibição, por isso o notebook usa um screenshot automático. |

O notebook também tem links `experimentalStudy_...`. São sessões temporárias do laboratório, que exigem login e expiram, por isso não foram incluídos aqui.

## ▶️ Como rodar

```bash
pip install numpy jupyter
jupyter notebook
```

Os exercícios foram feitos no Huawei Cloud ModelArts. A célula que usa `np.save("/data/input/...")` precisa de uma pasta `data/input/` criada localmente, ou de um ajuste no caminho. As células de screenshot dependem do Playwright (`pip install playwright` e `playwright install chromium`) e de acesso à internet.

## 👤 Autor

GitHub: [@thallescotta](https://github.com/thallescotta)

<!-- Opcional: adicione seu nome completo e seu LinkedIn. -->

## ⚠️ Aviso

Projeto pessoal de estudo. O material do curso pertence à Huawei. Huawei, HCCDA e ModelArts são marcas da Huawei Technologies Co., Ltd.
