[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
# Awesome-Continual-Test-Time-Adaptation
A curated repository of papers and research works on Continual Test Time Adaptation (CTTA), primarily featuring published articles in the field.

# [Timeline](#timeline)
*Sorted chronologically (newest first).*  

### [2025](#2025)
|Year|Venue|Paper Title|Code/Project|
|:-:|:-:|-|:-:|
|2025|CVPR|Maintaining Consistent Inter-Class Topology in Continual Test-Time Adaptation|[Code](https://github.com/Successybbdwm/TCA)|
|2025|CVPR|Unsupervised Continual Domain Shift Learning with Multi-Prototype Modeling|N/A|

### [2024](#2024)
|Year|Venue|Paper Title|Code/Project|
|:-:|:-:|-|:-:|
|2024|ECCV|[Reshaping the Online Data Buffering and Organizing Mechanism for Continual Test-Time Adaptation](https://arxiv.org/abs/2407.09367)|[Code](https://github.com/z1358/OBAO)|
|2024|CVPR|[Continual-MAE: Adaptive Distribution Masked Autoencoders for Continual Test-Time Adaptation](https://arxiv.org/abs/2312.12480)|[Code](https://github.com/RanXu2000/continual-mae)|
|2024|CVPR|[A Versatile Framework for Continual Test-Time Domain Adaptation: Balancing Discriminability and Generalizability](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_A_Versatile_Framework_for_Continual_Test-Time_Domain_Adaptation_Balancing_Discriminability_CVPR_2024_paper.html)|N/A|
|2024|CVPR|[BECoTTA: Input-dependent Online Blending of Experts for Continual Test-time Adaptation](https://arxiv.org/abs/2402.08712)|[Code](https://github.com/daeunni/becotta)|
|2024|ICASSP|[Diversity-aware Buffer for Coping with Temporally Correlated Data Streams in Online Test-time Adaptation](https://arxiv.org/abs/2401.00989)|N/A|
|2024|ICRA|[Distribution-Aware Continual Test Time Adaptation for Semantic Segmentation](https://arxiv.org/abs/2309.13604)|[Code](https://github.com/RochelleNi/DAT)|
|2024|ICLR|[ViDA: Homeostatic Visual Domain Adapter for Continual Test Time Adaptation](https://arxiv.org/abs/2306.04344)|[Code](https://github.com/Yangsenqiao/vida)|
|2024|WACV|[Effective Restoration of Source Knowledge in Continual Test Time Adaptation](https://arxiv.org/abs/2311.04991)|N/A|
|2024|WACV|[Continual Test-time Domain Adaptation via Dynamic Sample Selection](https://openaccess.thecvf.com/content/WACV2024/papers/Wang_Continual_Test-Time_Domain_Adaptation_via_Dynamic_Sample_Selection_WACV_2024_paper.pdf)|N/A|
|2024|BMVC|[AR-TTA: A Simple Method for Real-World Continual Test-Time Adaptation](https://arxiv.org/abs/2309.10109)|N/A|
|2024|IJCAI|[Navigating Continual Test-time Adaptation with Symbiosis Knowledge](https://www.ijcai.org/proceedings/2024/0589.pdf)|N/A|

### [2023](#2023)
|Year|Venue|Paper Title|Code/Project|
|:-:|:-:|-|:-:|
|2023|TMLR|[SANTA: Source Anchoring Network and Target Alignment for Continual Test Time Adaptation](https://openreview.net/forum?id=V7guVYzvE4)|[Code](https://github.com/goirik-chakrabarty/test-time-adaptation)|
|2023|CVPR|[Robust Mean Teacher for Continual and Gradual Test-Time Adaptation](https://arxiv.org/abs/2211.13081)|[Code](https://github.com/mariodoebler/test-time-adaptation)|
|2023|CVPR|[A Probabilistic Framework for Lifelong Test-Time Adaptation](https://arxiv.org/abs/2212.09713)|[Code](https://github.com/dhanajitb/petal)|
|2023|CVPR|[EcoTTA: Memory-Efficient Continual Test-time Adaptation via Self-distilled Regularization](https://arxiv.org/abs/2303.01904)|[Community Implementation](https://github.com/Lily-Le/EcoTTA)|
|2023|AAAI|[Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation](https://arxiv.org/abs/2212.04145)|N/A|
|2023|NeurIPS|[RDumb: A simple approach that questions our progress in continual test-time adaptation](https://arxiv.org/abs/2306.05401)|[Code](https://github.com/oripress/CCC)|
|2023|IJCAI|[Exploring Safety Supervision for Continual Test-time Domain Adaptation](https://www.ijcai.org/proceedings/2023/183)|N/A|

### [2022](#2022)
|Year|Venue|Paper Title|Code/Project|
|:-:|:-:|-|:-:|
|2022|CVPR|[Continual Test-Time Domain Adaptation](https://arxiv.org/abs/2203.13591)|[Code](https://github.com/qinenergy/cotta)|
|2022|ICML|[Efficient Test-Time Model Adaptation without Forgetting](https://arxiv.org/abs/2204.02610)|[Code](https://github.com/mr-eggplant/EATA)|
    
# [Technical Approaches](#technical-approaches)
### [Parameter Recovery or Regularization](#parameter-recovery-or-regularization)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2022|CVPR|Random|[Continual Test-Time Domain Adaptation](https://arxiv.org/abs/2203.13591)|[Code](https://github.com/qinenergy/cotta)|
|2022|ICML|Data-driven, Fisher|[Efficient Test-Time Model Adaptation without Forgetting](https://arxiv.org/abs/2204.02610)|[Code](https://github.com/mr-eggplant/EATA)|
|2023|CVPR|Data-driven, Fisher|[A Probabilistic Framework for Lifelong Test-Time Adaptation](https://arxiv.org/abs/2212.09713)|[Code](https://github.com/dhanajitb/petal)|
|2023|NeurIPS|Periodical|[RDumb: A simple approach that questions our progress in continual test-time adaptation](https://arxiv.org/abs/2306.05401)|[Code](https://github.com/oripress/CCC)|
|2024|WACV|Peak Detection|[Effective Restoration of Source Knowledge in Continual Test Time Adaptation](https://arxiv.org/abs/2311.04991)|N/A|

### [Sample Filtering](#sample-filtering)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2022|ICML|Entropy|[Efficient Test-Time Model Adaptation without Forgetting](https://arxiv.org/abs/2204.02610)|[Code](https://github.com/mr-eggplant/EATA)|
|2023|IJCAI|Self-adaptive Thresholds|[Exploring Safety Supervision for Continual Test-time Domain Adaptation](https://www.ijcai.org/proceedings/2023/183)|N/A|
|2024|IJCAI|Self-adaptive Thresholds|[Navigating Continual Test-time Adaptation with Symbiosis Knowledge](https://www.ijcai.org/proceedings/2024/0589.pdf)|N/A|
|2024|CVPR|Self-adaptive Thresholds|[A Versatile Framework for Continual Test-Time Domain Adaptation: Balancing Discriminability and Generalizability](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_A_Versatile_Framework_for_Continual_Test-Time_Domain_Adaptation_Balancing_Discriminability_CVPR_2024_paper.html)|N/A|
|2024|WACV|Dynamic Thresholds|[Continual Test-time Domain Adaptation via Dynamic Sample Selection](https://openaccess.thecvf.com/content/WACV2024/papers/Wang_Continual_Test-Time_Domain_Adaptation_via_Dynamic_Sample_Selection_WACV_2024_paper.pdf)|N/A|
|2024|CVPR|Entropy|[BECoTTA: Input-dependent Online Blending of Experts for Continual Test-time Adaptation](https://arxiv.org/abs/2402.08712)|[Code](https://github.com/daeunni/becotta)|
|2024|ECCV|Entropy|[Reshaping the Online Data Buffering and Organizing Mechanism for Continual Test-Time Adaptation](https://arxiv.org/abs/2407.09367)|[Code](https://github.com/z1358/OBAO)|

### [Contrastive Learning](#contrastive-learning)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2023|CVPR|Source Prototypes|[Robust Mean Teacher for Continual and Gradual Test-Time Adaptation](https://arxiv.org/abs/2211.13081)|[Code](https://github.com/mariodoebler/test-time-adaptation)|
|2023|TMLR|Source Prototypes|[SANTA: Source Anchoring Network and Target Alignment for Continual Test Time Adaptation](https://openreview.net/forum?id=V7guVYzvE4)|[Code](https://github.com/goirik-chakrabarty/test-time-adaptation)|
|2023|IJCAI|Reweighted|[Exploring Safety Supervision for Continual Test-time Domain Adaptation](https://www.ijcai.org/proceedings/2023/183)|N/A|
|2024|IJCAI|Reweighted|[Navigating Continual Test-time Adaptation with Symbiosis Knowledge](https://www.ijcai.org/proceedings/2024/0589.pdf)|N/A|
|2025|CVPR|Multi-granularity|Maintaining Consistent Inter-Class Topology in Continual Test-Time Adaptation|[Code](https://github.com/Successybbdwm/TCA)|

### [Buffer-enhanced](#buffer-enhanced)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2023|CVPR|Source Samples|[Robust Mean Teacher for Continual and Gradual Test-Time Adaptation](https://arxiv.org/abs/2211.13081)|[Code](https://github.com/mariodoebler/test-time-adaptation)|
|2024|BMVC|Source Samples|[AR-TTA: A Simple Method for Real-World Continual Test-Time Adaptation](https://arxiv.org/abs/2309.10109)|N/A|
|2024|ICASSP|Diversity|[Diversity-aware Buffer for Coping with Temporally Correlated Data Streams in Online Test-time Adaptation](https://arxiv.org/abs/2401.00989)|N/A|
|2024|ECCV|Target Samples|[Reshaping the Online Data Buffering and Organizing Mechanism for Continual Test-Time Adaptation](https://arxiv.org/abs/2407.09367)|[Code](https://github.com/z1358/OBAO)|

### [PEFT-based](#peft-based)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2023|AAAI|Input Prompts|[Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation](https://arxiv.org/abs/2212.04145)|N/A|
|2023|CVPR|Meta Nets|[EcoTTA: Memory-Efficient Continual Test-time Adaptation via Self-distilled Regularization](https://arxiv.org/abs/2303.01904)|[Community Implementation](https://github.com/Lily-Le/EcoTTA)|
|2024|ICLR|Adapters|[ViDA: Homeostatic Visual Domain Adapter for Continual Test Time Adaptation](https://arxiv.org/abs/2306.04344)|[Code](https://github.com/Yangsenqiao/vida)|
|2024|ICRA|Selective|[Distribution-Aware Continual Test Time Adaptation for Semantic Segmentation](https://arxiv.org/abs/2309.13604)|[Code](https://github.com/RochelleNi/DAT)|
|2024|CVPR|MoE with Adapters|[BECoTTA: Input-dependent Online Blending of Experts for Continual Test-time Adaptation](https://arxiv.org/abs/2402.08712)|[Code](https://github.com/daeunni/becotta)|

### [Reconstruction](#reconstruction)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2024|CVPR|HOG Recons|[Continual-MAE: Adaptive Distribution Masked Autoencoders for Continual Test-Time Adaptation](https://arxiv.org/abs/2312.12480)|[Code](https://github.com/RanXu2000/continual-mae)|

### [Warm-up based (need source data)](#warm-up-based-need-source-data)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2023|CVPR|Mean Teacher|[Robust Mean Teacher for Continual and Gradual Test-Time Adaptation](https://arxiv.org/abs/2211.13081)|[Code](https://github.com/mariodoebler/test-time-adaptation)|
|2023|AAAI|Input Prompts|[Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation](https://arxiv.org/abs/2212.04145)|N/A|
|2023|CVPR|Meta Nets|[EcoTTA: Memory-Efficient Continual Test-time Adaptation via Self-distilled Regularization](https://arxiv.org/abs/2303.01904)|[Community Implementation](https://github.com/Lily-Le/EcoTTA)|
|2024|ICLR|Adapters|[ViDA: Homeostatic Visual Domain Adapter for Continual Test Time Adaptation](https://arxiv.org/abs/2306.04344)|[Code](https://github.com/Yangsenqiao/vida)|
|2024|CVPR|Domain Augmentation, Routers, Adapters|[BECoTTA: Input-dependent Online Blending of Experts for Continual Test-time Adaptation](https://arxiv.org/abs/2402.08712)|[Code](https://github.com/daeunni/becotta)|

### [Relationship-guided](#relationship-guided)
|Year|Venue|Key Words|Paper Title|Code/Project|
|:-:|:-:|:-:|-|:-:|
|2024|ECCV|Domain-invariant Inter-class Relation|[Reshaping the Online Data Buffering and Organizing Mechanism for Continual Test-Time Adaptation](https://arxiv.org/abs/2407.09367)|[Code](https://github.com/z1358/OBAO)|
|2025|CVPR|Uniform Topological Relation|Maintaining Consistent Inter-Class Topology in Continual Test-Time Adaptation|[Code](https://github.com/Successybbdwm/TCA)|

# Resources
