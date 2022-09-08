# Soundclim manual annotations

There are two main types of annotations: presence-absence and bounding boxes.

## Presence-absence
Presence-absence are annotations at a global scale, indicating the presence or absence of a species in a 60 s audio recording. This is the main target that needs to be automated, and hence is the final test.

## Bounding boxes

Bounding boxes are annotations at a finer scale, in time and frequency. Annotations are performed using Audacity and the following standards:

- Samples are heard and visually analyzed with a spectrogram
- Distorted signals (clipped or distorted by the microphone) are not annotated.
- Only samples that can be clearly identified are marked. Samples should be heard and observed in the spectrogram clearly.
- Consecutive samples can be mixed down if the silence between sounds is shorter than 5s.
- Annotate the presence of background species if they are clear (high SNR)

### Annotation codes

Each species is coded by the first three letters of the genus and the first three letters of the epithet, using all upper case letters. For example *Dendropsophus minutus* would be DENMIN.

Each sample is also annotated according to the following cases:
- Clear call of single species (CLR)
- Single species in chorus (CHO)
- Overlap with other sounds (MED)
- Overlap with other species (OVL)
- Distant call (FAR)


### Site codes and researcher names


|Site code| Researcher name        |
|---------|------------------------|
| INCT1   | José Perez Pombal jr.  |
| INCT2   | José Perez Pombal jr.  |
| INCT3   | José Perez Pombal jr.  |
| INCT4   | Luis Felipe Toledo     |
| INCT5   | Luis Felipe Toledo     |
| INCT6   | Luis Felipe Toledo     |
| INCT7   | Rodrigo Lingnau        |
| INCT8   | Rodrigo Lingnau        |
| INCT9   | Rodrigo Lingnau        |
| INCT10  | Selvino Neckel de Oliveira |
| INCT11  | Selvino Neckel de Oliveira |
| INCT12  | Selvino Neckel de Oliveira |
| INCT13  | Leandro Juen           |
| INCT14  | Leandro Juen           |
| INCT15  | Leandro Juen           |
| INCT16  | Franco Leandro de Souza |
| INCT17  | Franco Leandro de Souza |
| INCT18  | Franco Leandro de Souza |
| INCT19  | Wilian Vaz Silva.      |
| INCT20  | Wilian Vaz Silva.     |
| INCT21  | Wilian Vaz Silva.      |
| INCT22  | Alessandro Ribeiro de Morais |
| INCT23  | Alessandro Ribeiro de Morais |
| INCT24  | Alessandro Ribeiro de Morais |
| INCT25  | Luciana Barreto Nascimento |
| INCT26  | Luciana Barreto Nascimento |
| INCT27  | Luciana Barreto Nascimento |
| INCT28  | Paulo Garcia          |
| INCT29  | Paulo Garcia          |
| INCT30  | Paulo Garcia          |
| INCT31  | Rodrigo Barbosa Ferreira |
| INCT32  | Moacir Santos Tinoco. |
| INCT33  | Geraldo Jorge Barbosa de Moura |
| INCT34  | Mirco Solé            |
| INCT35  | Mirco Solé            |
| INCT36  | Mirco Solé            |
| INCT37  | Natan Medeiros Maciel |
| INCT38  | Natan Medeiros Maciel |
| INCT39  | Natan Medeiros Maciel |
| INCT40  | Rogério P. Bastos     |
| INCT41  | Rogério P. Bastos     |
| INCT42  | Rogério P. Bastos     |
| INCT43  | Fausto Nomura         |
| INCT44  | Fausto Nomura         |
| INCT45  | Fausto Nomura         |
| INCT46  | Rogério P. Bastos/Diego |
| INCT47  | Rogério P. Bastos/Diego |
| INCT48  | Rogério P. Bastos/Diego |




### Links

Detailed document GDrive [link](https://docs.google.com/document/d/1wz_B2mZFgrGbCHzPcAOZLDFaE0e76rv6Gc8V_JEYyCg/edit)

Spreadsheet w/ info about species/libraries [link](https://docs.google.com/spreadsheets/d/1F6AXYNF79QpDCbcFUuTHXH0IqtbpGzYtwebtIUq3xuY/edit#gid=0)

Raw data audio libraries [link](https://drive.google.com/drive/folders/1-aZqiwX436IfPnYRl6mTpX5sW2JFWhlC?usp=sharing)
