# Bachelor-Thesis

📌 English Version

This thesis focuses on the application of Artificial Intelligence (AI) and Explainable AI (XAI) techniques to enhance the detection of cyber intrusions in network systems. Traditional Intrusion Detection Systems (IDS) based on static rules have several limitations, such as the inability to detect zero-day attacks and a high rate of false positives. The use of Machine Learning (ML) provides a more adaptive approach, but the lack of transparency in ML models can make them difficult to interpret for security analysts and administrators.

The research leverages the NSL-KDD dataset, a widely adopted benchmark in cybersecurity, and implements two classification models: Random Forest and Gradient Boosting. The primary goal is to assess model accuracy, identify the most relevant features for attack recognition, and apply Explainable AI techniques to make the decision-making process more transparent.

Experimental analysis shows that both models achieve high accuracy levels (over 99%), with Gradient Boosting slightly outperforming Random Forest in terms of precision. The use of SHAP (SHapley Additive Explanations) and Permutation Importance enabled the identification of the most influential network traffic features for classification.

The findings highlight that integrating XAI into Intrusion Detection Systems not only enhances trust in model effectiveness but also provides security experts with valuable insights to strengthen cybersecurity defenses. This study represents a significant step toward adopting more interpretable and reliable AI-based detection systems, with potential applications in corporate network monitoring and protection against emerging threats.

📌 Versione in italiano

Questa tesi si concentra sull’applicazione dell’Intelligenza Artificiale (IA) e delle tecniche di Explainable AI (XAI) per migliorare il rilevamento delle intrusioni informatiche nei sistemi di rete. I tradizionali Intrusion Detection System (IDS) basati su regole statiche presentano numerosi limiti, come l’incapacità di individuare attacchi zero-day e l’elevato numero di falsi positivi. L’uso del Machine Learning (ML) offre un approccio più adattivo, ma la mancanza di trasparenza nei modelli può renderli difficili da interpretare per analisti e amministratori di sicurezza.

La ricerca utilizza il dataset NSL-KDD, un benchmark ampiamente adottato nella cybersecurity, e implementa due modelli di classificazione: Random Forest e Gradient Boosting. L’obiettivo è valutare l’accuratezza dei modelli, identificare le feature più rilevanti per il riconoscimento degli attacchi e applicare tecniche di Explainable AI per rendere il processo decisionale più trasparente.

L'analisi sperimentale mostra che entrambi i modelli raggiungono elevati livelli di accuratezza (oltre il 99%), con il Gradient Boosting che offre prestazioni leggermente superiori in termini di precisione. L’utilizzo di SHAP (SHapley Additive Explanations) e Permutation Importance ha permesso di individuare le caratteristiche del traffico di rete più influenti per la classificazione.

I risultati evidenziano come l’integrazione della XAI nei sistemi di Intrusion Detection non solo migliori la fiducia nell’efficacia dei modelli, ma fornisca anche una guida agli esperti di sicurezza per rafforzare le difese informatiche. Lo studio rappresenta un passo significativo verso l’adozione di sistemi di rilevamento basati su IA più interpretabili e affidabili, con potenziali applicazioni nel monitoraggio delle reti aziendali e nella protezione dalle minacce emergenti.
