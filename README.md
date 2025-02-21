# Enhancing User Experience with Visual Controls for Local Differential Privacy

This is the code repository for the project that presents a user-centric approach to implementing Local Differential Privacy (LDP) in smart home environments, focusing on voice command privacy. The interface translates complex LDP parameters into four intuitive privacy levels. The interface combines visual controls with concrete examples showing how privacy transformations affect voice commands. By mapping mathematical privacy parameters to user-friendly settings while maintaining theoretical guarantees, our approach explores making differential privacy more accessible in IoT environments.

We built an interactive prototype in Figma that demonstrates the user interface for adjusting privacy settings: [Figma Prototype for Smart Home Privacy Widget](https://www.figma.com/proto/NbBGjJAZFVnNLcnAnNpP4Q/Smart-Home-Privacy-Widget---Prototype).

We use the [voice command dataset](https://www.kaggle.com/datasets/emanuelbuttaci/audios/data) containing user interactions with a voice-controlled virtual assistant. The metadata file describes audio recordings from multiple speakers, including speakers' properties and audio file paths with 9854 records. Each record includes pre-anonymized age ranges (e.g., "22-40"), gender, and English fluency level (marked as "advanced"). The command data consists of two main categorical components: actions (such as "activate" and "deactivate") and categories (including "music" and "lights"). The pre-existing age anonymization through range categorization aligns with our objective of enhancing privacy protection through DP mechanisms.
