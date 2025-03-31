# ICML-REBUTTAL
We used ASSE-Net (ours), Spiking-FullSubnet, and Spiking-U_Net, which were trained on the Voicebank+Demo dataset, to infer 12 real-world recorded speech samples (including music noise, door opening sounds, highway noise, background speech, keyboard typing sounds, and other real-world scenarios). We then invited volunteers to rate each speech sample they heard on a scale of 1 to 5 (the results are shown in Table 1). Table 1 presents the results of our proposed model ASSE-Net (ours), Table 2 shows the results of Spiking-FullSubnet, and Table 3 displays the results of Spiking-U_Net. Table 4 compiles the results by first calculating the average score for each speech sample across all volunteers, and then averaging these averages across all speech samples for each model, providing a more direct view of the superiority of our proposed model.
| SPEECH | MEN1 | MEN2 | MEN3 | MEN4 | MEN5 | MEN6 | MEN7 | MEN8 | MEN9 | MEN10 | MEN11 | MEN12 | MEN13 | MEN14 | MEN15 | avg. |
|--------|------|------|------|------|------|------|------|------|------|-------|-------|-------|-------|-------|-------|------|
| speech1 | 4.2  | 4    | 3    | 4    | 4    | 4    | 5    | 4    | 4    | 4     | 4     | 4     | 4     | 4     | 4     | 4.01 |
| speech2 | 4.1  | 5    | 4    | 4.5  | 3    | 4    | 4    | 4    | 4    | 4     | 4     | 4     | 3     | 4     | 4.2   | 3.99 |
| speech3 | 3.5  | 3    | 2    | 2.7  | 3    | 4    | 5    | 3    | 3    | 3     | 3     | 3     | 4     | 4     | 4.3   | 3.37 |
| speech4 | 4.5  | 4    | 4    | 3.5  | 3    | 4    | 5    | 3    | 4    | 3     | 4     | 4     | 4     | 4     | 4.3   | 3.89 |
| speech5 | 4.3  | 3    | 3    | 3.8  | 3    | 3    | 4    | 2    | 4    | 3     | 4     | 4     | 4     | 5     | 4.5   | 3.64 |
| speech6 | 3.9  | 3    | 2    | 3    | 3    | 3    | 4    | 3    | 4    | 2     | 2     | 3     | 4     | 4     | 3.8   | 3.18 |
| speech7 | 3.8  | 4    | 4    | 4.5  | 3    | 4    | 5    | 4    | 5    | 4     | 3     | 5     | 3     | 5     | 4.2   | 4.10 |
| speech8 | 3.6  | 5    | 4    | 3    | 4    | 4    | 5    | 2    | 5    | 4     | 4     | 4     | 4     | 4     | 4.5   | 4.00 |
| speech9 | 3.8  | 3    | 3    | 4    | 3    | 3    | 4    | 1    | 4    | 2     | 4     | 3     | 4     | 4     | 4     | 3.32 |
| speech10| 3.9  | 3    | 3    | 4.6  | 3    | 4    | 5    | 3    | 5    | 2     | 3     | 4     | 4     | 4     | 3.8   | 3.69 |
| speech11| 3.9  | 4    | 4    | 4.65 | 3    | 3    | 5    | 4    | 4    | 4     | 4     | 5     | 4     | 5     | 3.9   | 4.09 |
| speech12| 4.0  | 4    | 4    | 4.76 | 3    | 4    | 4    | 4    | 5    | 4     | 3     | 4     | 4     | 5     | 4.2   | 4.06 |
| avg.    | 3.96 | 3.75 | 3.33 | 3.92 | 3.17 | 3.67 | 4.58 | 3.08 | 4.25 | 3.25  | 3.5   | 3.92  | 3.83  | 4.33  | 4.14  | **3.78** |
                                            Table 1: Results of the Proposed ASSE-Net Model.




| SPEECH | MEN_1 | MEN_2 | MEN3 | MEN4 | MEN5 | MEN6 | MEN7 | MEN8 | MEN9 | MEN10 | MEN11 | MEN12 | MEN13 | MEN14 | MEN15 | avg. |
|--------|-------|-------|------|------|------|------|------|------|------|-------|-------|-------|-------|-------|-------|------|
| speech1 | 4     | 2     | 2    | 4    | 3    | 3    | 4    | 3    | 4    | 3     | 2     | 3     | 4     | 4     | 3.8   | 3.25 |
| speech2 | 3.8   | 3     | 3    | 4.5  | 4    | 3    | 4    | 4    | 4    | 4     | 4     | 4     | 4     | 4     | 4     | 3.82 |
| speech3 | 2.9   | 2     | 1    | 1    | 2    | 2    | 3    | 5    | 1    | 2     | 1     | 1     | 4     | 3     | 1.7   | 2.17 |
| speech4 | 3.8   | 2     | 3    | 3    | 4    | 4    | 2    | 4    | 3    | 4     | 3     | 3     | 4     | 4     | 4     | 3.39 |
| speech5 | 3.9   | 3     | 3    | 3    | 4    | 4    | 5    | 2    | 4    | 4     | 2     | 3     | 4     | 3     | 3     | 3.39 |
| speech6 | 3.2   | 1     | 2    | 3.5  | 2    | 3    | 2    | 4    | 3    | 3     | 4     | 2     | 4     | 3     | 2.5   | 2.81 |
| speech7 | 4     | 4     | 3    | 3.8  | 4    | 4    | 3    | 4    | 4    | 4     | 2     | 5     | 3     | 5     | 4     | 3.79 |
| speech8 | 3.3   | 2     | 2    | 4.1  | 3    | 4    | 4    | 1    | 3    | 4     | 1     | 3     | 4     | 4     | 3.8   | 3.08 |
| speech9 | 3.1   | 3     | 1    | 4.15 | 2    | 2    | 3    | 3    | 2    | 3     | 3     | 2     | 4     | 3     | 2.6   | 2.72 |
| speech10| 3.8   | 2     | 2    | 4.5  | 3    | 3    | 4    | 3    | 5    | 4     | 3     | 4     | 4     | 4     | 2.7   | 3.47 |
| speech11| 4     | 2     | 3    | 3.5  | 3    | 4    | 5    | 4    | 4    | 4     | 2     | 4     | 3     | 5     | 3     | 3.57 |
| speech12| 3.9   | 2     | 2    | 4    | 3    | 3    | 3    | 1    | 4    | 4     | 3     | 3     | 3     | 4     | 3.7   | 3.11 |
| avg.   | 3.64  | 2.33  | 2.25 | 3.59 | 3.08 | 3.25 | 3.5  | 3.17 | 3.42 | 3.58  | 2.5   | 3.08  | 3.75  | 3.83  | 3.23  | 3.21 |
                                            Table 2: Results of the Spiking-FullSubnet Model.

