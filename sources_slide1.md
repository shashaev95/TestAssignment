# Слайд 1 «Парк чипов OpenAI и Anthropic» — источники

**Дата, на которую верны цифры: 22.09.2026.**
Компании не публикуют официальные цифры парка GPU — все значения ниже это оценки открытых источников. Каждой цифре на слайде соответствует пункт списка.

## 1. OpenAI — размер парка

1. **Stargate Abilene: ~509 тыс. H100-эквивалентов, 75% кампуса сдано**
   stargate.how — «GPT-6 Astra: the first 100000-GPU training run at Stargate Abilene»
   https://stargate.how/news/gpt-6-astra-first-100000-gpu-training-run-stargate-abilene (18.09.2026)
   *Данные Epoch AI: 509 тыс. H100-эквивалентов на Stargate Abilene; ~1 млн ожидается к 4 кв. 2026; Abilene составит 75% всех мощностей OpenAI.*

2. **~150–200 тыс. GPU GB200 в работе; 4 из 8 корпусов; цель ~1 млн к концу 2026**
   TechTimes — «OpenAI Projects $278B Cash Burn» (со ссылкой на Presenc AI)
   https://www.techtimes.com/articles/327752/20260920/openai-projects-278b-cash-burn-record-round-runs-dry-before-revenue-catches.htm (20.09.2026)
   *4 из 8 корпусов Abilene сданы, ~150–200 тыс. GPU GB200 уже обслуживают обучение и инференс mid-2026; OpenAI арендовала ~450 тыс. GPU у Oracle; ~2 млн H100-эквивалентов ожидаются в 2027.*

3. **GPT-6 Astra обучена на 100+ тыс. GPU; ещё 400 тыс. GPU на подходе**
   Axios — «"Welcome to the AGI era," OpenAI says as GPT-6 Astra»
   https://www.axios.com/2026/09/03/openai-astra-gpt-6-agi-brockman (03.09.2026)
   *OpenAI: Astra построена на крупнейшем тренировочном запуске компании; релиз 3 сентября 2026.*

   PC Gamer / Jensen Huang (NVIDIA), 06–07.09.2026
   https://www.pcgamer.com/software/ai/jensen-huang-says-100-000-nvidia-gpus-were-used-to-train-openais-latest-model-gpt-6-astra-and-theres-already-plans-to-bring-quadruple-that-amount-of-hardware-online/
   *Хуанг: модель обучена на «~100K+ Nvidia Grace Blackwell NVLink72»; следующие 400 000 GPU будут развёрнуты. Грег Брокман подтвердил: речь о GPU, а не стойках.*

4. **Мощность ~2 ГВт (май 2026)**
   Waystar Analysis — «When AI Compute Catches Up: A May 2026 Status Report»
   https://waystaranalysis.substack.com/p/when-ai-compute-catches-up-a-may (11.05.2026)
   *OpenAI располагает ~2 ГВт операционных мощностей (май 2026); совместные мощности OpenAI + Anthropic — ~3–3.5 ГВт. План Stargate — ~10 ГВт.*

## 2. Anthropic — размер парка

5. **>1 млн чипов AWS Trainium2 (Project Rainier, апрель 2026)**
   Waystar Analysis (тот же источник, см. п. 4)
   *Anthropic использует >1 млн Trainium2 с апреля 2026: «тренируем и обслуживаем Claude».*

6. **Аренда Colossus у xAI/SpaceX: 220 тыс. GPU сразу, 325 тыс. по контракту, $1,25 млрд/мес до 2029**
   Measured AI — «xAI's Colossus Cluster: A Gigawatt of AI Data Centers»
   https://measuredai.substack.com/p/xai-colossus-data-center-cluster (25.06.2026)
   *Контракт Anthropic–xAI: 220 тыс. GPU доступно немедленно, 325 тыс. по полному контракту.*

   Creeta News — «Anthropic xAI Colossus-1: Pricing, GPUs, and Rate Limits 2026»
   https://news.creeta.com/en/anthropic-xai-colossus-1-compute-deal-2026/ (28.05.2026)
   *Anthropic платит xAI $1,25 млрд/мес за Colossus 1 (220 тыс. GPU); мощность идёт в основном на инференс Claude.*

7. **CoreWeave — мультигодовой контракт на GPU-облако для Claude**
   The Next Web — «CoreWeave signs multi-year Anthropic deal»
   https://thenextweb.com/news/coreweave-has-agreed-a-multi-year-gpu-cloud-deal-with-anthropic-to-power-claude-at-production-scale-its-second-major-ai-infrastructure-announcement-in-48-hours (10.04.2026)
   *CoreWeave обслуживает Claude at production scale; основной трейн — на AWS Trainium.*

8. **~400 тыс.+ GPU-эквивалентов NVIDIA суммарно**
   Presenc AI — «Frontier Lab GPU Counts 2026»
   https://presenc.ai/research/frontier-lab-gpu-counts-2026 (22.05.2026)
   *Сводка по лабораториям: Anthropic ~400 тыс. эффективных GPU, OpenAI Stargate 7 ГВт и т.д.*

## 3. Деление «обучение vs инференс»

9. **Претрейн 7% / пост-трейн и RL 55% / инференс 38% (4 кв. 2026, обе лаборатории суммарно)**
   FourWeekMBA — «OpenAI and Anthropic's Compute Mix Has Inverted»
   https://fourweekmba.com/ai-openai-anthropic-compute-mix-bandwidth-bound-hardware/ (14.09.2026)
   *Модельная оценка: претрейн упал с 67% (1 кв. 2024) до 7% от compute; рост пост-трейна и инференса.*

10. **Контекст: сплит 30/70 специфичен для OpenAI; Anthropic смещена к обучению**
    ITK Services — «AI training versus AI inference: the technical foundations»
    https://itkservices3.com/background/training_v_inference (11.05.2026)
    *Разбиение 30/70 — оценка, характерная для OpenAI; у Anthropic на этом этапе смещение в сторону обучения; у Meta инференс-нагрузка выше.*

## 4. Дополнительные источники для сверки (не вошли в слайд напрямую)

11. Shattered.io — «GPT-6 Astra: 100,000-GPU Training Run Explained» (10.09.2026) — детали рана Astra и Stargate Abilene.
12. Datavook — «xAI Colossus 2 News: 1M GPU Supercluster Live» (09.06.2026) — контекст: у xAI Colossus 2 (1,02 млн GPU), часть мощностей сдаётся в аренду, включая Anthropic.
13. Dev.to — «Anthropic x Google x Broadcom: The $21B AI Infrastructure Deal» (07.04.2026) — ~$21 млрд чипов Google TPU Ironwood через Broadcom для Anthropic.
