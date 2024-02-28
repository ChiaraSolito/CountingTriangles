# CountingTriangles

Confront algorithm implementation of Mining Massive Datasets Book to count triangles, with standard object of GraphFrames library.

## How to Run

- Install Scala (version must be different from 2.13, that generates problems with other
libraries), here you can find the command to install it on Linux (x86-64 architecture) or [else check here](https://www.scala-lang.org/download/):

```(bash)
curl -fL https://github.com/coursier/coursier/releases/latest/download/cs-x86_64-pc-linux.gz | gzip -d > cs && chmod +x cs && ./cs setup
```


- Clone this repository:

```(bash)
git clone https://github.com/ChiaraSolito/CountingTriangles.git
```

- Download the pySpark library, with GraphFrames and SparkMeasures included (available [here on OneDrive](https://univr-my.sharepoint.com/:u:/g/personal/chiara_solito_studenti_univr_it/EdpZzBAhJsRJqaWQVC3sILoB1o_CA95KGCMpMGGmDUxioA?e=lLEcg6));
- Unzip the library inside the root of the project;
- Install the requirements (requirements.txt)
- Change the environment variables with the correct path;
- Run the Notebook.