| SPEECH | MEN_1 | MEN_2 | MEN3 | MEN4 | MEN5 | MEN6 | MEN7 | MEN8 | MEN9 | MEN10 | MEN11 | MEN12 | MEN13 | MEN14 | MEN15 | avg.  |
|--------|-------|-------|------|------|------|------|------|------|------|-------|-------|-------|-------|-------|-------|-------|
| speech1 | 3     | 1     | 1    | 2    | 2    | 3    | 2    | 1    | 1    | 2     | 2     | 2     | 2     | 2     | 2.5   | 1.9   |
| speech2 | 3.1   | 1     | 1    | 1    | 2    | 2    | 2    | 1    | 1    | 2     | 2     | 1     | 3     | 2     | 2.4   | 1.77  |
| speech3 | 2.9   | 1     | 1    | 1    | 1    | 2    | 1    | 2    | 1    | 2     | 3     | 1     | 2     | 1     | 1.8   | 1.58  |
| speech4 | 3.3   | 4     | 2    | 4    | 3    | 3    | 3    | 3    | 2    | 3     | 3     | 3     | 3     | 2     | 2.9   | 2.95  |
| speech5 | 3.5   | 5     | 2    | 3.8  | 4    | 3    | 4    | 2    | 4    | 3     | 1     | 4     | 2     | 3     | 3.5   | 3.19  |
| speech6 | 2.9   | 2     | 1    | 1    | 1    | 2    | 1    | 3    | 1    | 2     | 2     | 1     | 2     | 1     | 1.2   | 1.61  |
| speech7 | 3.8   | 4     | 2    | 3.75 | 3    | 3    | 3    | 2    | 2    | 4     | 4     | 4     | 2     | 3     | 3     | 3.10  |
| speech8 | 2.8   | 4     | 1    | 2.9  | 3    | 4    | 2    | 2    | 2    | 3     | 1     | 3     | 2     | 2     | 2.6   | 2.49  |
| speech9 | 3.1   | 2     | 2    | 4.2  | 2    | 3    | 3    | 1    | 2    | 3     | 3     | 3     | 2     | 4     | 2.4   | 2.65  |
| speech10 | 3.3   | 3     | 2    | 3.3  | 3    | 3    | 3    | 3    | 3    | 3     | 3     | 3     | 3     | 3     | 2.5   | 2.94  |
| speech11 | 3.5   | 3     | 3    | 4.25 | 3    | 3    | 4    | 2    | 3    | 3     | 4     | 4     | 2     | 2     | 2.4   | 3.08  |
| speech12 | 3.6   | 4     | 2    | 4    | 1    | 3    | 2    | 1    | 4    | 4     | 2     | 3     | 2     | 2     | 2.6   | 2.68  |
| avg.|3.23 | 2.83 | 1.67 | 2.93 | 2.33 |2.83 |2.50 | 1.92 | 2.17 | 2.83| 2.50 | 2.67 | 2.25 | 2.25| 2.48 | **2.49** |
                                             Table 3: Results of the Spiking-U_Net Model.



| SPEECH |  ASSE-Net（ours） | Spiking-FullSubnet | Spiking-U_Net |
|--------|------------------|--------------------|---------------|
| speech1 | **4.01**             | 3.25               | 1.9           |
| speech2 | **3.97**             | 3.82               | 1.77          |
| speech3 | **3.37**             | 2.17               | 1.58          |
| speech4 |  **3.89**             | 3.39               | 2.94          |
| speech5 |   **3.64**             | 3.39               | 3.19          |
| speech6 |   **3.18**             | 2.81               | 1.61          |
| speech7 |   **4.10**              | 3.79               | 3.10          |
| speech8 |   **4.01**             | 3.08               | 2.49          |
| speech9 |    **3.32**             | 2.72               | 2.65          |
| speech10|  **3.69**             | 3.47               | 2.94          |
| speech11|    **4.10**              | 3.57               | 3.08          |
| speech12|     **4.06**             | 3.11               | 2.68          |
| avg.    |     **3.78**             | 3.21               | 2.49          |
                      Table 4: Average scores for each speech sample across all testers under different model processing.
